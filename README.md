# Immersive VR Arcade Game for Oculus Quest 2

## Overview
This project is a fast-paced arcade-style Virtual Reality (VR) game developed for the **Oculus Quest 2** platform using the **Unity engine**. Players defend themselves against waves of projectiles using melee (a saber) and ranged (a flintlock pistol) weapons, while avoiding explosive hazards in a dynamic virtual environment.

The game emphasizes immersive, skill-based gameplay with intuitive motion controls optimized for standalone VR hardware.

## Features
- **Intuitive VR Controls:** Use Oculus Quest 2 controllers for natural interaction.
- **Weapon Mechanics:** Saber slicing and flintlock pistol aiming.
- **Dynamic Environment:** Projectiles and bombs with realistic physics.
- **Visual Effects:** Particle systems and motion blur during special mechanics.
- **WASD Movement:** Supported via XR Device Simulator for developer testing.
- **Instruction Prompts:** In-game tutorial and onboarding for beginners.
- **Performance Optimized:** Smooth gameplay on Oculus Quest 2 hardware.

## Technologies Used
- **Unity Engine**
- **Oculus Quest 2 SDK**
- **Unity XR Interaction Toolkit**
- **C# Scripting**
- **Open-source assets** (From Open-source PirateRush project adaptation)

## Installation & Setup

### Prerequisites
- Oculus Quest 2 headset with developer mode enabled.
- Unity Hub and Unity Editor installed (compatible version).
- Android SDK and ADB tools installed for deployment.
- USB cable to connect Oculus Quest 2 to PC.

### Steps to Build and Deploy
1. Clone this repository:
   git clone https://github.com/avinavmishra820/VR-project.git
2. Open the project in Unity Editor.
3. Configure the **XR Plugin Management** and set Oculus as the target platform.
4. Build the APK for Android.
5. Connect your Oculus Quest 2 headset via USB.
6. Use ADB to install the APK:
   adb install -r path_to_your_apk.apk
7. Launch the game from the Oculus Quest 2 library.

## How to Play
- Point at the **Start Game** button in the main menu and press the trigger to begin.
- Use the saber to slice incoming projectiles by physically swinging your hand.
- Aim the flintlock pistol by pointing and pressing the trigger.
- Avoid explosive bombs to survive longer.
- Access the **Tutorial** option in the main menu for detailed gameplay instructions.

## Future Work (Can Be Improved)
- Multiplayer modes (cooperative and competitive).
- Narrative-driven campaigns.
- Cross-platform support (HTC Vive, Valve Index).
- AI-driven adaptive gameplay.
- Enhanced accessibility and control customization.

## References
This project builds on various research and open-source contributions, including:
- Unity XR Toolkit documentation
- Oculus SDK guides
- Inspired By Open-source project 
- Research papers on VR game design and user experience

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


