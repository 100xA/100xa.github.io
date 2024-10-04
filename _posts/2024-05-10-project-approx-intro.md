---
layout: post
title: Introduction Project "Approx" 
description: "Building an AI-Powered PDF to Obsidian Assistant"
comments: false
tags: [python, ml, obsidian]
---

# Building an AI-Powered PDF to Obsidian Assistant

## The "Aha" Moment

Last week, I found myself drowning in PDFs. Again. :(

Between research papers, documentation, and various digital books, I had accumulated a small library of PDFs that needed to be integrated into my Obsidian vault. As I manually copied, pasted, and formatted the twentieth document of the day, I had that classic developer thought: "There has to be a better way."

There is none, so I need to build one. 

## What is Obsidian? 

[Obsidian](https://obsidian.md/) is a powerful knowledge management tool that allows users to create a personal knowledge base using markdown files. It enables users to link notes together, creating a network of interconnected ideas, which enhances the way information is organized and retrieved. This project aims to leverage Obsidian's capabilities by automating the integration of PDF content into the vault, ensuring that the structure and connections within the knowledge base are preserved and enriched.

## The Problem

If you're like me, your Obsidian vault is more than just a collection of notes—it's a carefully curated digital garden. Each note has its place, its connections, its tags, and its role in the greater knowledge graph. Simply dumping PDF content into it would be like throwing random plants into a well-maintained garden. The structure matters.

**Here are my requirements:**

1. Preserve my existing vault structure
2. Maintain the integrity of my knowledge graph
3. Generate meaningful connections to existing notes
4. Keep my tagging system consistent
5. Save me time (obviously!)
6. Seemlessly integrate into Obsidian (no copy pasting action)


## The Solution: Meet the Obsidian PDF Agent

A rough overview (for now)

![Mermaid Diagramm for Approx](/assets/images/blog/mermaid-diagram.png)
### How It Works

Imagine having a really smart research assistant who:
- Reads and understands your PDFs
- Knows how you organize your notes
- Creates perfectly formatted markdown files
- Places them in the right folders
- Suggests relevant connections to your existing notes
- Maintains your tagging system

That's essentially what this agent will do, but automatically. By that we have built 

## Real-World Example

Here's what happened when I fed it a research paper about cognitive biases:

Before:
```
research_paper_123.pdf
└── 50 pages of dense academic text / uni scripts
```

After:
```markdown
---
title: "Understanding Cognitive Biases in Decision Making"
source: "Journal of Behavioral Economics, 2024"
tags: [psychology, decision-making, cognitive-bias]
related: [[Decision Making Framework]], [[Behavioral Economics]]
---

## Key Findings
- Discovery of three new cognitive biases
- Impact on financial decision making
- Potential mitigation strategies

[... rest of the intelligently formatted content ...]

![Specifically Integrated Link to another node]

```

## Final Notes

I will be back soon with updates. I am mostly new to this field, so mistakes (learning opportunities) will happen. I will be posting weekly on my progress. Thank you for reading <3.


# Links 

- [Approx Repo](https://github.com/100xA/approx)