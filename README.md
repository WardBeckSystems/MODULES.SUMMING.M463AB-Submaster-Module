# M463AB Submaster Module · Summing

Ward-Beck Systems M463AB, 1986|19. Wiki page: [M463AB on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M463AB.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 57 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 10 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 6 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 219 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 2 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 14 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 36 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1986 - M463AB - P003 1-1.jpg](MANUALS/1986%20-%20M463AB%20-%20P003%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | dB +7 -0.5 dB (with fader &quot;in-hand&quot; position) |
| **Frequency response** | +/ -0.25 dB from 20 Hz |
| **Noise** | dB below dBm nomina output level (20 Hz 20 kHz } |
| **Harmonic distortion** | Less than 0.25% from Hz kHz +28 dBm less Typically less than 0.05% cross most bandwidth) |
| **Source impedances** |  |
| &nbsp;&nbsp;Summing | 30,000 ohms, balanced |
| **Input impedances** |  |
| &nbsp;&nbsp;Summing | Less than ohms |
| **Output impedance** | Less than 100 ohms (at 8-109A ouiput and DIRECT output Less than 200 ohms MONITOR output. |
| **Load impedance** | 600 ohms, balanced (at insertion Point and DIRECT output). |
| **Output level** | -10 aBm nomina insertion dBm nominal DIRECT output _ +30 dBm maximum |
| **Phasing** | Input and output terminals designated by numbers are Phase |
| **Power requirements** | +/-25 volts dc, 200 mA maximum. MA nominal |
| **Ambient temperature** | degrees Celsius |
| **Dimensions** | wide 7.0&quot; high 6.5 (41 Mm 178 Mm 165 Mm deep |

## Circuit description

From [1986 - M463AB - Submaster Module (2).pdf](MANUALS/1986%20-%20M463AB%20-%20Submaster%20Module%20(2).pdf) pages 4-9 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M46 3AB i s designed to accept combined 0&lt;' mixed feeds from pre,,;ou sly a S5 i g ned mixing channel inputs. The assigned mixing channel inputs a r-e amplified and routed to thea p PrQ p r-;a te points within the console system.

Input and Summing Ampl ifi er

The signal originating frQm thee x te r-n a l mixing n e twor-k i sap plied to the summing cUr'&quot;r'&quot;en t nodes of the input amp l i fie r vi.. edge connector pins \ and A.

0 1 t h rough 08 fOr'&quot;m &quot; surrm ing amp l i fie r comprising a b a i anced input and an.un b.. ian c e d output. to correct for smalls y stem level var i aHon's, trim pot R7 i sin corp or&quot; ted asp art of the pre amplifier. The differ enti alba lance adj u s tme n t control R6 serves to minimize Common mode types i g na l s originating ahead oft h e amplifier. C12 couples the output of the summing &quot; mpl if i e r toe lo w-p ass filter consisting of R22, R 23, R24, C13, C14, CIS and 21. The 3 d B ro ll_off point i s loc&quot; ted a tap pro x i ma tel y 40 kHz.

The output of 2t is cO&lt;.Jpled through C1 8 tot he output amp l i f i er 8-10911..

8-10911. Output Amplifier and INSERT

The 8 -109 11. amp l i fie r r -ets est h e nominal signal level to.O dBm. The output i sac t i ve l y balanced &quot; n d fed tot h e &quot;inse rt point &quot; at pins 15 &quot; n d S.

Pins 15 and S a r'&quot;e us u&quot;ll y connected t o a n o r-maH ed set of insert jacks, with the output 5 ide connected tot h e subm&quot; s t e r fade r.

The reoeO&lt;.Jt put is return ed tot he module on pins 9 &quot; n d K. The feed forth e PRE f AOE outputs i s normally picked u pat them i x ing fade r input and i s returned tot h emo d ul e via pins 14 and R.

8-109F Boost &quot;r Amplifier

This &quot; mp t i fie rope rates with again o f 33 dB. I t.-ec overS the I S dB

&quot; i n-h &quot;n d&quot; 10 5 05 incur red b y the fader and provides add i ti o n alga i n

top r odu ce a nominal level of +8 dBm at its output.

WAR O - BECKS YSTEMS L.to.

**CIRCUIT OESCR IPT ION**

DIRECT Output on d MONITOR Output

Tn e OlR ECT o ulPul ol)gea rs atp ins 16 and T. An additional Isolated oulPul isp ro v ided atp ins 17/U. T~ latter ou tpU I maybe utilized as a meter ing and /or mon ilor lakeoff. Care should betaken to restrict loading of this OUlput 10 SK oI'lms or higher.

Mas l er Output sd and PAN Conlrol

Ale f t and aright MASTER output are also being fed b y t ne 8_ 109F outputs ig n al. Tn a y ara routed via PANs witch SWl and PAN Con l rol R29 to R32. T~ master outpul sore connected to the apPl&quot;'09r lal. module OUtput terminals via summing n elwork res islors 10 be com_ b ined witH feeds from o t n e r sub mas le r m l&quot; ing channels.

Au,,' l la &quot;y Outputs

In addition, a SOLO output i s e veuee te via SW7, to allow selective mon it_ ing of the par l icu l.,r s ubmas ter channel. Ot~r feeds or lg ln.,ti n g from tne 8 _109F amplifier are supplied 10 I ~ P OSTFADE RS, FB and PAc han nell.

PRE /POST Selector SwitChes and Level Controls

P RE/POST l election oft ~ RS, FB and PAc h anne l sis facllh.,ted by s wl lc n e s SW2, SW3 and SW/o respectively; each swilCh Is ' followed b y its a s itOClated lev a l ccoeee r • The OUlputs oft he level con lrols a &quot;e fed to the summing OUtputl via ind iv id u ala ss ig n....... t s wl t c n e s. Fo l lo win,.. Ihe.,ss lgnment Iwitcne s, the l e OUl puts are fed to their appropriate mi,, 'ng b Uies vie lumm ingres ll tOl&quot;S.

Con t&quot;ol Functions

A de; c c o net e;on taCI il available on the SOLOs wilCh SW7.

Pow e,. SUPDI&quot; Decoupl ing

An active po we,. supply decou pll ng network consist ing o f C9 t n &quot; o ugh

Clio p,.ovides Iiolat ion between the module and the. / -25 volts u p ply

rail l. T,. an s ist or l C13 and Clio mo nit o,. the supply cur ren l. Int h e even l of excessive powers u p ply demands, such as from component

fall u,. e ora mpli';er overdrive, the current flow ing through 011 and

012 will be limited.

WAFl OSEC I&lt; SYSTEMS L.T O

**'''''' NUMBER**

cr,-, Tl9OFJJ7M006 AS

C.P~C: l tOt'&quot; &quot;&quot; uF /6 V J30 uF / 6 V eeteee ce del e leOS 10 pF Philips 2222_6 J8-10 109

CO 10 pF cs ISpF 22 t2-6J8_1 0 1S9 C' J.J p F 2222.6J8-09JJ8 C' J. J pF C&gt;O 10 u F /25 V

en 10 uF /25 V CO2 JJ u F/ l 0 V TJ 900J J6MOI OAS cta 1500 p F As&quot;l c:o C0 9 2_&quot;'C.1S J/lot m 220p F Ph ~l i p s 2222-630-03221 m JJpF 2222_6]8-103J9

ere 10 p F 2222_6]8_ 10 109 m 4.7 p F 2222-6 ]8-09478 eta 3] u F/ 10 V Kernel T39OJJ6MQ10AS c ts 0.0 22 u F As&quot;lc:o CQ9 2_MC_22lM C&gt;O 22 u F /25 V Philips 0]0 1622 9

C&quot; 22 u F /25 V C22 22 u F / 25 V C2J 22 u F / 25 V

CR, Diod&quot; del&quot; t&quot; CR' delete CR, MOloro l. lN4003

0' Transistor Nal ion al

0' PN 3645

0' 2N4401

**MFG PART NUMBER**

ce T..a n. I&quot;to.. National PNJ6 to 5 Q' PNJ569 Q' PNJ6 to 5 Q' PNJ569 Q&gt;O PNJ6 to 5

cuT IP 298 eta TIP J08

**PNJ569**

PNJ6 to 5

RO R&quot; &quot;i sto.. 1/ 4W 5'

Ph:,&quot; P.

T.. im POI etr ov 2K

R? &quot;&quot; Pl h&quot;..

s rtov 1K

0 &gt;0 R&quot; &quot; l sIO&quot; 1/ 4W 5'

Ph ~,li p s

0&quot; lK'

0&quot; '00 0 20 '00

0 22 '&quot;

**0 2J**

0 26 '20

**M~JA8 SU8MASTER MODULE**

RJll AI'

**RJ2 1**

R.... i.. tor 1! 4W 5'

Philips

A., R es l,~tor 1/ 4W 5 ~ Philips

**A&quot; 2.2**

2.2

J,l106JAB SUBMA STER MODULE

was ~ ecommen dst h e ule 0 1...e !,&gt;l~ceme n l !,&gt; 1I.~t s m.. d e by the s!'&gt;ecif ied

m~ nul~clu~e~s lo~ continued o!,&gt;lim um equip men l !,&gt;e...f o ~man ce.

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMVhtcXVzMFBCOXM/view?resourcekey=0-MgwdcLndFOjfdAdOb_b4kA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMVhtcXVzMFBCOXM&resourcekey=0-MgwdcLndFOjfdAdOb_b4kA" width="240" alt="1986 - M463AB - 463-04-102 - PAN SOLO SWICN.jpg"></a><br><sub>1986|19 · 463-04-102 - PAN SOLO SWICN · <a href="MECHANICAL/1986%20-%20M463AB%20-%20463-04-102%20-%20PAN%20SOLO%20SWICN%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZWF5Z3NDS0JOTG8/view?resourcekey=0-R6YNCt_TtYtAkZGQMV5h9w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZWF5Z3NDS0JOTG8&resourcekey=0-R6YNCt_TtYtAkZGQMV5h9w" width="240" alt="1986 - M463AB - 463-04-103 - MON TOR OUT SOLO.jpg"></a><br><sub>1986|19 · 463-04-103 - MON TOR OUT SOLO · <a href="MECHANICAL/1986%20-%20M463AB%20-%20463-04-103%20-%20MON%20TOR%20OUT%20SOLO%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M463AB.stl`](MECHANICAL/M463AB.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M463AB)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (TECHNICAL DATA: wide 7.0" high 6.5 (41 Mm 178 Mm 165 Mm deep)
- **From the drawing:** 8 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M463AB - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M463AB.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEc2RUN6R2pUcW8/view?resourcekey=0-Xiz3oevf2PJsx3PwQckVvA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEc2RUN6R2pUcW8&resourcekey=0-Xiz3oevf2PJsx3PwQckVvA" width="240" alt="1986 - M463AB - 463-01-019 - ONITOR JUTPUT IRECT OUTPUT.jpg"></a><br><sub>1986|19 · 463-01-019 - ONITOR JUTPUT IRECT OUTPUT · <a href="SCHEMATICS/1986%20-%20M463AB%20-%20463-01-019%20-%20ONITOR%20JUTPUT%20IRECT%20OUTPUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcTN4a3FSMHRhalk/view?resourcekey=0-yUrjIXamlmCjtRYWc8MYfw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcTN4a3FSMHRhalk&resourcekey=0-yUrjIXamlmCjtRYWc8MYfw" width="240" alt="1986 - M463AB - 463-01-019 - PRE FADE INPUT PAN INSERT FADER.jpg"></a><br><sub>1986|19 · 463-01-019 - PRE FADE INPUT PAN INSERT FADER · <a href="SCHEMATICS/1986%20-%20M463AB%20-%20463-01-019%20-%20PRE%20FADE%20INPUT%20PAN%20INSERT%20FADER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUVZFSVhzZElSZXM/view?resourcekey=0-1Zti1ThPMk3am961B7c4OQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUVZFSVhzZElSZXM&resourcekey=0-1Zti1ThPMk3am961B7c4OQ" width="240" alt="1986 - M463AB - 463-02-019 - LALL RESISTORS ISK UNLESS.jpg"></a><br><sub>1986|19 · 463-02-019 - LALL RESISTORS ISK UNLESS · <a href="SCHEMATICS/1986%20-%20M463AB%20-%20463-02-019%20-%20LALL%20RESISTORS%20ISK%20UNLESS%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZGgwVlEzZndNTk0/view?resourcekey=0-19grsfmsMNOBtBwyFa3bUw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZGgwVlEzZndNTk0&resourcekey=0-19grsfmsMNOBtBwyFa3bUw" width="240" alt="1986 - M463AB - 463-02-019 - LESS OTHERWISE SPECIFIED COMPONENT DESIGNATIONS.jpg"></a><br><sub>1986|19 · 463-02-019 - LESS OTHERWISE SPECIFIED COMPONENT DESIGNATIONS · <a href="SCHEMATICS/1986%20-%20M463AB%20-%20463-02-019%20-%20LESS%20OTHERWISE%20SPECIFIED%20COMPONENT%20DESIGNATIONS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYS0yNl9YajRXS00/view?resourcekey=0-Nqs5HYe7dtlXE1gsSVDK7g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYS0yNl9YajRXS00&resourcekey=0-Nqs5HYe7dtlXE1gsSVDK7g" width="240" alt="1986 - M463AB - 463-06-027 - COMPONENT SIDE NOIES PINS.jpg"></a><br><sub>1986|19 · 463-06-027 - COMPONENT SIDE NOIES PINS · <a href="SCHEMATICS/1986%20-%20M463AB%20-%20463-06-027%20-%20COMPONENT%20SIDE%20NOIES%20PINS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNkFoeFYwZDJLb1k/view?resourcekey=0-VjCkdwYG_4ExhwT8sLQDhg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNkFoeFYwZDJLb1k&resourcekey=0-VjCkdwYG_4ExhwT8sLQDhg" width="240" alt="1986 - M463AB - 463-06-027 - REVISION APR ENT SIDE.jpg"></a><br><sub>1986|19 · 463-06-027 - REVISION APR ENT SIDE · <a href="SCHEMATICS/1986%20-%20M463AB%20-%20463-06-027%20-%20REVISION%20APR%20ENT%20SIDE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcS1NRzFOMzR0a00/view?resourcekey=0-fKsP1i3JQwjTleCICqf7Fg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcS1NRzFOMzR0a00&resourcekey=0-fKsP1i3JQwjTleCICqf7Fg" width="240" alt="1986 - M463AB - 8-109-02-002 - OUTPUT AMPLIFIER CKDAL SCHEMATIC.jpg"></a><br><sub>1986|19 · 8-109-02-002 - OUTPUT AMPLIFIER CKDAL SCHEMATIC · <a href="SCHEMATICS/1986%20-%20M463AB%20-%208-109-02-002%20-%20OUTPUT%20AMPLIFIER%20CKDAL%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbm5jbkhHeTgwUlU/view?resourcekey=0-ZdPm3gp6JAkTBs18L6YO-g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbm5jbkhHeTgwUlU&resourcekey=0-ZdPm3gp6JAkTBs18L6YO-g" width="240" alt="1986 - M463AB - 8-109-02-002 - RII RIZ.jpg"></a><br><sub>1986|19 · 8-109-02-002 - RII RIZ · <a href="SCHEMATICS/1986%20-%20M463AB%20-%208-109-02-002%20-%20RII%20RIZ%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVnhiVnNaaGc1MnM/view?resourcekey=0-3O8bdjSolNLxyhebvH6UIA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVnhiVnNaaGc1MnM&resourcekey=0-3O8bdjSolNLxyhebvH6UIA" width="240" alt="1986 - M463AB - 8-109-02-007 - NDMINAL VALUE.jpg"></a><br><sub>1986|19 · 8-109-02-007 - NDMINAL VALUE · <a href="SCHEMATICS/1986%20-%20M463AB%20-%208-109-02-007%20-%20NDMINAL%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKekhJcDZXYVZMM3M/view?resourcekey=0-xvZsbBNgx3P-3kxxr4yDYQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKekhJcDZXYVZMM3M&resourcekey=0-xvZsbBNgx3P-3kxxr4yDYQ" width="240" alt="1986 - M463AB - 8-109-02-007 - NOMINAL VALUE.jpg"></a><br><sub>1986|19 · 8-109-02-007 - NOMINAL VALUE · <a href="SCHEMATICS/1986%20-%20M463AB%20-%208-109-02-007%20-%20NOMINAL%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSWVOMGExRU9hN2M/view?resourcekey=0-Iid6P4v1nllV_zXI93E_-A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSWVOMGExRU9hN2M&resourcekey=0-Iid6P4v1nllV_zXI93E_-A" width="240" alt="1986 - M463AB - 8-109-06-002 - OUTPUT AMPLIFIER.jpg"></a><br><sub>1986|19 · 8-109-06-002 - OUTPUT AMPLIFIER · <a href="SCHEMATICS/1986%20-%20M463AB%20-%208-109-06-002%20-%20OUTPUT%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY0p2MzNLLXdlaDA/view?resourcekey=0-s0XcarrczHITC3TFzFPB5Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY0p2MzNLLXdlaDA&resourcekey=0-s0XcarrczHITC3TFzFPB5Q" width="240" alt="1986 - M463AB - 8-109-06-002.jpg"></a><br><sub>1986|19 · 8-109-06-002 · <a href="SCHEMATICS/1986%20-%20M463AB%20-%208-109-06-002%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVktiMGdTTndTdXc/view?resourcekey=0-nrfM3juqDR0DNQ9oVOxcEg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVktiMGdTTndTdXc&resourcekey=0-nrfM3juqDR0DNQ9oVOxcEg" width="240" alt="1986 - M463AB - 8-109-06-007 - BOOSTER AMPLIFIER.jpg"></a><br><sub>1986|19 · 8-109-06-007 - BOOSTER AMPLIFIER · <a href="SCHEMATICS/1986%20-%20M463AB%20-%208-109-06-007%20-%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX3VQRWN2QloyZVk/view?resourcekey=0-kXm7ZYFkugYW3-ihF74kmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX3VQRWN2QloyZVk&resourcekey=0-kXm7ZYFkugYW3-ihF74kmw" width="240" alt="1986 - M463AB - 8-109-06-007 - DRI ENG.jpg"></a><br><sub>1986|19 · 8-109-06-007 - DRI ENG · <a href="SCHEMATICS/1986%20-%20M463AB%20-%208-109-06-007%20-%20DRI%20ENG%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M463AB - RTO-144 Connections.pdf`

## RTO-144 pinout

22 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | INPUT | in |  | variant |
| 2 | OUT | out |  | variant |
| 3 | OUT | out |  | variant |
| 4 | FB OUT | out |  | variant |
| 5 | OUT | out |  | variant |
| 6 | IN | in |  | variant |
| 7 | IN | in |  | variant |
| 8 | OUT | out |  | variant |
| 9 | CTL | control |  | variant |
| 10 | IN | in |  | variant |
| 13 | SHIELD | ground |  | variant |
| 14 | PREFADE IN | in |  | variant |
| 15 | FADER IN | in |  | variant |
| 16 | DIRECT OUT | out |  | variant |
| 17 | MONITOR OUT | out |  | variant |
| 18 | CTL COM | ground |  | variant |
| 19 | 25V | other |  | variant |
| 20 | ±COMMON | ground |  | variant |
| 21 | +25V | power |  | variant |
| 22 | CHASS/S GND | ground |  | variant |
| A | FB | other |  | variant |
| B | RS | other |  | variant |
| L | MI/M2 | other |  | variant |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQU5pNEhsQzJJaFE/view?resourcekey=0-SMnBZdwiVxKMMXJFEzydoA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQU5pNEhsQzJJaFE&resourcekey=0-SMnBZdwiVxKMMXJFEzydoA" width="240" alt="1986 - M463AB - P001 - Title Page.jpg"></a><br><sub>1986|19 · P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSm1RQk9tbjJTNkE/view?resourcekey=0-yA1fhkAmsKpDAlPgBZNz8Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSm1RQk9tbjJTNkE&resourcekey=0-yA1fhkAmsKpDAlPgBZNz8Q" width="240" alt="1986 - M463AB - P002.jpg"></a><br><sub>1986|19 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV3VtQ0steWpGR2c/view?resourcekey=0-g_rJ_LAFboLxX7bIxtQk5g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV3VtQ0steWpGR2c&resourcekey=0-g_rJ_LAFboLxX7bIxtQk5g" width="240" alt="1986 - M463AB - P003 1-1.jpg"></a><br><sub>1986|19 · P003 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdHVPYTQ1WFFQQlk/view?resourcekey=0-kA1dxNdepyemTL2-Zy331Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdHVPYTQ1WFFQQlk&resourcekey=0-kA1dxNdepyemTL2-Zy331Q" width="240" alt="1986 - M463AB - P004 2-1.jpg"></a><br><sub>1986|19 · P004 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT0ZfUWVkeGFMdDg/view?resourcekey=0---hoCkm-Q7WM66rJxCYvDA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT0ZfUWVkeGFMdDg&resourcekey=0---hoCkm-Q7WM66rJxCYvDA" width="240" alt="1986 - M463AB - P005 2-2.jpg"></a><br><sub>1986|19 · P005 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSEZYY3JiWC1IdEk/view?resourcekey=0-7W7ChtDGKfspwHU9NZueVw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSEZYY3JiWC1IdEk&resourcekey=0-7W7ChtDGKfspwHU9NZueVw" width="240" alt="1986 - M463AB - P006 3-1.jpg"></a><br><sub>1986|19 · P006 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSXdlM0JxVkdQY3M/view?resourcekey=0-uO3YCtEYI65FVhaOYIeM5A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSXdlM0JxVkdQY3M&resourcekey=0-uO3YCtEYI65FVhaOYIeM5A" width="240" alt="1986 - M463AB - P007 3-2.jpg"></a><br><sub>1986|19 · P007 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNE5oa3RiQzFmWGc/view?resourcekey=0-hiBFQJ9WLmyJ6NSTsWyCcw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNE5oa3RiQzFmWGc&resourcekey=0-hiBFQJ9WLmyJ6NSTsWyCcw" width="240" alt="1986 - M463AB - P008 3-3.jpg"></a><br><sub>1986|19 · P008 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQk9EWURaRWp1UEU/view?resourcekey=0-nGYw_6cUl24H5TBticpHgg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQk9EWURaRWp1UEU&resourcekey=0-nGYw_6cUl24H5TBticpHgg" width="240" alt="1986 - M463AB - P009 3-4.jpg"></a><br><sub>1986|19 · P009 3-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbk1xNm4tcGRTZFE/view?resourcekey=0-Nv_2YR1CvuO2MGUb6cgDjg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbk1xNm4tcGRTZFE&resourcekey=0-Nv_2YR1CvuO2MGUb6cgDjg" width="240" alt="1986 - M463AB - P010 8-109.jpg"></a><br><sub>1986|19 · P010 8-109</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSjk2dkRYTzl0ekk/view?resourcekey=0-Zl2ykHXTk_KhpjJMc428DQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSjk2dkRYTzl0ekk&resourcekey=0-Zl2ykHXTk_KhpjJMc428DQ" width="240" alt="1986 - M463AB - P011 - 8-109-1-1.jpg"></a><br><sub>1986|19 · P011 - 8-109-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOEs4V2hDMU1qNkE/view?resourcekey=0-1YKQo9O6Wm0UHtQoFO1Wtg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOEs4V2hDMU1qNkE&resourcekey=0-1YKQo9O6Wm0UHtQoFO1Wtg" width="240" alt="1986 - M463AB - P012 - 8-109-1-2.jpg"></a><br><sub>1986|19 · P012 - 8-109-1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbGlqcDJldGhyYWs/view?resourcekey=0-AKuBZqP29WcjyKVEPIiq9Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbGlqcDJldGhyYWs&resourcekey=0-AKuBZqP29WcjyKVEPIiq9Q" width="240" alt="1986 - M463AB - P013 - 8-109-2-1.jpg"></a><br><sub>1986|19 · P013 - 8-109-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRGlsaDRVdDRyRnc/view?resourcekey=0-CF_ExHr0UaRsHXzleJkjYA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRGlsaDRVdDRyRnc&resourcekey=0-CF_ExHr0UaRsHXzleJkjYA" width="240" alt="1986 - M463AB - P014 - 8-109-2-2.jpg"></a><br><sub>1986|19 · P014 - 8-109-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX1N0TUVsN25hTW8/view?resourcekey=0-nMA8AAyudToKX_ytkAKMcg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX1N0TUVsN25hTW8&resourcekey=0-nMA8AAyudToKX_ytkAKMcg" width="240" alt="1986 - M463AB - P015 - 8-109-2-3.jpg"></a><br><sub>1986|19 · P015 - 8-109-2-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaTc0RUlVYW12SkU/view?resourcekey=0-uK00IJGzq5DZ-2k_5E3eew" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaTc0RUlVYW12SkU&resourcekey=0-uK00IJGzq5DZ-2k_5E3eew" width="240" alt="1986 - M463AB - P016 - 8-109-2-4.jpg"></a><br><sub>1986|19 · P016 - 8-109-2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWXN4bEJUSzZEdTQ/view?resourcekey=0-Hoyhu1haus2mXogENW4E7w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWXN4bEJUSzZEdTQ&resourcekey=0-Hoyhu1haus2mXogENW4E7w" width="240" alt="1986 - M463AB - P017 - 8-109-2-5.jpg"></a><br><sub>1986|19 · P017 - 8-109-2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEt4UDl3Y09Da28/view?resourcekey=0-d-usCe7WPxUKSyWgTYe8Og" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEt4UDl3Y09Da28&resourcekey=0-d-usCe7WPxUKSyWgTYe8Og" width="240" alt="1986 - M463AB - Submaster Module (2).pdf"></a><br><sub>1986|19 · Submaster Module (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRXl1blgySGkzMXM/view?resourcekey=0-E1X8hDDMjdkvHesxwFmvOA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRXl1blgySGkzMXM&resourcekey=0-E1X8hDDMjdkvHesxwFmvOA" width="240" alt="1986 - M463AB - Submaster Module.pdf"></a><br><sub>1986|19 · Submaster Module</sub></td></tr>
</table>

Not on Google Drive yet: `M463AB - P002.jpg`

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1986 - M463AB - 463-01-019 - ONITOR JUTPUT IRECT OUTPUT.kicad_sch](KICAD/1986%20-%20M463AB%20-%20463-01-019%20-%20ONITOR%20JUTPUT%20IRECT%20OUTPUT.kicad_sch)
- [1986 - M463AB - 463-01-019 - PRE FADE INPUT PAN INSERT FADER.kicad_sch](KICAD/1986%20-%20M463AB%20-%20463-01-019%20-%20PRE%20FADE%20INPUT%20PAN%20INSERT%20FADER.kicad_sch)
- [1986 - M463AB - 463-02-019 - LALL RESISTORS ISK UNLESS.kicad_sch](KICAD/1986%20-%20M463AB%20-%20463-02-019%20-%20LALL%20RESISTORS%20ISK%20UNLESS.kicad_sch)
- [1986 - M463AB - 463-02-019 - LESS OTHERWISE SPECIFIED COMPONENT DESIGNATIONS.kicad_sch](KICAD/1986%20-%20M463AB%20-%20463-02-019%20-%20LESS%20OTHERWISE%20SPECIFIED%20COMPONENT%20DESIGNATIONS.kicad_sch)
- [1986 - M463AB - 8-109-02-002 - OUTPUT AMPLIFIER CKDAL SCHEMATIC.kicad_sch](KICAD/1986%20-%20M463AB%20-%208-109-02-002%20-%20OUTPUT%20AMPLIFIER%20CKDAL%20SCHEMATIC.kicad_sch)
- [1986 - M463AB - 8-109-02-002 - RII RIZ.kicad_sch](KICAD/1986%20-%20M463AB%20-%208-109-02-002%20-%20RII%20RIZ.kicad_sch)
- [1986 - M463AB - 8-109-02-007 - NDMINAL VALUE.kicad_sch](KICAD/1986%20-%20M463AB%20-%208-109-02-007%20-%20NDMINAL%20VALUE.kicad_sch)
- [1986 - M463AB - 8-109-02-007 - NOMINAL VALUE.kicad_sch](KICAD/1986%20-%20M463AB%20-%208-109-02-007%20-%20NOMINAL%20VALUE.kicad_sch)
- [1986 - M463AB - Submaster Module (2) p20.kicad_sch](KICAD/1986%20-%20M463AB%20-%20Submaster%20Module%20(2)%20p20.kicad_sch)
- [1986 - M463AB - Submaster Module p20.kicad_sch](KICAD/1986%20-%20M463AB%20-%20Submaster%20Module%20p20.kicad_sch)
- [1986 - M463AB - Submaster Module p27.kicad_sch](KICAD/1986%20-%20M463AB%20-%20Submaster%20Module%20p27.kicad_sch)
- [1986 - M463AB - Submaster Module p31.kicad_sch](KICAD/1986%20-%20M463AB%20-%20Submaster%20Module%20p31.kicad_sch)
- [M463AB.kicad_sym](KICAD/M463AB.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
