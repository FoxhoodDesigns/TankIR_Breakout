Miniature TankIR shield. Intended to be attached on top of a Arduino Nano for compact size
Components are identical to regular TANKIR schematic in regards of transistor and resistor uses.
For 5V Regulator you can use anything be it a regular 7805 (Inefficient) or one of its many drop-in replacements

Pinouts are largely the same as on Open Panzer. If you face it by its little slot in the middle: The right pin of most JST-SH connectors are the 5V. The left the GND/Open-Collector.
Servo and RC are slightly annoying. A tiny + at the corner indicates the Signal pin

Please note that this board lacks extra Servo outputs and a Button Trigger to save space. This is meant to be triggered by other control boards or (with a little bit of work on the code:) Potentially a RC Input
