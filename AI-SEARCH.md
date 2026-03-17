# AI Search (for Humans IN government)

*A Practical Guide*

DrupalCon Chicago — Gov Summit\
Dan Moriarty & Tim Broeker\
Electric Citizen

**Speaker notes:**

- Many clients have started to ask about AI search
- We haven't "solved" it but we are learning alongside our clients
- Citizen expectations have already shifted, whether we're ready or not

---

# Electric Citizen

### *Minneapolis · Drupal · 15 Years in State & Local Government*

- State Gov — agencies and portals
- City & County — Sites & systems
- Higher Ed — State university platforms

*Current Status: Helping our clients figure out what AI means for their web presence.*

**Visual:** Clean EC branding. Put Current status into a label and a nicely styled box for the quote.

**Speaker notes:**

- What it says on the tin...

---

# For most government sites, it's still 2006

*20 years later it is better, but not a lot better.*

**Visual:** Full-bleed split — left: Google AI Overview or ChatGPT giving a direct answer. Right: a real gov site search results page, long list of blue links. Headline only.

**Speaker notes:**

- Search has gotten better on most gov sites, but fundamentally the same as it was 20 years ago. And usually just as frustrating.
- From ChatGPT/November 2022 and onward— the public's mental model of "search" changed permanently
- Google AI Overviews, Perplexity — citizens get answers
- Typcial gov search -- citizens get a list and a prayer

---

# YOUR CITIZENS are LIVING in 2026

They're asking ChatGPT or Claude instead.\
The answers they get back are pretty good.\
But they comes from **third-party vendor sites**, not just from your dot gov site.\
The answers can be factually incorrect.

**The question isn't whether this is happening. It's whether your agency controls the answers, on your site and off your site.**

**Visual:** Possible Visual of Claude search for how do I renew my contractor license in MN vs [mn.gov](http://mn.gov) results

**Speaker notes:**

- Tim's car sale/DMV andecdote
- Your citizens are already using AI to find your content, you just don't know it
- You no longer control the answer
- But you can start to take it back (both on your own site and in gen AI\*)
- Getting accurate, current information straight from your site is more critical than ever

---

# So What Now?

*Let's get on the same page.*

*What even is AI Search? A chat bot? How do we get from here to there?*

**Visual:** Subtitle slide with nice design

**Speaker notes:**

- We know gov search is tough, and stuck in the past
- And that there is a real cost to not getting better (trust+financial)
- How do we get from there to there?

---

# "AI Search" Means Everything. And Nothing.

*Depending on who's talking, it might mean...*

- A smarter list of links with a search summary
- A search bar that understands plain English
- A simple bot that answers questions
- A fully conversational chat bot that knows your website inside and out
- An agent that completes tasks for you
- All of the above
- None of the above

*No wonder everyone's confused.*

---

**Visual idea:** Single column, left-aligned, each bullet appearing like a definition that keeps getting replaced — almost like the term refuses to sit still. Clean dark background, slightly playful typography. The last two lines land as the punchline.

**Speaker notes:**

- Your internal teams and your leadership need to know the difference
- This talk exists to give you a shared vocabulary and a map
- We're going to define exactly what we mean and show you where each thing fits

---

# **THE 5 Stages of Search**

*Where you are — and where you're going*

1. Keyword Search -- *Most sites today; Search API/ Basic relevance scoring*
2. Semantic Search -- Meaning not keyword (*Vector DB/Advanced Solr)*
3. Grounded AI Search — *Grounded AI Search. Your content ONLY. Citations required. No conversation.*
4. Conversational AI -- *Grounded Conversational AI. The real win.*
5. Agentic AI -- **The future**

**Visual:** Most important graphic in the deck — invest real design time. Horizontal road or ladder, five labeled stages, "you are here" marker at Stage 1. Clean, modern, readable from the back of the room.

**Speaker notes:**

- Almost every gov site in the country is at Stage 1 right now
- Some who have really invested in Solr/search are at Stage 2
- Very few (if any) are at stage 4
- None are at stage 5
- Lots of stuff in beta/internal
  - Utah Tax Commission

---

# STAGE 1

**Keyword Search**\
*"You search. You hunt."*

- Returns a list ranked by keyword relevance
- User does all the interpretive work
- Where almost every gov site is today
- Familiar. Cheap. Often deeply frustrating.

**Visual:** Real screenshot of a generic gov site search results page — long list, mixed relevance, no direct answer.

**Speaker notes:**

- A keyword search engine looks for your words somewhere in the indexed content — any context, any order, any relevance
- We've accepted this as normal for 25 years

---

# STAGE 2

**Semantic Search**\
*"You search. It understands."*

- Understands intent, not just keywords
- Finds the right page even if the exact words don't match
- Still returns links — not answers
- Low risk. Achievable now. (Custom, SaaS platforms)

**Visual:** Before/after — same natural language query, Stage 1 results vs Stage 2 results. Difference immediately visible.

**Speaker notes:**

- Not really "AI Search"
- Vector embeddings match meaning, not vocabulary
- The gap between how citizens ask questions and how government titles its pages is enormous — semantic search closes most of it
- Achievable right now, low risk, no generative AI required

---

# STAGE 3

**Grounded AI Search**\
*"You ask. It answers. You can verify."*

- Natural language question — direct answer
- Generated only from your approved, indexed content
- Every answer cites its source
- Won't invent what it can't find
- **The responsible target for government right now**

**Visual:** Critical design asset. Mockup of a grounded gov search interface — citizen question, direct answer, visible "Source: \[Page Title · URL\]" citation. Achievable, not futuristic.

**Speaker notes:**

- Nobody in US government has fully deployed this at scale for citizen-facing search yet
- The technology exists — what's missing is the content foundation and governance to support it
- Indiana and Utah are the closest — and both are deliberately keeping it internal until it's ready

---

# STAGE 4

**Conversational AI**\
*"You talk. It assists."*

- Multi-turn — remembers context within a session
- Handles follow-ups and clarifications naturally
- Grounding still required — more critical, not less
- **Aspirational for most gov orgs right now**

**Visual:** Multi-turn conversation mockup — 3-4 exchanges, citizen refining a question. Near-future but not science fiction.

**Speaker notes:**

- The citizen doesn't have to get their question right the first time
- "Actually I meant the commercial license, not residential" — the system holds context across that exchange
- Grounding is more critical here, not less — the conversation can go unexpected directions

---

# STAGE 5

**Agentic AI**\
*"You describe a goal. It acts."*

- Doesn't just answer — takes steps on your behalf
- *"I need to renew my contractor license"* — checks eligibility, pre-fills form, submits application
- Search disappears as a concept — citizen states a need, system resolves it
- **Nobody in government is here yet**

**Visual:** Goal to steps to resolution flow. Slightly more futuristic treatment — this is forward-looking.

**Speaker notes:**

- The citizen says "I need to renew my contractor license" — system checks eligibility, pre-fills the application, submits it, sends confirmation
- NASCIO published research on this trajectory just weeks ago — it's not speculative
- Requires everything above it to be solid — you can't have agents acting on citizens' behalf on a broken content foundation

---

# Getting From Here to There

*How to start the journey to Stage 3 and Stage 4*

**Visual:** Subtitle slide with nice design

**Speaker notes:**

- We know gov search is tough, and stuck in the past
- And that there is a real cost to not getting better (trust+financial)
- How do you get from there to there?

---

# UNDERSTAND THE BARRIERS

**The Limitations Are Real**

- Content sprawl — 40 agencies, independent content. AI inherits all of it.
- Policy lags and legal risks — Your state is probably establishing AI governance right now
- Procurement lags — 6 month contract negotiations, 3-month AI release cycles
- Staff capacity — 1-2 people running an entire state portal
- Speed of change -- AI is moving faster than us mortals can comprehend

**Visual:** Wall with labeled sections — each one a barrier. Clean, readable, slightly wry.

**Speaker notes:**

- States are standing up AI governance frameworks now — know what's coming in your state before your pilot gets ahead of it

---

# You Can't AI Your Way Out of Bad Content

*The Hard Truth*

- Outdated content — Last reviewed 2019. AI cites every stale page confidently.
- Orphaned pages — Five CMS migrations deep. Nobody owns them.
- Org-chart IA — Built around departments, not citizen tasks.
- Under-resourced — 1-2 people running an entire state portal.

> Bolt an LLM onto a broken content foundation and you get a **confident, well-spoken wrong answer.**\
> In government, that's a liability.

**Visual:** Gate/checkpoint on the roadmap — clear visual barrier between Stage 2 and Stage 3. Amber warning treatment.

**Speaker notes:**

- AI doesn't fix bad content — it retrieves it, generates from it, and cites it confidently
- Stale permit fee from 2019 — AI tells citizens the wrong amount with a source citation
- Every state portal we've worked with has some version of all four of these problems

---

# **Fix YOUR Foundation**

*Preparing for long-term success in an AI-driven world*

- Kill the dead weight — Archive or remove. Every irrelevant page is retrieval noise.
- Content audit — Map what's current, stale, redundant. Can't fix what you haven't mapped. Figure out your PDFs.
- Fix your structure — Structured content types, clean taxonomies, citizen-centered IA.
- Ask the hard questions — Are you patching legacy debt, or does this site need a clean rebuild?
- Uploading 100s of PDFs is not the answer

> AI search quality is directly proportional to content quality.

**Visual:** Checklist aesthetic. Actionable, not overwhelming.

**Speaker notes:**

- In our experience more sites need a full rebuild than their owners want to admit — patching legacy architecture for AI readiness usually costs more and produces worse results than starting clean
- Content audit is the one thing you can start this week with no approval needed

---

# Choose a Path

*A map, not a prescription*

**Path 1 — Purpose-Built SaaS**\
e.g. *Cludo, Coveo*\
Stage 3 and 4 today. Gov-specific. No dev team required.

**Path 2 — You May Already Have It**\
*Microsoft Azure · Google Vertex · AWS*\
Inside your enterprise agreement. FedRAMP authorized. Drupal integration paths exist.

**Path 3 — Build Drupal-Native**\
*Drupal AI + Search API + Vector DB*\
Own your architecture. Own your data. No vendor lock-in.

**Visual:** Three clean columns, simple icons, one-line descriptor each. This is orientation, not detail.

**Speaker notes:**

- Three realistic paths — not recommending one over the others
- The middle column is the most underused and most surprising for this audience
- Many agencies are paying for Microsoft or AWS enterprise agreements with AI capabilities they've never activated
- All three have Drupal integration paths — this isn't SaaS vs. custom, it's a spectrum
- Next slide goes deeper on tradeoffs

---

# PATH 1 — PURPOSE-BUILT SAAS

*e.g. Cludo, Coveo and other up-and-comers*

Pros:

- Stage 3 and 4 capable now
- Gov-specific features, analytics, admin UI out of the box
- No internal dev capacity needed to operate
- Supported and maintained

Cons:

- Expensive — enterprise subscription pricing
- Crawler-based — not tightly coupled to your Drupal content architecture
- Data sovereignty — where do citizen queries go?
- Vendor lock-in — switching is painful

**Visual:** Simple pros/cons two-column layout. Clean, scannable.

**Speaker notes:**

- These are the vendors doing it most completely for gov right now -- there are VERY FEW
- Crawler-based means they index your public site — they're not connected to Drupal's content layer, structured fields, or taxonomy
- Data sovereignty is the question your legal and IT teams will ask
- If you need Stage 3/4 now and don't have dev capacity — this is the only realistic path today

---

# PATH 2 — YOU MAY ALREADY HAVE IT?

*Microsoft Azure · Google Vertex AI · AWS*\
Pros:

- Likely inside your existing enterprise agreement
- FedRAMP authorized — procurement already done
- Drupal integration paths exist for all three
- Stage 3 capable with proper configuration

Cons:

- Not turnkey — requires real configuration and dev work
- Gov IT may own the contract — web team still needs to connect it to Drupal
- Still requires the same content foundation work

**Visual:** Three provider logos, simple pros/cons. The NYC callout gets its own visual treatment — a small warning flag or amber highlight.

**Speaker notes:**

- Ask your IT department before signing a new vendor contract
- Azure AI Search has a Search API module for Drupal — direct integration path exists
- Google Vertex AI Search has a Drupal module — also a direct path
- Some offer FedRAMP authorization

---

# PATH 3 — BUILD DRUPAL-NATIVE

*Drupal AI + Search API + Vector DB + LLM*

Pros:

- You own the architecture and the data
- Tightly coupled to your structured Drupal content
- No ongoing vendor fees beyond LLM and vector DB API costs
- Data stays in your infrastructure
- No vendor lock-in — swap LLM providers without rebuilding
- Lowest long-term cost, highest control

Cons:

- Requires a capable Drupal dev team and AI expertise
- Not a module-install-and-done situation
- Middleware layer required — chunking, embedding, pipeline
- Ecosystem still maturing
- You own the maintenance burden

**Visual:** Simple Drupal stack diagram — Search API → Vector DB → LLM → Answer. Clean, shows the architecture without overwhelming.

**Speaker notes:**

- Drupal's structured content, taxonomies, and APIs are a genuine head start — the retrieval foundation grounded AI needs is already partially built
- The 48 provider integrations means you can use Azure, Google, Anthropic, OpenAI or others as your LLM — and swap without rebuilding
- This is the path with the most control and lowest long-term cost
- It also requires the most upfront investment and the right team

---

# The Content Foundation Requirement

*Whichever path you choose:*

Your content has to be current.\
Your content has to be structured.\
Your content has to be governed.

*AI doesn't fix bad content.*\
*It retrieves it. Generates from it. Cites it. Confidently.*

\
**Visual:** Full-width statement slide. Dark background. Clean typography. No bullets — just the three lines and the closing warning.

**Speaker notes:**

- This is the point worth repeating
- Every vendor will tell you their platform handles content quality — none of them do
- The content work is yours regardless of which path you choose
- And that work is valuable right now, today, before you spend a dollar on AI tooling

---

# Don't Panic

**Where Government Actually Is Right Now**

- **Only 24%** of state CIOs have data governance frameworks for GenAI
- **82%** of state gov employees using GenAI — **almost entirely internal**
- **\~0** citizen-facing grounded AI implementations at scale in US gov
- Most states: "Developing" and prototyping across all AI readiness categories

**Visual:** Code for America AI Landscape Assessment maturity visualization. Source credited. Most states clustered low.

**Speaker notes:**

- 82% sounds impressive — it means drafting emails and summarizing documents
- Utah, Indiana — moving carefully and deliberately, keeping AI internal until it's ready
- Utah CIO said explicitly: don't want citizens relying on a chatbot that hasn't been fully vetted
- The ones who look "behind" are often just being responsible

---

# **Let's Talk**

*We've been working in state & local government for 15 years.*\
*Right now there is no more interesting moment to be doing it.*

**Dan Moriarty** — Co-founder\
**Tim Broeker** — Co-founder\
electriccitizen.com

\[QR CODE — electriccitizen.com or dedicated landing page TBD\]

**Conversations we're having:**

- Getting foundations right — content audits, IA, governance
- Prototyping what comes next — grounded AI search pilots

**Visual:** Clean EC branding. QR code bottom right — large enough to scan from mid-room.