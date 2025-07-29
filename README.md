# 🌧️ Rain Loader Animation

A beautiful, lightweight CSS rain loader animation with dark/light theme support and easy code copying functionality.

## ✨ Features

- **Realistic rain animation** with cloud, falling drops, and surface ripples
- **Dark/Light theme toggle** with smooth transitions
- **Copy-to-clipboard functionality** for easy integration
- **Pure CSS animations** - no JavaScript dependencies for the animation
- **Responsive design** that works on all screen sizes
- **Smooth performance** with optimized CSS keyframes

## 🚀 Quick Start

1. **Download or copy the HTML file**
2. **Open in any modern web browser**
3. **Use the copy buttons to get the animation code**

## 📋 Code Structure

### HTML Structure
```html
<div class="wrapper">
    <div class="cloud">
        <div class="cloud_left"></div>
        <div class="cloud_right"></div>
    </div>
    <div class="rain">
        <div class="drop"></div>
        <!-- More drops... -->
    </div>
    <div class="surface">
        <div class="hit"></div>
        <!-- More hits... -->
    </div>
</div>
```

### Key CSS Classes
- `.wrapper` - Main container (180px × 200px)
- `.cloud_left` & `.cloud_right` - Storm cloud elements
- `.drop` - Individual raindrops with staggered animations
- `.hit` - Surface impact ripples

## 🎨 Customization

### Colors
- **Light theme**: Gray clouds with blue raindrops
- **Dark theme**: Darker clouds with lighter blue raindrops
- Easy to modify colors by changing CSS variables

### Animation Speed
```css
.drop {
    animation: rain_401 0.8s infinite ease-out; /* Change 0.8s */
}
```

### Number of Drops
Add more `.drop` and `.hit` elements in HTML and corresponding CSS nth-child rules.

## 💻 Integration

### 1. Copy Animation Only
Use the "Copy CSS" and "Copy HTML" buttons to get just the animation code.

### 2. Include in Your Project
```html
<!-- Add to your HTML -->
<div class="wrapper">
    <!-- Rain animation HTML -->
</div>

<!-- Add to your CSS -->
<style>
    /* Rain animation CSS */
</style>
```

### 3. Use as Loading Indicator
```css
.loading-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.8);
    display: flex;
    justify-content: center;
    align-items: center;
}
```

## 🌟 Animation Details

- **Duration**: 0.8 seconds per cycle
- **Easing**: `ease-out` for natural motion
- **Staggered timing**: Each drop has different delay
- **Infinite loop**: Seamless continuous animation
- **Performance**: Hardware-accelerated transforms

## 🔧 Browser Support

- ✅ Chrome 50+
- ✅ Firefox 45+
- ✅ Safari 10+
- ✅ Edge 15+
- ✅ Mobile browsers

## 📱 Responsive Behavior

- Fixed dimensions (180px × 200px) for consistent animation
- Container adapts to different screen sizes
- Touch-friendly theme toggle button

## 🎯 Use Cases

- **Loading screens** for web applications
- **Weather-themed interfaces**
- **Progress indicators** with visual appeal
- **Decorative elements** for landing pages
- **User engagement** during wait times

## 🤝 Contributing

Feel free to:
- Suggest improvements
- Report issues
- Create variations
- Share use cases

## 📄 License

Free to use for personal and commercial projects.

---

**Made with ❤️ using pure CSS animations**
