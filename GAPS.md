# What this repository does not hold — 116th Congress

## Roll-call votes taken after the last published text

45 roll calls were taken later than the most recent
dated text version of their measure, so there is no commit for them to
sit on. Every record in this repository is the record *as of* the version
it accompanies -- see the caveat in the README -- and a vote cannot be
written onto text that predates it.

This is a limit of the shape of this repository, not an upstream gap and
not a build failure. The votes themselves are published; they are listed
here with the address the chamber serves them from.

| Measure | Vote | When |
|---|---|---|
| `hjres-27` | House 116-1-31 | 2019-01-15, after the last version committed (2019-01-14) |
| `hjres-90` | Senate 116-2-201 | 2020-10-19, after the last version committed (2020-06-30) |
| `hr-268` | Senate 116-1-10 | 2019-01-24, after the last version committed (2019-01-22) |
| `hr-268` | Senate 116-1-53 | 2019-03-26, after the last version committed (2019-01-22) |
| `hr-268` | Senate 116-1-55 | 2019-04-01, after the last version committed (2019-01-22) |
| `hr-268` | Senate 116-1-56 | 2019-04-01, after the last version committed (2019-01-22) |
| `hr-268` | Senate 116-1-9 | 2019-01-24, after the last version committed (2019-01-22) |
| `hr-2740` | Senate 116-1-292 | 2019-09-18, after the last version committed (2019-07-10) |
| `hr-2740` | Senate 116-1-342 | 2019-10-31, after the last version committed (2019-07-10) |
| `hr-6172` | House 116-2-115 | 2020-05-28, after the last version committed (2020-05-14) |
| `hr-6782` | House 116-2-113 | 2020-05-28, after the last version committed (2020-05-08) |
| `hres-79` | House 116-1-65 | 2019-01-30, after the last version committed (2019-01-28) |
| `hres-304` | House 116-1-174 | 2019-05-01, after the last version committed (2019-04-10) |
| `hres-755` | Senate 116-2-33 | 2020-02-05, after the last version committed (2020-01-15) |
| `hres-755` | Senate 116-2-34 | 2020-02-05, after the last version committed (2020-01-15) |
| `hres-832` | House 116-2-38 | 2020-02-06, after the last version committed (2020-02-05) |
| `hres-1148` | House 116-2-207 | 2020-09-29, after the last version committed (2020-09-24) |
| `s-109` | Senate 116-1-7 | 2019-01-17, after the last version committed (2019-01-11) |
| `s-178` | Senate 116-2-153 | 2020-07-30, after the last version committed (2019-12-03) |
| `s-178` | Senate 116-2-168 | 2020-09-10, after the last version committed (2019-12-03) |
| `s-178` | Senate 116-2-198 | 2020-09-30, after the last version committed (2019-12-03) |
| `s-178` | Senate 116-2-199 | 2020-09-30, after the last version committed (2019-12-03) |
| `s-178` | Senate 116-2-203 | 2020-10-20, after the last version committed (2019-12-03) |
| `s-178` | Senate 116-2-207 | 2020-10-21, after the last version committed (2019-12-03) |
| `s-311` | Senate 116-1-27 | 2019-02-25, after the last version committed (2019-02-04) |
| `s-311` | Senate 116-2-58 | 2020-02-25, after the last version committed (2019-02-04) |
| `s-1332` | Senate 116-1-130 | 2019-06-03, after the last version committed (2019-05-07) |
| `s-2657` | Senate 116-2-63 | 2020-03-02, after the last version committed (2019-12-17) |
| `s-2657` | Senate 116-2-64 | 2020-03-04, after the last version committed (2019-12-17) |
| `s-2657` | Senate 116-2-67 | 2020-03-09, after the last version committed (2019-12-17) |
| `s-2657` | Senate 116-2-68 | 2020-03-09, after the last version committed (2019-12-17) |
| `s-3275` | Senate 116-2-57 | 2020-02-25, after the last version committed (2020-02-12) |
| `s-3985` | Senate 116-2-126 | 2020-06-24, after the last version committed (2020-06-18) |
| `s-4653` | Senate 116-2-200 | 2020-10-01, after the last version committed (2020-09-23) |
| `s-4675` | Senate 116-2-204 | 2020-10-20, after the last version committed (2020-09-24) |
| `sjres-2` | Senate 116-1-6 | 2019-01-16, after the last version committed (2019-01-15) |
| `sjres-8` | Senate 116-1-52 | 2019-03-26, after the last version committed (2019-02-14) |
| `sjres-20` | Senate 116-1-161 | 2019-06-13, after the last version committed (2019-05-13) |
| `sjres-26` | Senate 116-1-162 | 2019-06-13, after the last version committed (2019-05-14) |
| `sjres-50` | Senate 116-1-331 | 2019-10-23, after the last version committed (2019-10-22) |
| `sjres-52` | Senate 116-1-337 | 2019-10-30, after the last version committed (2019-10-29) |
| `sjres-53` | Senate 116-1-324 | 2019-10-17, after the last version committed (2019-09-09) |
| `sjres-77` | Senate 116-2-261 | 2020-12-09, after the last version committed (2020-11-18) |
| `sjres-78` | Senate 116-2-262 | 2020-12-09, after the last version committed (2020-11-18) |
| `sres-50` | Senate 116-1-57 | 2019-04-02, after the last version committed (2019-02-13) |

## What the derived amendment execution could not do

125,639 amendatory instructions were read from the measures in this
repository, and **28,747 of them (22.9%) were
carried out**. Each measure's `derived/amendments.md` holds its own,
with the reason beside every one that was not.

This is not a build failure and it is not going to improve much. A bill
is a list of instructions *about* law, and most of them refer to the law
by structure — *strike subsection (k)* — so the words being removed are
in the US Code and not in the bill. Nothing here guesses them. An
instruction is carried out only where the bill states both the text
removed and the text inserted, so the result follows from the bill alone
and can be checked against it.

| Why an instruction was not carried out | Instructions |
|---|---|
| the instruction refers to the law by structure rather than quoting it, so the words it changes are in the US Code and not in this bill | 49,511 |
| the bill names no machine-readable US Code section | 23,768 |
| the bill quotes the text inserted but describes where it goes | 12,923 |
| the bill quotes the text struck but describes what replaces it | 10,597 |
| the bill quotes text on both sides, but not as a single substitution this could carry out | 93 |

**The rate varies enormously between Congresses, and that is upstream.**
An instruction can only be placed if GPO tagged the citation it names,
and whether they did is a fact about the year rather than about the
bill: sampled at 1,500 documents per Congress, 64% of the 108th's carry
a machine-readable US Code citation, 55% of the 113th's — and 5% of the
111th's and 5% of the 112th's. So a Congress here may report a very low
share carried out while the reading of it worked perfectly. Compare this
table with a neighbouring Congress before concluding anything about the
bills themselves.

Counted on each measure's last committed version. An instruction
usually survives from the introduced text to the enrolled one, so
counting every version would report the same instruction several times.
