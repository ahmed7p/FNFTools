ShowImageEvent Options Guide
----------------------------
By ahmed7p39

[ FIELD TITLE ]           | [ DESCRIPTION ]

Image Path/Name           - Path to the image file (e.g., Showimage/GGMU).
Stay Time                 - How many seconds the image stays before exiting.
ZIndex                    - Layer order; higher numbers stay on top.
Camera                    - Choose between Hud, Game, or Stage layers.
Scale                     - Size multiplier (1.0 is default size).
Scroll                    - How much the image follows the camera (0 to 1).

Starting Position         - The spawn point (Up, Down, Left, Right, Center).
Final Position            - The resting point during 'Stay Time'.
    (Options include presets or 'XY' for manual coordinates).

Duration (Start)          - Time in steps to move from Start to Final.
X (Start)                 - Horizontal offset for the Final Position.
Y (Start)                 - Vertical offset for the Final Position.
Easing Type(Start)        - The movement curve for the entry animation.

End Position              - Where the image moves to when it exits.
Easing Type(End)          - The movement curve for the exit animation.
Duration (End)            - Time in steps to move from Final to End.
X (End)                   - Horizontal offset for the End Position.
Y (End)                   - Vertical offset for the End Position.

Fade Type                 - Transparency effect (Fade In, Out, InOut, or None).
Fade Time                 - Duration of the transparency effect in seconds.

Shake Type                - Apply a vibration/shake style directly to the image.
Shake Intensity           - The pixel offset intensity or roughness of the image vibration.
Shake Axes                - Select the movement direction for the shake (X, Y, or XY).
Shake Time                - The total duration of the image shake effect in seconds.

----------------------------