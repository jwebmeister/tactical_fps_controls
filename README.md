# tactical_fps_controls
 My dream (proposed) controls for tactical FPS, specifically for controlling weapon attached tactical devices, in games like Ground Branch and Gray Zone Warfare.  
 
 I made a VoiceAttack profile to demonstrate the use of these controls in Ground Branch, see [YouTube video link](https://www.youtube.com/watch?v=2RRXgJaxBos). I've included the VA profiles, which are proofs of concept, so be warned it's not user friendly and some monkeying will be required if it's used, more specifically the controls set as detailed [below](#ground-branch).

[![YT Video demonstrating controls in Ground Branch](https://img.youtube.com/vi/2RRXgJaxBos/0.jpg)](https://www.youtube.com/watch?v=2RRXgJaxBos)

Updated: I implemented another version ("*Scroll*" VA profile), which the details below and the [update video](https://www.youtube.com/watch?v=YHG_dfX_JfI) now reflect. Hold CapsLock and scroll mouse wheel to select mode & release CapsLock to set the laser + illuminator mode from a list of modes (ideally shown as UI in-game). It feels better than what I had initially, at least for those without scroll wheel left/right. Credit to Evil Gamer on the GZW discord for the suggestion.

[![Quick updated YT Video demonstrating scroll wheel controls in Ground Branch](https://img.youtube.com/vi/YHG_dfX_JfI/0.jpg)](https://www.youtube.com/watch?v=YHG_dfX_JfI)

## General Controls Scheme

- Custom Tactical Device Group On/Off + Tactical Devices Menu
    - Press - Custom Tactical Device Group toggle On/Off, as set by player within Tactical Devices Menu
    - Hold - Tactical Devices Menu / Attachment Select Wheel

- White light (VIS) On/Off
    - Continuous Press - Hold On
    - Double Press - Toggle On/Off

- Laser (VIS/IR) + Illuminator (IR) On/Off
    - Continuous Press - Hold On
    - Double Press - Toggle On/Off
    - Default Modes:
        - Mode 0 (VIS) - Laser VIS
        - Mode 1 (IR) - Laser IR
        - Mode 2 (IR) - Laser IR + Illuminator IR wide beam
        - Mode 3 (IR) - Laser IR + Illuminator IR narrow beam
        - Mode 4 (IR) - Illuminator IR wide beam
        - Mode 5 (IR) - Illuminator IR narrow beam

- Laser + Illuminator Mode Selector
    - Hold - Show current laser + illuminator mode
    - Hold + Mouse Wheel Scroll Up/Down - Select desired laser + illuminator mode 0/1/2/3/4/5 (shown on ui)
    - Release - Set desired laser + illuminator mode 0/1/2/3/4/5

## Ground Branch

- Mouse Thumb Button 1 (back) - White light (VIS) On/Off
- Mouse Thumb Button 2 (forward) - Laser (VIS/IR) + Illuminator (IR) On/Off

- CapsLock - Laser + Illuminator Mode Selector
    - Hold - Show current laser + illuminator mode
    - Hold + Mouse Wheel Scroll Up/Down - Select desired laser + illuminator mode 0/1/2/3/4/5 (shown on ui)
    - Release - Set desired laser + illuminator mode 0/1/2/3/4/5

- Tab - Custom Tactical Device Group On/Off + Attachment Select Wheel
    - Press - Custom Tactical Device Group toggle On/Off, as set by player within Attachment Select Wheel
    - Hold - Attachment Select Wheel

- Home (or Mouse Wheel Left) - Laser + Illuminator Mode Switch (optional)
- End (or Mouse Wheel Right) - Illuminator (IR) narrow/wide beam divergence (optional)

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

- Mouse Thumb Button 1 (back) - White light (VIS) On/Off
- Mouse Thumb Button 2 (forward) - Laser (VIS/IR) + Illuminator (IR) On/Off

- CapsLock - Laser + Illuminator Mode Selector
    - Hold - Show current laser + illuminator mode
    - Hold + Mouse Wheel Scroll Up/Down - Select desired laser + illuminator mode 0/1/2/3/4/5 (shown on ui)
    - Release - Set desired laser + illuminator mode 0/1/2/3/4/5

- T - Custom Tactical Device Group On/Off + Tactical Devices Menu
    - Press - Custom Tactical Device Group toggle On/Off, as set by player within Tactical Devices Menu
    - Hold - Tactical Devices Menu

- Home (or Mouse Wheel Left) - Laser + Illuminator Mode Switch (optional)
- End (or Mouse Wheel Right) - Illuminator (IR) narrow/wide beam divergence (optional)

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
    - There are very few in-game scenarios (e.g. signalling and searching) where a Illuminator IR only mode would be a significant improvement over using the Laser IR + Illuminator IR mode, to the point that disabling it as a default tactical device mode is recommended to reduce the complexity of controls, however players could enable it in game settings or via Custom Tactical Device Group.
    - Illuminator IR beam divergence is set based on the environment, specifically expected engagement range and visible distance. Beam divergence can be changed (to wide beam or narrow beam) within the Tactical Devices menu or as an optional keybind.
- Tactical Device Groups (default):
	- Custom, as set by player within Tactical Devices Menu / Attachment Select Wheel
	- White Light (VIS)
	- Laser (VIS/IR) + Illuminator (IR)
		- Mode 0 (VIS) - Laser VIS
        - Mode 1 (IR) - Laser IR
        - Mode 2 (IR) - Laser IR + Illuminator IR wide beam
        - Mode 3 (IR) - Laser IR + Illuminator IR narrow beam
        - Mode 4 (IR) - Illuminator IR wide beam
        - Mode 5 (IR) - Illuminator IR narrow beam
- Tactical Devices Menu / Attachment Select Wheel:
	- Same as current implementation, except only affects Custom Tactical Device Group, which is toggled on/off via the same key (single press)
- From testing in games like Ground Branch, Gray Zone Warfare, EFT, other tactical shooters and UE5 editor, I've found:
    - Having to press & hold on any more than two buttons for tactical devices (specifically mouse thumb buttons as the most ergonomic, but also tried keyboard keys like T, caps lock etc.) was too uncomfortable or unintuitive for me.
    - Toggling on/off can too often be too slow or unresponsive (feels like dropped input at times), particularly for quick 'firefly' lasing or flashing, which is almost necessary when the enemy also has NODs or when using white light.
    - The attachment wheel / tactical devices list with individual tactical device functions is too slow.
    - Cycling through every tactical device mode by a single button press, particularly without UI to indicate mode (EFT), is too slow/cumbersome and can unnecessarily emit visible or IR light.
