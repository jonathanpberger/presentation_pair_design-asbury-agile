### Todo
- [] core practice talk
- [] blog post
- [] transcription notes
- [] gdoc of `pairing`


---

**Hi :-)**

---


# Pair Design for Fun and Profit

IxDA Grand Rapids, 2014

Jonathan Berger, Pivotal Labs

---

**Who Am I?**

- @jonathanpberger
- ~30 agile projects since ~2008
- design, code, product
- interested in agile practice for design

---

**Table of Contents**

---

# Pairing and Design

For years, Developers have used Pair Programming to improve the health and happiness of their code—and themselves. Can similar techniques be applied to design? What might Pair Design look like as a practice? [Cooper][] has paired for years, and we've been experimenting with Pair Design at Pivotal as well.


# history
## Pairing—where does it come from?
  - came out of continuous code review
  - "would 100% pairing fail?" no!

## Pairing as crit
  pairing came from code review is good, more frequent code review is better, continuous code review is best.

  Does the same thing work for crit?


## setup: what do you need to make pairing successful?
  - no cubicles
  - etiquette: verbalize thoughts, announce "let me try something..."
  - < 2 keyboards? WTF?!
  - dvorak? use a hardware dongle
  - remote pairing: ipad, floating heads, ask [Joe Moore][]

---

# Benefits

## Why Pair Design?

Pair design enjoys many benefits which come over unchanged from pair programming: pairing reduces the cost of change, creates predictability, reduces waste, and promotes learning, knowledge-transfer, and continuous improvement.  It helps teams to start from a shared foundation, to make creative decisions collaboratively, to externalize and validate thinking, to optimize for progress (not perfection), to remove individual ego and promote shared ownership of product.

## Pairing for knowledge transfer
## Pairing for skill transfer
- Overlapping Broken Combs

## Pairing for fresh eyes
- pairing encourages rotation

## Pairing for bus count

## What is pairing?
- not the same as collaboration


## enablement
  - knowledge transfer (good for businesses)
  - skill transfer (good for individuals)
  - Ramping up new teammates
  - enabling rotation => better Bus Count

## collective ownership of code
  - tie-in to CI

## buddy system for attn
  - your pair doesn't care about your facebook or email
  - sustainable pace
  - fun!

---

# Practice
### "Synth/Gen" Whiteboard pairing

It's very common to pair at the whiteboard: two Pivots, one marker. The "Generator" has the marker in hand, and tends to come up with ideas. The "Synthesizer" stands back, asking questions, probing, thinking of edge cases, keeping the big picture in context. This technique is frequently used to map out feature sets or user-flows at about the epic level of granularity.

### Medium-Fidelity Illustrator Pairing

When whiteboard-fidelity is no longer sufficient to make design decisions, two designers will sit down at a single copy of Adobe Illustrator (or Photoshop, or Sketch or the like) and work on the design together. This greatly resembles pair programming, and they'll trade off control of the cursor just as pair programmers do. The designers discuss the design challenge, occasionally turning to the computer to test out a feeling, illustrate an idea, or enshrine a decision. When they hit an impasse, they may split up for a short time (usually 10-30 minutes) to work through ideas on their own before converging again, presenting their explorations, and continuing to work the design.

### Two-keyboard "Cross-functional" Code pairing

When it's time to implement design, "Cross-functional pairing" is a misnomer when two designers pair together on code, but the name stuck. While it's usually untested,

http://www.andersramsay.com/2011/09/26/cross-functional-pairing/


### Cross-Functional pairing

Cross-Functional pairing usually describes a designer and a developer pairing together on styling and front-end code. Pairing across disciplines is crucial for good communication across teams. The knowledge-sharing benefits of cross-functional pairing tend to be even more pronounced than during intra-disciplinary pairing.

Traditionally, a designer painstakingly creates a pixel-perfect high-fidelity static mockup, then hands it off to the developer who builds the software, after which the designer looks for errors and red-lines the result. Then, the developer would amend the software to match the redlines, the designer would review the result, and the process would repeat until the designer was satisfied (or exhaustion set in). This process is slow, siloed, and adversarial.

By contrast, cross-functional design pairing sits the designer and the developer together at the keyboard to style the software. This has several economies and advantages:

- because the designer is working directly on the full-fidelity software, there's no need to reproduce the design in mock-ups (a time-consuming task),
- because the work is being done directly on the app, there's no time spent marking up (on the designers part) and decoding (on the developers part) redlines (both time-consuming tasks),
- because they're pairing and having a conversation, the developer learns the rationales behind the design decisions.

Developers are also learning general design theory which helps them make better design decisions when designers aren't available. Meanwhile, the designer learns about the relative cost of implementing various design strategies in the application. They also learn more about implementation, which helps them make design decisions which better fit the technology when developers aren't around.

So far we've only described the efficiencies of Cross-Functional Pairing which make it cheaper and more effective than solo design. Pairing also introduces advantages which aren't available to solo design. When designing in front of working software (rather than static mock-ups), designers are able to generatively experiment and design in real-time. They can play with interactions, make changes at full-fidelity, and be creative in a way that's impossible in a mock-up. Furthermore, the designer and developer are taken from an adversarial context ("You didn't implement my design correctly!" or "this design is inconsistent / bad / not worth the effort") to a collaborative context, which contributes to unit cohesion, a better bus-count, and collective ownership of the product.

---

Some solo techniques include:

### Double-Speed Documentation

Once made, design decisions often have to be documented. Design pairs will split up to create the [Minimum Viable][] [DRY documentation][]. Because there are two designers, they deliver in half the time.

### Exquisite Corpse

The name Exquisite Corpse is taken from the surrealist literary parlor game of the early 20th century in which "players draw in turn on a sheet of paper, fold it to conceal part of the drawing, and then pass it to the next player for a further contribution". In exquisite corpse, designers will set a short timer (usually 10-30m), work on a design direction, and then pass it off to the next designer. Alternately, designers can forego the timer and just say "ready?" when they're stuck. Ideally, several revolutions are completed each hour, allowing for rapid iteration, idea generation, and refinement.

### Diverge / Converge

SOMETIMES WE'LL BREAK OUR PAIR, WORK ON SOMETHING SOLO FOR ~20M OR WHEN WE GET STUCK, WHICHEVER COMES FIRST, AND THEN RECONVENE.


---

## hogging the keyboard
  - flip it around
  - toys to occupy hands

## talking points about pairing
  - "this doesn't feel good" — how to make it better?
  - "doesn't it take 2x as long?"
  - the expensive part of software development is maintaince; GIGO

## the "Tri-pairing" canard
  - protect the notion of "pairing"

## war stories
  - best pair EVAR!
  - worst pair EVAR!



---

## links

[Joe Moore]: <>

---
<script src="js/impressConsole.js"></script>
<script>
    impressConsole().init();
    // impressConsole().open(); // for console to open automatically
</script>


