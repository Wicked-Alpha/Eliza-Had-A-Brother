# Exhibit 06: The psychiatrist tests

A widely repeated fact about PARRY is that 33 psychiatrists could tell it from a real patient only 48 percent of the time. That line merges two different experiments. Colby's own files separate them.

## What was actually measured

All of the figures below come from two of Colby's files from the Stanford AI Lab: a February 1973 paper draft by Colby and Franklin Dennis Hilf, and a February 1974 chapter draft.

| Group | What they did | Result |
|---|---|---|
| 8 psychiatrists, the "interview judges" | Interviewed PARRY and a hospitalized patient by teletype and rated each reply for paranoia on a 0 to 9 scale. They knew a computer was carrying the messages, but none knew a paranoid simulation existed. They were told only after both interviews that one of the patients might be a computer model. | The interviews became the transcripts used below |
| 33 psychiatrists, the "protocol judges" | Rated the transcripts for paranoia. Their names were drawn at random from 105 in the 1970 American Psychiatric Association directory, and they were not told at first that a computer was involved. | A paranoia rating, not a machine-spotting test |
| Psychiatrists | Sent a pair of transcripts, one patient and one PARRY, and asked which was the machine. 100 were asked and 41 replied. | 21 of 41 right, 51 percent |
| ACM computer scientists | Asked the same question. 100 were asked and 67 replied. | 32 of 67 right, 48 percent |
| Psychiatrists, control | Asked the same question about RANDOM-PARRY, a version that used PARRY's lines in random order regardless of what was said to it. 200 were asked and 69 replied. | 34 of 69 right, 49 percent |

So the 33 psychiatrists were rating paranoia, and the 48 percent belongs to the computer scientists.

## Why the control matters

RANDOM-PARRY was picked out at about the same rate as PARRY. Colby's chapter draft draws the lesson directly: when a random model passes a test, that strongly suggests the test is weak. The same draft shows that judges did separate RANDOM-PARRY from real patients when asked to rate replies along specific dimensions, such as thought disorder and bizarreness.

Colby's University of California memorial calls PARRY the first program to pass the Turing test. That is the memorial's claim. Read it next to the RANDOM-PARRY result.

## Two details from the chapter draft

- **A human in the loop.** When PARRY was the patient, Sylvia Weber watched what the interviewing psychiatrist typed, and retyped any input that had misspellings or characters the program could not accept. PARRY's replies went back to the psychiatrist unedited.
- **Familiar lines.** The draft prints part of an interview with the weak version of the model. In it, PARRY says it went to the track at Bay Meadows a while back, that there is a lot of crooked gambling going on there, and that people get on its nerves. PARRY says the same things to the DOCTOR in [RFC 439](../01-rfc-439/).

## The validation paper

Colby, Hilf, Weber and Kraemer reported the validation work in "Turing-like indistinguishability tests for the validation of a computer simulation of paranoid processes," *Artificial Intelligence*, vol. 3, pages 199 to 221, 1972.

## Weizenbaum's reply

Weizenbaum answered with a letter to *Communications of the ACM* in July 1974, titled "Automating psychotherapy," which parodied the logic of the PARRY experiment.

## Sources

- [Colby, chapter draft, SAIL file CHAP6[4,KMC], dated 18 February 1974](https://saildart.org/CHAP6[4,KMC])
- [Colby and Hilf, "How to Use and How Not to Use Turing-like Tests in Evaluating the Adequacy of Simulation Models," SAIL file TTT[4,KMC], dated 28 February 1973](https://saildart.org/TTT[4,KMC])
- [DOI 10.1016/0004-3702(72)90049-5](https://doi.org/10.1016/0004-3702%2872%2990049-5)
- [University of California In Memoriam, Kenneth Mark Colby](https://senate.universityofcalifornia.edu/_files/inmemoriam/html/KennethMarkColby.htm)
- [Stuart M. Shieber, "Lessons from a Restricted Turing Test"](https://www.eecs.harvard.edu/~shieber/Biblio/Papers/loebner-rev-html/loebner-rev-html.html)
