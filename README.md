# custom-tw3-settings

Contains custom gamepad settings for The Witcher 3 Enhanced Edition Redux

## Combat Mappings

```
xbox A / ps Cross: Roll
xbox B / ps Circle: Dodge
xbox Y / ps Triangle: Cast Selected Sign
xbox X / ps Square: Parry/Counterattack
```

```
LBumper: Medium Distance Modifier
LTrigger: Long Distance Modifier
RBumper: Light Attack
RTrigger: Heavy Attack
```

```
Dpad-Up: Radial Menu
Dpad-Right: Toggle Sheath Silver Sword
Dpad-Left: Toggle Sheath Steel Sword
Dpad-Down: Quick Use Item (torch, bomb etc.)
```

## Quick Meditation Fix

By default, hold left stick to pass time does not work. This is due to passing time being linked to "Sprint". By default, on gamepad the left stick only handle "Sprint Toggle". To fix this I've mapped pass time("Sprint") to xbox X / ps Square. You can change this by changing the "Sprint" control under [ScriptedActions] and [Exploration]. 

Still working on fixing the meditation toggle. 

## Recommendations

Left thumbstick is pretty sensitive, I recommend using Steam and changing controller configurations there. Use the default Witcher 3 configuration, then modify the left stick so that the acceleration is atleast relaxed (I use wide). Change the deadzone to custom and make it a square, and play around with the upper bounds til it feels ok.

These changes are needed because the left stick also controls whether Geralt will perform a close attack/medium attack/far attack when using manual targeting and is extremely sensitive. With the above changes, it's much easier to be deliberate when wanting to do a close attack/far attack. 
