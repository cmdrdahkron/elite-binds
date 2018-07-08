# Dahkron's Elite:Dangerous Binds

I'm currently using an Xbox controller with which I first used the advanced joypad configuration, but found it didn't quite do everything I wanted and I still had to reach for the keyboard from time to time.  So I tried using [this guy's config](https://forums.frontier.co.uk/showthread.php?t=71532) and whilst it's really good I had trouble remembering what was what and it didn't feel entirely logical to me.

So after much tweaking and experimentation I've created my own, based somewhat on the one above (same keyboard binds, for example) and arranged it in a way that is much easier for me to remember and still has everything I could possibly need at my fingertips.

I wondered if other Xbox controller users might be interested in trying it too.

**UPDATE:** I've added a config for the PS4 controller too.

## Rationale

There are three role specific modifier buttons.  ![A](images/a_s.jpg) is for combat, ![B](images/b_s.jpg) is for ui and ![X](images/x_s.jpg) is for utilities.  That way there's one less thing for me to think about and I just know that for example holding A yields combat related actions (targeting, hardpoints, weapon groups, etc).

![Y](images/y_s.jpg) has one single purpose, which is to target ahead.

### Bindings

![Supercruise Bindings](images/xbox/supercruise.png)

![System bindings](images/xbox/system.png)

![Landing overrides](images/xbox/landing.png)

## Installing

1. Start &rarr; Run &rarr; `%LOCALAPPDATA%`
2. Go to Frontier Developments &rarr; Elite Dangerous &rarr; Options &rarr; Bindings
3. Copy [Dahkron-Xbox.binds](https://raw.githubusercontent.com/cmdrdahkron/elite-binds/master/Dahkron-Xbox.binds) or [Dahkron-PS4.binds](https://raw.githubusercontent.com/cmdrdahkron/elite-binds/master/Dahkron-PS4.binds) into Bindings folder (right click and save either of these links)
4. Run Elite, go to controls options and select it from the preset menu

## Changes

##### 18/07/08

* FLIGHT THRUST > VERTICAL THRUST AXIS: added small deadzone
* FLIGHT LANDING OVERRIDES: Added Forward and Backward Thrust on dpad_up and down
* FLIGHT MISCELLANEOUS: Swap "warp" binding to "Toggle Frame Shift Drive"
* MISCELLANEOUS > SHIP LIGHTS : ![A](images/a_s.jpg)+![X](images/x_s.jpg)+dpad_up
* MODE SWITCHES > AUTO FOCUS ON TEXT INPUT FIELD: off (was on)
* UPTHRUSTBUTTON: keyboard binding was W►up S►down now is R►up F►down
* Added keyboard bindings for WINGMAN and NAV LOCK (7890-)
* Rearranged the XML to match the order the game wants. Now it's easier to use a diff-tool
* Added binding for ground vehicules
* Converted to new buttons names :
```
Pad_DPadUp    ► GamePad_DPadUp
Pad_DPadDown  ► GamePad_DPadDown
Pad_DPadLeft  ► GamePad_DPadLeft
Pad_DPadRight ► GamePad_DPadRigh
Pad_Start     ► GamePad_Start
Pad_Back      ► GamePad_Back
Pad_LThumb    ► GamePad_LThumb
Pad_RThumb    ► GamePad_RThumb
Pad_LBumper   ► GamePad_LBumper
Pad_RBumper   ► GamePad_RBumper
Pad_A         ► GamePad_FaceDown
Pad_B         ► GamePad_FaceRight
Pad_X         ► GamePad_FaceLeft
Pad_Y         ► GamePad_FaceUp
Pad_LStickX   ► GamePad_LStickX
Pad_LStickY   ► GamePad_LStickY
Pad_RStickX   ► GamePad_RStickX
Pad_RStickY   ► GamePad_RStickY
Pad_LTrigger  ► Pos_GamePad_LTrigger
Pad_RTrigger  ► Pos_GamePad_RTrigger
Pad_Unplugged ► GamePad_Unplugged
```

##### 17/03/15

 * Added a PS4 binds file (thanks to my mate Jon!)

##### 22/01/15

* Moved jettison cargo to ![A](images/a_s.jpg)+![X](images/x_s.jpg)+RThumb as it conflicted with ship lights on the same binding. Ship lights are ![X](images/x_s.jpg)+RThumb. This puts all the 'smuggle' type actions together on ![A](images/a_s.jpg)+![X](images/x_s.jpg).
* Added ![A](images/a_s.jpg)+![X](images/x_s.jpg)+LBumper and ![A](images/a_s.jpg)+![X](images/x_s.jpg)+RBumper to set thrust to 0 and 75% respectively.
* Removed the crosshair.  Sorry, it bugged me.  You can turn it on again by switching on 'Show mouse widget' in the control options after you've loaded the preset.

##### 20/01/15

* Fixed a couple of errors on the diagrams.

## Contributing

Please feel free to fork, submit pull requests and/or create issues.
