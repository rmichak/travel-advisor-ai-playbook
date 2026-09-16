# The Travel Advisor's AI Playbook: prompt kit

## What this is

Every prompt from the session, in the order it ran, written out in full and ready to paste. Each prompt sits in a grey box. Copy the whole box, paste it into ChatGPT or Claude, and replace the bracketed parts with your own scenario.

The kit is organized around the three hires from the morning: the Researcher, the Writer, and the Chaser. Each one ends with a short list of what you take home.

**Two Projects to create.** Everything you build lives in one of two Projects in your AI tool, so it is still there next week:

- "Destination answers" holds your reusable destination replies (Researcher).
- "My writing" holds your voice rules. Run every Writer and Chaser prompt inside it.

Saving instructions for both ChatGPT and Claude are in the Researcher and Writer sections below.

**Your Monday:** pick one hire. Run its prompts on one real client. Change nothing else this week.

**Every person, booking, and price in this document is invented.** The sample client scenarios are fictional. Use your own scenario with the client's identity stripped out first.

**Free-tier facts used here were checked against the OpenAI and Claude help centers on September 15, 2026.** Free plans change. If a menu or setting has moved, look for the same words in the nearest place, or email us at support@empowerment-ai.com.

---

## The one rule, and the sample scenarios

### The rule

Strip the client's identity before you paste. An AI assistant needs the trip: who is traveling in general terms, when, what they like, what they can spend, what they asked. It never needs the name, the passport number, the date of birth, the home address, the loyalty number, or the card. Replace names with "the client" or "the couple." Replace booking numbers with "[booking]." The answer is just as good.

### Sample scenario A: the anniversary couple (Researcher blocks)

> A couple in their early sixties celebrating their 35th anniversary. They want Portugal in October, about ten days. Budget around $9,000 for two, not counting flights, which they will book with points. She has limited mobility: a few steps are fine, long stairs and cobbled hills are not. They love food and wine, are not interested in museums, and would rather stay in one or two places than tour. They emailed: "Is October a good time for Portugal? Will it be too rainy? And is Porto or Lisbon better for people who don't want to walk uphill all day?"

### Sample scenario B: the spring break family (Supplier comparison)

> Seven people: two grandparents in their late sixties, two parents, three kids ages 6, 9, and 14. Spring break week, mid-March. All-inclusive, direct flight from Dulles, five nights. Budget about $12,000 total. Grandparents want quiet and a good beach. Kids want a water slide. Parents want a swim-up bar and one nice dinner without the kids. They asked you to compare two resorts.

### Sample scenario C: the group cruise you are selling now (Writer and Chaser blocks)

> You are hosting a seven night Western Caribbean sailing in February 2027 out of Fort Lauderdale. Group rate holds until October 15. Balcony cabins from $1,650 per person, interior from $1,050, plus $40 per person onboard credit from the group. Ports: Cozumel, Roatan, Costa Maya, and a private island. You have space for eight more cabins. You are selling it to past clients and on Facebook.

### Sample quote that went quiet (Chaser)

> You sent a quote nine days ago for scenario A: a ten night Portugal trip, Lisbon four nights and the Douro Valley six nights, a private driver for the transfers, $8,750 for two. The client said "looks great, let me talk to my husband" and has not replied since.

### Sample payment coming due (Chaser)

> A family booked on the group cruise. Final payment of $2,300 is due November 1. Today is October 20.

### Sample welcome home (Chaser)

> The anniversary couple just got back from Portugal. Trip ran October 8 to 18. The Douro Valley hotel was the highlight; they sent you a photo from the terrace.

---

## Hire one: the Researcher

Job description: turns a client question into a brief with a list of things to verify. Compares suppliers into a table. Answers the destination questions you get forty times a season, in your words. Never sends anything to a client.

### R1: emailed question into a research brief

Paste, replace the bracketed parts with your own scenario.

```
You are a research assistant for a travel advisor. I am going to describe a client and paste the question they emailed me. Turn it into a research brief I can use to write my reply.

The client:
[A couple in their early sixties celebrating their 35th anniversary. Portugal in October, about ten days. Budget around $9,000 for two, not counting flights. She has limited mobility: a few steps are fine, long stairs and steep cobbled hills are not. They love food and wine, are not interested in museums, and prefer one or two bases over a tour.]

What they emailed me:
"[Is October a good time for Portugal? Will it be too rainy? And is Porto or Lisbon better for people who don't want to walk uphill all day?]"

Give me the brief with these headings:
1. Short answer (three sentences I could say to them on the phone)
2. Weather and timing for their dates, with the caveats
3. Porto versus Lisbon for limited mobility, specifically: which neighborhoods are flat, where the hills and stairs are, and how people get around them
4. Two or three base options that fit food and wine over museums
5. Questions I should ask the client before I quote
6. What to verify: every fact in this brief that could be wrong or out of date, and where I should check it

Rules: plain language, no marketing words. If you are not sure about something, say so instead of guessing. Do not invent hotel names or prices.
```

What good output looks like: six headings, the short answer is actually short, section 6 is a real list (elevator locations, tram accessibility, specific rainfall averages, hotel step-free access). If section 6 is empty or vague, the model skipped the instruction; ask "Redo section 6 as a checklist."

Try the same prompt in the other tool. Paste R1 into ChatGPT and into Claude and compare the two answers. Same prompt, two different colleagues. Use the one that sounds more like you. Keep the other for a second opinion.

### R2: supplier comparison side by side

```
I am a travel advisor comparing two options for a client. Build me a side by side comparison table.

The client:
[Seven people: two grandparents in their late sixties, two parents, three kids ages 6, 9, and 14. Spring break week, mid-March. All-inclusive, direct flight from Dulles, five nights. Budget about $12,000 total. Grandparents want quiet and a good beach. Kids want a water slide. Parents want a swim-up bar and one nice dinner without the kids.]

The two options:
1. [Resort A, Riviera Maya]
2. [Resort B, Punta Cana]

Compare them in one table with these rows: kids' water slide or water park, adults-only area or quiet section, beach quality and swimming conditions in March, restaurants that need reservations, kids' club ages, connecting or family rooms, distance from the airport, and anything that would be a problem for grandparents.

After the table, add:
- Which one fits this family better, and why, in three sentences
- What you are not confident about. Be honest: you do not have this week's prices or current amenity lists, so list every row I need to confirm with the supplier before I quote
- Three questions to ask the client that would change the recommendation

Do not invent prices. If you do not know an amenity for certain, write "confirm" in the cell.
```

After the table appears, pick one row and check it on the supplier's site in a second tab. Whether it was right or wrong, the lesson is the same: it built the checklist. You still verify.

If you sell cruises rather than resorts, swap the two options for two ships or two lines and swap the rows: cabin categories for a family of seven, kids' program ages, adults-only pool, port intensity for the grandparents, dining reservations, drink packages.

### R3: the reusable destination answer

```
I am a travel advisor. Write the answer I will send to clients who ask me about [Portugal in October]. I get this question many times a season, so make it something I can reuse with small edits.

Audience: my clients, mostly couples and families from the US who have not been before.

Format:
- Open with a two sentence honest verdict
- Weather and crowds in that month, in plain terms
- What is great about that month specifically
- What to know before booking (anything that could disappoint them)
- One line inviting them to tell me their dates so I can start on a quote

Tone: warm, direct, sounds like a person who has been there, not a brochure. Under 200 words. No exclamation points. No bullet points in the final answer; write it as short paragraphs I can paste into an email.

At the end, separately, list any fact in the answer I should double check before I reuse it.
```

Edit the result until it sounds like you. Then save it. This is the one you reuse.

### Saving R3 so it is still there Monday

**ChatGPT (free):** left sidebar, Projects, New project, name it "Destination answers." Inside the project, open the chat where you built the answer, or paste the final version into a new chat there. Open the project's three dot menu, choose Project settings, paste into the Instructions box, and click Save:

```
When I give you a destination and a month, write the client answer in the same format, length, and tone as the saved Portugal in October answer in this project. Under 200 words, short paragraphs, honest verdict first, end by asking for their dates. List facts to double check separately at the end.
```

Free accounts: unlimited Projects, 5 files per project, project instructions and project memory included (OpenAI help center, checked September 15, 2026).

**Claude (free):** claude.ai/projects, New Project, "Destination answers." On the right, project knowledge: paste the final Portugal answer as text (use the + button, add as text). Set project instructions with the same paragraph as above.

Free accounts: 5 Projects maximum, project instructions and project knowledge included (Claude help center, checked September 15, 2026). Five is enough: "Destination answers," "My writing," and three spare.

### Researcher kit: what you take home

- R1 Emailed question into a brief
- R2 Supplier comparison table
- R3 Reusable destination answer
- Where they live: the "Destination answers" Project
- The habit: read the "what to verify" section every time

---

## Hire two: the Writer

Job description: writes in your voice from your saved instructions. Turns confirmations into client summaries. Drafts the posts and emails for what you are selling. You read everything before it goes out.

### First, strip the emails (3 minutes)

Open three past client emails you wrote. Copy the text into a plain document. Delete: client names, booking and confirmation numbers, dates of birth, addresses, phone numbers, anything about payment. Replace names with "the client." Keep everything else, including how you open, how you close, and the little phrases you always use. Your voice is in what is left.

Paste text. Do not upload files. Free ChatGPT allows three file uploads a day, and you do not need to spend them here.

### Three sample emails, already stripped (if you did not bring your own)

**Sample 1**

> Hi there,
>
> So glad you're excited about Italy! I've been thinking about your trip all week. Here's where I landed: four nights in Rome, then the train up to Florence for three, and I'd love to end you in the countryside for two nights so you can actually breathe before the flight home.
>
> The hotel I have in mind for Rome is one I've stayed in myself. Small, family run, and the breakfast alone is worth it.
>
> Take a look at the attached and let me know what you think. Nothing is locked in until you say go.
>
> Talk soon,
> [advisor]

**Sample 2**

> Hi,
>
> Quick update on the cruise. Your cabin is confirmed, and I got you the balcony on the starboard side like you asked, so you'll have the sunrise view coming into port.
>
> Two things to do before you sail: make sure everyone's passports are good through next August, and let me know if you want me to add the drink package. It's cheaper now than onboard.
>
> That's it for now. I'll send the full packet about three weeks out.
>
> Best,
> [advisor]

**Sample 3**

> Hi,
>
> Welcome home! I hope the flight back was painless. I saw the photo from the terrace and honestly, I'm a little jealous.
>
> When you've unpacked and caught your breath, I'd love to hear what you thought. What was the best day? Anything you'd change?
>
> And whenever you're ready to start dreaming about the next one, you know where I am.
>
> Warmly,
> [advisor]

### W1: teach the AI your voice from three of your own emails

```
I am a travel advisor. Below are three emails I wrote to clients, with the names and details removed. Study how I write and give me a style guide for my own voice, so that anything you write for me later sounds like me and not like generic AI.

Be specific and quote my actual phrases. Cover:
- How I open and how I sign off
- Sentence length and rhythm
- How formal or casual I am
- Words and phrases I reuse
- Things I never do (for example, exclamation points, bullet points, sales language)
- How I ask the client to do something
- Anything else that is distinctive

Write it as a numbered list of rules, under 200 words, that I can paste into a settings field as instructions. Start with the line "Write as me, a travel advisor. My voice:"

Email 1:
[paste]

Email 2:
[paste]

Email 3:
[paste]
```

Read the result. Correct anything that is wrong ("I do use exclamation points, but one per email at most"). The final list is yours.

### Saving your voice where it sticks

**ChatGPT (free), recommended: a Project.** Projects, New project, name it "My writing." Open the project's three dot menu, Project settings, paste the W1 result into the Instructions box, Save. Every chat inside that Project uses it. Client work stays separate from anything personal, and the Project keeps its own memory.

**ChatGPT (free), account-wide alternative:** Settings, Personalization, the single Custom instructions box ("Additional behavior, style, and tone preferences"). Paste the voice rules there. This applies to every chat, inside or outside Projects. Check the character limit on the free plan (paid plans were raised to 5,000 characters in July 2026; if the free box is shorter, the 200 word version fits).

**Claude (free): a Project.** claude.ai/projects, New Project, "My writing," Set project instructions, paste, Save instructions. Every chat inside the Project uses it. Claude also has account-level preferences under Settings, Profile, but the Project is the cleaner home for client work.

**Test it.** Inside the Project, type:

```
Write two sentences telling a client their room upgrade came through.
```

If it sounds like you, done. If not, edit the instructions, not the prompt.

### W2: confirmation details into a clean itinerary summary

Run this inside the "My writing" Project. Paste the confirmation text with guest names, booking numbers, and payment details removed.

Sample confirmation text (invented, already stripped):

> CONFIRMATION [booking]. Guests: 2 adults. Package: Lisbon and Douro, 10 nights. Oct 8: Arrive LIS 07:35 on [flight]. Private transfer to hotel. Oct 8 to 12: Hotel in Lisbon, Chiado district, superior room, breakfast included, 4 nights. Oct 12: Private driver Lisbon to Douro Valley with stop in Coimbra (approx 4.5 hrs). Oct 12 to 18: Quinta in the Douro Valley, river view room, half board (breakfast and dinner), 6 nights. Includes: one winery visit with tasting on Oct 14, one river cruise on Oct 16. Oct 18: Private transfer to OPO for 13:10 departure on [flight]. Not included: lunches, gratuities, travel insurance, anything not listed. Deposit received. Balance of $[amount] due Aug 25. Cancellation: full refund to Jul 1, 50% to Aug 24, no refund after.

```
Turn this supplier confirmation into a clean itinerary summary I can send to the client. Write it in my voice (use the instructions in this project).

Sections, in this order:
1. A two sentence welcome
2. Day by day, one line per day, with dates, in plain language (no supplier codes)
3. What's included
4. What's not included, stated clearly so there are no surprises
5. What they still need to do, with dates (balance due, insurance decision, passports)
6. A one line closing inviting questions

Rules: do not add anything that is not in the confirmation. If something is unclear in the confirmation, put it in brackets like [confirm with me] so I catch it. Keep it under 300 words. Leave a placeholder for the client's name at the top.

Confirmation:
[paste]
```

The "what's not included" section is the one that prevents the angry call in March.

### W3: Facebook post and client email for a trip you are selling now

Run inside the "My writing" Project.

```
I am selling this trip right now and need two things: a Facebook post for my business page and an email to past clients who might want in. Write both in my voice (use the instructions in this project).

The trip:
[Seven night Western Caribbean sailing, February 2027, out of Fort Lauderdale. I am hosting the group. Group rate holds until October 15. Balcony cabins from $1,650 per person, interior from $1,050, plus $40 per person onboard credit from the group. Ports: Cozumel, Roatan, Costa Maya, and a private island. Eight cabins left.]

The Facebook post:
- Under 90 words
- One hook line, one specific detail, one clear next step (message me)
- No hashtag lists, no emojis, no "unforgettable," no "dream vacation"
- Mention that I am on the ship too

The client email:
- Subject line, plus three short paragraphs
- Paragraph 1: why I am hosting this one
- Paragraph 2: the facts (dates, ports, price, the deadline)
- Paragraph 3: end with a question that is easy to answer yes to
- Leave a placeholder for the client's first name

Then give me one alternate hook line for the post in case the first one is flat.
```

A second ask is normal and fast. If the first draft is not right, say so plainly: "Make the post shorter and take out the word 'unforgettable.'"

### Writer kit: what you take home

- The stripping checklist (names, numbers, dates of birth, addresses, payment)
- W1 Teach the AI my voice
- W2 Confirmation into itinerary summary
- W3 Facebook post and client email for a trip I am selling
- Where they live: the "My writing" Project with the voice in its instructions
- The habit: edit the instructions, not the prompt, when it stops sounding like you

---

## Hire three: the Chaser

Job description: drafts the follow-up nobody enjoys writing, on time, in your voice. The free version reminds you and drafts. The built version watches, drafts, and sends after you approve.

Run C1, C2, C3 inside the "My writing" Project so the voice applies.

### C1: the friendly nudge for a quiet quote

```
Write a follow-up email to a client whose quote has gone quiet. In my voice (use the instructions in this project).

The situation:
[Nine days ago I sent a quote for a ten night Portugal trip: Lisbon four nights, Douro Valley six nights, private driver for the transfers, $8,750 for two. The client said "looks great, let me talk to my husband" and has not replied.]

Rules:
- Two short paragraphs, under 100 words
- Warm, no guilt, no "just checking in," no "I wanted to follow up"
- Mention one specific detail from the quote so it does not read as a template
- Give them an easy way to say "not now" as well as "yes"
- End with one question
- Leave a placeholder for the client's first name

Then write a second version for ten days after this one, shorter, that gently mentions the hold on the Douro hotel will not last forever, without inventing a date.
```

### C2: the payment deadline reminder

```
Write a payment reminder email to a client. In my voice (use the instructions in this project).

The situation:
[A family is booked on my hosted group cruise in February. Final payment of $2,300 is due November 1. Today is October 20. They can pay by the link I sent earlier or by calling me.]

Rules:
- Under 120 words
- Warm and matter of fact. This is a helpful heads-up, not a collections notice
- State the amount, the date, and exactly how to pay, each on its own line
- Mention one thing they have to look forward to
- Offer to help if the timing is a problem
- Leave a placeholder for the client's first name
```

### C3: the welcome-home note with the review ask

```
Write a welcome-home email to a client who just got back. In my voice (use the instructions in this project).

The situation:
[The anniversary couple just returned from Portugal, October 8 to 18. The Douro Valley hotel was the highlight; they sent me a photo from the terrace.]

Rules:
- Under 130 words
- Open by referencing the photo, not "welcome back!"
- Ask one real question about the trip
- Then ask for a review in one sentence, with the link as a placeholder [review link], and make it easy to skip
- Do not mention the next trip. This email is about this one
- Leave a placeholder for the client's first name
```

Replace [review link] with your Google Business review link, once, and keep it in the prompt.

### C4: one thing running unattended, on a free account

**What is honestly true on September 15, 2026:**

| | ChatGPT Free | Claude Free |
|---|---|---|
| Scheduled reminders and drafts | Yes. "Scheduled" page. Up to 3 active tasks. Once a day at most. A window (morning, afternoon, night), not an exact time. Rolled out to free accounts in late August 2026. | No. Claude's scheduled tasks live in Cowork, which is on the paid plans. |
| Reads your inbox or CRM | No (event triggers are paid plans) | No |
| Sends email to a client | No | No |
| Exact time, hourly, or webhook triggers | Paid plans | Paid plans (Cowork) |

**ChatGPT scheduled task (web app; the desktop app may not show "Scheduled").**

Open ChatGPT on the web. Find "Scheduled" in the sidebar. New task. Schedule: every weekday, morning. Prompt:

```
This is my weekday quote check. Ask me: "Which quotes are still waiting on a reply? Paste each one as a line: client type, trip, price, days since sent." For each line I paste back, draft a friendly two sentence follow-up in my voice: warm, no guilt, one specific detail from the quote, ending with one easy question. Keep each under 60 words. If I reply "none," say "Good, nothing to chase" and stop.
```

What it does: a nudge arrives every weekday morning with the drafter attached. What it does not do: read your email or know which quotes are open. You paste, it drafts, you send.

Free plan limits from the OpenAI help center, checked September 15, 2026: 3 active tasks for Free, once per day maximum, flexible windows only. Exact delivery times and hourly schedules need a paid plan. If "Scheduled" is missing from your account, use the web version; if still missing, use the calendar reminder below and check again later.

**The no-AI fallback, for everyone (2 minutes):**

1. Gmail: Settings (gear), See all settings, Advanced, Templates: Enable, Save. Compose a new email, paste C1's draft, three dot menu, Templates, Save draft as template, name it "Quiet quote nudge." Repeat for C2 and C3. If the Templates option has moved, look for it under Advanced first.
2. Google Calendar: new event, "Chase open quotes," weekdays 9:00 AM, repeat weekly on weekdays, notification 0 minutes before. Open it, open the template, personalize two lines, send.

Boring, free, and it works every day.

### The built version: free tier versus built for you

It drafts. You approve. Nothing reaches a client without your eyes on it.

| | Free tier | Built for you |
|---|---|---|
| Drafts the nudge in your voice | Yes | Yes |
| Reminds you on a schedule | Yes (ChatGPT tasks or a calendar) | Yes |
| Watches your inbox or CRM for quotes going quiet | No | Yes |
| Sends after you approve, from your address | No | Yes |
| Cost | $0 | One-time setup, then a small monthly tool cost. Ask us for the range. |

### Chaser kit: what you take home

- C1 Quiet quote nudge (plus the ten-days-later version)
- C2 Payment deadline reminder
- C3 Welcome home with review ask
- C4 The scheduled task prompt, or the Gmail template plus calendar reminder
- The honest table of what free does and does not do

---

## What it actually costs, side by side

Sources: Claude pricing page (claude.com/pricing, September 15, 2026) for Claude Pro. ChatGPT Plus price: verify at openai.com/chatgpt/pricing. Virtual assistant ranges: 2026 industry pricing guides (Wishup, Cherry Assistant, Virtustant, Ocean's Talent); ranges vary by source, and these are the overlapping bands.

| Option | Monthly cost | What you get | What you do not get |
|---|---|---|---|
| Free ChatGPT or Claude | $0 | Everything built this morning: Projects, saved voice, drafts, research briefs, a daily scheduled nudge (ChatGPT) | Usage limits. No inbox access. Nothing sends itself. |
| One paid plan (ChatGPT Plus about $20; Claude Pro $20, or $17 a month billed annually) | about $20 | More usage. ChatGPT: 5 scheduled tasks with exact times. Claude: Cowork with scheduled tasks. | Still does not send email for you |
| Both paid | about $40 (about $480 a year) | A second opinion on everything, and both tools' extras | Same |
| Offshore virtual assistant, part time (about 20 hours a week) | $350 to $1,300 | A person who can call suppliers, use your CRM, and think | Your time to hire, train, and manage. Time zone. Turnover. |
| US-based virtual assistant, part time | $1,200 to $3,000 ($25 to $50 an hour) | Same, in your time zone, with travel experience if you are lucky | Same management load, and the price |
| A built automation (the chaser you just saw) | One-time setup, then a small monthly tool cost | Watches, drafts, sends after your approval, never forgets | Judgment. Phone calls. Anything not in the spec. |

What none of these do, including the humans: decide for you, hold the client relationship, or be accountable at 2 AM when the flight cancels. That is the job clients pay you for. These three take the parts they do not.

---

## Which one do you hire first (a note to self)

Write down one word: researcher, writer, or chaser. Then one sentence: why that one first.

Whatever you picked is your Monday. Open its Project, run those prompts on one real client, and do nothing else new for a week.

Questions: support@empowerment-ai.com
