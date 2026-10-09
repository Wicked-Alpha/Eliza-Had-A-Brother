# Eliza Had A Brother

An archive of the 1972 meeting between PARRY and the DOCTOR, built from the documents. Every claim links to its source. Where the record is silent, this archive says so.

## The short version

On Monday, 18 September 1972, two programs held a conversation over the ARPANET.

**PARRY**, Kenneth Colby's model of a person with paranoid beliefs, was running on the Stanford Artificial Intelligence Laboratory's computer, **SAIL**. The **DOCTOR**, a program that played a psychotherapist, was running on BBN's **TENEX** system. Both were reached from UCLA, from a host the record calls **UCLA/SEX**.

Vint Cerf published the transcript four months later as **RFC 439, "PARRY Encounters the DOCTOR,"** dated 21 January 1973. PARRY talks about the races at **Bay Meadows**, a bookie who did not pay off, and the MAFIA. The DOCTOR keeps asking what that suggests. It ends when PARRY says goodbye and the DOCTOR answers:

> It's been my pleasure, that's $399.29 please.

The comment printed beneath it in the RFC: *talk about tricky operators...*

The full transcript is in [Exhibit 01](exhibits/01-rfc-439/).

## Three things many retellings get wrong

1. **It did not happen at the Washington conference.** Many accounts place the conversation at the International Conference on Computer Communication (ICCC), held 24 to 26 October 1972 at the Washington Hilton. RFC 439 dates the session to 18 September, 36 days earlier. The ICCC attendee booklet lists the DOCTOR and PARRY as two separate demos. This archive has found no primary source that places a conversation between them at ICCC. See [Exhibit 07](exhibits/07-iccc-1972/).
2. **The DOCTOR on the line was not Joseph Weizenbaum's ELIZA from MIT.** It ran on BBN's machine, and the code evidence ties it to Bernie Cosell's Lisp version of the program, written at BBN. Even in 1972, the ICCC booklet credited the DOCTOR to Weizenbaum. See [Exhibit 03](exhibits/03-cosell-doctor/).
3. **PARRY and Weizenbaum's original ELIZA met much later.** The earliest exchange between them that this archive has found took place in April 2026, after both programs had been revived, with the turns relayed by hand. See [Exhibit 08](exhibits/08-parry-meets-eliza-2026/).

More in [CORRECTIONS.md](CORRECTIONS.md).

## Why "Eliza Had A Brother"

ELIZA and PARRY came out of the same small circle, and the two men behind them knew each other before either program existed.

- Weizenbaum's 1963 paper on SLIP, the list-processing package ELIZA was later written with, thanks Colby for his advice and support ([Shrager, arXiv 2406.17650](https://arxiv.org/html/2406.17650v2)).
- In 1966, Colby's group at Stanford published its own therapy-dialogue program, crediting Weizenbaum of MIT with the first program of the type ([Colby, Watt and Gilbert, 1966](https://stacks.stanford.edu/file/druid:hk334rq4790/hk334rq4790.pdf)).
- Pamela McCorduck's 2019 memoir describes Colby's program as the beginning of "a bitter academic feud between Weizenbaum and Colby." Weizenbaum charged that it was just a version of his own ELIZA. Colby answered that the psychiatric skill in it was his own contribution ([McCorduck excerpt, Computer History Museum](https://computerhistory.org/blog/the-promise-of-the-doctor-program-early-ai-at-stanford/)).
- PARRY came later and went the other way. It was a separate program, in a different language, that played the patient instead of the therapist. Colby's 1973 draft preface credits Sylvia Weber Russell, then a Stanford computer science graduate student, with writing the original version ([Exhibit 05](exhibits/05-parry-1971/)).

So the title is a metaphor: two programs whose makers fell out. In 1972, the closest PARRY came to ELIZA was a cousin of it running at BBN.

## The exhibits

| # | Exhibit | What is here |
|---|---|---|
| 01 | [RFC 439, "PARRY Encounters the DOCTOR" (1973)](exhibits/01-rfc-439/) | Full text, unmodified |
| 02 | [RFC 371, Kahn's ICCC announcement (July 1972)](exhibits/02-rfc-371/) | Full text, unmodified |
| 03 | [Cosell's DOCTOR, 1969 and 1972 listings](exhibits/03-cosell-doctor/) | Runnable transcription. CC BY-SA 3.0 for Cosell's code, an MIT-style notice for the rest |
| 04 | [ELIZA, 1965](exhibits/04-eliza-1965/) | Notes and links |
| 05 | [PARRY, 1971](exhibits/05-parry-1971/) | Notes and links |
| 06 | [The psychiatrist tests](exhibits/06-psychiatrist-tests/) | The real numbers |
| 07 | [ICCC, October 1972](exhibits/07-iccc-1972/) | What the booklet shows |
| 08 | [PARRY meets ELIZA, 2026](exhibits/08-parry-meets-eliza-2026/) | The revival |

Also: [TIMELINE.md](TIMELINE.md), [SOURCES.md](SOURCES.md), [LICENSE.md](LICENSE.md).

## A note on language

PARRY simulated a person with paranoid beliefs. Colby's papers describe it as a model of "paranoid processes," the clinical language of the period. This archive uses the original terms when quoting the record.

## Not affiliated

ELIZA, PARRY and DOCTOR here mean the historical research programs. This archive is not affiliated with any company, product or token that uses those names, and it does not endorse any of them.

## Corrections

If you can show that something here is wrong, open an issue and include the source.
