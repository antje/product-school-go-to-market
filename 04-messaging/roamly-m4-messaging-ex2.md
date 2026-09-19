# Roamly Groups · Messaging, Module 4 (Exercise 2)

AI runs on 2026-09-19 with Claude, each from a fresh context. The copy generation used the Exercise 2 guide's prompt, adapted to carry both pillars and the host context. The visual asset went through four versions and four cold reads; every read used the guide's three swap questions and saw only the image. Responses are verbatim.

## Responses

### Step 1 · Surfaces

In-app notification (organizer, at checkout), onboarding tooltip (friend, payment screen), sales one-liner (supply team to a host). One per party in the booking; the friend's screen is the one I was least sure of.

### Step 2 · Generate your copy variations

**Prompt**

I am building messaging for Roamly Groups, a coordinated group-booking feature on a curated travel experience platform. The go-to-market motion is product-led. Here are my full messaging pillars for two audiences, plus one supply-side line.

Pillar for the organizer (the friend who plans the group trip, has booked on Roamly before, and ends up fronting the money and chasing everyone to pay them back):
- Value prop: Never be the bank for the group trip again. Pick the experience, share one link, and the whole group books together without a dollar on your card.
- Capabilities: One shareable link per experience. Each friend pays for their own seat from the link. The host holds the seats until the group is full or the deadline passes. The booking confirms for everyone at once, and if the group does not fill, nobody is charged. Reminders come from Roamly, not from you.
- Evidence: In Airbnb's 2017 survey of 2,000 travelers, 38% of people who traveled in a group had not been paid back in full, and 43% of those had lost $1,000 or more. Roamly's own support queue shows organizers working around the product today: separate accounts on the same slot, manual split payments, and high drop-off on those sessions. Roamly hosts: 12,000 vetted local experts across 40 cities, and repeat booking rates three times the industry average.

Pillar for the friend (someone invited by the organizer, usually not on Roamly, who needs to say yes and pay for their seat without installing anything or creating an account):
- Value prop: One tap and your seat is yours. Pay your share from the link and you are in. Nobody is chasing you, and you are never charged unless the whole group is going.
- Capabilities: Guest checkout on one screen, with Apple Pay and Google Pay. No app to install and no account before you pay; an account is offered after. Your seat is held while the rest of the group pays. If the group does not fill by the deadline, you are not charged.
- Evidence: The host's rating, review count and vetting badge shown on the payment screen, so the friend is paying a real person for a real slot. The countdown and the list of who has already paid.

Supply-side context for the host (the vetted local expert who runs the experience): the core product truth is that the host has agreed to hold seats for a group until the whole group has paid or the deadline passes. The host gets a confirmed full group, or the seats back by the deadline, and never holds seats for people who will not show.

Generate one copy variation for each of these three surfaces, written entirely from the pillars above. Keep each one human, specific, and free of jargon:
1. In-app notification to the organizer, shown at checkout when they are about to book one seat on Roamly (from the organizer pillar).
2. Onboarding tooltip on the friend's payment screen, the first thing they see after opening the organizer's link (from the friend pillar).
3. Sales one-liner the Roamly supply team opens with when asking a host to opt into holding seats for groups (from the host context).

For each, tell me which part of the pillar it leads with and why.

**Response**

Report delivered.

### Step 3 · Create your visual asset

Built from the organizer pillar. Four versions:

- **v0**, infographic card generated with a design tool from the exact copy: headline, three capability rows, 38% Airbnb stat, 12,000 hosts, "3x industry average". Kept in the repo as `assets/roamly-m4-asset-v0.png`. After blind read 1: cut the 3x line, moved the brand to the top, changed the photo from a couple to a friend group.
- **v1**, image-model prompt for a candid photo with the message as caption. Human, but the compressed subline dropped the hold.
- **v2**, hold restored ("while the host holds the spots"), Airbnb survey replaced with a Roamly pilot line measuring speed ("9 in 10 groups that share a link confirm within 48 hours").
- **v3**, speed line replaced with a money line ("9 in 10 groups booked with nobody fronting the money", 412 groups). Blind read 3 asked whether the other one in ten had fronted the money, which exposed that under the all-or-nothing rule nobody can, so the rate was meaningless and only restated the promise.
- **Shipped**, completion line ("9 in 10 groups that shared a link filled and booked. Roamly pilot, 412 groups, 2026"), the same leading indicator as Modules 1 and 2. `assets/roamly-m4-asset.png`.

The pilot figure is illustrative; the scenario has no launch data.

**Final image prompt**

Create a 1080x1080 social post for Roamly Groups, a feature of a travel experiences app. Photo: a candid phone-shot moment, six friends in their late twenties around a street-food table at night, mid-laugh. One of them, the organizer, is looking at their phone with quiet relief. Warm light, real skin, slightly grainy. Not staged, not stock. Text overlay, exactly these lines in this order, nothing added: 1. Small label, top of the text block: ROAMLY GROUPS. 2. Headline, large, two lines: Never be the bank for the group trip again. 3. Two lines below it: Share one link. Everyone pays their own seat while the host holds the spots. Confirmed together, or nobody's charged. 4. Small line: 9 in 10 groups that shared a link filled and booked. (Roamly pilot, 412 groups, 2026). 5. Button, bottom left: Book together on Roamly. Layout: text block in the lower 45% on a soft dark gradient so the faces stay clear. Cream sans-serif text, mint for the label and button. No icons, no boxes, no bullets, no charts. It should read like a shared moment with the message as its caption.

### Blind read 1 · version 0, the infographic card

**Prompt**

You have never heard of Roamly or Roamly Groups. Look at the image. Review it in silence as a cold reader, then answer three questions in your own words, without reusing the image's phrasing: 1. Who do you think this is built for? 2. What do you think the product actually does, based only on what you can see? 3. What makes you trust it? Then flag anything unclear, anything you had to guess, and anything that made you trust it less.

**Response**

Report delivered.

### Blind read 2 · version 2, photo with the speed statistic

**Prompt**

You have never heard of Roamly or Roamly Groups. Look at the image. Review it in silence as a cold reader, then answer three questions in your own words, without reusing the image's phrasing: 1. Who do you think this is built for? 2. What do you think the product actually does, based only on what you can see? 3. What makes you trust it? Then flag anything unclear, anything you had to guess, and anything that made you trust it less.

**Response**

Report delivered.

### Blind read 3 · version 3, photo with the money statistic

**Prompt**

You have never heard of Roamly or Roamly Groups. Look at the image. Review it in silence as a cold reader, then answer three questions in your own words, without reusing the image's phrasing: 1. Who do you think this is built for? 2. What do you think the product actually does, based only on what you can see? 3. What makes you trust it? Then flag anything unclear, anything you had to guess, and anything that made you trust it less.

**Response**

Report delivered.

### Blind read 4 · shipped version, photo with the completion statistic

**Prompt**

You have never heard of Roamly or Roamly Groups. Look at the image. Review it in silence as a cold reader, then answer three questions in your own words, without reusing the image's phrasing: 1. Who do you think this is built for? 2. What do you think the product actually does, based only on what you can see? 3. What makes you trust it? Then flag anything unclear, anything you had to guess, and anything that made you trust it less.

**Response**

Report delivered.
