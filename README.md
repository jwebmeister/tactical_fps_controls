# tactical_fps_controls
 My dream (proposed) controls for tactical FPS, specifically for controlling weapon attached tactical devices, in games like Ground Branch and Gray Zone Warfare.  
 
 I made a VoiceAttack profile to demonstrate the use of these controls in Ground Branch, see [YouTube video link](https://www.youtube.com/watch?v=2RRXgJaxBos). I've included the VA profile, which is a proof of concept, so be warned it's not user friendly and some monkeying will be required if it's used, more specifically the controls set as detailed [below](#ground-branch).

[![YT Video demonstrating controls in Ground Branch](https://img.youtube.com/vi/2RRXgJaxBos/0.jpg)](https://www.youtube.com/watch?v=2RRXgJaxBos)

## General Controls Scheme

- Tactical Device Button 0 
    - Press - Tactical Device Group 0 toggle On/Off - Custom, as set by player within Tactical Devices Menu / Attachment Select Wheel
    - Hold - Tactical Devices Menu / Attachment Select Wheel

- Tactical Device Button 1 - Tactical Device Group 1 On/Off - White light (VIS)
    - Continuous Press - Hold On
    - Double Press - Toggle On/Off

- Tactical Device Button 2 - Tactical Device Group 2 On/Off - Laser (VIS/IR) / Illuminator (IR)
    - Continuous Press - Hold On
    - Double Press - Toggle On/Off
    - Default Modes:
        - Mode 1 (VIS) - Laser VIS
        - Mode 2 (IR) - Laser IR
        - Mode 3 (IR) - Laser IR + Illuminator IR
        - Mode 4 (IR) (disabled by default, can be enabled in settings) - Illuminator IR

- Tactical Device Button 3 (optional) - Laser VIS/IR Mode Switch
    - Switch TDG2 function between VIS Mode and last used IR Mode; e.g. Mode 1 (Laser VIS) and Mode 2/3/4 (last used)

- Tactical Device Button 4 (optional) - Laser Illuminator Mode Switch
    - Switch TDG2 function between IR Modes; e.g. Mode 2 (Laser IR), Mode 3 (Laser IR + Illuminator IR)

- Tactical Device Button 5 (optional) - Illuminator (IR) narrow/wide beam divergence

- Tactical Device Buttons 3 & 4 & 5 - Laser VIS/IR Mode Switch + Laser Illuminator Mode Switch + Illuminator (IR) narrow/wide beam divergence
    - Single Press - Tactical Device Button 4 - Switch TDG2 function between IR Modes; e.g. Mode 2 (Laser IR), Mode 3 (Laser IR + Illuminator IR), Mode 4 (Illuminator IR)
    - Double Press - Tactical Device Button 5 - Switch Illuminator (IR) narrow/wide beam divergence
    - Hold Press - Tactical Device Button 3 - Switch TDG2 function between VIS Mode and last used IR Mode; e.g. Mode 1 (Laser VIS) and Mode 2/3/4 (last used)

## Ground Branch

- Mouse Thumb Button 1 (back) - Tactical Device Group 1 On/Off - White light (VIS)
- Mouse Thumb Button 2 (forward) - Tactical Device Group 2 On/Off - Laser (VIS/IR) / Illuminator (IR)

- CapsLock - Tactical Device Buttons 3 & 4 & 5 - Laser VIS/IR Mode Switch + Laser Illuminator Mode Switch + Illuminator (IR) narrow/wide beam divergence
    - Single Press - Tactical Device Button 4 - Laser Illuminator Mode Switch
    - Double Press - Tactical Device Button 5 - Illuminator (IR) narrow/wide beam divergence
    - Hold Press - Tactical Device Button 3 - Laser VIS/IR Mode Switch

- Tab - Tactical Device Button 0 / Attachment Select Wheel
    - Press - Tactical Device Group 0 On/Off - Custom, as set by player within Attachment Select Wheel
    - Hold - Attachment Select Wheel

- Home (or Mouse Wheel Left) - Tactical Device Button 4 (optional) - Laser Illuminator Mode Switch
- End (or Mouse Wheel Right) - Tactical Device Button 5 (optional) - Illuminator (IR) narrow/wide beam divergence

- Left Alt + Mouse Wheel Up - Scope Zoom In
- Left Alt + Mouse Wheel Down - Scope Zoom Out

- Middle Mouse Button - Look Around

- Mouse Wheel Up (while ADS) - Primary/Secondary sight
- Mouse Wheel Down (while ADS) - Weapon canting
- Mouse Wheel Up - Raise Weapon
- Mouse Wheel Down - Lower Weapon

- T - Squad Commands

- Page Up - Reticle Brightness Up
- Page Down - Reticle Brightness Down

## Gray Zone Warfare

- Mouse Thumb Button 1 (back) - Tactical Device Group 1 On/Off - White light (VIS)
- Mouse Thumb Button 2 (forward) - Tactical Device Group 2 On/Off - Laser (VIS/IR) / Illuminator (IR)

- CapsLock - Tactical Device Buttons 3 & 4 & 5 - Laser VIS/IR Mode Switch + Laser Illuminator Mode Switch + Illuminator (IR) narrow/wide beam divergence
    - Single Press - Tactical Device Button 4 - Laser Illuminator Mode Switch
    - Double Press - Tactical Device Button 5 - Illuminator (IR) narrow/wide beam divergence
    - Hold Press - Tactical Device Button 3 - Laser VIS/IR Mode Switch

- T - Tactical Device Button 0 / Tactical Devices Menu
    - Press - Tactical Device Group 0 On/Off - Custom, as set by player within Tactical Devices Menu
    - Hold - Tactical Devices Menu

- Mouse Wheel Left (or alternatively, Home) - Tactical Device Button 4 (optional) - Laser Illuminator Mode Switch
- Mouse Wheel Right (or alternatively, End) - Tactical Device Button 5 (optional) - Illuminator (IR) narrow/wide beam divergence

- Mouse Wheel Up - Scope Zoom In
- Mouse Wheel Down - Scope Zoom Out

- Middle Mouse Button - Look Around

- Left Alt + Mouse Wheel Up - Primary/Secondary sight
- Left Alt + Mouse Wheel Down - Weapon canting

- Insert - Reticle Next
- Delete - Reticle Previous

- Page Up - Zeroing Next Range
- Page Down - Zeroing Previous Range

## Notes

- White light:
    - Dedicated button, no double-duty with IR to reduce risk of mistaken and/or uncontrolled visible light emissions; in almost all environments, including under NODs, there are scenarios where white light may be needed instantly as a quick action/reaction.
    - Quick access, used in split second as quick action/reaction, need to control and reduce risk from visible light emissions, e.g. quick burst on/off to check area, then reposition away from emission point.
    - Beam divergence typically can't be changed for white lights attached to weapons (referring to common real-world devices).
- Laser (VIS):
    - Can double-duty button with Laser (IR), provided there's a mode switch between Laser VIS and Laser IR, as players are typically only using one or the other at the same time. Additionally, common real-world devices use a mode selector + single activation button.
    - Quick access, used in split second as action, need to control and reduce risk from visible light emissions, e.g. quick burst on/off to lase target.
- Laser (IR):
    - Can double-duty button with Laser (VIS), provided there's a mode switch, as typically only using one or the other at the same time. Additionally, common real-world devices also typically use a mode selector + single activation button.
    - Can double-duty button with Illuminator (IR), provided there's a mode switch between Laser IR and Laser IR + Illuminator IR. See additional notes under Illuminator IR.
    - Quick access, used in split second as action/reaction, need to control and reduce risk from infrared light emissions, e.g. quick burst on/off to lase target.
- Illuminator (IR):
    - Can double-duty button with Laser (IR), provided there's a mode switch, as most in-game scenarios (as opposed to real-world) require either Laser IR, or Laser IR + Illuminator IR. 
    - The IR mode (laser or laser + illuminator) is generally set based on the general ambient illumination of the environment, set once and not changed within the same environment, except when operating in CQB with friendlies or mixed CQB+distant engagement ranges/environments, where you want to quickly swap between laser only and laser + illuminator. 
    - In environments with sufficient ambient illumination, it is better to only use laser (IR) without illuminator (IR) to avoid bursting friendlies wearing NODs with excessive IR illumination (this happens) and not wash-out the laser (this typically never happens with good real-world devices, but it does happen in-game), however if the environment has insufficient ambient illumination, typically both Laser (IR) and Illuminator (IR) will be used at the same time and avoid spending time/mental effort swapping modes. Additionally, common real-world devices use a mode selector + single activation button.
    - There are very few in-game scenarios (e.g. signalling and searching) where a Illuminator IR only mode would be a significant improvement over using the Laser IR + Illuminator IR mode, to the point that disabling it as a default tactical device mode is recommended to reduce the complexity of controls, however players could enable it in game settings or via Tactical Device Group 0.
    - Illuminator IR beam divergence is set based on the environment, specifically expected engagement range and visible distance. Beam divergence can be changed (to wide beam or narrow beam) within the Tactical Devices menu or as an optional keybind.
- Tactical Device Groups (default):
	- Tactical Device Group 0 - Custom, as set by player within Tactical Devices Menu / Attachment Select Wheel
	- Tactical Device Group 1 - White Light
	- Tactical Device Group 2 - Laser (VIS), Laser (IR), Laser (IR) + Illuminator (IR)
		- Mode 1 (VIS) - Laser VIS
		- Mode 2 (IR) - Laser IR
		- Mode 3 (IR) - Laser IR + Illuminator IR
		- Mode 4 (IR), disabled by default, can be enabled in settings - Illuminator IR
- Tactical Devices Menu / Attachment Select Wheel:
	- Same as current implementation, except only affects Tactical Device Group 0, which is toggled on/off via the same key (single press)