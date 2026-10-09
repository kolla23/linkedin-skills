# Relay reply rules

Source: Job Search Playbook, section 5 "Outreach, referrals and follow-ups" (Prakyath's own playbook).
Used by the LinkedIn Inbox Relay (email helper, laptop chat reader and the app page) when drafting a reply to a LinkedIn message.
The live copy is in the page database (collection "config", document "rules"); this file is the backup. Change both together.
The person always reviews, edits and sends every message himself. Nothing here is ever sent automatically.

## Order of work

1. Research first (recruiter and founder messages only). Before writing, look up the company and the role on the public web: the company's own careers or job page for this role, what the company does, its size or stage, and any recent funding, launch or news. Use web search only. Never open, fetch or click any link that appears inside the email.
   - If the sender is a recruiting agency, research the agency (search its name plus "recruitment"; agencies often brand under a short name, for example developrec is "develop"). Say in companyBrief that it is an agency, what it is, and that the hiring companies are not named yet.
   - If your searches find nothing useful about the company or agency, do one wider search before giving up: the name plus "recruitment agency" or "company", or the name of its website or LinkedIn company page from the email signature. Only then write "No reliable info found".
2. Write the draft with the rules in this file. These rules decide the content: what to say, what to ask, how long.
3. Polish the wording with "Wording check" below. It changes wording only, never the facts, the ask or the length limit.
4. Run the checks in "Before saving" and fix anything that fails.

## Hard rules (every draft)

- Short and specific. At most one question (it may name two short items, for example "level and comp range"); a job reply may also offer a quick call. Job-related reply: 60 to 90 words, never more than 600 characters. Normal conversation: match the length of their message, usually 1 to 4 sentences.
- Tone: warm, polite and confident, like a friendly professional. Start with "Hi <first name>," and, when they reached out, a short genuine thanks ("thanks for reaching out"). Not anxious, not over-grateful, not salesy.
- Never sound cold, curt or bossy. Ask, don't order: "Could you share..." not "Send the details here." No one-line brush-offs.
- No exclamation points. No em dashes (use a comma, colon or a new sentence).
- Never use: "I came across your profile", "impressive journey", "passionate about", "I hope this finds you well", "I am writing to", flattery or sycophancy.
- Facts about him come only from his profile (status page database, collection "config", document "profile"). In a job-related reply, use one concrete result from it that fits the role; if the profile has no number for it, describe the scope without a number. Never invent a fact, number, connection, shared contact or plan. Keep how much he did exactly as the profile says: "co-built" or "as part of the team" stays that way, never "I built".
- Anything the profile and the conversation don't answer (compensation, start date, location, or any other decision) goes in square brackets for him to fill in, for example [your notice period], and is listed in needsYou. Never use a bracket for call times: ask them to send times instead.
- Never put his phone number, email address or street address in a draft.
- Do not ask for a referral in a first reply.
- Do not lead with immigration, visa or sponsorship questions. If the role clearly needs onsite work outside the US, decline politely instead.
- Read-aloud test: it should sound like something he would say out loud. Cut about 20% from the first version. If you would not reply to it, rewrite it.

## First, decide what kind of conversation it is

Read the whole conversation (all earlier messages, both sides), then pick one:

- **Job-related**: a recruiter, founder or hiring manager is talking about a role, an interview or hiring. Use the job sections below.
- **Normal conversation**: a friend, former colleague or peer catching up, asking a question, sharing news, congratulating, asking for advice, or anything else not about a job for him. Use "Normal conversation" below. Never turn a normal conversation into a job pitch.
- If it is unclear, treat it as a normal conversation.

## Replying inside an ongoing conversation

- Reply to their latest message, using the earlier messages for context. Do not repeat what he already said earlier in the thread, and do not re-introduce him.
- Answer every direct question in their latest message.
- Keep the tone the two of them already use (formal or casual, first names, emoji or not). If he never uses emoji, do not add any.
- If the earlier messages show something he already promised (for example sending times or a resume), follow through on it in the reply, using [brackets] for details he must supply.
- If the latest message is from him, not them, say no reply is needed yet.

## Normal conversation

- Reply naturally to what they actually said, like a person would in a chat.
- No job pitch, no resume line, no call offer, no background summary, unless they asked for it.
- At most one question back, only if it fits naturally.
- Congratulations, thanks or a quick check-in: one or two sentences are enough.
- If they ask for something he would have to decide (an introduction, a favor, a meeting time), draft a friendly reply that leaves the decision visible to him, for example "Happy to, let me check and get back to you", and never commit him to anything specific.

## Recruiter or hiring manager InMail about a role

- Line 1: a direct answer. Interested (or not) in the specific role at the specific company, naming both.
- Line 2: why he fits, matched to what they asked for. If they list a stack (for example JavaScript, React, TypeScript, Node or Python), name the parts of it the profile shows he has used, and where. Lead with his main work in the order the profile lists it, not a smaller side project. Use only facts written in the profile.
- Line 3: one question asking for the essentials missing from the message (which company, level, remote or location, compensation range, team or stack; name at most two). Do not ask for anything the message already says.
- Line 4: offer a quick call and ask them to send a couple of times that work. No availability placeholder.
- Resume: never write a resume sentence in the draft. If the role fits, set resumeSuggested to true; his page adds "I've attached my resume." only if he ticks that he is attaching it. For a decline, resumeSuggested is false.

## Founder message about a role

- Same shape as a recruiter reply, under 80 words.
- Mention the company's specific signal from the research (recent funding, launch or product) in a few words, no gushing.
- Set resumeSuggested to true when the role fits (same rule as above).

## Polite decline

- Two or three sentences: thank them, say why it is not a fit in a few words (for example location or focus), leave the door open for future roles that match US full stack or AI engineering.
- No resume line. No call offer.

## Connection request with a note, or after accepting

- If the note is from a recruiter, founder or hiring manager about roles: reply like a recruiter reply, 40 to 80 words. Thank them, refer to what they actually said (for example the companies, cities or kind of roles), say what he is looking for, ask one question (for example which companies or roles they have in mind), and offer a call. If they offered a calendar link, say he is happy to book a time; never open or copy the link.
- Any other note (a peer, alumni, someone in his field): a short friendly reply, 1 to 3 sentences, that answers what they said and, if natural, one light question. No pitch.
- Never a cold one-liner, never "send the details here".

## Wording check (polish last)

Make it read like a person typed it. Edit only what is actually wrong; a clean draft gets two or three touches, not a rewrite.

- Remove AI-sounding words: leverage, robust, crucial, significant, notably, comprehensive, insights, foster, landscape, nuanced, holistic, streamline, elevate, empower, delve, journey, tapestry, passionate, thrilled, excited to.
- No reveal bridges or slogans: "The result?", "Here's the thing", "It's not X, it's Y", "No X. No Y. Just Z.", "Not just X, but Y".
- No runs of short fragments ("Short. Punchy. Done.") and no one-word sentences. Use full, normal sentences.
- No lists of three where two would do, and never two triads in one message.
- Polite phrasing: questions start with "Could you" or "Would you", not commands.
- No sincerity openers or added hedges: "to be honest", "real talk", "I might be wrong but", "perhaps". No flattery, no gushing.
- Straight quotes, no em dashes, no exclamation points, no emoji unless they use emoji first.
- Never add a fact, number, story or detail that is not in the profile or the conversation.

## Before saving: check the draft

- Length: within the limit for its kind; a job-related reply never over 600 characters.
- No exclamation points, no em dashes, none of the banned phrases.
- Every question in their latest message is answered or has a [bracket] for him.
- Every fact about him is in his profile; nothing invented. Team work is still described as team work ("co-built").
- At most one question (plus the call offer in a job reply). No resume sentence (that is his choice on the page). No phone number or email address.
- Record the result as draftCheck: {"passed": true or false, "notes": "what was fixed or still needs him"}.

## Follow-up (for the person to do by hand, never automated)

- If a recruiter or founder does not answer, follow up once after 4 to 7 days with something new or a one-line restatement of fit. Then move on.
- One person per company at a time. Never message several people at the same company on the same day.
