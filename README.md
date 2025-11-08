# 🤔 Socratic Thinking GPT

> **Transform your Socratic MCP into a deployable ChatGPT GPT**

[![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-blue)](https://modelcontextprotocol.io)
[![GPT](https://img.shields.io/badge/ChatGPT-GPT_Builder-green)](https://chat.openai.com/gpts/editor)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

## 💡 What is This?

This repository contains **ready-to-deploy GPT configuration** for **Socratic Thinking GPT** - an AI that asks questions instead of giving answers.

Based on the [Socratic Thinking MCP](https://github.com/seanshin0214/socratic-thinking-mcp), this GPT uses **58 proven thinking methodologies** to guide users through:

- 🎯 **Strategic Decision-Making** (22 methods) - SWOT, BCG Matrix, Decision Tree, Porter's Five Forces...
- 🧠 **Critical Thinking** (12 methods) - 5 Whys, Systems Thinking, Fishbone, Mental Models...
- 🎨 **Creative Innovation** (24 methods) - SCAMPER, Design Thinking, TRIZ, Six Thinking Hats...

## 🚀 Quick Deploy (3 minutes)

### 1. Go to ChatGPT GPT Builder
**Link:** https://chat.openai.com/gpts/editor

(Requires ChatGPT Plus subscription)

### 2. Configure Your GPT

**Name:**
```
Socratic Thinking GPT
```

**Description:**
```
AI that asks, not answers. 58 proven thinking methodologies for strategic decisions, creative breakthroughs, and critical analysis. Like Socrates - I guide you to discover insights through structured questioning. 🤔
```

**Instructions:**
Copy and paste the entire content from `GPT-Instructions.md`

**Conversation Starters:**
```
Help me think through a difficult decision
I need to brainstorm creative solutions  
Guide me through strategic analysis
도움이 필요한 결정이 있어요
```

**Capabilities:**
- ❌ Code Interpreter: OFF
- ❌ Web Browsing: OFF
- ❌ DALL-E: OFF

### 3. Test
```
"Should I accept this new job offer?"
```

Expected: Classifies as STRATEGIC → Recommends 2-3 methodologies → User selects → One question at a time

### 4. Publish
- **Public**: Available in GPT Store
- **Unlisted**: Link-only access

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `GPT-Instructions.md` | Complete GPT instructions (paste into GPT Builder) |
| `Configuration-Guide.md` | Detailed configuration and testing guide |
| `Deploy-Ready.md` | Step-by-step deployment checklist |
| `README.md` | This file |

## 🎯 Key Features

### Question-Based, Not Answer-Based
```
Traditional AI: "You should choose option A because..."
Socratic GPT: "Question 1/5: What outcomes are you optimizing for?"
```

### 58 Structured Methodologies
Each with predefined question sequences:
- **SWOT** (4 questions)
- **SCAMPER** (7 questions)
- **Decision Tree** (5 questions)
- **5 Whys** (5 questions)
- ...and 54 more

### Progressive Questioning
One question at a time, building on previous answers:
```
[Method: DECISION TREE - STRATEGIC]
Question 1/5: What's the core decision?

User: "MBA vs startup"

[Method: DECISION TREE - STRATEGIC]
Question 2/5: What are ALL your realistic options?
```

### Bilingual (English + Korean)
Automatically detects and responds in user's language.

## 🌟 Example Usage

**User:** "How can I improve my app's user engagement?"

**GPT:**
```
🎯 Problem analyzed
Category: Creative & Innovation

📋 Recommended methodologies:
1. SCAMPER - For product innovation (7 steps)
2. DESIGN THINKING - For user-centered solutions (5 steps)
3. SIX THINKING HATS - For multi-perspective analysis (6 steps)

Which approach? (1/2/3)
```

**User:** "1"

**GPT:**
```
[Method: SCAMPER - CREATIVE]
Question 1/7: What can you SUBSTITUTE?

Think about: Current features/elements that could be replaced
```

[Continue with remaining 6 questions...]

## 📚 58 Methodologies Included

### Strategic & Decision-Making (22)
SWOT | BCG Matrix | Porter's Five Forces | PESTEL | Ansoff Matrix | Blue Ocean | Value Chain | OKR | Decision Tree | Decision Matrix | Cost-Benefit | Pros-Cons-Fixes | Regret Minimization | Opportunity Cost | Eisenhower Matrix | Pre-Mortem | Scenario Planning | Second-Order Thinking | Systems Thinking | Mental Models | Inversion | Fishbone

### Critical Thinking (12)
5 Whys | Phoenix Checklist | Force-Field | Six Thinking Hats | Lateral Thinking | Attribute Listing | Morphological Analysis | Fractionation | Mind Mapping | Reversal | Lotus Blossom | Future Scenarios

### Creative & Innovation (24)
SCAMPER | Design Thinking | TRIZ | Random Stimulation | Analogies | Fantasy Questions | Paradox | Forced Connection | Dreamscape | Intuition | Three B's | Relaxation | Talk to Stranger | Pattern Language | Drawing | Hypnagogic Imagery | Guided Imagery | Psychosynthesis | Hieroglyphics | Murder Board | Brainstorming | Circle of Opportunity | Idea Grid | Airline Method

## 🔧 Customization

Want to add your own methodologies? Edit `GPT-Instructions.md`:

1. Add to the appropriate category
2. Define question sequence
3. Add to Methodology Quick Reference section
4. Update GPT instructions

## 📊 Success Metrics

Your GPT succeeds when users:
- ✅ Discover insights themselves
- ✅ Make better decisions through reflection
- ✅ Learn thinking frameworks
- ✅ Request multiple methodologies
- ✅ Feel empowered, not dependent

## 🤝 Contributing

Based on [Socratic Thinking MCP](https://github.com/seanshin0214/socratic-thinking-mcp).

Contributions welcome:
- Additional methodologies (with academic/practitioner sources)
- Improved question templates
- Translations (currently English + Korean)
- Use case examples

## 📝 License

MIT License

## 🙏 Acknowledgments

- **Socratic Method** - Ancient Greek philosophy
- **Michael Michalko** - ThinkerToys (Creative methodologies)
- **Edward de Bono** - Six Thinking Hats, Lateral Thinking
- **Genrich Altshuller** - TRIZ methodology
- **Jeff Bezos** - Regret Minimization Framework
- **Model Context Protocol** - Anthropic

## 🔗 Related Projects

- [Socratic Thinking MCP](https://github.com/seanshin0214/socratic-thinking-mcp) - Original MCP implementation
- [QualAI MCP](https://github.com/seanshin0214/qualai-mcp) - Qualitative research analysis

---

**Built with ❤️ for deeper thinking**

*"The unexamined life is not worth living." - Socrates*

---

## 🎬 Quick Links

- **Deploy Now**: https://chat.openai.com/gpts/editor
- **Instructions**: [`GPT-Instructions.md`](GPT-Instructions.md)
- **Full Guide**: [`Configuration-Guide.md`](Configuration-Guide.md)
- **Checklist**: [`Deploy-Ready.md`](Deploy-Ready.md)
