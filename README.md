# Polykit-X Voice Card

# Pinout

| Pin # | Description          | Short         | Voltage Range | Type   | Direction | Note |
|-------|----------------------|---------------|---------------|--------|-----------|------|
| 1     | Ground               | GND           |               |        |           |
| 2     | +12V                 | +12V          |               |        |           |
| 3     | -12V                 | -12V          |               |        |           |
| 4     | +5V                  | +5V           |               |        |           |
| 5     | -5V                  | -5V           |               |        |           |
| 6     | Pitch control        | PITCH         | ±5V           | CV     |           |
| 7     | PWM                  | PWM           | 0V to 5V      | CV     |           |
| 8     | FM                   | FM            |               | Signal |           |
| 9     | Soft sync            | SSYNC         |               | Signal |           |
| 10    | Hard sync            | HSYNC         |               | Signal |           |
| 11    | Envelope Attack      | ADSR_A        | 0V to -5V     | CV     |           |
| 12    | Envelope Decay       | ADSR_D        | 0V to -5V     | CV     |           |
| 13    | Envelope Sustain     | ADSR_S        | 0V to 5V      | CV     |           |
| 14    | Envelope Release     | ADSR_R        | 0V to -5V     | CV     |           |
| 15    | Envelope Trigger     | TRIG          | 0V/5V         | Trig   |           |
| 16    | Envelope Gate        | GATE          | 0V/5V         | Gate   |           |
| 17    | Envelope Output      | ADSR_OUT      | 0V to 5V      | CV     |           |
| 18    | Enable saw signal    | SAW_ON        | 0V/5V         | Switch |           |
| 19    | Enable triangle sig. | TRIANGLE_ON   | 0V/5V         | Switch |           |
| 20    | Enable ext. signal   | EXTERNAL_ON   | 0V/5V         | Switch |           |
| 21    | Neg. freq. by ADSR   | FREQ_ADSR_NEQ | 0V/5V         | Switch |           |
| 22    | Freq. by ADSR        | FREQ_ADSR     | 0V/5V         | Switch |           |
| 23    | Res. by ADSR         | RES_ADSR      | 0V/5V         | Switch |           |
| 24    | Neg. res. by ADSR    | REF_ADSR_NEQ  | 0V/5V         | Switch |           |
| 25    | Input level 1        | LVL1          | 0V to 5V      | CV     |           |
| 26    | Input level 2        | LVL2          | 0V to 5V      | CV     |           |
| 27    | VCA                  | VCA_CV        | 0V to 5V      | CV     |           |
| 28    | Output panning       | PAN_CV        | 0V to 5V      | CV     |           |
| 29    | External input       | EXTERNAL_IN   |               | Signal |           |
| 30    | Freq. control        | FREQ_CV       | 0V to 5V      | CV     |           |
| 31    | Res. control         | RES_CV        | 0V to 5V      | CV     |           |
| 32    | Filter mode A        | FILTER_MODE_A | 0V/5V         | Switch |           |
| 33    | Filter mode B        | FILTER_MODE_B | 0V/5V         | Switch |           |
| 34    | Filter mode C        | FILTER_MODE_C | 0V/5V         | Switch |           |
| 35    | Output left          | OUT_L         |               | Signal |           |
| 36    | Output right         | OUT_R         |               | Signal |           |

Note on Pitch CV: A 100k ohm resistor on input is needed. Multiple CV sources can be added by using multiple resistors in parallel
Note on output left/right: Volume can be adjusted by changing R32/R33
