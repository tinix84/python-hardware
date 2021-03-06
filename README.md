A collection of simple Python wrappers for various test equipment and other hardware.

# Important

Note that little documentation is available and many are dated, incomplete and/or buggy!
Most of the code is probably best used as a reference for interfacing serial,
GPIB, USB, etc. devices with Python

# Description

* `t100.py` - [Times Technology T100 VHF/UHF Vector Antenna Impedance Analyzer](http://timestechnology.com.hk/support-T100.html) (serial)
* `si570.py` - [SDR Kits QRP2000 USB-Controlled Synthesizer](http://sdr-kits.net/QRP2000_Description.html) with [PE0FKO firmware](https://code.google.com/p/usbavrsi570/) (USB)
* `signalhound` - [Signal Hound USB-SA44 Spectrum Analyzer](https://www.signalhound.com/products/) (USB)
* `hp8657a.py` - [Hewlett Packard 8657A Signal Generator](http://www.home.agilent.com/en/pd-1000002201%3Aepsg%3Apro-pn-8657A/synthesized-signal-generator-100-khz-to-1040-mhz) (GPIB\*)
* `rotor` - [Yaesu GS-232A and Rotor-EZ antenna rotors](http://www.universal-radio.com/catalog/hamrot/4228.html) (serial)
* `rsa300` - [Tektronix RSA306 Spectrum Analyzer](http://www.tek.com/spectrum-analyzer/rsa306) (USB)
* `hp8590.py` - [HP/Agilent HP8590 Spectrum Analyzer](http://www.testequipmentdepot.com/usedequipment/hewlettpackard/spectrumanalyzers/8590de.htm) (GPIB)

\* requires PyVISA < 1.6

# License

All of the code contained here is licensed by the GNU General Public License v3.

If you modify anything here then feel free to send a pull request!
