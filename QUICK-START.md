# 🚀 Quick Start Guide

## Deploy in 3 Minutes

### Step 1: Go to GPT Builder
**URL:** https://chat.openai.com/gpts/editor

(Requires ChatGPT Plus subscription)

### Step 2: Configure

**Name:**
```
Socratic Thinking GPT
```

**Description:**
```
AI that asks, not answers. 58 proven thinking methodologies for strategic decisions, creative breakthroughs, and critical analysis. Like Socrates - I guide you to discover insights through structured questioning. 🤔
```

**Instructions:**
Copy entire content from [`GPT-Instructions.md`](GPT-Instructions.md) and paste into Instructions field.

**Conversation Starters:**
1. `Help me think through a difficult decision`
2. `I need to brainstorm creative solutions`
3. `Guide me through strategic analysis`
4. `도움이 필요한 결정이 있어요`

**Capabilities:**
- ❌ Code Interpreter: OFF
- ❌ Web Browsing: OFF  
- ❌ DALL-E: OFF

### Step 3: Test

Try this:
```
"Should I accept this new job offer?"
```

**Expected behavior:**
1. ✅ Classifies as STRATEGIC
2. ✅ Recommends 2-3 methodologies
3. ✅ User selects one
4. ✅ Asks ONE question at a time
5. ✅ Never gives direct answers

### Step 4: Publish

Choose:
- **Public** - GPT Store listing (recommended)
- **Unlisted** - Link-only access

---

## Testing Checklist

Before publishing, verify these work:

### ✅ Strategic Decision
```
Input: "Should I quit my job?"
Expected: Recommends Decision Tree, Regret Minimization, Pros-Cons-Fixes
```

### ✅ Creative Problem
```
Input: "How to improve my app UX?"
Expected: Recommends SCAMPER, Design Thinking, Six Hats
```

### ✅ Critical Analysis
```
Input: "Why are we losing customers?"
Expected: Recommends 5 Whys, Fishbone, Systems Thinking
```

### ✅ Korean Support
```
Input: "MBA를 할지 창업을 할지 고민이에요"
Expected: Responds in Korean with same flow
```

### ✅ No Answer Giving
```
Input: "What should I do?"
Expected: Asks question to help USER decide, NOT gives answer
```

### ✅ One Question at a Time
```
After method selection:
Expected: Shows [Method: X - CATEGORY] and asks ONE question, waits for answer
```

---

## Common Issues

### ❌ GPT gives direct answers instead of asking
**Fix:** Emphasize in testing: "Never answer. Always ask questions."

### ❌ GPT batches multiple questions
**Fix:** Test specifically: "Ask ONE question at a time, not multiple"

### ❌ Methodology not shown
**Fix:** Verify format `[Method: NAME - CATEGORY]` appears

### ❌ User not choosing methodology
**Fix:** Ensure 2-3 options presented before starting questions

---

## Post-Deploy

After publishing, you'll get a URL like:
```
https://chat.openai.com/g/g-XXXXXXXX
```

Share this link or make it discoverable in GPT Store.

---

## Quick Reference

**Repository:** https://github.com/seanshin0214/socratic-thinking-gpt
**Instructions:** [`GPT-Instructions.md`](GPT-Instructions.md)
**Full Docs:** [`README.md`](README.md)

---

**Questions?** Open an issue on GitHub.

**Ready?** [Deploy Now →](https://chat.openai.com/gpts/editor)
