# Placeholder Assets for Griffin's Rise Trading Journal

## Banner Assets

### Welcome Banner
- **Filename:** welcome-banner.svg
- **Dimensions:** 1200x300px
- **Content:** "🎯 Welcome to Griffin's Rise Trading Journal - Your Journey to Trading Mastery Begins Now!"
- **Style:** Gradient background (blue to purple), bold white text, Griffin logo
- **Usage:** First login welcome screen

### Onboarding Progress Banner
- **Filename:** onboarding-progress-banner.svg
- **Dimensions:** 800x150px
- **Content:** Dynamic progress bar with current step indication
- **Style:** Professional dark theme matching app design
- **Usage:** Top of onboarding modal

### Achievement Celebration
- **Filename:** achievement-celebration.svg
- **Dimensions:** 400x400px
- **Content:** Trophy icon with confetti animation placeholders
- **Style:** Golden trophy, colorful confetti elements
- **Usage:** Completion of major onboarding milestones

## Video Placeholder Graphics

### CeFi Security Video Thumbnail
- **Filename:** cefi-security-thumb.jpg
- **Dimensions:** 1280x720px
- **Content:** Exchange logos with shield/security icons
- **Text Overlay:** "Secure Your Exchange Accounts"
- **Style:** Professional, trustworthy, security-focused

### DeFi Wallet Video Thumbnail
- **Filename:** defi-wallet-thumb.jpg
- **Dimensions:** 1280x720px
- **Content:** MetaMask logo with wallet/key graphics
- **Text Overlay:** "DeFi Wallet Setup & Security"
- **Style:** Modern, tech-forward, safety emphasis

### Test Trading Video Thumbnail
- **Filename:** test-trading-thumb.jpg
- **Dimensions:** 1280x720px
- **Content:** Chart graphics with small position indicators
- **Text Overlay:** "Your First Test Trades"
- **Style:** Beginner-friendly, encouraging, educational

### Journal Setup Video Thumbnail
- **Filename:** journal-setup-thumb.jpg
- **Dimensions:** 1280x720px
- **Content:** Journal/notebook graphic with trading charts
- **Text Overlay:** "Master Your Trading Journal"
- **Style:** Professional documentation theme

## Interactive Element Assets

### Tooltip Pointers
- **Filename:** tooltip-pointer.svg
- **Dimensions:** 20x20px
- **Content:** Question mark icon in circle
- **Style:** Subtle blue, hover effects
- **Usage:** Throughout UI for contextual help

### Progress Checkmarks
- **Filename:** progress-check.svg
- **Dimensions:** 24x24px
- **Content:** Animated checkmark
- **Style:** Green checkmark with subtle animation
- **Usage:** Onboarding step completion

### Step Icons
- **Base Dimensions:** 48x48px
- **Style:** Line art icons matching app theme
- **Icons needed:**
  - welcome-icon.svg (home/wave)
  - email-icon.svg (envelope)
  - 2fa-icon.svg (shield)
  - cefi-icon.svg (bank/building)
  - defi-icon.svg (wallet)
  - trading-icon.svg (chart-line)
  - journal-icon.svg (book)
  - education-icon.svg (graduation-cap)
  - trophy-icon.svg (trophy)

## Badge Assets

### Onboarding Complete Badge
- **Filename:** onboarding-complete-badge.svg
- **Dimensions:** 120x120px
- **Content:** "Onboarding Complete" with Griffin logo
- **Style:** Gold/yellow theme with premium feel
- **Usage:** Profile display, achievement showcase

### Security Master Badge
- **Filename:** security-master-badge.svg
- **Dimensions:** 120x120px
- **Content:** Shield icon with "Security Master" text
- **Style:** Blue/silver security theme
- **Usage:** Completing all security setup steps

### First Trade Badge
- **Filename:** first-trade-badge.svg
- **Dimensions:** 120x120px
- **Content:** Chart icon with "First Trade" text
- **Style:** Green/profit theme
- **Usage:** Completing first test trade

## Animation Placeholders

### Confetti Animation
- **Type:** CSS/JavaScript animation
- **Duration:** 3 seconds
- **Content:** Falling confetti particles
- **Colors:** Griffin's Rise brand colors
- **Usage:** Achievement celebrations

### Progress Bar Fill
- **Type:** CSS animation
- **Duration:** 1 second ease-out
- **Content:** Smooth progress bar fill effect
- **Style:** Gradient blue to green
- **Usage:** Onboarding step completion

### Tooltip Fade
- **Type:** CSS transition
- **Duration:** 0.3 seconds
- **Content:** Fade in/out with slight scale
- **Style:** Smooth, professional
- **Usage:** Tooltip show/hide

## Implementation Notes

All assets should:
- Use Griffin's Rise brand colors (#232946 background, #dbeafe text, blue accents)
- Be optimized for web (SVG preferred for scalability)
- Include alt text for accessibility
- Support dark theme (current app theme)
- Be placeholder-ready for easy replacement with final designs

## File Structure
```
/onboarding/assets/
├── banners/
│   ├── welcome-banner.svg
│   ├── onboarding-progress-banner.svg
│   └── achievement-celebration.svg
├── videos/
│   ├── cefi-security-thumb.jpg
│   ├── defi-wallet-thumb.jpg
│   ├── test-trading-thumb.jpg
│   └── journal-setup-thumb.jpg
├── icons/
│   ├── step-icons/
│   └── ui-elements/
├── badges/
│   ├── onboarding-complete-badge.svg
│   ├── security-master-badge.svg
│   └── first-trade-badge.svg
└── animations/
    ├── confetti.css
    ├── progress-fill.css
    └── tooltip-fade.css
```