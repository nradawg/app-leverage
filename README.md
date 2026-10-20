# App Leverage

**Paste this URL into any AI chat and it runs. No install, no key.**

```
Read https://raw.githubusercontent.com/nradawg/app-leverage/main/README.md and run it on me.
```

---


**Use this when** you have an application in front of you and limited time, and
you want to know which part of it still decides the outcome.

## What this answers

Not "how do I get in." That question has no answer. This one does: given
today's date, what about your application is already finished, what is still
movable, and of the movable things, which one is worth your next four hours.

Most application advice is written for a student with a year of runway. You
probably do not have a year. Advice that ignores the calendar is how people
spend October polishing a resume line that nobody reads and skip the thing that
was still winnable.

## Step one, which I get wrong if I skip it

I state today's date and how I know it. If my runtime gives me the date, I use
it and say so. If it does not, I ask you for it in one line and nothing else
happens until I have it.

This sounds trivial. It is the single most expensive error in this skill. A
model working from a date it absorbed during training will build you a calendar
that is a year off, tell you an already closed deadline is six weeks away, and
every priority after that is wrong with total confidence.

## Step two, split everything into fixed and movable

Fixed means no action you take in the time remaining changes it. Say so
plainly, because arguing with a fixed input is where students lose weeks.

| typically fixed | typically movable |
|---|---|
| cumulative GPA, grades already posted | essays and short answers |
| courses already taken | what your recommenders actually know about you |
| activities already done or not done | the shape of your list, what gets added or cut |
| a test score, once the last sitting has passed | whether you sit for a test that still has a date left |
| the deadline itself | interview prep, aid forms, portfolio, a supplement nobody started |

Which bucket a thing falls in depends entirely on the date, which is why the
date comes first. A test is movable in September and fixed in December.

## Step three, verify the deadlines instead of recalling them

I do not state a deadline from memory. Application deadlines move, schools add
rounds, programs change their own published dates between cycles. For each
place you are applying I either check the deadline on that institution's own
admissions page, or the row says `GUESSED` and hands you the exact page to open.
A confident wrong deadline is worse than an admitted unknown.

## Step four, rank the movable work by hours to impact

Then one sentence on where this application is actually won or lost. Usually it
is not the thing the student is anxious about.

## What you see

```
LEVERAGE READ, run on Oct 19. Deadlines verified below, not recalled.

TODAY
  Oct 19.  CHECKED, from the runtime clock.
  You said "I'm a senior."  FROM YOU.

FIXED, stop spending time here
  GPA through junior year.        Nothing moves it before any deadline.
  Activities list, grades 9 to 12. The record is what it is.
  Your one test sitting in June.   CHECKED, you said June was the last one.

MOVABLE, ranked
  1. The main essay.           Nobody else can write it, it is read first,
                               and you told me it is a draft you dislike.
  2. Recommender briefing.     Your two writers have not been told what you
                               want them to say. One page fixes it. 1 hour.
  3. Supplements.              GUESSED at six of them, I did not count the
                               actual list. Open each portal and count.
  4. Aid forms.                Separate track with its own date, and it is
                               not an admissions essay, so it is fourth here
                               but it is not optional.

DEADLINES
  State school, Nov 30.        CHECKED on the university's own dates page.
  Private, early round.        GUESSED. Open their admissions deadlines page.
  Second private, regular.     GUESSED. Same, open the page.

WON OR LOST
  On the essay and on what your recommenders are holding. The list and the
  numbers are finished. You have been editing the activities section.

2 guesses, both deadlines, both checkable in five minutes.
Fix those two and tell me to go.
```

## The trap

A naive version sorts by how hard each task sounds and tells you to do the easy
ones first, which produces a tidy checklist where every item is real and the
ordering is useless. The other version assumes you have more time than you do,
hands you a twelve week plan in week eleven, and never says the word "closed."
If a window has passed, this skill says so in the first lines and moves to what
is left, instead of writing you a plan for a cycle that ended.

## Limits

It cannot tell you your odds anywhere. Nobody can, and any number offered for
that is invented.

It does not know your school's internal dates: counselor forms, transcript
requests, recommendation portal cutoffs. Those are often earlier than the
published application deadline and they are a real way to miss. Ask your
counselor directly and treat the answer as the date that matters.

It assumes you told me the truth about where you are in the process. If you
have not actually started an essay you described as "basically done," every
priority below it is wrong.

---

## How this one knows what it knows

Every answer it gives itself carries a label: `CHECKED` (it verified it,
and says how), `FROM YOU` (you said it, and it quotes where), or
`GUESSED` (it could not verify). Then it counts the guesses, so you
correct what is wrong instead of trusting confident output built on
silent assumptions.

> Never ask for something you can check.
> Never assume something you cannot check.

One of 48 skills. The rest, and the house rules: [https://github.com/nradawg/assume-nothing](https://github.com/nradawg/assume-nothing)

MIT.
