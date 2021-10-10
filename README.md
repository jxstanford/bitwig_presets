# bitwig_presets

Repository of presets I've created in Bitwig Studio 4.x or later.

## DIN Sync Grid v1.0
Based on https://e-rm.de/data/E-RM_report_HowToDinSync_10_14_EN.pdf

### Usage examples
- Set the CV outs to ES8 ports for example, then to Pam's and Metron. 
- Pam's Run = Y, 24ppqn
- Metron Reset = Snc, 24ppqn

### Notes
- grid is set to quarter note phase cycles
- scale is set to 24:1 for 24 pulses per quarter note
- OR gate ensures clock is low when stopped/paused
- AND gate ensures Run is high when playing or paused (non-zero phase)

