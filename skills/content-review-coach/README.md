# Content Review Coach

**A Claude skill that teaches a content marketer to review a blog post, use case page, customer
story or interview the way a senior reviewer would, and to finish with a decision about what to do
with the piece.**

## Why I built it

When a new content marketing manager joined my team, one of her first jobs was to go through our
existing content and decide what to do with each piece. Was it already well written, and what made
it work? Or was the keyword focus wrong? Did it need more images, or a rewrite? Was it a poor match
for our audience, and should we cut our losses and take it down?

There were too many pieces for me to go through each one with her. And the point wasn't for her to
know what Berry and I thought of each article. It was for her to learn to judge content the way we do.

So instead of having her ask Berry (who's really great at this) or me, I turned the way we review
into a coach. It asks for your gut reaction first, then the questions we'd ask, and only then shows
you what we'd have seen, in the pieces that work as well as the ones that don't.

## Who it's for

- Anyone who's been asked to improve existing content without much content or SEO experience
  behind them.
- A manager who wants their team to get better at judging content, and can't review every piece
  with them.

## How a session works

1. **Share a piece of content.** Paste it, upload a file or give a URL. It works on blog posts, use
   case pages, customer stories and interviews.
2. **Give your gut reaction.** Good, bad or mixed, and what made you feel that way. The coach starts
   from what you've already noticed.
3. **Answer a handful of questions.** Five to seven, all at once, picked for this piece and for what
   you didn't mention. Short answers and "not sure" are fine. One question always comes up in some
   form: does this piece belong on your site at all?
4. **See what a senior reviewer would see.** One reply that quotes the piece, says what's working and
   what isn't, and compares that with your answers.
5. **Decide what to do with it.** Keep it, promote it, edit it, restructure it, rewrite it, or take
   it down. The coach gives its recommendation, then asks for yours.

You answer before you see the coach's take, because that's where the learning happens: you find out
exactly where your read matched a senior reviewer's and where it didn't. A session is about four
exchanges, so it fits between other work.

## What's in this folder

```
SKILL.md                 the coaching method
references/house.md      your company: products, buyer, settled facts, house style
references/lenses.md     what a senior reviewer looks for, in depth
references/examples.md   worked examples of senior reviews
```

## Using it on your own content

The skill ships set up for **Plinth**, an invented company that makes software for architecture
studios, so you can try it straight away. Before you use it on your own content, spend some time
filling in `references/house.md` with:

- **What your company sells**, and which of your products work together.
- **Who buys**, and who reads your content but doesn't buy.
- **The topics you can credibly write about**, and the ones you can't.
- **Product facts that are settled**: renamed features, how things are structured, what's on which
  plan. The coach only calls a claim wrong when it contradicts one of these.
- **Your house style for use case pages.**
- **Where your drafts and published pieces live.**

The coach judges everything that depends on your company against this file, so the time you put in
here is what makes its feedback fit your content.

It's also worth replacing the Plinth examples in `references/examples.md` with real reviews from your
own team. They teach better than invented ones. Nothing else needs changing.

To install it, see [the main README](../../README.md#install).

## Credits

The reviewing method combines two people's patterns: mine (structure, story, form, facts, links,
whether the right product is in the right place) and those of
[Christopher (Berry) Dunford](https://www.linkedin.com/in/christopher-berry-dunford-ba461688/), a
senior content strategist (where a piece sits in the funnel, sales-piece titles, self-promotion, how early
the product turns up).

The buzzword list draws on Emma Stratton's work on plain B2B messaging.
