# Thanks for Downloading

Thank you for downloading this **Advanced Third-Person Controller**! This controller is designed to offer a wide range of features and flexibility for your game projects. I hope it enhances your development experience and helps you create something amazing.

If you find this Advanced Third-Person Controller useful, consider supporting my work by [Ko-fi](https://ko-fi.com/neonfirestudio). If you don't have an account there, you can also support me through [Itch.io](https://neonfire-studio.itch.io/godot-advanced-third-person-controller). Your support is greatly appreciated and helps me continue to improve and add more features!

[Take a look at the development plan for it.](https://github.com/NeonfireStudio/godot-advanced-third-person-controller/blob/main/FuturePlan.md)

## How to Use

1. Install this repository.
2. Drag and drop the **Player** folder into your project.
3. Add the following input maps:
    ```plaintext
    left -> A
    right -> D
    forward -> W
    backward -> S
    jump -> Space
    sprint -> Shift
    crouch -> CTRL
    roll -> Shift + C
    slide -> Shift + V
    interact -> F
    emote_1 -> 1
    emote_2 -> 2
    emote_3 -> 3
    emote_4 -> 4
    right_mouse -> Right Mouse Button
    scroll_up -> Mouse Wheel Up
    scroll_Dowm -> Mouse Wheel Down
    fullscreen -> F11
    tab -> Show Cursor
    ESC -> Return to Menu
    ```
4. Add the player to your scene
5. Run and test your game, it is ready!

## Why It Is Advanced?

The **Advanced Third-Person Controller** stands out due to its range of advanced features, including:

- **Basic Movement**  
- **Multiplayer Support**  
- **Locomotion and Strafing**  
- **Advanced Animation System with Emotes**  
- **Dynamic Footsteps Based on Material**  
- **Highly Customizable Controller**  

Its future versions will be even better, with more advanced features and optimizations.

## How to Replace the Default Character

### Requirements

Your custom models must contain the following animations:
```plaintext
Idle
Walking
Running
Jumping
FallingIdle
CrouchIdle
CrouchWalking
Rolling
Sliding
Lifting
RunToStop
JogLeft
JogRight
JogForward
JogBackward (Optional)
JogBackLeft (Optional)
JogBackRight (Optional)
JogForwardLeft
JogForwardRight
HeadYes
HeadNo
Waving
WavingBothHands
PunchLeft
PunchRight
HardLand
```
### Important Notes on Animations!
- Every animation must be in place.
- You can change the animations in the animation tree if the name not matches with you chararcter model.
### Steps

1. Add your character model to the project and make it local.
2. Adjust the size and position of your model as per the default character.
3. Set the `anim_player` of the **AnimationTree** node to your model's animation player.
4. In the **Skeleton3D** node of your model, add a **BoneAttachment3D** and name it "HandPalm".
5. Set the **hand_palm** export variable to reference this "HandPalm" node which is the hand palm bone of your model.
6. Change the timers in the scene (like RollTimer, PickupTimer, etc.) to work well with the controller.
7. Test your character; it should now be fully integrated and ready for use.

## Current Features (v1.0):

- Basic Movement
- Strafing
- Locomotion
- Run To Stop
- Rolling/Sliding
- Roll On Fall From Height
- Picking Up Object
- 4 Types Of Emotes
- Godot Robo Character (mannequin)
- Simple Menu
- Multiplayer
- Footstep Based On Material
- Stylish Environment
- Easily Editable Controller  
...And More Coming In Future!

## Known Issues

- Footstep sound may not work in Multiplayer Mode.
- Picking up object may not work in Multiplayer Mode.
- You can`t get or set player rotation directly by codes, instead you need to use set_player_rotation or get_player_rotation function to do it.  
...I will try to fix it in future versions.

## Important Notes
- You can`t get or set player rotation directly by codes, instead you need to use set_player_rotation or get_player_rotation function to do it [/ul]
- This template is highly depends on the quality of your chararcter [/ul]

## Controls

- **Movement** | WASD
- **Strafe** | Right Mouse
- **Sprint** | Shift
- **Jump** | Space
- **Crouch** | CTRL
- **Roll** | Shift + C
- **Slide** | Shift + V
- **Pick Up Object** | F
- **Emotes** | 1-4
- **Zoom In/Out** | Scroll Up/Down
- **Toggle Fullscreen** | F11

## Screenshots

*Add some relevant screenshots of the project here*

![Screenshot 1](link_to_screenshot_1)
![Screenshot 2](link_to_screenshot_2)

## Credits

**Project Presented By**: [Neonfire Studio](https://neonfire-studio.itch.io)  
**Project Developed By**: Sandipan Saha  
**Godette Model Created By**: [zahlenmaler](https://sketchfab.com/3d-models/godette-rigged-dd05b69799a2438e97c90d166f6e416a)  
**Godette Model Animated By**: Sandipan Saha  
**Godot Plush Model By**: [FR3NKD](https://fr3nkd.gumroad.com/l/vhfvy)  
**Grid Textures & Sounds From**: [Kenney](https://kenney.nl)

## Copyright

Licensed under the [MIT License](https://opensource.org/license/mit):

- You are free to use this project for both commercial and non-commercial purposes.
- You may not resell this project or any of its components.
- You may not create YouTube tutorials or other instructional content based on this project without permission.

### 3D Model Animations:

- These models are available for use in non-commercial projects only.

### Others:

- The other assets are under CC0 License.

## Social Links

- [YouTube Channel](https://www.youtube.com/@NeonfireStudio)
- [Twitter](https://twitter.com/KingGD245)
- [Reddit](https://www.reddit.com/user/Financial-Junket9978)
- [GitHub](https://github.com/NeonfireStudio)
- [Itch.io](https://neonfire-studio.itch.io)
- [Discord](https://discord.gg/FFyC65gJcg)
