# shoes-3D-website
A modern e-commerce website for shoes with scroll-controlled video playback. The product video scrubs forward/backward as users scroll, remaining always in view.


🔧 How It Works:
1. Scroll-to-Video Sync - JavaScript maps scroll position to video timeline using requestAnimationFrame for buttery-smooth playback synchronization.

2. Dual-Layout Architecture - Fixed-position video container on left (35% width) with independent scrollable content section on right (55% width).

3. Performance Optimization - CSS will-change, transformZ(0), and hardware acceleration techniques prevent video stuttering during rapid scrolling.

4. Responsive Design System - Media queries adapt layout from desktop split-view to mobile vertical stacking while maintaining functionality.

5. Video Optimization - Dual-format support (MP4 + WebM) with preloading and smart quality reduction during fast scrolling events.

6. State Management - Scroll position tracking with debouncing and smooth interpolation algorithms for seamless video scrubbing.

7. Progressive Enhancement - Core shopping functionality works even if JavaScript fails, with graceful fallbacks for older browsers.

