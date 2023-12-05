# chronic_NPX_mouse
Build files for chronic, recoverable Neuropixels 1.0 or 2.0 implants in mice. Used in [this protocol collection](dx.doi.org/10.17504/protocols.io.e6nvwjo87lmk/v2).

Chronic recoverable implant based off of [(Juavinett et al, 2019)](https://elifesciences.org/articles/47188) and modified by Janna Aarse, who generously shared her build files with me to modify.

**Components**
* Body piece (single for 1.0 probes, left and right for dual 2.0 probes)
* Wing (attaches to body with screw & nut)
* Flex holders (go around the PCB and lower part of flex cable)
* Dome (covers side of shanks opposite the wings)
* Headstage holder
* **NEW** Lower profile headstage holder (see 2.1 design folder). This holder sits behind the implant, so the attachments during surgery are substantially shorter (at the expense of losing LED tracking). The holder is mounted during surgery (adds .14g), and you can choose to attach the headstage during surgery as well (adds a total of 1.04g). During recording, simply plug in the Omnetics connector. Optionally, hook a paper clip (attached to a counterweighted pulley) into the hole to relieve some of the weight during recording.

**Versions**
* Single 1.0 probe
* Dual 2.0 beta probes
* Dual 2.0 probes (same as beta probe files, just with updated flex holders and headstage holder by Frances Cho and probe + headstage files from Neuropixels)
* 2.1 design (same as 2.0 builds, but I will be updating these files over time as I test new versions). 

**Possible modifications**
* If you don't need LED tracking, you can remove the arms of the headstage holder.
* Body pieces can attach to either side of the probe and at any height. You can also mount the body pieces at any angle, though the wing pieces are rounded so that angling the body piece is unnecessary, even at extreme angles of insertion.
* All flex holders, except for flex holder #1 (with tab slot), are optional. If your probes are very close together, you can skip the flex holders (except holder #1) and just cover the wires and PCB with electrical tape.
* If your probes are angled towards each other such that the body pieces might collide, you can (1) attach a dovetail as a shim under the body piece to move it away, (2) mount the body piece farther to the side of the probe, or (3) angle the wing holder portion away from the probe. See the angled body piece example in the 2.0 probe folder.
