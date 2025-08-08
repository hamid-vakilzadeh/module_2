<template>
  <div class="card-grid" :style="gridStyle">
    <div
      v-for="(card, index) in cards"
      :key="index"
      class="card-item"
      :style="cardStyle"
    >
      <div class="card-icon" v-if="card.icon">
        <carbon:tools v-if="card.icon === 'carbon:tools'" class="icon" />
        <carbon:security v-if="card.icon === 'carbon:security'" class="icon" />
        <carbon:analytics
          v-if="card.icon === 'carbon:analytics'"
          class="icon"
        />
        <carbon:network-3
          v-if="card.icon === 'carbon:network-3'"
          class="icon"
        />
        <carbon:workflow-automation
          v-if="card.icon === 'carbon:workflow-automation'"
          class="icon"
        />
        <carbon:task v-if="card.icon === 'carbon:task'" class="icon" />
        <carbon:growth v-if="card.icon === 'carbon:growth'" class="icon" />
        <carbon:warning-alt
          v-if="card.icon === 'carbon:warning-alt'"
          class="icon"
        />
      </div>
      <h3 class="card-title">{{ card.title }}</h3>
      <p class="card-text">{{ card.text }}</p>
    </div>
  </div>
</template>

<script setup>
import { computed } from "vue";

const props = defineProps({
  cards: {
    type: Array,
    required: true,
    // Expected format: [{ title: String, text: String, icon?: String }]
  },
  cardWidth: {
    type: Number,
    default: 250, // minimum card width in pixels
  },
  gap: {
    type: Number,
    default: 20,
  },
});

// Calculate optimal grid layout based on card count and minimum width
const gridStyle = computed(() => {
  const cardCount = props.cards.length;
  const minCardWidth = props.cardWidth;
  const gap = props.gap;

  // Available width (assuming slide is ~900px wide with some margin)
  const availableWidth = 850;

  // Calculate how many cards can fit per row
  const cardsPerRow = Math.floor((availableWidth + gap) / (minCardWidth + gap));

  let columns;

  if (cardCount <= cardsPerRow) {
    // All cards fit in one row
    columns = cardCount;
  } else {
    // Multiple rows needed
    if (cardCount <= 4) {
      // For 3-4 cards, use 2x2 grid or 3x1 + 1x1
      columns = cardCount === 3 ? 3 : 2;
    } else {
      // For more cards, distribute evenly
      columns = Math.min(cardsPerRow, Math.ceil(Math.sqrt(cardCount)));
    }
  }

  return {
    display: "grid",
    gridTemplateColumns: `repeat(${columns}, 1fr)`,
    gap: `${gap}px`,
    width: "100%",
    margin: "20px auto",
    justifyItems: "center",
  };
});

const cardStyle = computed(() => {
  return {
    width: "100%",
    maxWidth: `${props.cardWidth * 1.2}px`, // Allow some flexibility
  };
});
</script>

<style scoped>
.card-grid {
  /* Grid styles are applied via computed style */
}

.card-item {
  background-color: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  transition:
    transform 0.3s ease,
    box-shadow 0.3s ease;
  min-height: 140px;
  justify-content: flex-start;
}

.card-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}

.card-icon {
  width: 50px;
  height: 50px;
  background: linear-gradient(135deg, #7f4f24, #414833);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 10px;
  flex-shrink: 0;
}

.icon {
  width: 25px;
  height: 25px;
  color: white;
}

.card-title {
  color: #414833;
  font-size: 1.1rem;
  margin-bottom: 8px;
  font-weight: 700;
  line-height: 1.3;
  flex-shrink: 0;
}

.card-text {
  color: #666;
  font-size: 0.9rem;
  line-height: 1.4;
  margin: 0;
  flex-grow: 1;
  display: flex;
  align-items: center;
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .card-grid {
    grid-template-columns: 1fr !important;
    gap: 15px !important;
  }

  .card-item {
    padding: 15px;
  }

  .card-title {
    font-size: 1rem;
  }

  .card-text {
    font-size: 0.85rem;
  }
}
</style>
