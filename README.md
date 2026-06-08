# Hey, I'm Matt

I'm a product builder. I build apps, tools, automations, and websites with AI — things that take multiple teams and multiple sprints at my day job. I do them in hours and days, then write about what worked and what didn't.

**What I've Been Building**

- Spun up multiple agents in Claude Code to run competitive analysis on a new product idea before writing a single line of code
- Built a PM skill taxonomy from 76 real job descriptions, with a weighted scoring model and eval matrix, tested against five synthetic cases before shipping
- Prototyped and shipped a full AI career tool for PMs from zero to live, including the prompt engineering, scoring logic, and email delivery pipeline
- Built a custom web analytics tracker from scratch and deployed it alongside GA4 as a live benchmark
- Shipped long-form blog content on PM and automation using a fully structured AI workflow, start to finish

**Current Projects**

**Koalafied** · [mattgeer.com/koalafied](https://mattgeer.com/koalafied/) · [GitHub](https://github.com/mdgeer/koalafied)

I built this because I was pasting job descriptions into Claude, trying to understand what a role was actually asking for and where to go learn it. Koalafied systematizes that: paste a resume and a job description, get a skill gap analysis, a learning path, and a 30-day action plan delivered via email.

Two things worth calling out:
- The scoring model uses a weighted PM skill taxonomy built from 76 real job descriptions. Claude handles the judgment work; the math runs separately so scores stay consistent and defensible.
- The eval matrix was built before launch, with five synthetic test cases designed to catch hallucinations, scoring drift, and inference violations.

Open source.

**Analytics** · *(repo private — link coming after rebuild)*

GA4 is too complicated for what most solo builders actually need, and it still doesn't surface the data that matters: funnel performance, traffic sources, commercial signals. I figured I knew exactly what I'd want out of a tracker, so I built it.

Worth noting:
- Went from prototype to working MVP in a few hours. Next.js, Postgres, and a tracking script you drop on any site with a single line.
- Built funnel tracking early. Still not quite where I want it, but the foundation is there.

A proper planning session and an AI layer are next. That's where it gets interesting.

## About

My current PM role is non-traditional. I sit at the intersection of product, commercial, SEO, and content, working across teams and stakeholders on all of it.

I've been building on the internet for 17 years across SEO, content writing, websites, email, and paid media, all centered on getting traffic to things and turning it into something. Most of that experience now goes in two directions: I use AI and automation to do that work faster and better, and that same background in traffic and distribution is what helps me get eyes on what I'm building now.

Follow along on [LinkedIn](https://www.linkedin.com/in/matt-geer/) to see what I'm working on day to day.
