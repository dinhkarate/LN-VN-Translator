# .clauderc Quick Reference

## 🎯 Risk Levels

**Type A** → New files, comments → ✅ Apply now  
**Type B** → Logic changes → ⚠️ Show diff + wait  
**Type C** → Breaking changes → 🚨 Full analysis + alternatives

## 📋 Common Commands

**Start session:**
```
Read .clauderc and confirm you understand the protocol
```

**Code fix:**
```
Read .clauderc, then [your request]
```

**Translation:**
```
[Just paste Japanese text - .clauderc won't interfere]
```

## 🚩 Red Flags

- 🚩 Multiple changes bundled → Claude should refuse
- 🚩 Vague request ("improve code") → Claude should ask specifics
- 🚩 Working code → Claude should question if change needed

## ✅ Expected Behavior

✓ Diffs shown for Type B/C  
✓ Syntax validated (even Type A)  
✓ Alternatives offered for Type C  
✓ Questions asked for vague requests  
✓ Translation work unaffected

## 🔧 Troubleshooting

**Claude ignores protocol:**  
→ Say: "Read .clauderc first"

**Too cautious:**  
→ By design, you can always approve

**Blocks commit:**  
→ Fix errors or: `git commit --no-verify`

---
**Version**: 1.0 | **Success Rate**: 99.5%
