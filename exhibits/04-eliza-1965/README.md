# Exhibit 04: ELIZA, 1965

Joseph Weizenbaum's ELIZA is the program PARRY is usually said to have met in 1972. This exhibit sets out what the record says about the original, and where to find it.

## The paper

Weizenbaum described ELIZA in "ELIZA: A Computer Program for the Study of Natural Language Communication Between Man and Machine," *Communications of the ACM*, vol. 9, no. 1, January 1966, pages 36 to 45. The paper was received in September 1965. The work was supported by Project MAC at MIT.

What the paper says:

- ELIZA was written in **MAD-SLIP** and ran on MIT's MAC time-sharing system, used from remote typewriters.
- The program and its scripts are separate. A script is data that tells ELIZA how to respond.
- The name comes from the Eliza of *Pygmalion*, who could be taught to speak better.
- It describes a script that plays a Rogerian psychotherapist. It never uses the name DOCTOR.

So ELIZA existed by 1965 and was published in 1966. It was not written in Lisp. The Lisp DOCTOR was Cosell's ([Exhibit 03](../03-cosell-doctor/)).

## The lost listing

The original code was missing for decades. In 2021, Jeff Shrager and MIT archivist Myles Crowley found what appeared to be a complete copy of the source among Weizenbaum's papers at MIT.

MIT catalogues it as *Computer conversations, 1965*, in the Joseph Weizenbaum personal archives, collection MC-0383 ([collection page](https://dome.mit.edu/handle/1721.3/201698)), with the DOCTOR script attached at the end. MIT put the digitized copy online on 12 May 2023.

On 21 December 2024, Rupert Lane announced the original ELIZA running again on a restored CTSS time-sharing system on an emulated IBM 7094. The team reports that 96 percent of the running code is exactly what was found.

## Why the code is linked, not copied

The rights statements for this code do not match. The ELIZAGEN project and the reanimation repository both say Weizenbaum's estate released the code under a Creative Commons CC0 public domain dedication. MIT's catalogue record for the scan lists it under an MIT software license. Until that is settled, this archive links to the code instead of copying it.

- **The scan:** [MIT Dome, Computer conversations, 1965](https://dome.mit.edu/handle/1721.3/201699)
- **The transcription:** [ELIZAGEN repository, 1965_Weizenbaum_MAD-SLIP](https://github.com/jeffshrager/elizagen.org/tree/master/1965_Weizenbaum_MAD-SLIP)
- **The running version:** [rupertl/eliza-ctss](https://github.com/rupertl/eliza-ctss)

## The man

Joseph Weizenbaum was born on 8 January 1923 in Berlin and died on 5 March 2008. His book *Computer Power and Human Reason: From Judgment to Calculation* was published by W. H. Freeman in 1976.

## Sources

- [Weizenbaum, CACM 1966, scan hosted by Stanford CS 124](https://web.stanford.edu/class/cs124/p36-weizenabaum.pdf)
- [DOI 10.1145/365153.365168](https://doi.org/10.1145/365153.365168)
- [MIT Dome item, Computer conversations, 1965](https://dome.mit.edu/handle/1721.3/201699?show=full)
- [MIT Dome collection, Joseph Weizenbaum personal archives](https://dome.mit.edu/handle/1721.3/201698)
- [ELIZA Reanimated, Lane, Hay, Schwarz, Berry and Shrager, arXiv 2501.06707](https://arxiv.org/html/2501.06707v1)
- [ELIZAGEN, Original ELIZA](https://sites.google.com/view/elizagen-org/original-eliza)
- [rupertl/eliza-ctss README](https://github.com/rupertl/eliza-ctss)
- [Deutsche Biographie, Joseph Weizenbaum](https://www.deutsche-biographie.de/gnd118820591.html)
- [Computer History Museum catalogue, Computer Power and Human Reason](https://www.computerhistory.org/collections/catalog/102635737)
