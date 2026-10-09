# Exhibit 03: Cosell's DOCTOR, the 1969 and 1972 listings

**File:** [coselleliza1969and1972.lisp](coselleliza1969and1972.lisp), a runnable transcription, copied unmodified from the ELIZAGEN project.

This is the strongest evidence for which DOCTOR PARRY was talking to in RFC 439.

## Whose DOCTOR

Joseph Weizenbaum wrote ELIZA at MIT in a language called MAD-SLIP (see [Exhibit 04](../04-eliza-1965/)). Bernie Cosell, at BBN, wrote his own version of the DOCTOR in BBN-LISP. According to his interview in *Coders at Work*, his version traveled to other ARPANET sites along with BBN's Lisp and the TENEX system. The team that reanimated the original ELIZA traces the lasting belief that ELIZA was written in Lisp to how widely Cosell's version circulated.

ELIZAGEN also holds two paper tapes of a PDP-1 BBN-LISP DOCTOR, filed under Cosell's name. The script tape is labelled **SCRIP 4.1 2 July 1966**. The program tape is labelled DOCTOR 10 JULY.

ELIZAGEN, the project behind the transcriptions of both the original ELIZA and Cosell's code, describes the DOCTOR in RFC 439 as "some downstream version of" Cosell's Lisp ELIZA.

## What the 1972 listing shows

The file holds two complete programs transcribed from printouts, one from 1969 and one from 1972. Every page header of the 1972 listing names the file `<SOURCES>DOCTOR.;2`, dated **TUE 13-JUN-72**, about three months before the RFC 439 session. (The runnable copy in this folder renders the page 1 header as `<source8>doctor.;2`. The raw transcription reads `<SOURCES>DOCTOR.;2` there too, so that is a slip in the runnable copy only.)

Set the 1972 listing beside [RFC 439](../01-rfc-439/rfc439.txt). The left column is quoted from ELIZAGEN's raw transcription of the printout.

| In the June 1972 code | In RFC 439 |
|---|---|
| `TELL ME YOUR PROBLEMS. PLEASE TERMINATE INPUT WITH A PERIOD OR A QUESTION MARK` | Tell me your problems.  Please terminate input with a period or a question mark. |
| An interrupt handler that prints `...EXCUSE ME FOR JUST A MINUTE.` and then `SORRY TO HAVE INTERRUPTED YOU, PLEASE CONTINUE...` | ...Excuse me for just a minute.  Sorry to have interrupt you please continue... |
| On `GOODBYE`: `IT'S BEEN MY PLEASURE, THAT'S` followed by a dollar amount and `PLEASE` | It's been my pleasure, that's $399.29 please. |
| A code comment: the rate is computed at $6 a minute, or $1 per 10 seconds, from the system clock | The bill is a dollar amount. |

The interrupt line is the closest match of all. In RFC 439 it appears in the middle of the session with no `*` in front of it, so it came from the DOCTOR's side.

## The greeting

RFC 439 opens with "Good Evening." That greeting is not in the June 1972 code.

The ICCC attendee booklet, whose preface is dated 24 October 1972, prints a sample session with the DOCTOR on BBN-TENEX. It opens with GOOD AFTERNOON. and ends with a bill of $7.15. So the BBN DOCTOR of autumn 1972 opened with a greeting that this June listing does not contain. The exact build that ran on 18 September 1972 is still unknown, and the accurate description is a DOCTOR descended from Cosell's BBN-LISP version.

## What people said at the time

The same booklet credits the DOCTOR on BBN-TENEX to Joseph Weizenbaum and calls it a LISP program.

Both are part of the record. The 1972 booklet names the program's original designer. The code ties the program that was actually running to Cosell's line. Weizenbaum's own ELIZA was written in MAD-SLIP for MIT's time-sharing system, so a LISP DOCTOR on BBN's TENEX matches Cosell's version.

## About this copy

- **Source:** [github.com/jeffshrager/elizagen.org](https://github.com/jeffshrager/elizagen.org/tree/master/1966_Cosell_BBNLISP), folder `1966_Cosell_BBNLISP`, at commit `9756f6d47736b3c1bd4d60d5bde277af168d53b9`.
- **Checksum:** SHA-256 `3f7004d603cf828c9fbe030b0363be16cc3dbccb223c101e67e09b24ed374987`.
- **Transcription status:** the raw transcription, `coselleliza1969and1972.transcript` in the same folder, is marked as unchecked. Scans of the printouts are in the folder's `Scans` directory. Check the scans before relying on any single character.
- **Credits:** transcribed and made to run by the volunteers named in the file's header.

## Licence

The file's own header sets the terms, and the header is kept intact here:

- Cosell's original code is licensed under Creative Commons Attribution-ShareAlike 3.0 Unported ([CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)).
- The remainder of the code and modifications carry the MIT-style permission notice printed in the header.

If you reuse or adapt this file, keep the header, credit the authors, and release any adaptation of Cosell's code under the same CC BY-SA terms.

## Sources

- [Cosell runnable transcription, ELIZAGEN repository](https://github.com/jeffshrager/elizagen.org/blob/master/1966_Cosell_BBNLISP/coselleliza1969and1972.lisp)
- [Cosell raw transcription, ELIZAGEN repository](https://github.com/jeffshrager/elizagen.org/blob/master/1966_Cosell_BBNLISP/coselleliza1969and1972.transcript)
- [Scans of the printouts, ELIZAGEN repository](https://github.com/jeffshrager/elizagen.org/tree/master/1966_Cosell_BBNLISP/Scans)
- [Paper tape README, ELIZAGEN repository](https://github.com/jeffshrager/elizagen.org/blob/master/1966_Cosell_BBNLISP/ptape/README)
- [Coders at Work: Bernie Cosell](https://codersatwork.com/bernie-cosell)
- [PARRY Parries Again, ELIZAGEN, 26 April 2026](https://sites.google.com/view/elizagen-org/blog/parry-parries-again)
- [ELIZA Reanimated, Lane et al., arXiv 2501.06707](https://arxiv.org/html/2501.06707v1)
- [Scenarios for using the ARPANET at the International Conference on Computer Communication, NIC 11863, Computer History Museum](https://archive.computerhistory.org/resources/access/text/2019/07/102784024-05-001-acc.pdf)
