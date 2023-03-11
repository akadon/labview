# LabVIEW

School projects for NI LabVIEW. Temperature regulation with DAQ hardware, signal analysis, and utility VIs.

Requires LabVIEW to open the `.vi` files.

## Files

- `Temp-1.vi` - temperature control system with hysteresis regulation. Reads from a DAQ input (sine wave 0 to -5V), displays real-time temperature chart with min/max/mean tracking, and toggles heating/cooling outputs based on configurable upper/lower thresholds. Front panel shows current temperature, regulation count, and control buttons (Kühlung ein / Heizung ein).
- `Sig-Ana.vi` - signal analysis with configurable sampling rate and waveform display
- `mw-dar.vi` - waveform display (Kurvenverlauf) with time axis
- `ZuFaGen-1_V01.vi` - random number generator

Screenshot in `docs/Image.jpg` shows the Temp-1.vi front panel and block diagram.
