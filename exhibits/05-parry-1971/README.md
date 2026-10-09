# Exhibit 05: PARRY, 1971

PARRY was Kenneth Mark Colby's computer model of a person with paranoid beliefs, built at Stanford. It played the patient. The person at the keyboard played the psychiatrist.

## The first paper

Colby, Sylvia Weber and Franklin Dennis Hilf described the model in "Artificial Paranoia," *Artificial Intelligence*, vol. 2, no. 1, pages 1 to 25, 1971. The paper was accepted on 4 January 1971.

What the paper says:

- The model was written in **MLISP**, which translates into LISP 1.6, and ran on the PDP-6/10 time-shared system of the Stanford Artificial Intelligence Project.
- By the time of the paper, 23 out of 25 psychiatrists who had interviewed the model had judged it paranoid.
- The word PARRY does not appear anywhere in it. The name appears in the October 1972 ICCC booklet ([Exhibit 07](../07-iccc-1972/)) and in RFC 439 ([Exhibit 01](../01-rfc-439/)).

So PARRY was in print in 1971. The common claim that it was written in 1972 is wrong.

## Who PARRY was meant to be

The 1971 paper describes a hypothetical 28-year-old single man who works as a post office clerk. He has no siblings and lives alone. He attacked a bookie who, he believes, did not pay off on a bet, and now fears the bookie will use his connections in the underworld to have him hurt or killed.

There were two versions. The weak version has no delusions about an organized conspiracy. The strong version can be drawn into delusions about the Mafia.

In a sample interview printed in the paper, the model gives its name as **Frank Smith**.

The same story runs through RFC 439. There, PARRY tells the DOCTOR that it beat up a bookie who did not pay off and thought he might use his friends in the underworld to get even.

## Who wrote it

Colby led the work. His December 1973 draft preface, kept among his files from the Stanford AI Lab, credits Sylvia Weber Russell, then a Stanford computer science graduate student, with writing the original version of the program.

PARRY was its own program. It was written in a different language from ELIZA, and it modeled a patient where ELIZA's best-known script modeled a therapist.

## A note on terms

The 1971 paper uses "paranoid" as the name for a general mode of thinking, and points out that clinicians agree far less on subcategories such as paranoid schizophrenia. Later summaries often say PARRY simulated paranoid schizophrenia, which is narrower than Colby's own framing. His 1975 book is titled *Artificial Paranoia: A Computer Simulation of Paranoid Processes*.

## The code

Much of PARRY's source survives in the Carnegie Mellon University Artificial Intelligence Repository, under `areas/classics/parry`. Its readme, written by Martin Frost of Stanford on 5 September 1991, describes it as MLISP plus PDP-10 assembly for the WAITS operating system, not portable and possibly incomplete.

The readme states no licence, so this archive links to the code and does not copy it.

- [PARRY in the CMU AI Repository](https://www.cs.cmu.edu/Groups/AI/util/areas/classics/parry/0.html)

## The man

Kenneth Mark Colby was born in 1920 in Waterbury, Connecticut. He graduated from Yale Medical School in 1943, joined the UCLA psychiatry faculty in 1974, and died on 20 April 2001.

## Sources

- [Colby, Weber and Hilf, "Artificial Paranoia," 1971, scanned copy](https://courses.cs.umbc.edu/471/papers/colby_71.pdf)
- [DOI 10.1016/0004-3702(71)90002-6](https://doi.org/10.1016/0004-3702%2871%2990002-6)
- [Colby, draft preface, SAIL file PREF[4,KMC]](https://saildart.org/PREF[4,KMC]13)
- [Wellcome Collection record, Artificial Paranoia (1975)](https://wellcomecollection.org/works/pvxkk7yg)
- [CMU AI Repository, PARRY readme](https://www.cs.cmu.edu/Groups/AI/util/areas/classics/parry/readme.txt)
- [University of California In Memoriam, Kenneth Mark Colby](https://senate.universityofcalifornia.edu/_files/inmemoriam/html/KennethMarkColby.htm)
