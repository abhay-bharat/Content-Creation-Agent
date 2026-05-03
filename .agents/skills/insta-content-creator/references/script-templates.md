# Script Templates

Reusable templates for different content types. Adapt these to your idea, don't memorize them verbatim.

---

## REEL SCRIPT TEMPLATE (20-35 seconds)

### Structure
1. **Hook (3-5 sec)**: Stop scrolling
2. **Setup (5 sec)**: What are we talking about?
3. **Core (8-10 sec)**: The meat / insight
4. **Why it matters (5 sec)**: So what?
5. **CTA (2-3 sec)**: Action

### Word Count Guide
- **Hook**: 10-15 words
- **Setup**: 15-20 words
- **Core**: 40-60 words
- **Why it matters**: 15-25 words
- **CTA**: 10-15 words
- **Total**: ~120-150 words (for 20-30 sec reel at natural pace)

---

## Template 1: Concept Explanation Reel

```
[HOOK - 4 sec]
"Your RAG system is probably broken."

[SETUP - 5 sec]
"Most engineers think the model is the problem.
It's not."

[CORE - 10 sec]
"The issue: vector search alone fails.
You need three layers:

1. Better chunking (semantic boundaries, not token limits)
2. Intelligent routing (which docs to search)
3. Quality evaluation (measuring what actually works)"

[WHY IT MATTERS - 5 sec]
"80% of RAG failures are data quality, not model.
Fix this, your accuracy jumps 40-60%."

[CTA - 2 sec]
"Save this. Test your pipeline this week.
Tell me what you find."
```

---

## Template 2: News/Tool Announcement Reel

```
[HOOK - 3 sec]
"OpenAI just shipped something important."

[SETUP - 4 sec]
"New function calling API.
Here's why engineers should care."

[CORE - 12 sec]
"Old way: Hacky prompt engineering to get JSON output.
New way: Native JSON mode with defined schema.

Real benefit: 10x fewer parsing errors, faster inference, cheaper tokens."

[WHY IT MATTERS - 4 sec]
"This is how production systems get built.
Tooling matters as much as the model."

[CTA - 2 sec]
"What are you building with this?
Comment below."
```

---

## Template 3: Mental Model / Simplified Concept

```
[HOOK - 4 sec]
"How transformers actually work in 30 seconds."

[SETUP - 3 sec]
"Forget the math. Think in layers."

[CORE - 12 sec]
"Layer 1: Position (where am I in the text?)
Layer 2: Meaning (what words matter to this word?)
Layer 3: Combination (mix all the relevant meanings)

Repeat 12+ times = deep understanding of context."

[WHY IT MATTERS - 4 sec]
"Understanding this explains 80% of LLM behavior.
Why they hallucinate, why prompting works, why scaling matters."

[CTA - 2 sec]
"Save this, re-read it next time a model surprises you."
```

---

## Template 4: Misconception Correction

```
[HOOK - 3 sec]
"You're probably wrong about embeddings."

[SETUP - 4 sec]
"Common myth: Embeddings store meaning."

[CORE - 10 sec]
"Reality: Embeddings store statistical patterns.

Two sentences can be 'close' in embedding space
but mean opposite things.
Or far apart but deeply connected.

Embeddings are useful. But they're not semantics."

[WHY IT MATTERS - 5 sec]
"This changes how you debug RAG systems.
Stop trusting similarity scores blindly."

[CTA - 2 sec]
"How is this breaking your systems? Tell me in comments."
```

---

## Template 5: How-To / Practical Tip

```
[HOOK - 4 sec]
"Speed up your LLM calls by 50%."

[SETUP - 3 sec]
"One pattern, three implementations."

[CORE - 12 sec]
"Batch your API calls.

Instead of:
- Call API, wait, get response ✗ (slow)

Do this:
- Queue 50 requests, send batch, process responses ✓ (fast)

Tools: Python async, Anthropic batch API, OpenAI batch processing."

[WHY IT MATTERS - 4 sec]
"Production systems need this.
Gets you 3-5x throughput on same hardware."

[CTA - 2 sec]
"Which tool are you using? Let me know what speed you hit."
```

---

## CAROUSEL TEMPLATE (8-10 slides)

### Structure
- **Slide 1**: Hook + preview
- **Slides 2-5**: Teaching (one idea per slide)
- **Slides 6-8**: Framework, comparison, or proof
- **Slide 9**: Deeper insight or resource
- **Slide 10**: CTA

### Slide 1 (Hook)
```
[Large headline - 48-60px]
"The Framework Every AI Engineer Needs"

[Subheading - 32px]
"To go from training to production

[Icon or teaser image]

[Small text]
"Swipe for 10 takeaways →"
```

### Slide 2-4 (Teaching Points - One Per Slide)
```
[Headline - 40px]
"Step 1: Define Your Metric"

[Content - 28px]
"What does success look like?
- Accuracy? Latency? Cost?
- Speed? User satisfaction?

Pick one primary metric.
Everything else is secondary."

[Visual: Simple diagram or icon]
```

### Slide 5+ (Framework/Comparison)
```
[Headline]
"Production Tradeoff Matrix"

[Visual: Clean 2x2 grid or table]
Fast/Cheap ← → Accurate/Slow

[Brief labels]
Pick your corner. Optimize there.
```

### Last Slide (CTA)
```
[Headline - 40px]
"The Framework in One Sentence"

"Design for your specific constraints,
not for an ideal world."

[CTA - 32px]
"💾 SAVE THIS
👉 SHARE YOUR STACK
🔗 DM me your production setup"

[Follow button]
```

---

## AI SIGNALS TEMPLATE (5 slides - LOCKED)

### Slide 1: Hook
```
[Large headline - 48px]
"Anthropic just launched something big"

[Subheading - 28px]
"And it changes how you build AI systems"
```

### Slides 2-3: What Happened
```
[Headline]
"The Release"

[Content]
- What: [Thing released]
- When: [Date]
- Cost: [Pricing if relevant]
- Availability: [Open source / API / Private]

[Real example or screenshot]
```

### Slide 4: Why It Matters
```
[Headline]
"Why This Matters"

[Content]
- For engineers: [Specific impact]
- For AI teams: [Use case implications]
- For the industry: [Broader shift]

"This is a shift from X to Y"
```

### Slide 5a: Your Analysis (ThinkingLab Take)
```
[Headline]
"Our Take"

[Your engineer perspective]
"This fixes the problem of [X]
But creates new challenge in [Y]

Best used for: [Specific use case]
Not ready for: [Caution area]"
```

### Slide 5b: Source
```
[Headline]
"Read More"

[Link]
Original: [URL]

[Credit]
"Source: [Official blog / announcement]"
```

---

## BUILD LOG TEMPLATE (Visual + Caption)

### Image: Before/After or Process Photo
- Screenshot of code/model output
- Or: Photo of setup/experiment
- High contrast, clean framing

### Caption
```
"Build Log: [Experiment name]

What I tried: [Brief description]

Results: [Numbers/metrics/outcome]

Surprising? [Yes/No] - [Insight]

Next: [What I'm testing next]

[Tag others working on this]"
```

---

## MENTAL MODEL MONDAY TEMPLATE

### Reel or Carousel Option

**If Reel:**
Follow Template 3: Mental Model / Simplified Concept

**If Carousel:**
```
Slide 1: Headline + teaser
Slides 2-5: Break down concept in 4 pieces
Slide 6: Visual (diagram / analogy)
Slide 7: Real-world application
Slide 8: Common misconception
Slide 9: Further reading
Slide 10: CTA (Save + Share)
```

---

## Copy Tips for All Formats

### Hook Writing
- Start with verb (action): "Fix", "Learn", "Discover", "Understand"
- Use number specificity: "3 misconceptions" not "some misconceptions"
- Create gap: Problem + solution hint
- Be conversational: "Your X is probably broken" not "Is X optimized?"

### Body Copy
- Short sentences (5-12 words average)
- Active voice (verb-subject-object)
- Concrete examples before abstract concepts
- Bold the key number/insight
- Use colons to reveal information

### CTA Copy
- **Save**: "Save this, test your pipeline"
- **Share**: "Share this with your team"
- **Follow**: "Follow for more AI engineering insights"
- **Comment**: "What's your experience? Comment below"
- **DM**: "DM me your setup"

### Avoid
- Salesy language ("You won't believe!")
- Exclamation marks (max 1 per post)
- ALL CAPS (ok for emphasis, not whole sentences)
- Emojis overuse (pick 1-2 per post max)
- Technical jargon without explanation

---

## Template Testing & Iteration

### Track What Works
For each template you use, note:
- Hook type (Surprise/Clarify/Opportunity)
- Format (Reel/Carousel/etc)
- Topic area
- Saves rate achieved
- Engagement rate

After 5-10 posts with a template, identify:
- Highest performing: Use again
- Lowest performing: Modify or retire
- Consistent: Your template is proven, optimize variations

### Adapt, Don't Memorize
These templates are starting points, not formulas.
Your voice is the content.
Adapt freely based on your idea.
