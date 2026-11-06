# The AI Agent Operator's Toolkit
## 50+ Battle-Tested Prompts for Building, Running, and Monetizing AI Agents
### Version 1.0 — November 2026

**Price suggestion: $29–$49 on Gumroad**

---

## Table of Contents
1. Agent Design & Architecture
2. Prompt Engineering for Agents
3. Tool Use & Function Calling
4. Memory & Context Management
5. Multi-Agent Orchestration
6. Monetization & Business Automation
7. Debugging & Optimization
8. Niche Agent Templates

---

## 1. Agent Design & Architecture

### Prompt 1: Define Agent Role & Goals
```
You are an expert AI agent architect. Design a complete specification for an AI agent with the following role: [ROLE, e.g., "Freelance Proposal Writer for Web Developers"].

Include:
- Clear mission statement
- Primary goals and success metrics
- Input sources and expected outputs
- Constraints and safety boundaries
- Required tools/APIs
- Memory requirements
- Escalation rules for human review

Output as a structured JSON schema.
```

### Prompt 2: System Prompt Generator
```
Create a production-ready system prompt for an AI agent that [SPECIFIC TASK]. The agent should:
- Be concise and action-oriented
- Refuse requests outside its scope
- Ask clarifying questions when needed
- Format outputs in a specific structure: [FORMAT]

Make the prompt under 400 tokens while remaining highly effective.
```

---

## 2. Prompt Engineering for Agents

### Prompt 3: Chain-of-Thought Agent
```
Act as a step-by-step reasoning agent. For the task "[TASK]", break it down into:
1. Information gathering
2. Analysis
3. Option generation
4. Decision criteria
5. Final recommendation with confidence score

Show your reasoning at each step, then provide the final output.
```

### Prompt 4: Self-Critique Loop
```
Complete the following task: [TASK]

After completing it, critique your own work on these dimensions:
- Accuracy
- Completeness
- Clarity
- Actionability

Then revise the output based on your critique. Show both versions.
```

---

## 3. Tool Use & Function Calling

### Prompt 5: Tool Selection Agent
```
You have access to these tools: [LIST TOOLS]. 

Given the user request: "[REQUEST]", decide which tool(s) to use, in what order, and what parameters to pass. Output only the tool call plan in JSON.
```

### Prompt 6: Web Research Agent
```
You are a research agent. Find the most recent, high-quality information on: [TOPIC]

For each finding:
- Source URL
- Key claim
- Confidence level (1-10)
- Date of information

Synthesize into a 200-word brief with citations.
```

---

## 4. Memory & Context Management

### Prompt 7: Long-Term Memory Summarizer
```
Summarize the following conversation history into a structured memory entry that can be retrieved later:

[CONVERSATION]

Include:
- User preferences
- Key decisions made
- Open tasks
- Important facts
```

### Prompt 8: Context Window Optimizer
```
You have a limited context window. Given this large document [DOCUMENT], extract only the sections most relevant to answering: "[QUESTION]". Rank relevance and return the top 3 passages with explanations.
```

---

## 5. Multi-Agent Orchestration

### Prompt 9: Manager Agent
```
You are a manager agent coordinating three specialist agents:
1. Researcher
2. Writer
3. Critic

For the goal "[GOAL]", assign tasks to each agent, collect their outputs, and synthesize a final deliverable. Show the workflow.
```

### Prompt 10: Debate Agents
```
Simulate a debate between two agents with opposing viewpoints on: [TOPIC]

Agent A argues for [POSITION A]
Agent B argues for [POSITION B]

After 3 rounds, a third agent synthesizes the strongest points from both sides.
```

---

## 6. Monetization & Business Automation

### Prompt 11: Lead Qualification Agent
```
You are a lead qualification agent for [BUSINESS]. Score this lead on a 1-10 scale for fit and urgency:

Lead info: [LEAD DATA]

Provide score, reasoning, and recommended next action.
```

### Prompt 12: Content Repurposing Agent
```
Take this original content: [CONTENT]

Repurpose it into:
1. A Twitter/X thread (5-7 posts)
2. A LinkedIn post
3. An email newsletter section
4. 3 short video script ideas

Maintain the core message while adapting tone for each platform.
```

### Prompt 13: Pricing Strategy Agent
```
Analyze pricing for a digital product in the niche of [NICHE]. Competitors charge [PRICES]. Recommend an optimal price point with justification based on value, competition, and conversion psychology.
```

---

## 7. Debugging & Optimization

### Prompt 14: Agent Failure Analyzer
```
This agent failed with the following error/output: [ERROR]

Original system prompt: [PROMPT]
User input: [INPUT]

Diagnose the root cause and provide a fixed version of the prompt or logic.
```

### Prompt 15: Token Cost Optimizer
```
Rewrite this agent prompt to achieve the same result while using approximately 40% fewer tokens. Preserve all critical instructions.

Original: [PROMPT]
```

---

## 8. Niche Agent Templates

### Prompt 16: Solopreneur Operations Agent
```
You are the operations manager for a solopreneur running a [BUSINESS TYPE]. Your daily tasks include:
- Prioritizing the top 3 revenue-generating activities
- Drafting client communications
- Tracking key metrics
- Suggesting automation opportunities

Today's inputs: [INPUTS]
```

### Prompt 17: Etsy/Gumroad Product Lister
```
Create a high-converting product listing for: [PRODUCT]

Include:
- SEO-optimized title (under 140 chars)
- 5 bullet points highlighting benefits
- Full description with keywords
- 13 relevant tags
- Pricing recommendation
```

### Prompt 18: Customer Support Agent
```
Respond to this customer message as a helpful, professional support agent for [PRODUCT]:

Customer: [MESSAGE]

Guidelines: Empathize first, solve the problem, offer next steps. Never promise refunds without approval.
```

---

## Bonus: Automation Workflows

### Workflow 1: Daily Content Agent
System prompt + scheduled trigger that researches trends, drafts posts, and queues them.

### Workflow 2: Lead Response Agent
Monitors form submissions or emails, qualifies leads, and drafts personalized responses.

### Workflow 3: Revenue Tracking Agent
Pulls sales data (manual or API), analyzes trends, and sends weekly summary with recommendations.

---

## How to Use This Toolkit
1. Copy any prompt and customize the bracketed sections.
2. Test in your preferred LLM (Claude, GPT, Grok, Gemini).
3. Iterate based on output quality.
4. Combine prompts into multi-step agent workflows.
5. Sell customized versions of these to clients or as your own digital products.

**License**: Personal and commercial use permitted. Reselling the pack as-is is not allowed.

---

*Created with AI assistance for maximum practical value. Update prompts as models improve.*
