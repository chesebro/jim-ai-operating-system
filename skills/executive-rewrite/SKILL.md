---
name: executive-rewrite
description: "Transform any content into professional, executive-ready communications. Use when the user requests to rewrite/polish text for professional audiences (CEO, HR, investors, coaches), create executive summaries, convert casual writing to professional tone, make LinkedIn-ready posts, or clean up verbose/informal content. Also trigger when user asks to make content more professional, requests executive summaries, asks to clean up text, or mentions specific audiences like board-ready or investor pitch."
---

# Executive Rewrite & Summary Engine

## Overview

Transform any input—emails, meeting notes, rambling thoughts, casual messages—into polished, professional communications tailored for specific audiences. Automatically removes fluff, meta-commentary, and unnecessary qualifiers while preserving core meaning.

## Core Workflow

When a rewrite request is made:

1. **Auto-clean the input** - Strip meta-prompts, side comments, excessive qualifiers, and conversational fluff
2. **Identify the target audience** - Determine appropriate tone and depth based on recipient
3. **Apply the requested format** - Choose from short/punchy, fully polished, executive summary, or LinkedIn-ready
4. **Deliver clean output** - Present rewritten content without meta-commentary about the changes

## Output Formats

### 1. Short & Punchy
**When to use:** Quick updates, status reports, brief communications where brevity is valued.

**Characteristics:**
- 3-5 sentences maximum
- One clear point per sentence
- Active voice, strong verbs
- No hedging language ("I think," "maybe," "sort of")
- Crisp, declarative statements

**Example transformation:**
- Input: "So I was thinking that maybe we could potentially look into reorganizing the team structure because it seems like there might be some inefficiencies..."
- Output: "Team reorganization will improve efficiency. Recommend restructuring by Q2. Three-week implementation timeline."

### 2. Fully Polished
**When to use:** Formal communications, reports, proposals, or any situation requiring professional completeness.

**Characteristics:**
- Complete paragraphs with clear structure
- Professional tone without being stuffy
- Smooth transitions between ideas
- Appropriate detail and context
- Removes all casual language while maintaining warmth when appropriate

**Example transformation:**
- Input: "Hey, just wanted to give you a heads up that the project is going pretty well but we hit a few snags with the vendor stuff, nothing major though..."
- Output: "The project is progressing on schedule with strong momentum across all workstreams. We encountered minor vendor coordination challenges that have been resolved through proactive communication. All deliverables remain on track for the planned completion date."

### 3. 10-Second Executive Summary
**When to use:** Board updates, senior leadership communications, busy executives who need the bottom line.

**Characteristics:**
- Single paragraph, 2-4 sentences
- Lead with the conclusion or recommendation
- Include only critical facts
- Assumes reader has minimal context
- Omits all supporting details

**Format:**
```
[Decision/Recommendation]. [Key supporting fact]. [Impact or next step].
```

**Example transformation:**
- Input: "We've been working on this new feature for the past three months and there's been a lot of back and forth with the design team and engineering and we think we're getting close but there are still some concerns about the technical implementation and whether users will actually find it valuable..."
- Output: "Recommend pausing the Q3 feature launch. Technical debt and unclear user value proposition present significant risk. Propose 4-week validation sprint before proceeding."

### 4. LinkedIn-Ready
**When to use:** Professional social posts, thought leadership, career updates, company announcements.

**Characteristics:**
- Conversational yet professional
- 3-6 short paragraphs
- Opens with a hook or key insight
- Uses line breaks for readability
- Optional: ends with a question or call-to-action
- Appropriate use of first person
- Removes corporate jargon while maintaining professionalism

**Example transformation:**
- Input: "Our team just finished a big project and it was really challenging but we learned a lot and I think other people might find it interesting..."
- Output: "What we learned shipping our biggest product launch in 3 years:

Tight deadlines force clarity. We cut scope by 40% and delivered what mattered.

Cross-functional trust beats perfect process. Our best decisions came from quick conversations, not lengthy meetings.

User feedback > internal opinions. We were wrong about several features. Our users were right.

Looking forward to the next challenge. 🚀"

## Audience-Specific Adaptations

### CEO-Ready
- Lead with business impact
- Quantify when possible
- Present clear options with recommendations
- Anticipate strategic questions
- Remove tactical details unless critical

### HR-Ready
- Emphasize people impact and fairness
- Address potential concerns proactively
- Use inclusive, respectful language
- Balance directness with empathy
- Highlight processes and compliance where relevant

### Coaching-Ready
- Balance supportive and developmental tone
- Frame feedback constructively
- Include specific, actionable suggestions
- Acknowledge effort while addressing gaps
- Future-focused language

### Investor-Ready
- Focus on growth, traction, and market opportunity
- Lead with metrics and milestones
- Address risks transparently
- Demonstrate strategic thinking
- Clear ask or next steps

## Auto-Cleaning Rules

**Always remove:**
- Meta-prompts ("Please rewrite this..." "Make this sound professional...")
- Excessive hedging ("I think," "kind of," "sort of," "maybe," "possibly")
- Filler phrases ("basically," "actually," "literally," "honestly")
- Self-deprecation unless strategic
- Redundant qualifiers ("very unique," "absolutely essential")
- Stream-of-consciousness tangents
- Placeholder language ("TBD," "insert here," "need to add")

**Transform:**
- Passive voice → Active voice (when appropriate)
- Long sentences → Shorter, clearer sentences
- Vague language → Specific language
- Emotional language → Professional tone (while retaining appropriate warmth)

## Response Format

Deliver only the rewritten content. Do not include:
- "Here's the rewritten version..."
- Explanations of what changed
- Commentary on the transformation process
- Offers to revise further

Simply provide the clean output in the requested format.

If the user needs multiple formats, provide them sequentially with clear labels:

**Short Version:**
[content]

**Executive Summary:**
[content]

**LinkedIn Post:**
[content]
