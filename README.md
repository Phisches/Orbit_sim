## Artemis Orbit Simulation

This is an **interactive web-based space flight simulator** built with HTML5 Canvas, where the user pilots a spacecraft on a mission to the Moon around Earth. Here's what it does:

### **Core Features:**

1. **Physics Simulation**
   - Realistic orbital mechanics with gravitational attraction from both Earth and Moon
   - The Moon orbits Earth at a fixed distance (1,200 units)
   - Ship experiences acceleration based on gravity from both bodies

2. **Flight Controls**
   - **Manual Control**: Hold buttons to apply thrust (accelerate or brake)
   - **Autopilot**: Schedule burns at apoapsis (highest orbit point) or periapsis (lowest orbit point)
   - **Thrust Power**: Adjustable slider (5-100%)
   - **Time Warp**: Speed up simulation (1x, 5x, or 20x speed) for long travel

3. **Trajectory Prediction**
   - Dashed line shows predicted path based on current velocity
   - Automatically detects if the trajectory will hit Earth (red) or Moon (green)
   - Displays apoapsis and periapsis (orbit extremes) with markers

4. **Visual Elements**
   - Earth (blue sphere) at center
   - Moon (gray sphere with craters) orbiting Earth
   - Moon orbital path (blue dashed circle)
   - Spacecraft with visible thrust flames when burning
   - Real-time orbit visualization

5. **Game Objectives**
   - Reach the Moon by expanding your orbit until it intersects the Moon's path
   - Land successfully on either the Moon or return to Earth
   - Educational: Learn real orbital mechanics (Hohmann transfers)

6. **UI**
   - Help modal with orbital mechanics tutorial (in German)
   - Status messages for autopilot events
   - Responsive design with Tailwind CSS
   - Collapsible control panel

### **Technical Details:**
- Written in vanilla JavaScript with Canvas 2D rendering
- Uses numerical integration (semi-implicit Euler method) for physics
- Implements auto-zoom camera to keep relevant objects visible
- Mobile-friendly with touch event support
- German language interface 

This is essentially a **Kerbal Space Program-lite** experience focused on teaching orbital mechanics through interactive gameplay!
