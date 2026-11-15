# Voice — register, for drafting from nothing

Derived by measurement from ~23k words of hand-written research prose.

**Open this only when there is no surrounding document to take the register from.**
When extending existing work — a new section of a post, another part of a design —
imitation of the document you are appending to is faster and more accurate than any
list. That is what happened on both live uses of this skill, and neither opened this
file.

What used to be this file's "epistemic" section has moved. Those moves do their work
inside Pass 1 and Pass 2, not in a reference nobody opens; two of them duplicated
`structure.md` outright. What remains here is sentence and section register, which
is the part a list can actually carry.

## Sentence

1. **Short declaratives carry the load.** The heaviest sentences are the shortest.
   "No model is consulted at any point in construction."
2. **Long sentences coordinate; they do not subordinate.** Chain clauses with
   em-dash or semicolon. No stack of nested "which" clauses.
3. **The em-dash marks the turn** — the pivot or the qualification that reverses
   direction. Never decorative.
4. **Bold marks the load-bearing quantity or the claim, never a phrase.** Roughly
   once per 120 words. Discipline is what keeps it meaningful.
5. **Numbers go inline, in the sentence making the claim, with their instrument.**
   Never "as shown in Table 4". The table supports the number; it does not house
   it.
6. **Deltas where the movement is the point:** "13% → 87%", "two-way 75%,
   constrained 61%, free generation 12%".
7. **Tense splits by kind.** Present for what is true; past for what you did.
8. **Second person to hand the reader a move:** "Turn it around:". Once per piece.

## Section

9. **Headers are plain speech, often a question.** "How I got it wrong", "So how
   bad is it, really?" Never "Methodology", "Experimental Results".
10. **One job per section, then stop.** 1–4 paragraphs. No transition sentence
    between sections, no summary at the end of one.
11. **The conclusion arrives in the first two sentences.** Nothing is withheld for
    suspense; the piece then earns it.
12. **The summary slot states the result, including a negative one.** "The edit
    finally ran and said no."
13. **End on an artifact plus a self-implicating admission, not a recap.** "I know
    that because an early version did exactly that, and inflated its own number by
    forty points."
14. **At most one lyric sentence per piece, at a boundary.** It survives because
    it is rationed.

## Three epistemic moves that are register, not structure

The rest of what was here now lives where it is used — claim fates and scope in the
Pass 1 audit, priced gaps and bounded criticism in `structure.md` §2 and §7. These
three are phrasings rather than checks, so they stay:

15. **Separate aspiration from mechanism.** "The aspiration is real; the mechanism
    is sampling. Those are different things, and the difference is the whole
    argument." The most characteristic analytic move in the corpus, and it has no
    home in the passes.
16. **Credit prior work for the part that is not new, explicitly.** "Prompt
    sensitivity is not my finding. What is new here is locating it inside an editing
    benchmark and pricing it." Pre-empts the reviewer and costs one sentence.
17. **Report error with its magnitude and cause**, never as apology. "inflated its
    own number by forty points" — not "I made a mistake."

## The X-not-Y construction, and its budget

"A rather than B" / "A, not B" / "A is real; B is sampling". It appears about once
per 190 words in the reference corpus and it is load-bearing — it fixes a boundary
by naming what a thing is not.

It is also the most imitable feature here, so it overfires easily. **The budget is
semantic, not a rate:** use it where the two halves are genuinely
*expected-versus-new*, which is the job ROME gives it —

> "The presence of strong causal states at a late site … is unsurprising, but
> their emergence at an early site … is a new discovery."

— and it will not overfire. Used for mere emphasis, it degrades into mannerism.

## The sentence no one would say

Added 2026-11-15, from one label that got published:

> PLAIN — the same paper, said so it can still be checked

The author could not name the fault and called it **inhumane**: *"no human writes
like this, or thinks like this. I would never see myself writing such sentences."*
He was right, and nothing caught it. The word-level lint scored the containing file
at **0.0 per 10k** and the vocabulary census at **zero defects**, both before and
after that sentence existed.

**What it is.** The label does two jobs at once: it names the thing, and it defends
the thing's existence. `said so it can still be checked` answers an objection nobody
raised — *is this the dumbed-down version?* — in the position where a name belongs.
The writer has stopped addressing the reader and started winning an argument with an
imagined objector.

**Why it is worse than clumsy.** The clause asserts a virtue the artifact already
demonstrates. That page keeps every number, keeps its limits, and keeps the control
it got wrong. Telling a reader the work can be checked is weaker than letting them
check it, so the label **subtracts from what the page had already earned**. Self-praise
in the furniture reads as doubt about the furniture.

### Two tests

**Say it aloud, to a person, about your own work.** "This is the plain version, said
so it can still be checked." Nobody says that. If you would not say it, do not label
with it. This is the author's own test and it is the one that generalises — most of
this family is not a pattern, so no regex will find it.

**Delete the justifying clause. Does the label still name the thing?** If yes, the
clause was argument rather than name, and it goes. `PLAIN` on its own, or `In plain
words`, names it.

### The line it sits on

Not every em-dash apposition is this. The sibling label on the same component —
`THREADS — how this paper was reached` — is fine, and the difference is the whole
rule:

| | |
| --- | --- |
| `THREADS — how this paper was reached` | says what is **in** it |
| `PLAIN — the same paper, said so it can still be checked` | says why it is **good** |

Describe the contents and you are naming. Assert the merit and you are arguing.

The narrow, lintable case is the rule `self-justifying label`. It is anchored hard —
short name-like left side, virtue-claiming right side — and it fires on zero of the
corpus and zero of 27k words of this author's own prose. The rest is caught by
reading, with the two tests above.
