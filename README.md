# 3D Floating Fight Club Soap Effect

This project creates a **3D floating, spinning soap bar** inspired by *Fight Club* using **CSS 3D transforms** and animations.

## Features
- **3D Cuboid Structure** resembling a soap bar
- **Smooth Floating Animation** for a surreal effect
- **Spinning Rotation** using CSS keyframes
- **Blurry Text Outline Effect** for an aesthetic glow
- **Fully Responsive & Scalable**

## Technologies Used
- HTML5
- CSS3 (including **3D transforms, animations, shadows**)

## How to Use
1. Include the HTML file in your project.
2. Link the `style.css` file for styling.
3. Customize colors, size, and effects as needed.

## Customization Options
### 1. **Change Soap Color**
Modify the `.face` class in **style.css**:
```css
.face {
  background-color: #ff6f96; /* Change to any hex color */
}
```

### 2. **Adjust Floating Effect**
Modify the `float` animation in **style.css**:
```css
@keyframes float {
  0% { transform: translateY(0px); }
  50% { transform: translateY(-10px); }
  100% { transform: translateY(0px); }
}
```

### 3. **Blurry Text Outline Effect**
Modify the `.text` class in **style.css**:
```css
.text {
  text-shadow: 0px 0px 10px rgba(255, 255, 255, 0.8);
}
```

## Preview
Just open the HTML file in a browser, and the **3D floating Fight Club soap** will appear and spin smoothly.

## Author
Created by Fishdicg

## License
MIT License

