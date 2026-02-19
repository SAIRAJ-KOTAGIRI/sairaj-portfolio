# Portfolio Theme Guide

Your portfolio now includes **9 beautiful color themes** that you can easily switch between! 

## 🎨 Available Themes

### 1. **Blue Cyan** (Default) 
- Primary: `#1e3a8a` (Deep Blue)
- Secondary: `#3b82f6` (Bright Blue)
- Accent: `#0ea5e9` (Cyan)
- **Best for:** Professional, tech-forward appearance
- **Vibe:** Modern, corporate, trustworthy

### 2. **Purple Pink**
- Primary: `#7c3aed` (Deep Purple)
- Secondary: `#a855f7` (Light Purple)
- Accent: `#ec4899` (Hot Pink)
- **Best for:** Creative, trendy portfolios
- **Vibe:** Artistic, vibrant, energetic

### 3. **Green Teal**
- Primary: `#059669` (Forest Green)
- Secondary: `#10b981` (Emerald)
- Accent: `#14b8a6` (Teal)
- **Best for:** Environmental, health, wellness industries
- **Vibe:** Fresh, natural, growth-oriented

### 4. **Orange Red**
- Primary: `#dc2626` (Deep Red)
- Secondary: `#f97316` (Orange)
- Accent: `#fb923c` (Light Orange)
- **Best for:** Bold, energetic, startup vibes
- **Vibe:** Warm, passionate, dynamic

### 5. **Indigo Violet**
- Primary: `#4c1d95` (Deep Indigo)
- Secondary: `#6d28d9` (Vivid Purple)
- Accent: `#8b5cf6` (Light Purple)
- **Best for:** Premium, luxury, AI/ML portfolios
- **Vibe:** Sophisticated, mysterious, innovative

### 6. **Emerald Mint**
- Primary: `#065f46` (Deep Emerald)
- Secondary: `#059669` (Medium Green)
- Accent: `#10b981` (Fresh Green)
- **Best for:** Eco-friendly, sustainable tech
- **Vibe:** Calm, balanced, nature-inspired

### 7. **Navy Gold**
- Primary: `#001f3f` (Navy Blue)
- Secondary: `#003d82` (Deep Blue)
- Accent: `#fbbf24` (Gold)
- **Best for:** Finance, luxury, premium services
- **Vibe:** Elegant, prestigious, high-end

### 8. **Rose Coral**
- Primary: `#9f1239` (Deep Rose)
- Secondary: `#be185d` (Rich Pink)
- Accent: `#fb7185` (Coral)
- **Best for:** Design, UX/UI, creative fields
- **Vibe:** Soft, elegant, modern

### 9. **Slate Cyan**
- Primary: `#1e293b` (Dark Slate)
- Secondary: `#475569` (Medium Slate)
- Accent: `#06b6d4` (Cyan)
- **Best for:** Minimalist, modern design
- **Vibe:** Clean, minimal, professional

## 🎛️ How to Switch Themes

### Using the Theme Switcher:
1. **Click the circular button** (🌙/☀️) in the bottom-right corner
2. **A theme panel will appear** showing 9 color options
3. **Click any color square** to instantly apply that theme
4. The selection is **saved automatically** to your browser

### Using Keyboard Shortcuts:
- **Double-click** the theme toggle button to switch between light/dark mode
- **Ctrl+D** (or **Cmd+D** on Mac) to toggle dark mode

## 🌓 Dark Mode

All themes work beautifully in **both light and dark modes**:
- Click the moon/sun icon and then double-click to toggle dark mode
- Or use **Ctrl+D / Cmd+D**
- Your preference is saved across sessions

## 💾 Persistence

Your selected theme and dark mode preference are automatically saved to your browser's local storage, so your choices are remembered when you visit again!

## 📋 Recommendations by Industry

| Industry | Recommended Themes |
|----------|-------------------|
| **Tech/Software** | Blue Cyan, Slate Cyan, Indigo Violet |
| **Finance** | Navy Gold, Blue Cyan, Slate Cyan |
| **Design/Creative** | Purple Pink, Rose Coral, Orange Red |
| **Startup/Entrepreneur** | Orange Red, Purple Pink, Indigo Violet |
| **Environmental/Green Tech** | Green Teal, Emerald Mint |
| **Healthcare** | Green Teal, Rose Coral, Emerald Mint |
| **Luxury/Premium** | Navy Gold, Indigo Violet, Rose Coral |

## 🔧 Customizing Colors

To add or modify themes, edit the `:root` CSS variables in the `<style>` section:

```css
:root[data-theme="your-theme"] {
    --primary-light: #YOURCOLOR;
    --secondary-color: #YOURCOLOR;
    --accent-color: #YOURCOLOR;
    --accent-glow: #YOURCOLOR;
}
```

Then add a new theme button in the HTML theme switcher panel and update the JavaScript theme options.

## ✨ Tips for Best Results

1. **Test all themes** with your profile image to see which complements it best
2. **Consider your industry** - some themes convey different professional vibes
3. **Dark mode adds depth** - try each theme in both light and dark modes
4. **Consistency matters** - stick with one theme for your actual portfolio deployment

---

**Enjoy customizing your portfolio! 🎉**
