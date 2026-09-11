# TARGET

Six lines. This is the whole skill we teach in Session 1.

A model will guess at every decision you leave open, and it guesses badly.
Six lines close off the six decisions that matter most. That is the entire
trick, and it is why the second site you build today will be better than the
first.

**T**hing &middot; **A**udience &middot; **R**equirements &middot;
**G**uardrails &middot; **E**xperience &middot; **T**est

Fill these in, then paste all six lines into Gemini. Replace the italic prompt
after each dash and leave the dashes alone.

---

- **T &mdash; Thing:** *one sentence. If someone asked "what did you make?", this is the answer*
- **A &mdash; Audience:** *a specific person, not a category*
- **R &mdash; Requirements:** *the two or three things that, if missing, make it pointless*
- **G &mdash; Guardrails:** *what it must never do*
- **E &mdash; Experience:** *sections in order, one accent color, one site it should feel like*
- **T &mdash; Test:** *what you would check before showing it to someone whose opinion you care about*

---

## Stuck on a line?

**T &mdash; Thing.** Keep it to one sentence. If it needs two, you are probably
building two things.

**A &mdash; Audience.** "Employers" is too vague to be useful. "A recruiter at a
company I actually want to work at, who will give this 30 seconds on their
phone" tells the model about length, layout, and what goes first.

**R &mdash; Requirements.** Not everything you *want*. The things that, if you
took them out, would make the whole thing pointless. Two or three, not eight.

**G &mdash; Guardrails.** This one feels strange to answer and it is the most
useful line in the file. What does every other version of this get wrong? What
would embarrass you? What are you tired of seeing?

**E &mdash; Experience.** The line everyone writes worst, because it is tempting
to write moods. *"Forest aesthetic with beach vibes"* gives a model nothing to
build. Structure does: **sections in order, one accent color, one reference.**
Write "hero, story, three highlights, contact. Deep green. Lots of whitespace.
Should feel like a clean personal site, not a resume" and you will get something
completely different.

**T &mdash; Test.** You need a finish line, or you will keep fiddling until the
room clears out. What is the one thing that has to be true?

---

## A worked example

Deliberately not a personal website. Copy the *shape*, not the words.

- **Thing:** A page that shows which Cal Poly dining spots have the shortest lines right now.
- **Audience:** Me and my three roommates, on our phones, walking out of class.
- **Requirements:** Show every dining location, let anyone report a wait time, sort shortest first.
- **Guardrails:** Never require an account. Never take more than two taps to report a wait.
- **Experience:** One screen, no scrolling. Big tappable cards in a single column. Green for short waits, red for long. Feels like a weather app, not a spreadsheet.
- **Test:** I can open it walking out of Building 52, know where to eat in under three seconds, and report a wait without thinking about it.

Nothing in there is clever. It is specific, it is short, and every line closes
off a decision the model would otherwise make badly on its own.

---

## My prompt

- **Thing:** 一个给大学生记账的网页
- **Audience:** 我自己每天做记账总结或者买完东西之后 
- **Requirements:** 要有不同种类的记账（萌物，礼物，生活用品，旅行，吃饭，其余），要有一个剩余总金额的记录，有些时候是输入人民币，有些时候输入美元，记账本用美元，汇率按照6.75来算，还要有一个可以更改的计划在每个种类上支出多少钱，每次在那个种类上花钱了就在那一类的预算里面扣
- **Guardrails:** 不需要账户和密码，不要等待太久才刷新
- **Experience:** 要可爱，小动物元素，手绘风格，one page 但是里面记账模块可以scroll
- **Test:** 我可以随时查看我的支出情况和用来买到了一些啥

Nothing in there is clever. It is specific, it is short, and every line closes
off a decision the model would otherwise make badly on its own.

---

## Why this file exists

You built this site twice today. Once from a one-line prompt, once from the six
lines above. The second one was better, and it was better because of this file,
not because the AI got smarter in between.

The tool will change three times before you graduate. TARGET will not.
