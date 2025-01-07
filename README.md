# Immersive_Kiosk_Unity


### Features

- **Dual Control Modes**: Use VR controllers or keyboard/mouse for navigation and interactions.
- **Interactive Environment**: Explore a fully interactive VR world.
- **Grabbable and Usable Items**: Interact with kiosk items in a realistic way.
- **Optimized for VR**: Designed for smooth performance on the Meta Quest.
- **Customizable Layout**: Modify the kiosk’s items and layout to suit your needs.

---

### Navigation

- **Keyboard Controls**:
  - Use `W` to move forward.
  - Use `S` to move backward.
  - Use `A` to move left.
  - Use `D` to move right.

### Interaction

1. Press `2` to select the **left hand** or `3` to select the **right hand**.
2. Use the `W`, `S`, `A`, `D` keys to position the selected hand/controller.
3. **Mouse Interaction**:
   - Click the mouse button to press on an item.
4. If you are done using the hands/controllers, press `1` to deactivate them.

---

## Build Instructions

### Build Instructions

1. Install Unity version **2022.3.16f1**.
2. Install VRTK version **VRTK v4**.
3. Clone the repository:
   ```bash
   git clone https://github.com/Sengeki1/Immersive_VR_Kiosk.git
   cd Immersive_VR_Kiosk
   ```
4. Open the project in Unity.
5. Set the target platform to Android (for Meta Quest) or Windows (for desktop testing). If target platform is for Meta Quest, ensure that ``UnityXRPluginFramework`` is enabled and ``CameraRigs.SpatialSimulator`` is disabled. One can do this by clicking Toggle Active State.
6. Build and deploy using Unity’s build tools.

---
