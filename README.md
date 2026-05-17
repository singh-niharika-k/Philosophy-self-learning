# How to Think About Being Alive

A self-guided 4-week course in philosophy, built around the passages I highlighted while reading *How to Think About Being Alive* — a primer on metaphysics, ethics, relationships, and how to live.

🔗 **Live site:** `https://<your-username>.github.io/<repo-name>/`

---

## What this is

A single-file, self-paced interactive course. Eighteen chapters across four weeks, with a "Why you flagged this" callout on each chapter tying the material back to the highlights and questions I made in the original document, plus a short quiz and a guided journal prompt per chapter.

It's a personal learning tool, but it works as a starter introduction to philosophy for anyone interested in the same threads — existentialism, friendship, attention, community, building a worldview.

## What's in it

**Week 1 — Foundations & The Self You're Authoring**
What philosophy actually is, a closer look at epistemology, the free will question, meaning as something you make rather than find, and the self as a process rather than a fixed thing.

**Week 2 — Frameworks for Living**
Stoicism (regulation without suppression), the four voices of existentialism, utilitarianism and its link to democratic socialism, Kant on intent vs impact, and virtue ethics' pursuit of eudaimonia.

**Week 3 — Real Relationships**
Aristotle's three kinds of friendship, Martin Buber's I-Thou moments, care ethics (showing up, listening, noticing), and Simone Weil on attention as the rarest form of generosity.

**Week 4 — Community, Belonging & Building Your Worldview**
Communitarianism's claim that belonging is constitutive of personhood, loneliness as a civic crisis, the ongoing project of composing a worldview, and a curated reading list to extend the threads.

## How to use it

Open the site. Pick a week. Work through chapters in order, or jump to whatever pulls at you. Each chapter has:

- A short reading
- A quick multiple-choice quiz with feedback on the answer
- A journal prompt designed to test the idea against your actual life

Progress, quiz answers, and journal entries save automatically to your browser. Close the tab and they're still there when you come back.

## A note on saved data

Everything is stored in your browser's `localStorage` — there's no backend, no account, no tracking. The tradeoff: data lives in **one browser on one device**. If you journal on your laptop and then open the site on your phone, the phone won't see what you wrote on the laptop. Pick one device as your "philosophy device" if you want continuity.

To export your journal entries, open the browser console (`F12` on most browsers, `Cmd+Option+I` on Mac) and run:

```js
copy(localStorage.getItem("philosophy_course_v1"))
```

That copies a JSON blob with all your progress and journal entries to your clipboard.

## Built with

Plain HTML, CSS, and JavaScript in a single file. No frameworks, no build step, no dependencies. The styling uses system serif fonts; no external assets are loaded.

## Source material

The content is adapted from a personal learning document titled *How to Think About Being Alive: A Self-Guided Introduction to Philosophy*, expanded with additional context on the passages I marked as most interesting.
