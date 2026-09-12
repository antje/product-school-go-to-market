# Roamly Groups · GTM Strategy, Module 1 (Exercise 2)

AI runs on 2026-09-12 with Claude, in one conversation, started from a fresh context. Prompts are the Exercise 2 guide's prompts with the inputs below filled in. Responses are verbatim. The V1 one-pager and the infographic (Step 5) are separate files: `roamly-m1-gtm-one-pager.md` and `roamly-m1-gtm-infographic.html`.

## Responses

### Step 1 · Commit to a GTM motion

**Which motion did you choose, PLG, SLG, CLG, or a hybrid? Explain why; if hybrid, what are your primary vs. secondary layers?**

PLG primary, CLG secondary.

Run through the five inputs for Roamly Groups:

- Time to value: minutes. The organizer creates a group, shares a link, friends pick and pay. Value lands in the first session.
- Buyer and user: same person. The organizer books and attends. The friends who pay their share are also users.
- Annual contract value: low. One booking is tens to a few hundred dollars per seat. No procurement, no contract.
- Sales cycle: self-serve. Nobody at Roamly should ever touch a group booking.
- Scales via: product virality. Every group booking sends invites to people who are not on Roamly yet. The invite step is the distribution.

All five land on PLG, so the product itself is the sales vehicle and the invite flow is the pitch.

Why a CLG layer: Roamly already grows through travel communities, review sites and social media, and group travel is peer-influenced by nature. The organizer is the peer who brings the group. Layering CLG means seeding the feature where organizers already talk to each other (travel subreddits, trip-planning creators, Roamly's own review and share surfaces) instead of buying reach. The key signal to watch is the one from class: referral becomes the top acquisition channel for Groups.

What we are not doing: SLG. Company teams would need invoicing, a buyer who is not the user and a human-led cycle. That is a later phase with a different motion, not this launch.

### Step 2 · Compile your strategic inputs

- **Target segment:** Friend groups of 3 to 8 planning a shared trip, reached through the organizer: an existing Roamly user with 2+ bookings who today opens a group chat, a spreadsheet and a payment app to get everyone booked, fronts the money, and chases friends to pay. Consumer, self-funded, no approval needed beyond the friends saying yes.
- **Value proposition:** Book experiences for your whole group in one place. Everyone sees the plan, everyone pays their own share, nobody chases anyone. For the organizer: no spreadsheet, no fronting the money, no reminders.
- **GTM motion:** PLG primary, CLG secondary (Step 1).
- **Primary goal:** Expand. Grow within the base: existing repeat users booking as a group instead of solo, so each booking carries several seats. New-user signups from invites are the second-order effect we measure, not the goal we launch against.
- **Target audience:** Active Roamly users with 2+ bookings in the last 12 months who show group signals (multiple accounts on the same slot, split-payment support tickets, "book for my friends" feedback), in the cities where those signals cluster.

### Step 3 · Pressure-test your strategy

**Prompt**

I am a Senior Product Manager at Roamly. I am developing a GTM strategy for Roamly Groups, a new feature enabling coordinated group booking, split payments and shared itinerary planning.

Here are my strategic inputs:
- Target segment: Friend groups of 3 to 8 people planning a shared trip, reached through the organizer. The organizer is an existing Roamly user with 2+ bookings who today opens a group chat, a spreadsheet and a payment app to get everyone booked, fronts the money, and chases friends to pay them back. Their acute pain is unpaid coordination work and carrying the financial risk for the group. Buying authority: consumer, self-funded, no approval needed beyond the friends saying yes.
- Value proposition: Book experiences for your whole group in one place. Everyone sees the plan, everyone pays their own share, and nobody has to chase anyone. For the organizer: no spreadsheet, no fronting the money, no reminding friends to pay you back.
- GTM motion: PLG primary, CLG secondary. All five motion inputs land on PLG: time to value is minutes, buyer and user are the same person, contract value is low (one booking, tens to a few hundred dollars per seat), the cycle is self-serve, and it scales through product virality because every group booking sends invites to people who are not on Roamly yet. The CLG layer seeds the feature where organizers already talk to each other (travel communities, trip-planning creators, Roamly's own review and share surfaces) rather than buying reach. Not SLG: company teams would need invoicing and a human-led cycle, which is a later phase.
- Primary goal: Expand. Grow within the existing base: repeat users booking as a group instead of solo, so each booking carries several seats. New-user signups from invites are a second-order effect we measure, not the goal we launch against. Target audience: active Roamly users with 2+ bookings in the last 12 months who show group signals (multiple accounts on the same slot, split-payment support tickets, "book for my friends" feedback), in the cities where those signals cluster.

Play the role of a skeptical CMO who has reviewed dozens of GTM plans. Tell me: (1) which of my inputs is the weakest and why, (2) the assumption I am most likely not seeing because I am too close to it, and (3) what you would cut or sharpen. Be direct.

**Response**

You asked for the skeptical CMO. Here it is.

#### 1. The weakest input is the goal

"Expand" does not survive contact with your own evidence.

Your strongest demand signal is "multiple accounts on the same slot." Read that again. It means the friends are already Roamly users, and they already booked. Roamly already has those seats. Groups consolidates them into one booking and changes the revenue by zero. Possibly by less than zero if anyone ever proposes a group discount.

So the expand case rests on one of two claims you have not made: either organizers who currently book solo will start bringing friends who would not otherwise have come, or lower friction raises trip frequency. Both may be true. Neither is stated, sized, or baselined. Right now "each booking carries several seats" is a description of the feature, not an outcome.

And you have built an acquisition engine and then said acquisition is not the goal. Every group booking invites people who are not on Roamly. That is the mechanism. Launching against a metric the mechanism does not naturally move means the launch will look like a failure on your own scorecard even if the product works.

What I would want on the page: a count of organizers who fit the segment (2+ bookings, group signals, target cities), the seats those organizers' groups already generate today, and the incremental seat number you are betting on. If that count is small, this is a retention play for your most loyal 3 percent, which is a fine thing to be but not what the deck says.

#### 2. The assumption you cannot see: you are the organizer

Every input is written from the organizer's chair. The organizer has the pain, the organizer is the existing user, the organizer gets the value prop. Fine. The organizer is one person out of eight.

"Buyer and user are the same person" is true for one seat. The other seats are separate buyers, each of whom has to say yes, sign up, and pay before the group is booked. Each one is a cold conversion. If each friend completes at 80 percent, a group of seven completes about a quarter of the time. "Time to value is minutes" is the organizer's clock. The group's clock runs until the last friend pays, which is days.

Worse, look at what the friend gets. Today they tap Venmo and they are done. Tomorrow they get a link to an app they do not use, create an account, and pay for something someone else picked. The organizer's life gets better. The friend's life gets worse, and the friends are the majority of the transaction. Your value proposition has no sentence for the friend. That is the gap.

The buried product question that decides whether the whole value prop is true: who holds the slot while six people pay? If Roamly holds inventory, the supply side eats that cost and will push back. If nobody holds it, the organizer either fronts the money after all or watches the slot disappear while chasing friends, now inside your app instead of in a group chat. "Nobody has to chase anyone" requires a hold mechanic that has not been designed or costed.

#### 3. Cut and sharpen

Cut "shared itinerary planning" from the launch. That is a different job (planning, not paying), a different competitor set, and a third claim in a value prop that should make one. Ship split pay at checkout. Itinerary is v2 if the payment loop closes.

Cut the CLG layer as a "motion." Reviews and share surfaces are owned channels. Creators and communities are a launch channel. Calling it a motion invites a question about community operations you have no plan for. Call it seeding and move on.

Sharpen the value prop to one line for the organizer and one for the friend. Organizer: "You never front the money." Friend: whatever makes the link faster than Venmo, and if you cannot write that sentence you do not have a friend-side product yet.

Sharpen the goal to a baseline and a delta. Use the same-slot signal as the baseline of seats you already have, not as proof of demand. State the incremental seats per organizer you expect and the group completion rate that gets you there.

Name the competitor honestly. It is not "spreadsheet and payment app." It is group chat plus Venmo, which works well enough for seven of the eight people. You win only if the friend's path is shorter than Venmo's, because the friends decide whether the group books, and they have no pain to sell against.

The pitch I would fund: "Split pay at checkout for organizers in four cities, hold mechanic designed, friend-side flow measured on completion rate first, seats per booking second, signups third." Same product, defensible metrics, and a launch that cannot be declared a failure by its own first slide.

### Step 4 · Push back and generate your one-pager

**Pushback chosen.** Finding 1 (the goal), on factual grounds: the CMO read the same-slot signal as seats already captured; the scenario says drop-off on those sessions is high, and current users are predominantly independent travelers. Findings 2 and 3 accepted.

**Prompt**

Here is my pushback on one of your assumptions: I am pushing back on your first finding. You read "multiple accounts on the same slot" as seats Roamly already has. The evidence says the opposite: drop-off on these group sessions is high, so those are bookings that started and died. They are seats we are losing, not seats we already own. And Roamly's current users are predominantly independent travelers, so most of the friends an organizer invites are not on Roamly today. Zero incremental revenue is wrong on both counts. Expand stands as the goal: the launch audience is existing organizers, and the outcome is completed group bookings that today fail.

I accept your second finding in full. The friend is the majority of the transaction and my value proposition says nothing to them. Refine with these changes: one value line for the organizer and one for the friend; group completion rate as the leading indicator, seats per booking as the success signal, invited-friend signups tracked as the acquisition by-product; a slot hold while the group pays as a launch requirement; CLG renamed to seeding, not a motion. Keep itinerary planning in the product but lead the launch message with split pay.

Based on this, refine my strategic inputs and generate a V1 GTM strategy one-pager that includes: a positioning statement, two to three key messages for the target audience, a recommended channel approach, and a suggested success metric for this motion.

Keep it concise and actionable. This is a first draft I will refine over the coming weeks.

**Response**

Taking the pushback on finding 1. You are right on both counts, and the second count strengthens finding 2: if most invited friends are not on Roamly, the friend's path is not a detail, it is the funnel. One thing to carry forward from the exchange: the drop-off number on those group sessions is now your baseline. Write it into the goal so the target is derived from it, not asserted.

#### Refined strategic inputs

**Target segment.** Organizers: existing Roamly users with 2+ bookings in the last 12 months and a group signal (same-slot sessions, split-pay tickets, "book for my friends" feedback), in the cities where failed group sessions cluster. Friends: the 2 to 7 people the organizer invites, mostly not on Roamly, who must each complete for the booking to exist. The organizer is who we reach. The friend is who we convert.

**Value proposition.** Organizer: you never front the money and you never chase anyone. Friend: one tap and your seat is yours, no account needed to pay. Both: Roamly holds the slot while the group pays, so the booking confirms for everyone at once or nobody is charged.

**GTM motion.** PLG. Entry point in product for segment organizers, invite link as the channel to friends, guest payment as the conversion path. Seeding (not a motion) in travel communities, trip-planning creators, and Roamly's own share and review surfaces in launch cities. No paid acquisition, no SLG.

**Goal.** Expand. Recover the group bookings that today start and die. Launch audience is existing organizers; the outcome is completed group bookings with several seats each. Invited-friend signups are tracked as the acquisition by-product.

**Launch requirements.** Slot hold for the payment window. Guest pay for friends with account creation offered after payment. Split pay leads the message; itinerary planning ships in the product, not in the headline.

#### Roamly Groups: V1 GTM one-pager

**Positioning statement**

For people who organize trips for their friends and end up fronting the money and chasing everyone to pay them back, Roamly Groups is a group checkout that holds the slot while every friend pays their own share. Unlike a group chat plus a payment app, the booking confirms for everyone at once and nobody is out of pocket.

**Key messages**

1. To the organizer: *Never front the money again.* Pick the experience, invite the group, and each friend pays their own seat. No spreadsheet, no reminders, no IOUs.
2. To the friend: *One tap and your seat is yours.* Pay your share from the link. No app to install, no account to create before you pay, nobody chasing you.
3. To both: *Confirmed together or charged never.* Roamly holds the slot while the group pays. If the group does not complete, nobody is charged and nobody is stuck.

**Channel approach**

- In product, primary. A "booking for a group?" entry point at checkout, shown to segment organizers in launch cities. A prompt after a booking that matches the same-slot pattern. Direct email to the cohort that filed split-pay support tickets, since they already asked for this.
- Invite link, the channel to friends. SMS or shared link, guest pay in one screen, account offer after payment. This is the step that decides completion rate, so it gets the design and testing budget.
- Seeding, launch cities only. Trip-planning creators and travel communities where organizers already talk. "Booked as a group of 6" on Roamly's share and review surfaces so every completed group is visible to the next organizer.
- Not doing at launch: paid acquisition, company or team bookings, itinerary planning as the headline.

**Success metrics**

- Leading indicator: group completion rate, the share of started group bookings that reach fully paid confirmation. Baseline is the current drop-off on same-slot group sessions. Set the target as a lift over that number, not a number picked from the air.
- Success signal: seats per booking among segment organizers versus their pre-launch baseline, read against a holdout of organizers who do not see the entry point.
- Acquisition by-product: invited-friend signups, and the share of them who make a second booking within 90 days. Measured, not targeted.
- Guardrails: held slots released unpaid (supply-side cost of the hold), and organizer time from invite to confirmation, so "minutes" stays honest.

**Open questions to close before launch**

- Hold window length and who bears the cost when a held slot is released unpaid.
- Guest pay without an account: what the friend sees in one screen, and the completion rate it needs to beat.
- The drop-off number and the organizer count in the four launch cities, so the target and the ceiling are written down.
