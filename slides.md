---
# You can also start simply with 'default'
theme: ./theme
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: AI for Accountants- A Practical Guide to ChatGPT and Data Security
info: |
  ## Presentation
  Small Firm Practitioners Conference
  Wednesday, August 13, 2025 - 2:05 PM - 2:55 PM
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# enable MDC Syntax: https://sli.dev/features/mdc
fonts:
  provider: google
  sans: Quicksand
  mono: Fira Code
mdc: true

themeConfig:
  color1: "#582F0E"
  color2: "#7F4F24"
  color3: "#936639"
  color4: "#A68A64"
  color5: "#B6AD90"
  color6: "#C2C5AA"
  color7: "#A4AC86"
  color8: "#656D4A"
  color9: "#414833"
  color10: "#333D29"
  primary: "#414833"
  secondary: "#7F4F24"
  accent: "#3A85DD"
  success: "#2ecc71"
  warning: "#e74c3c"
  info: "#9b59b6"
  background: "#B6AD90"
  textLight: "#FFFFFF"
  textDark: "#333333"
  link: "#7F4F24"

layout: cover
transition: none
---

# AI for Accountants: A Practical Guide to ChatGPT and Data Security

## Small Firm Practitioners Conference

## Wednesday, August 13, 2025 - 2:05 PM - 2:55 PM

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>

<!--
50-minute comprehensive course on ChatGPT ecosystem for CPAs with focus on security and practical applications
-->

---
align: center
title: Presenter
---

<img src="/HV-600x600.JPG" height=250 width=250 class="rounded-[3%]"/>

**Hamid Vakilzadeh, PhD**

Associate Professor, Department of Accounting

University of Wisconsin-Whitewater


**AI and Accounting Technology Researcher**

**Professional Training and Consulting Experience**

---

# Learning Objectives

<div class="objectives-container">
  <div class="objective-card">
    <div class="objective-icon">
      <carbon:network-3 class="icon" />
    </div>
    <h3>Master ChatGPT's Complete Ecosystem</h3>
    <p>Web, desktop, and enterprise platforms</p>
  </div>
  
  <div class="objective-card">
    <div class="objective-icon">
      <carbon:security class="icon" />
    </div>
    <h3>Understand Enterprise Security Features</h3>
    <p>Compliance, data protection, access controls</p>
  </div>
  
  <div class="objective-card">
    <div class="objective-icon">
      <carbon:workflow-automation class="icon" />
    </div>
    <h3>Implement Practical Workflow Applications</h3>
    <p>Document processing, client communication</p>
  </div>
  
  <div class="objective-card">
    <div class="objective-icon">
      <carbon:task class="icon" />
    </div>
    <h3>Navigate Professional Responsibility</h3>
    <p>Ethics, liability, quality control framework</p>
  </div>
</div>

<style>
.objectives-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  width: 100%;
  margin: 20px auto;
  gap: 20px;
}

.objective-card {
  background-color: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.objective-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}

.objective-icon {
  width: 50px;
  height: 50px;
  background: linear-gradient(135deg, #7F4F24, #414833);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 10px;
}

.icon {
  width: 25px;
  height: 25px;
  color: white;
}

.objective-card h3 {
  color: #414833;
  font-size: 1.1rem;
  margin-bottom: 8px;
  font-weight: 700;
}

.objective-card p {
  color: #666;
  font-size: 0.9rem;
  line-height: 1.4;
  margin: 0;
}
</style>


---

# ChatGPT Ecosystem for CPA Firms

<div class="roadmap-container">
  <div class="milestone-card">
    <div class="milestone-icon">
      <carbon:tools class="icon" />
    </div>
    <h3>Understanding the Ecosystem</h3>
    <p>The three-tier ChatGPT architecture and professional features</p>
  </div>
  
  <div class="milestone-card">
    <div class="milestone-icon">
      <carbon:security class="icon" />
    </div>
    <h3>Security & Compliance</h3>
    <p>Enterprise-grade protection and professional responsibility framework</p>
  </div>
  
  <div class="milestone-card">
    <div class="milestone-icon">
      <carbon:analytics class="icon" />
    </div>
    <h3>Practical Applications</h3>
    <p>Real-world implementations and automation workflows for CPAs</p>
  </div>
</div>

<style>
.roadmap-container {
  display: flex;
  justify-content: space-between;
  width: 100%;
  margin: 20px auto;
  gap: 20px;
}

.milestone-card {
  flex: 1;
  background-color: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.milestone-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}

.milestone-icon {
  width: 50px;
  height: 50px;
  background: linear-gradient(135deg, #7F4F24, #414833);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 10px;
}

.icon {
  width: 25px;
  height: 25px;
  color: white;
}

.milestone-card h3 {
  color: #414833;
  font-size: 1.1rem;
  margin-bottom: 8px;
  font-weight: 700;
}

.milestone-card p {
  color: #666;
  font-size: 0.9rem;
  line-height: 1.4;
  margin: 0;
}
</style>

---

# Why This Matters Now

ChatGPT serves **485 million users globally** with **74.8% market share** in AI search, transforming from simple chatbot into comprehensive business productivity platform.

<div class="matter-grid">

<div class="matter-card">
<div class="matter-icon">📈</div>
<h3>The Professional Opportunity</h3>
<ul>
<li>High accuracy in document processing</li>
<li>Enterprise-grade security for compliance</li>
<li>API integration for workflow automation</li>
</ul>
</div>

<div class="matter-card">
<div class="matter-icon">⚠️</div>
<h3>The Challenge</h3>
<ul>
<li>Understanding complete ecosystem architecture</li>
<li>Pricing and security requirements</li>
<li>Professional responsibility considerations</li>
<li>Implementation planning and risk management</li>
</ul>
</div>

</div>

<style>
.matter-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
  margin: 20px 0;
}

.matter-card {
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  text-align: center;
  transition: transform 0.3s ease;
}

.matter-card:hover {
  transform: translateY(-3px);
}

.matter-icon {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.matter-card h3 {
  color: #414833;
  font-size: 1.1rem;
  margin-bottom: 12px;
  font-weight: 700;
}

.matter-card ul {
  text-align: left;
  color: #666;
  line-height: 1.4;
  font-size: 0.9rem;
}

.matter-card li {
  margin-bottom: 4px;
}
</style>

---

# The ChatGPT Ecosystem: Three Access Points

<div class="access-grid">

<div class="access-point-card">
<div class="access-icon">🌐</div>
<h3>ChatGPT.com</h3>
<ul>
<li>Consumer-facing interface</li>
<li>Most CPAs' first encounter</li>
<li>Basic chat functionality</li>
<li>Web-based access</li>
</ul>
</div>

<div class="access-point-card">
<div class="access-icon">💻</div>
<h3>Desktop Applications</h3>
<ul>
<li>macOS & Windows native apps</li>
<li>Alt+Space quick access</li>
<li>Screen sharing capabilities</li>
<li>Record Mode for meetings</li>
</ul>
</div>

<div class="access-point-card">
<div class="access-icon">⚙️</div>
<h3>Platform.openai.com</h3>
<ul>
<li>Developer hub</li>
<li>Enterprise features</li>
<li>API access</li>
<li>Billing management</li>
</ul>
</div>

</div>

<style>
.access-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin: 20px 0;
}

.access-point-card {
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  text-align: center;
  transition: transform 0.3s ease;
}

.access-point-card:hover {
  transform: translateY(-3px);
}

.access-icon {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.access-point-card h3 {
  color: #414833;
  font-size: 1.1rem;
  margin-bottom: 12px;
  font-weight: 700;
}

.access-point-card ul {
  text-align: left;
  color: #666;
  line-height: 1.4;
  font-size: 0.9rem;
}

.access-point-card li {
  margin-bottom: 4px;
}
</style>

---

# 🎥 VIDEO DEMO: ChatGPT Web Interface Walkthrough

<div class="video-container">
  <div class="video-placeholder">
    <div class="play-button">▶</div>
    <h3>ChatGPT.com Demo</h3>
  </div>
</div>

<!--
**What we'll demonstrate:**
- Basic ChatGPT.com interface navigation
- Professional features for CPAs
- Document upload and analysis capabilities
-->

<style>
.video-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 30px 0;
}

.video-placeholder {
  width: 500px;
  height: 300px;
  background: linear-gradient(135deg, #414833, #7F4F24);
  border-radius: 12px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
  box-shadow: 0 8px 24px rgba(0,0,0,0.2);
}

.play-button {
  font-size: 3rem;
  margin-bottom: 15px;
  opacity: 0.9;
}

.video-placeholder h3 {
  font-size: 1.4rem;
  margin-bottom: 8px;
}

.video-placeholder p {
  font-size: 1rem;
  opacity: 0.9;
  margin: 0;
  padding: 0 20px;
}
</style>

---

# Desktop Applications

<div class="feature-comparison">
  <div class="feature-column">
    <h3>macOS App Features</h3>
    <div class="feature-list">
      <div class="feature-item">⚡ Native system integration</div>
      <div class="feature-item">⌨️ Alt+Space global shortcut</div>
      <div class="feature-item">📸 Screen sharing for document analysis</div>
      <div class="feature-item">🎙️ Record Mode for meeting transcription</div>
      <div class="feature-item">🚀 Improved performance over browser</div>
    </div>
  </div>

  <div class="feature-column">
    <h3>Windows Desktop App</h3>
    <div class="feature-list">
      <div class="feature-item">⌨️ Dedicated shortcuts and hotkeys</div>
      <div class="feature-item">💾 Better system resource management</div>
      <div class="feature-item">📱 Offline capabilities (limited)</div>
      <div class="feature-item">🔒 Enhanced security controls</div>
    </div>
  </div>
</div>

<div class="professional-benefit">
<strong>Professional Benefit:</strong> Desktop apps provide better integration with your files and software
</div>

<style>
.feature-comparison {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 30px;
  margin: 20px 0;
}

.feature-column h3 {
  color: #414833;
  font-size: 1.2rem;
  margin-bottom: 15px;
  font-weight: 700;
}

.feature-list {
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.feature-item {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
  font-size: 0.9rem;
  color: #666;
}

.feature-item:last-child {
  margin-bottom: 0;
}

.professional-benefit {
  background: #e8f4fd;
  border-left: 4px solid #3A85DD;
  padding: 12px;
  margin-top: 20px;
  border-radius: 0 8px 8px 0;
  color: #1a365d;
  font-size: 0.9rem;
}
</style>

---

# 🎥 VIDEO DEMO: Desktop Application Features


<div class="video-container">
  <div class="video-placeholder">
    <div class="play-button">▶</div>
    <h3>Desktop App Demo</h3>
  </div>
</div>

<style>
.video-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 30px 0;
}

.video-placeholder {
  width: 500px;
  height: 300px;
  background: linear-gradient(135deg, #414833, #7F4F24);
  border-radius: 12px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
  box-shadow: 0 8px 24px rgba(0,0,0,0.2);
}

.play-button {
  font-size: 3rem;
  margin-bottom: 15px;
  opacity: 0.9;
}

.video-placeholder h3 {
  font-size: 1.4rem;
  margin-bottom: 8px;
}

.video-placeholder p {
  font-size: 1rem;
  opacity: 0.9;
  margin: 0;
  padding: 0 20px;
}
</style>

<!--
**What we'll demonstrate:**
- Desktop app installation process
- Alt+Space quick access demonstration  
- Screen sharing for document analysis
-->

---

# Platform.openai.com: The Enterprise Hub

**The developer and enterprise control center for professional ChatGPT implementation:**

<div class="platform-features">
  <div class="feature-section">
    <h3>🔧 Developer Features</h3>
    <ul>
      <li>API access and management</li>
      <li>Custom model configurations</li>
      <li>Usage analytics and monitoring</li>
      <li>Billing and cost controls</li>
      <li>Team management tools</li>
    </ul>
  </div>

</div>


<style>
.platform-features {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 30px;
  margin: 20px 0;
}

.feature-section {
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.feature-section h3 {
  color: #414833;
  font-size: 1.1rem;
  margin-bottom: 15px;
  font-weight: 700;
}

.feature-section ul {
  list-style: none;
  padding: 0;
}

.feature-section li {
  padding: 3px 0;
  color: #666;
  position: relative;
  padding-left: 15px;
  font-size: 0.9rem;
}

.feature-section li::before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #2ecc71;
  font-weight: bold;
}

.platform-importance {
  background: #e8f4fd;
  border-left: 4px solid #3A85DD;
  padding: 15px;
  margin-top: 20px;
  border-radius: 0 8px 8px 0;
  color: #1a365d;
  font-size: 0.9rem;
}
</style>
---

# The Enterprise Hub

**The developer and enterprise control center for professional ChatGPT implementation:**

<div class="platform-features">


  <div class="feature-section">
    <h3>🏢 Enterprise Controls</h3>
    <ul>
      <li>Domain verification</li>
      <li>SAML SSO integration</li>
      <li>Data residency options</li>
      <li>Advanced security settings</li>
      <li>Audit logs and compliance</li>
    </ul>
  </div>
</div>

<div class="platform-importance">
<strong>Critical for CPA Firms:</strong> Platform.openai.com is essential for firms requiring enterprise-grade security, compliance features, and API integrations
</div>

<style>
.platform-features {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 30px;
  margin: 20px 0;
}

.feature-section {
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.feature-section h3 {
  color: #414833;
  font-size: 1.1rem;
  margin-bottom: 15px;
  font-weight: 700;
}

.feature-section ul {
  list-style: none;
  padding: 0;
}

.feature-section li {
  padding: 3px 0;
  color: #666;
  position: relative;
  padding-left: 15px;
  font-size: 0.9rem;
}

.feature-section li::before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #2ecc71;
  font-weight: bold;
}

.platform-importance {
  background: #e8f4fd;
  border-left: 4px solid #3A85DD;
  padding: 15px;
  margin-top: 20px;
  border-radius: 0 8px 8px 0;
  color: #1a365d;
  font-size: 0.9rem;
}
</style>

---

# 🎥 VIDEO DEMO: Platform.openai.com Walkthrough

<div class="video-container">
  <div class="video-placeholder">
    <div class="play-button">▶</div>
    <h3>Platform.openai.com Demo</h3>
    <p>Enterprise hub navigation, API setup, and team management</p>
  </div>
</div>

<!--
**What we'll demonstrate:**
- Platform.openai.com navigation
- Enterprise account setup
- API key generation and management
- Team and billing configuration
- Security and compliance settings
-->

<style>
.video-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 30px 0;
}

.video-placeholder {
  width: 500px;
  height: 300px;
  background: linear-gradient(135deg, #414833, #7F4F24);
  border-radius: 12px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
  box-shadow: 0 8px 24px rgba(0,0,0,0.2);
}

.play-button {
  font-size: 3rem;
  margin-bottom: 15px;
  opacity: 0.9;
}

.video-placeholder h3 {
  font-size: 1.4rem;
  margin-bottom: 8px;
}

.video-placeholder p {
  font-size: 1rem;
  opacity: 0.9;
  margin: 0;
  padding: 0 20px;
}
</style>

---

# Subscription Tiers: Professional Use Analysis

<div class="pricing-grid">
  <div class="pricing-card free-tier">
    <div class="tier-header">
      <h3>❌ Free Tier</h3>
      <div class="price">$0/month</div>
    </div>
    <div class="tier-features">
      <ul>
        <li>Daily capacity limits</li>
        <li>Slower response times</li>
        <li class="danger">Data retention risks</li>
        <li class="danger">Not suitable for professional use</li>
      </ul>
    </div>
  </div>

  <div class="pricing-card plus-tier">
    <div class="tier-header">
      <h3>⚠️ ChatGPT Plus</h3>
      <div class="price">$20/month per user</div>
    </div>
    <div class="tier-features">
      <ul>
        <li>80 messages every 3 hours</li>
        <li>Advanced Voice Mode</li>
        <li>Web search capability</li>
        <li class="warning">Limited security controls</li>
      </ul>
    </div>
  </div>

  <div class="pricing-card team-tier recommended">
    <div class="tier-header">
      <h3>✅ ChatGPT Team</h3>
      <div class="price">$25-30/user/month</div>
    </div>
    <div class="tier-features">
      <ul>
        <li class="highlight">Minimum for CPA firms</li>
        <li>Business data not used for training</li>
        <li>Admin console access</li>
        <li>Team workspace features</li>
      </ul>
    </div>
  </div>
</div>

<div class="professional-recommendation">
<strong>Professional Recommendation:</strong> Team plans represent minimum acceptable security level for CPA firms
</div>


<style>
.pricing-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 15px;
  margin: 20px 0;
}

.pricing-card {
  background: white;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  overflow: hidden;
  transition: transform 0.3s ease;
}

.pricing-card:hover {
  transform: translateY(-3px);
}

.pricing-card.recommended {
  border: 3px solid #2ecc71;
  position: relative;
}

.pricing-card.recommended::before {
  content: "RECOMMENDED";
  position: absolute;
  top: 0;
  right: 0;
  background: #2ecc71;
  color: white;
  padding: 4px 8px;
  font-size: 0.7rem;
  font-weight: bold;
}

.tier-header {
  padding: 15px;
  text-align: center;
}

.tier-header h3 {
  font-size: 1rem;
  margin-bottom: 8px;
  color: #414833;
}

.price {
  font-size: 1.1rem;
  font-weight: bold;
  color: #7F4F24;
}

.tier-features {
  padding: 0 15px 15px;
}

.tier-features ul {
  list-style: none;
  padding: 0;
}

.tier-features li {
  padding: 6px 0;
  border-bottom: 1px solid #f0f0f0;
  font-size: 0.85rem;
}

.tier-features li:last-child {
  border-bottom: none;
}

.danger {
  color: #e74c3c;
  font-weight: bold;
}

.warning {
  color: #f39c12;
  font-weight: bold;
}

.highlight {
  color: #2ecc71;
  font-weight: bold;
}

.free-tier {
  border: 2px solid #e74c3c;
}

.plus-tier {
  border: 2px solid #f39c12;
}

.team-tier {
  border: 2px solid #2ecc71;
}

.professional-recommendation {
  background: #e8f4fd;
  border-left: 4px solid #3A85DD;
  padding: 12px;
  margin-top: 20px;
  border-radius: 0 8px 8px 0;
  color: #1a365d;
  font-size: 0.9rem;
}
</style>

---

# Enterprise Security & Data Protection

**ChatGPT Enterprise implements comprehensive security for professional use:**

<div class="security-grid">
  <div class="security-category">
    <h3>🔒 Encryption Standards</h3>
    <ul>
      <li>AES-256 encryption for stored data</li>
      <li>TLS 1.2+ for data in transit</li>
      <li>End-to-end encryption protocols</li>
      <li>Zero data retention for API calls</li>
    </ul>
  </div>

  <div class="security-category">
    <h3>📋 Compliance Certifications</h3>
    <ul>
      <li>SOC 2 Type 2 compliance</li>
      <li>Cloud Security Alliance STAR Level 1</li>
      <li>Independent third-party audits</li>
      <li>GDPR and CCPA compliance</li>
    </ul>
  </div>

  <div class="security-category">
    <h3>👥 Access Controls</h3>
    <ul>
      <li>SAML SSO integration</li>
      <li>Multi-factor authentication</li>
      <li>Role-based access controls</li>
      <li>Domain verification</li>
    </ul>
  </div>

  <div class="security-category">
    <h3>🌍 Geographic Controls</h3>
    <ul>
      <li>Data residency options</li>
      <li>US, Europe, Japan, Canada</li>
      <li>Regulatory compliance support</li>
      <li>International data transfers</li>
    </ul>
  </div>
</div>

<style>
.security-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
  margin: 20px 0;
}

.security-category {
  background: white;
  padding: 18px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.security-category h3 {
  color: #414833;
  font-size: 1rem;
  margin-bottom: 12px;
  font-weight: 700;
}

.security-category ul {
  list-style: none;
  padding: 0;
}

.security-category li {
  padding: 3px 0;
  color: #666;
  position: relative;
  padding-left: 15px;
  font-size: 0.85rem;
}

.security-category li::before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #2ecc71;
  font-weight: bold;
}
</style>

---

# Document Processing Revolution

<div class="capabilities-showcase">
  <div class="capability-card">
    <div class="capability-icon">📄</div>
    <h3>Document Analysis</h3>
    <ul>
      <li>90%+ accuracy for invoice data extraction</li>
      <li>Bank statement transaction categorization</li>
      <li>Receipt processing for expense management</li>
      <li>Complex layouts and multiple languages</li>
    </ul>
  </div>

  <div class="capability-card">
    <div class="capability-icon">📊</div>
    <h3>Financial Processing</h3>
    <ul>
      <li>Forms 10-K analysis for insights</li>
      <li>Tax document analysis and research</li>
      <li>Multi-jurisdictional compliance</li>
      <li>Pattern recognition for opportunities</li>
    </ul>
  </div>
</div>


<style>
.capabilities-showcase {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 25px;
  margin: 20px 0;
}

.capability-card {
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  text-align: center;
}

.capability-icon {
  font-size: 2.5rem;
  margin-bottom: 12px;
}

.capability-card h3 {
  color: #414833;
  font-size: 1.1rem;
  margin-bottom: 12px;
  font-weight: 700;
}

.capability-card ul {
  text-align: left;
  list-style: none;
  padding: 0;
}

.capability-card li {
  padding: 3px 0;
  color: #666;
  position: relative;
  padding-left: 15px;
  font-size: 0.85rem;
}

.capability-card li::before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #2ecc71;
  font-weight: bold;
}
</style>

---

# 🎥 VIDEO DEMO: Document Processing Capabilities

<div class="video-container">
  <div class="video-placeholder">
    <div class="play-button">▶</div>
    <h3>Document Processing Demo</h3>
  </div>
</div>


<style>
.video-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 30px 0;
}

.video-placeholder {
  width: 500px;
  height: 300px;
  background: linear-gradient(135deg, #414833, #7F4F24);
  border-radius: 12px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
  box-shadow: 0 8px 24px rgba(0,0,0,0.2);
}

.play-button {
  font-size: 3rem;
  margin-bottom: 15px;
  opacity: 0.9;
}

.video-placeholder h3 {
  font-size: 1.4rem;
  margin-bottom: 8px;
}

.video-placeholder p {
  font-size: 1rem;
  opacity: 0.9;
  margin: 0;
  padding: 0 20px;
}
</style>

<!--
**What we'll demonstrate:**
- Invoice data extraction in real-time
- Financial statement analysis
- Tax document processing accuracy
-->

---

# Custom GPT Development for CPAs

<div class="gpt-development">
  <div class="development-steps">
    <h3>Creation Process</h3>
    <div class="step-list">
      <div class="step-item">
        <span class="step-number">1</span>
        <span>ChatGPT Plus, Team, or Enterprise subscription</span>
      </div>
      <div class="step-item">
        <span class="step-number">2</span>
        <span>Navigate to chatgpt.com/create</span>
      </div>
      <div class="step-item">
        <span class="step-number">3</span>
        <span>Configure behavioral guidelines</span>
      </div>
      <div class="step-item">
        <span class="step-number">4</span>
        <span>Upload knowledge files (up to 20)</span>
      </div>
      <div class="step-item">
        <span class="step-number">5</span>
        <span>Test and deploy to team</span>
      </div>
    </div>
  </div>

  <div class="cpa-implementations">
    <h3>CPA-Specific Implementations</h3>
    <div class="implementation-grid">
      <div class="impl-card">
        <div class="impl-icon">📋</div>
        <h4>Tax Advisor GPTs</h4>
        <p>Regulations and compliance</p>
      </div>
      <div class="impl-card">
        <div class="impl-icon">📊</div>
        <h4>Financial Analyzers</h4>
        <p>Statement interpretation</p>
      </div>
      <div class="impl-card">
        <div class="impl-icon">🔍</div>
        <h4>Audit Assistants</h4>
        <p>Procedure documentation</p>
      </div>
      <div class="impl-card">
        <div class="impl-icon">💰</div>
        <h4>Expense Categorizers</h4>
        <p>Transaction classification</p>
      </div>
    </div>
  </div>
</div>

<style>
.gpt-development {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 30px;
  margin: 20px 0;
}

.development-steps h3,
.cpa-implementations h3 {
  color: #414833;
  font-size: 1.2rem;
  margin-bottom: 15px;
  font-weight: 700;
}

.step-list {
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.step-item {
  display: flex;
  align-items: center;
  margin-bottom: 12px;
  font-size: 0.9rem;
}

.step-item:last-child {
  margin-bottom: 0;
}

.step-number {
  background: #7F4F24;
  color: white;
  width: 25px;
  height: 25px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-right: 12px;
  font-weight: bold;
  font-size: 0.8rem;
}

.implementation-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 12px;
}

.impl-card {
  background: white;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  text-align: center;
  transition: transform 0.3s ease;
}

.impl-card:hover {
  transform: translateY(-2px);
}

.impl-icon {
  font-size: 1.8rem;
  margin-bottom: 8px;
}

.impl-card h4 {
  color: #414833;
  font-size: 0.9rem;
  margin-bottom: 4px;
  font-weight: 600;
}

.impl-card p {
  color: #666;
  font-size: 0.8rem;
  margin: 0;
}
</style>

---

# 🎥 VIDEO DEMO: Custom GPT Creation

<div class="video-container">
  <div class="video-placeholder">
    <div class="play-button">▶</div>
    <h3>Custom GPT Creation Demo</h3>
  </div>
</div>



<style>
.video-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 30px 0;
}

.video-placeholder {
  width: 500px;
  height: 300px;
  background: linear-gradient(135deg, #414833, #7F4F24);
  border-radius: 12px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
  box-shadow: 0 8px 24px rgba(0,0,0,0.2);
}

.play-button {
  font-size: 3rem;
  margin-bottom: 15px;
  opacity: 0.9;
}

.video-placeholder h3 {
  font-size: 1.4rem;
  margin-bottom: 8px;
}

.video-placeholder p {
  font-size: 1rem;
  opacity: 0.9;
  margin: 0;
  padding: 0 20px;
}
</style>

<!--
**What we'll demonstrate:**
- GPT Builder interface navigation
- Knowledge file upload process
- Testing custom GPT functionality
-->

---

# 🎥 VIDEO DEMO: Simple Langflow API Example

<div class="video-container">
  <div class="video-placeholder">
    <div class="play-button">▶</div>
    <h3>Langflow Example Demo</h3>
    <p>Visual workflow builder demonstration showing ChatGPT API integration</p>
  </div>
</div>


<style>
.video-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 30px 0;
}

.video-placeholder {
  width: 500px;
  height: 300px;
  background: linear-gradient(135deg, #414833, #7F4F24);
  border-radius: 12px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
  box-shadow: 0 8px 24px rgba(0,0,0,0.2);
}

.play-button {
  font-size: 3rem;
  margin-bottom: 15px;
  opacity: 0.9;
}

.video-placeholder h3 {
  font-size: 1.4rem;
  margin-bottom: 8px;
}

.video-placeholder p {
  font-size: 1rem;
  opacity: 0.9;
  margin: 0;
  padding: 0 20px;
}
</style>

<!--
**What we'll demonstrate:**
- Langflow visual interface
- Drag-and-drop workflow creation
- ChatGPT API connection setup
-->

---

# Professional Responsibility Framework

**All AICPA Code of Professional Conduct requirements remain fully applicable to AI-assisted work:**

<div class="responsibility-grid">
  <div class="framework-section">
    <h3>🏛️ Current Standards</h3>
    <ul>
      <li>AICPA has not issued AI-specific standards</li>
      <li>Existing quality control requirements apply</li>
      <li>CPAs maintain ultimate responsibility</li>
      <li>Professional judgment cannot be replaced</li>
    </ul>
  </div>

  <div class="framework-section">
    <h3>⚖️ Ethical Considerations</h3>
    <ul>
      <li>Maintain professional competence</li>
      <li>Ensure independence and objectivity</li>
      <li>Protect confidential client information</li>
      <li>Avoid over-reliance without review</li>
    </ul>
  </div>

  <div class="framework-section">
    <h3>🛡️ Quality Control</h3>
    <ul>
      <li>All AI content requires human validation</li>
      <li>Review by qualified personnel</li>
      <li>Documentation of procedures</li>
      <li>Professional skepticism application</li>
    </ul>
  </div>

  <div class="framework-section">
    <h3>📋 Client Disclosure</h3>
    <ul>
      <li>Engagement letter modifications</li>
      <li>Informed consent requirements</li>
      <li>Quality control explanations</li>
      <li>Professional oversight assurance</li>
    </ul>
  </div>
</div>

<style>
.responsibility-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
  margin: 20px 0;
}

.framework-section {
  background: white;
  padding: 18px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.framework-section h3 {
  color: #414833;
  font-size: 1rem;
  margin-bottom: 12px;
  font-weight: 700;
}

.framework-section ul {
  list-style: none;
  padding: 0;
}

.framework-section li {
  padding: 3px 0;
  color: #666;
  position: relative;
  padding-left: 15px;
  font-size: 0.85rem;
}

.framework-section li::before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #3A85DD;
  font-weight: bold;
}
</style>

---

# Implementation Roadmap: Your Path to Success

<div class="implementation-phases">
  <div class="phase-card">
    <div class="phase-number">1</div>
    <h3>Assessment</h3>
    <p class="phase-duration">Weeks 1-2</p>
    <ul>
      <li>Firm-wide AI readiness assessment</li>
      <li>Technology infrastructure evaluation</li>
      <li>Staff competency analysis</li>
      <li>Use case identification</li>
    </ul>
  </div>

  <div class="phase-card">
    <div class="phase-number">2</div>
    <h3>Security Setup</h3>
    <p class="phase-duration">Weeks 3-4</p>
    <ul>
      <li>Subscription tier selection</li>
      <li>Data protection protocols</li>
      <li>Insurance review</li>
      <li>Legal consultation</li>
    </ul>
  </div>

  <div class="phase-card">
    <div class="phase-number">3</div>
    <h3>Pilot Implementation</h3>
    <p class="phase-duration">Month 2</p>
    <ul>
      <li>Non-sensitive testing</li>
      <li>Staff training programs</li>
      <li>Performance metrics</li>
      <li>Documentation procedures</li>
    </ul>
  </div>

  <div class="phase-card">
    <div class="phase-number">4</div>
    <h3>Scaling</h3>
    <p class="phase-duration">Months 3-6</p>
    <ul>
      <li>Application expansion</li>
      <li>Custom GPT development</li>
      <li>API integration</li>
      <li>ROI optimization</li>
    </ul>
  </div>
</div>

<style>
.implementation-phases {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 15px;
  margin: 20px 0;
}

.phase-card {
  background: white;
  padding: 18px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  text-align: center;
  transition: transform 0.3s ease;
}

.phase-card:hover {
  transform: translateY(-3px);
}

.phase-number {
  background: #7F4F24;
  color: white;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 10px;
  font-size: 1.2rem;
  font-weight: bold;
}

.phase-card h3 {
  color: #414833;
  font-size: 1.1rem;
  margin-bottom: 4px;
  font-weight: 700;
}

.phase-duration {
  color: #7F4F24;
  font-weight: bold;
  margin-bottom: 10px;
  font-size: 0.9rem;
}

.phase-card ul {
  text-align: left;
  list-style: none;
  padding: 0;
}

.phase-card li {
  padding: 2px 0;
  color: #666;
  font-size: 0.8rem;
  position: relative;
  padding-left: 12px;
}

.phase-card li::before {
  content: "•";
  position: absolute;
  left: 0;
  color: #3A85DD;
  font-weight: bold;
}
</style>

---
layout: default
---

# Next Steps: Your Action Plan

<div class="action-plan-grid">
  <div class="action-card">
    <div class="action-icon">⚡</div>
    <h3>This Week</h3>
    <ul>
      <li>Assess AI readiness</li>
      <li>Review insurance</li>
      <li>Draft policies</li>
    </ul>
  </div>

  <div class="action-card">
    <div class="action-icon">📋</div>
    <h3>Next Month</h3>
    <ul>
      <li>Select subscription</li>
      <li>Train staff</li>
      <li>Begin testing</li>
    </ul>
  </div>

  <div class="action-card">
    <div class="action-icon">🚀</div>
    <h3>3-6 Months</h3>
    <ul>
      <li>Scale applications</li>
      <li>Custom GPTs</li>
      <li>API integration</li>
    </ul>
  </div>

  <div class="action-card">
    <div class="action-icon">📊</div>
    <h3>Success Metrics</h3>
    <ul>
      <li>300%+ ROI</li>
      <li>90%+ accuracy</li>
      <li>4hrs → 30min</li>
    </ul>
  </div>
</div>

<style>
.action-plan-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 15px;
  margin: 15px 0;
}

.action-card {
  background: white;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 3px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.action-card:hover {
  transform: translateY(-3px);
}

.action-icon {
  font-size: 1.8rem;
  text-align: center;
  margin-bottom: 8px;
}

.action-card h3 {
  color: #414833;
  font-size: 1.2rem;
  margin-bottom: 5px;
  font-weight: 700;
  text-align: center;
}

.action-timeframe {
  color: #7F4F24;
  font-weight: bold;
  text-align: center;
  margin-bottom: 10px;
  font-size: 0.8rem;
}

.action-card ul {
  list-style: none;
  padding: 0;
}

.action-card li {
  padding: 2px 0;
  color: #666;
  position: relative;
  padding-left: 12px;
  font-size: 1rem;
  line-height: 1.3;
}

.action-card li::before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #2ecc71;
  font-weight: bold;
  font-size: 0.7rem;
}

.metrics li strong {
  color: #414833;
}
</style>

---
layout: center
align: center
---
# Thank You

## Questions & Discussion

**Hamid Vakilzadeh, PhD**  
Associate Professor, Department of Accounting  
University of Wisconsin-Whitewater


---

*This presentation provides educational information and does not constitute professional advice. Consult with qualified professionals for specific implementation guidance.*