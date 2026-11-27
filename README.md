# M406B Compressor Limiter · Dynamics

Ward-Beck Systems M406B, 1968|1. Wiki page: [M406B on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M406B.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 15 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 2 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 3 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 31 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 5 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 4 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 36 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [7 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1969 - M406B - P4.jpg](MANUALS/1969%20-%20M406B%20-%20P4.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Compression ratio** | Compression mode 2:1, 3:1, 5:1, 10:1 and L, Limit mode 20:1 |
| **Compression ratio** | 25dB |
| **Attack time** | Compression 10 milli sec |
| **Limit** | 100 micro sec |
| **Recovery time** | 500 msec, sec, sec, 5 sec |
| **Dees sing** | Control incorporated |
| **Phasing** | The low terminal number of the input pair and the low terminal number of the output pair are in phase. |
| **Power requirements** | 48 volts dc regulated from M648 or equivalent. 100 ma |
| **Ambient temperature** | 00 to 600c |
| **Dimensions** | 1.58w X 6.625L X 6D (depth below panel) inches |
| **Weight** | lbs net. |

## Circuit description

From [1969 - M406B - P7.jpg](MANUALS/1969%20-%20M406B%20-%20P7.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

Page off the compression or limiting action. Sw3-6 (portion of the slope switch) varies the Threshold level to 21 as the slope selection is changed. Also integral to 21 is the de-essing circuit which gives up to 8dB of boost at 6kHz increasing the amount of compression to the high frequency components present in the program material 21 output is coupled via C39 to T2 the secondary of which drives the detection rectifiers CR7 to CRlO_ The rectified audio signal is amplified by 25 _ The amount of gain this amplifier has determines the slope of the compressor 25 output feeds the compressor averaging circuitry which determines how fast compression takes place (determined by R102 and C37) and the recovery rate determined by the resistive values selected by Sw5, c38 is the main storage capacitor _ Q8 is high impedance source follower used to take the correction signal developed at its gate and drive the gain reduction meter amplifier as well as the comparator 24. The correction voltage developed at the source of Q8 is applied to pin 2 of comparator 24, CR3, CR4, R85 and R86 is linearizing circuit to correct for the logarithmic characteristics of the derived error correct ing voltage. The other input applied to pin of comparator 24 is saw tooth voltage with nominal amplitude of 3V P-p. The driving signal appearing at pin of 24 is var ing width pulse the duration of which is determined by the magnitude of the error correcting voltage applied to pin 2. Q4 and Q5 form free running oscillator with approximately 750kHz. frequency of Q6, R84 C32 is saw tooth forming circuit. Each time 06 is driven to saturation C32 is discharged and when it reaches an amplitude of 3V, 06 is again driven to saturation discharging C32. Level set control Rlll applies small amount of bias voltage to pin 2 of 24 and is adjusted to give approximately 2 dB of attenuation to the audio signal with the compressor switch Sw6 in the Off position. (Use this control to set compressor gain to unity) Q9 is the meter amplifier to amplify the error signal to magnitude capable of driving standard VU meter. Rl17 is the

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS3VKS2FtYkFnSE0/view?resourcekey=0-zEOxmOt8f6tiwm4vlZ_IlA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS3VKS2FtYkFnSE0&resourcekey=0-zEOxmOt8f6tiwm4vlZ_IlA" width="240" alt="1969 - M406B - wbsps - module - m406b compressors.jpg"></a><br><sub>1969|2 · wbsps - module - m406b compressors</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKai0xNHFHNlFsTVE/view?resourcekey=0-MfoBaFmgOh-cyP0bD6qV8g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKai0xNHFHNlFsTVE&resourcekey=0-MfoBaFmgOh-cyP0bD6qV8g" width="240" alt="1969 - M406B - wbsps - promo - m406b comp - 003.jpg"></a><br><sub>1969|2 · wbsps - promo - m406b comp - 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUllDTTJ5d0dXX1k/view?resourcekey=0-4ZIXJ2R8fWsucI7XNtJDwg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUllDTTJ5d0dXX1k&resourcekey=0-4ZIXJ2R8fWsucI7XNtJDwg" width="240" alt="1969 - M406B - wbsps - promo - m406b comp - 004.jpg"></a><br><sub>1969|2 · wbsps - promo - m406b comp - 004</sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1ZW7WEzyC340rOKXubBQ6AbNiBKe2PAvR/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1ZW7WEzyC340rOKXubBQ6AbNiBKe2PAvR" width="240" alt="1969 - M406B - SCHEMATIC CEILING CONTROL MODIFIED.png"></a><br><sub>1969|2 · SCHEMATIC CEILING CONTROL MODIFIED · <a href="SCHEMATICS/1969%20-%20M406B%20-%20SCHEMATIC%20CEILING%20CONTROL%20MODIFIED%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `WBS M406b Schematic and layout.jpg`

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1EODqKb4km-KTaxylSV1m-AWMdd6mbwAk/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1EODqKb4km-KTaxylSV1m-AWMdd6mbwAk" width="240" alt="1969 - M406B - IGRO RECX SYSIES LTU MTE DEC.png"></a><br><sub>1969|2 · IGRO RECX SYSIES LTU MTE DEC</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQjFuc1VmVHYzVk0/view?resourcekey=0-g0BZBK77swz-Jqvv-o6CpA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQjFuc1VmVHYzVk0&resourcekey=0-g0BZBK77swz-Jqvv-o6CpA" width="240" alt="1969 - M406B - P1.jpg"></a><br><sub>1969|2 · P1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUjZYWS1IVlBkSDQ/view?resourcekey=0-UHDs6Z2NjkEraBQGJli8oQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUjZYWS1IVlBkSDQ&resourcekey=0-UHDs6Z2NjkEraBQGJli8oQ" width="240" alt="1969 - M406B - P10.jpg"></a><br><sub>1969|2 · P10</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVmp4bWxiVm1nc0U/view?resourcekey=0-PZrRoynP9K33QOVzQnsWeg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVmp4bWxiVm1nc0U&resourcekey=0-PZrRoynP9K33QOVzQnsWeg" width="240" alt="1969 - M406B - P11.jpg"></a><br><sub>1969|2 · P11</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV0NudTd5VXlXVkk/view?resourcekey=0-g2oOftpqv4OAYH0HyOaIoQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV0NudTd5VXlXVkk&resourcekey=0-g2oOftpqv4OAYH0HyOaIoQ" width="240" alt="1969 - M406B - P12.jpg"></a><br><sub>1969|2 · P12</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaW41UHZMSmF4bkU/view?resourcekey=0-ezxHN5lffVBx7QZlnjYTig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaW41UHZMSmF4bkU&resourcekey=0-ezxHN5lffVBx7QZlnjYTig" width="240" alt="1969 - M406B - P13.jpg"></a><br><sub>1969|2 · P13</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQjZULU0tNzIxRkk/view?resourcekey=0-t5tmxMvMw3OFvLtTCaofDQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQjZULU0tNzIxRkk&resourcekey=0-t5tmxMvMw3OFvLtTCaofDQ" width="240" alt="1969 - M406B - P14.jpg"></a><br><sub>1969|2 · P14</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdU5qenZ5a19JSFE/view?resourcekey=0-_guQS71UWWVdFjGpMUX2Lw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdU5qenZ5a19JSFE&resourcekey=0-_guQS71UWWVdFjGpMUX2Lw" width="240" alt="1969 - M406B - P15.jpg"></a><br><sub>1969|2 · P15</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb2Ewa3NoYXNka3c/view?resourcekey=0-CSBQ2MBYCIzUu1gYwL5BPA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb2Ewa3NoYXNka3c&resourcekey=0-CSBQ2MBYCIzUu1gYwL5BPA" width="240" alt="1969 - M406B - P16.jpg"></a><br><sub>1969|2 · P16</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVHEtUlRIeHVDa0U/view?resourcekey=0-aHnQxdOHiHkCv00GxzY2dg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVHEtUlRIeHVDa0U&resourcekey=0-aHnQxdOHiHkCv00GxzY2dg" width="240" alt="1969 - M406B - P17.jpg"></a><br><sub>1969|2 · P17</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKODF0dlBtaTBlQkE/view?resourcekey=0-ezhZbQezYy4AM8bl3UEq8g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKODF0dlBtaTBlQkE&resourcekey=0-ezhZbQezYy4AM8bl3UEq8g" width="240" alt="1969 - M406B - P18.jpg"></a><br><sub>1969|2 · P18</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYW9xMF9GSTJDck0/view?resourcekey=0-jnIt52KGkGyuI7xG37STbw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYW9xMF9GSTJDck0&resourcekey=0-jnIt52KGkGyuI7xG37STbw" width="240" alt="1969 - M406B - P2.jpg"></a><br><sub>1969|2 · P2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUE10ajBCSHJJY3M/view?resourcekey=0-C4HnZjCRq0Q1Q7cAMBDfkg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUE10ajBCSHJJY3M&resourcekey=0-C4HnZjCRq0Q1Q7cAMBDfkg" width="240" alt="1969 - M406B - P3.jpg"></a><br><sub>1969|2 · P3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMk9xYjlFdmpFazQ/view?resourcekey=0-Eg0OTcuOctFICD-LfvGlfQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMk9xYjlFdmpFazQ&resourcekey=0-Eg0OTcuOctFICD-LfvGlfQ" width="240" alt="1969 - M406B - P4.jpg"></a><br><sub>1969|2 · P4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHIxNHIwNGlQSFE/view?resourcekey=0-6BwBviaoyGnekZsdsJHEmQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHIxNHIwNGlQSFE&resourcekey=0-6BwBviaoyGnekZsdsJHEmQ" width="240" alt="1969 - M406B - P5.jpg"></a><br><sub>1969|2 · P5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZGV0Ym91T3F4dk0/view?resourcekey=0-6_eE0ivHGZ3_BAj7d07J1g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZGV0Ym91T3F4dk0&resourcekey=0-6_eE0ivHGZ3_BAj7d07J1g" width="240" alt="1969 - M406B - P6.jpg"></a><br><sub>1969|2 · P6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRUhJb2Y2YzFpNUE/view?resourcekey=0-lGDFB_4M4RcRsdYTRdSZWw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRUhJb2Y2YzFpNUE&resourcekey=0-lGDFB_4M4RcRsdYTRdSZWw" width="240" alt="1969 - M406B - P7.jpg"></a><br><sub>1969|2 · P7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVE51LTVVbko1eUE/view?resourcekey=0-WySMXw5xUnAfkwlaafiOhQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVE51LTVVbko1eUE&resourcekey=0-WySMXw5xUnAfkwlaafiOhQ" width="240" alt="1969 - M406B - P8.jpg"></a><br><sub>1969|2 · P8</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVHVnRXN5UTE0Wms/view?resourcekey=0-8FXPdOKGtz7LQomm0l1BAA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVHVnRXN5UTE0Wms&resourcekey=0-8FXPdOKGtz7LQomm0l1BAA" width="240" alt="1969 - M406B - P9.jpg"></a><br><sub>1969|2 · P9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1wWfMD5LEh9b8i9zsNxbdSHNNKRbDSQ_l/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1wWfMD5LEh9b8i9zsNxbdSHNNKRbDSQ_l" width="240" alt="1969 - M406B - WBSps.ca - M406B - Part 1 - Brighter.png"></a><br><sub>1969|2 · WBSps.ca - M406B - Part 1 - Brighter</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1nsHBV9uRBErSeR5v8bzYFXVD01wLTRAo/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1nsHBV9uRBErSeR5v8bzYFXVD01wLTRAo" width="240" alt="1969 - M406B - WBSps.ca - M406B - Part 1.png"></a><br><sub>1969|2 · WBSps.ca - M406B - Part 1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1P_Cov2CV3f-N13HJB6UItPA1NjLK8QVU/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1P_Cov2CV3f-N13HJB6UItPA1NjLK8QVU" width="240" alt="1969 - M406B - WBSps.ca - M406B - Part 2 - Brighter.png"></a><br><sub>1969|2 · WBSps.ca - M406B - Part 2 - Brighter</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1bwnOPnQ_qox4mV_HlQuKwSGdgx5EPONm/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1bwnOPnQ_qox4mV_HlQuKwSGdgx5EPONm" width="240" alt="1969 - M406B - WBSps.ca - M406B - Part 3 - Brighter.png"></a><br><sub>1969|2 · WBSps.ca - M406B - Part 3 - Brighter</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1JRYBPV2-dqQxwPJGlhQk8TNHUZdFM82K/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1JRYBPV2-dqQxwPJGlhQk8TNHUZdFM82K" width="240" alt="1969 - M406B - WBSps.ca - M406B compressor.jpg"></a><br><sub>1969|2 · WBSps.ca - M406B compressor</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV0ZyaERmSlZaT2s/view?resourcekey=0-ZEQctXG2UuYgjndGItJcUg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV0ZyaERmSlZaT2s&resourcekey=0-ZEQctXG2UuYgjndGItJcUg" width="240" alt="1969 - M406B - Ward Beck Systems M406B 2.jpg"></a><br><sub>1969|2 · Ward Beck Systems M406B 2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRklla1RvTm11Qnc/view?resourcekey=0-XGLx69fhjRMBZHz7S4Kiag" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRklla1RvTm11Qnc&resourcekey=0-XGLx69fhjRMBZHz7S4Kiag" width="240" alt="1969 - M406B - Ward Beck Systems M406B.jpg"></a><br><sub>1969|2 · Ward Beck Systems M406B</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRGRFbFl1Nm5mNlk/view?resourcekey=0-UXjVbqWV5mYO9obEbEVVGQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRGRFbFl1Nm5mNlk&resourcekey=0-UXjVbqWV5mYO9obEbEVVGQ" width="240" alt="1969 - M406B - wbsps - promo - m406b comp - front.jpg"></a><br><sub>1969|2 · wbsps - promo - m406b comp - front</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ/view?resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ&resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" width="240" alt="1975 - M406B - PRICE LIST - PRICE LIST.jpg"></a><br><sub>1975|8 · PRICE LIST - PRICE LIST</sub></td></tr>
</table>

Not on Google Drive yet: `19xx - M406B - M 406B Waveforms.jpg`, `Archived - wbsps - promo - m406b comp - 002.jpg`

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1968 - B 406-02--13 - COMPRESSOR SCHEMATIC CEILING CONTROL MODIFIED - ISS 2.kicad_sch](KICAD/1968%20-%20B%20406-02--13%20-%20COMPRESSOR%20SCHEMATIC%20CEILING%20CONTROL%20MODIFIED%20-%20ISS%202.kicad_sch)
- [1969 - M406B - SCHEMATIC CEILING CONTROL MODIFIED.kicad_sch](KICAD/1969%20-%20M406B%20-%20SCHEMATIC%20CEILING%20CONTROL%20MODIFIED.kicad_sch)
- [M406B.kicad_sym](KICAD/M406B.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
