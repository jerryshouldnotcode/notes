---
layout: post
title:  "The UI/UX is the Product"
date:   2026-05-22 16:01:22
categories: software
---

<figure style="text-align: center;">
  <img src="{{ '/assets/images/smelly_nerds.png' | relative_url }}" alt="The infamous GitHub copypasta rant." />
  <figcaption><em>Fig 1: pardon the expletives, this just lives in my head rent-free lol.</em></figcaption>
</figure>

**TL, DR**: building for users? The frontend matters a lot more than you think.

So, I recently built and submitted Librarian v0.1 (an AI-powered PDF reading tool) as an entry to the Codex Creator Challenge. Currently, the MVP has a fair amount of features, the core of which are highlights, notes, and the ability to ask the document questions via an LLM. But I almost didn’t submit it. Even though my progress on the SPEC sheet was reasonable, I was unsatisfied with my tool’s look and feel. 

The showcase happened weeks after, and I got to see the top three submissions (really fantastic work; will link their projects below). The demos were great, and importantly, I landed on a new heuristic for thinking about product engineering. The UI/UX is the product. No one talked about the backend or technical issues; it was all about showing what the tool could do and letting the features speak for themselves.

This is the part where you scoff. *“Of course, captain obvious. Why would the user want to know anything else?”* 

And that’s valid. But that comes with interesting implications, coming from someone who’s done a lot more backend-y type programming. 

Anyone who understands backend engineering will agree that it’s structural. The core application logic, scalability concerns, and interfaces with other applications reside there. If this is true, good backend engineering… just sounds like good physical engineering. Most people don’t walk into a building fearing that the ceiling will collapse. They just trust that it won’t, unless there’s a reason to doubt. That expectation is load-bearing, but the bare minimum.

Even with Codex, I spent hours trying to figure out how to render highlights. I put together two different approaches: one for page rendering, and one at the text level. I had to merge rectangles with math. But that’s besides the point: if I say that highlights are a core feature of my app, then the highlights ***should*** just work. All backend interactions have this “correctness” to them, regardless of complexity.

Thinking design-first goes against my usual programming instincts. The way I usually code is why I enjoy backend and coding for labs. Things work/produce answers, or they don’t. Outside of that, I get ***that*** nagging feeling when something that works just fine feels off. There are general rules of thumb, but front-end “correctness” is fuzzy – there is no ultimate one-size-fits-all when multiple people use your products. All this nuance gets labeled as the frontend’s responsibility, but it’s the only perspective customers get. User-facing work is all the user sees.

I built Librarian's features before I could express what I was satisfied with. No target and no vocabulary creates the gap between 'functional enough' and 'exactly my intent.' If I’m building for users, the UI/UX is the product, and there has to be a fixed target: the dev’s taste, user surveys, PM’s instructions, etc. This target needs to be iterated over, and that’s where having the language for product feel comes in. If I were to grow in product engineering as a dev, that’s exactly what I would develop.

##### Projects Mentioned

- [TraceCode — Obinna Nwachukwu](https://tracecode.app/)
- [Where Dragons Dwell — Huiying Chang](http://dragon-map.vercel.app/)
- [FixMyShift — Andrew Bybee](https://fixmyshift.vercel.app/)

