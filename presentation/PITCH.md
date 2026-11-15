# Five minute pitch

Written for a general audience. No jargon survives unless it is explained in the
same breath. Timings are cumulative. The four physiology slides run 90 seconds and pace section two.
The older bubble-animation.html is superseded by them.
Word counts assume 160 words per minute, a normal pitch pace.

---

## What I changed from the first draft, and why

**The historical EVA record is out.** It is an argument with experts, conducted
in front of people who did not come for one. It belongs in the written
submission, not the pitch.

**One minute, not two.** Two ten second breath holds. You were right, and the
honest number is better than the cautious one. It takes the return from six to
one up to twenty-six to one.

**Everything technical now has a plain version first.** Nobody hears
"pulmonary capillary bed" and pictures anything. They hear "the smallest blood
vessels in the lungs" and they see it immediately.

**One analogy carries the whole explanation.** A bottle of fizzy drink. Open it
slowly and nothing happens. Open it fast and it foams. That is decompression,
and everyone in the room already understands it.

---

## The script

### 1. The hook — 0:00 to 0:36

> Open a bottle of fizzy drink slowly and nothing happens. Open it fast and it
> foams over.
>
> A spacewalk is the bottle. Cabin pressure down to a suit at a third of it, and
> gas dissolved in the body comes out as bubbles.
>
> NASA accepts up to a fifteen percent chance of decompression sickness on a
> moonwalk. Their plan sits at eight. That works for an average person, and
> nobody is average. Some people bubble far more than others, and there is no way
> to tell who.
>
> We think there is, and it takes ten seconds.

*Title slide. Hold it. The fan chart comes later, at the end of section two.*

---

### 2. How it works — 0:36 to 2:06

*Two slides, 90 seconds, and they advance themselves.*

> Drop the pressure on a body and nitrogen comes out of solution as bubbles. How
> big they are and how many of them there are decides what happens. Pain in the
> joints. An organ that stops working. That is decompression sickness.
>
> And almost nothing can monitor it. No scan, no blood test, no number for how
> much a given person actually bubbled.
>
> Except the bubbles have to go somewhere, and they all go to the same place.
> Everything in the veins comes back to the lungs, and the vessels there are the
> smallest in the body, so that is where bubbles stop.
>
> On the left is a normal lung unit. Air inside, blood running past, a barrier
> half a micron thick between them. Oxygen crosses out, carbon dioxide crosses
> in, almost as fast as the blood arrives.
>
> On the right, a bubble has lodged against it. The wall is damaged and swollen,
> and the gas is struggling to get across.
>
> So we measure that. One breath, ten seconds, before the spacewalk and after.
> The fall is the decompression stress that actually happened to that astronaut.

*Second slide, the fan chart.*

> Here is what that buys you. The black line is NASA's own predicted risk against
> suit pressure. The green line is a crew member whose lung barely moved. The red
> line is one whose lung moved a lot. Same suit, same protocol, three very
> different numbers.
>
> Today every one of them is flown as the black line.

---

### 3. What it buys, and who it is for — 2:06 to 3:05

> So here is the trade. Two breath holds per spacewalk. One minute of crew time.
> Across a five spacewalk lunar stay, five minutes.
>
> The way you prevent bubbles is to breathe pure oxygen before going out, and
> that costs nearly an hour of an astronaut sitting still.
>
> If the test shows someone barely bubbles, they do not need the full hour. Spend
> five minutes, get back a hundred and thirty. Twenty-six to one, and about
> thirty-eight thousand dollars of crew time.
>
> It runs the other way too. Someone who bubbles heavily, flying the average
> plan, sits at nine percent while everybody believes they are at three. Today
> nobody finds that person.
>
> And that is the part that matters. Right now a crew member walks out of the
> airlock carrying a number that belongs to a population, not to them. Their own
> risk is unknown. We hand them their own number, and the first honest answer to
> a question every one of them has already asked.

---

### 4. What we built — 3:05 to 4:02

*Two screens. Click, do not narrate the interface.*

> So what do we actually do.
>
> We take data from hardware that is already there. The breathing test exists.
> Cabin and suit pressures are already logged. Nothing new gets launched.
>
> We separate the fall caused by oxygen from the fall caused by bubbles, because
> without that split the measurement means nothing.
>
> And we turn it into two things. One for the crew member, answering a single
> question. Am I more sensitive than the plan assumes, or less.
>
> And one for the ground. Set the risk you will accept, fix whatever cannot move,
> and it solves the rest. Oxygen time, exercise, decompression rate. It tracks a
> whole mission, and each day is predicted using only the days before it. By day
> three you are not flying the textbook. You are flying that astronaut.
>
> It is built on NASA's published numbers and reproduces them. Where they say
> eight point four percent, we say eight point four.

---

### 5. The close — 4:02 to 4:56

> We should be straight about the weaknesses. Three numbers in our model have
> never been measured. We left them as visible dials rather than burying them in
> the code. And this is not a must-have. It is better than flying blind.
>
> It is also copyable, because it is arithmetic on an existing test. Our answer
> is that it is done, and it plugs into what already flies.
>
> It matters anyway, because NASA has this written down as an open question. They
> do not know what the oxygen requirements should be for the atmosphere they plan
> to fly to the Moon, and their standard says it has to be proven by testing, not
> modelling.
>
> Nobody has an instrument that can do that testing in space.
>
> A ten second breath hold is not the whole answer. But it is the first
> measurement that could turn their open question into data, and it costs one
> minute.

---

## Delivery notes

Four numbers have to land. **Fifteen percent.** **One minute.**
**Twenty-six to one.** **Nine percent instead of three.** Slow down on those and
speed up on everything between them.

The bottle is the whole explanation. If you only have thirty seconds and have to
cut to the bone, open with the bottle and go straight to section four.

Do not apologise for what the model does not know, state it. Section six is what
separates you from the field. If you overrun, lose fifteen seconds from section
five instead by dropping the mission tracking.

If a judge asks what the weakest part is, answer instantly: the number that sets
the scale of the whole thing comes from a 1995 study where we could only ever
read the summary, not the full paper. Having that loaded is worth more than
pretending there is no weak part.

If a judge asks whether this is already solved, the short answer is that it has
never been a problem in orbit because astronauts float. On the Moon they walk,
and walking makes bubbles. That is the whole reason this is open.

---

## SWOT, for the written submission and for questions

Not spoken. The pitch carries strengths in sections 4 and 5, and the weakness
and the threat in section 6, because volunteering them first is what makes the
rest credible. This table is what you answer from when a judge pushes.

| | |
|---|---|
| **Strengths** | Quick, one minute of crew time. Uses a test that already exists and hardware already flown, so nothing new is launched. Built for the space problem specifically rather than adapted from a clinical tool. Gives the astronaut their own number, which nothing currently does. Meets a need NASA has written down and not filled. |
| **Weaknesses** | Not a must-have. It improves on flying blind rather than replacing a decompression model. Three model coefficients have never been measured. The personal factor is an index, not a calibrated probability for that individual. |
| **Opportunities** | Plugs into the existing NASA pipeline rather than competing with it, so it can ship as a feature rather than a programme. The same measurement applies to commercial spaceflight, to diving and to hyperbaric medicine. |
| **Threats** | Not verified against flight data, and nobody can verify it without flying it. The method is simple enough to be copied once described. If NASA revises its own prebreathe standard first, the time saving argument shrinks. |

Two answers worth having ready.

**"Why has nobody done this?"** Because the lung test was treated as an outcome
to study, not an instrument to fly. Thorsen measured the drop in the nineties
and then it sat in the literature.

**"How confident are you in the numbers?"** NASA's own published figures come
back out of our model to two decimal places. The individual scaling does not,
and we have not claimed it does.
