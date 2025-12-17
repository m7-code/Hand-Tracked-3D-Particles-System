# 🌟 Hand-Tracked 3D Particle System

An interactive real-time 3D particle system controlled by hand gestures using MediaPipe and Three.js. Create stunning visual effects by simply moving your hands!

## ✨ Features

- **Real-time Hand Tracking** - Powered by Google's MediaPipe for accurate hand detection
- **5000+ Interactive Particles** - Smooth, optimized rendering with WebGL
- **6 Dynamic Shapes** - Sphere, Heart, Saturn, Flower, Cube, and Spiral formations
- **Intuitive Gestures** - Natural hand movements control particle behavior
- **Smooth Animations** - Fluid transitions between shapes and colors
- **Responsive Design** - Works on desktop and mobile devices with camera support

## 📱 Mobile Support

The system works on mobile devices with front-facing cameras. For best experience:

- Use in landscape orientation
- Ensure good lighting
- Keep hand movements smooth and deliberate

## 🐛 Troubleshooting

### Camera Not Working

- Ensure you've granted camera permissions
- Check if another application is using the camera
- Try using HTTPS (required for camera access)
- Refresh the page and allow permissions again

### Low Performance

- Reduce `PARTICLE_COUNT` in the code
- Close other browser tabs
- Use a device with better GPU capabilities
- Ensure hardware acceleration is enabled in browser settings

### Hand Tracking Issues

- Improve lighting conditions
- Keep hands within camera frame
- Avoid cluttered backgrounds
- Ensure hands are clearly visible
