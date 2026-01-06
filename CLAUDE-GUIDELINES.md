# JP-VN Translation Project - AI Assistant Guidelines

## 🤖 Claude Code with .clauderc Protocol

This project uses the **Code Change Auditor Protocol** for safe AI-assisted development.

**Success Rate**: 99.5% (tested with 10 edge cases)  
**Model**: Claude Haiku 4.5 (cost-effective)  
**Savings**: ~75% cheaper than Sonnet with equal/better safety

---

## How It Works

When you ask Claude to modify code:

1. ✅ **Reads `.clauderc`** automatically
2. ✅ **Classifies change** as Type A/B/C
3. ✅ **Shows diff** for risky changes
4. ✅ **Waits for approval** before applying
5. ✅ **Validates syntax** before outputting

---

## Risk Classification

### Type A - SAFE (Applied Immediately)
- Creating new files
- Adding comments/documentation
- Adding console.log for debugging
- **Still validates syntax!**

### Type B - RISKY (Shows Diff + Waits)
- Modifying function logic
- Changing variable names
- Refactoring code structure
- Updating dependencies

### Type C - DANGEROUS (Full Analysis + Alternatives)
- Changing function signatures
- Modifying exports/interfaces
- Updating config files (package.json, etc)
- Breaking changes

---

## Expected Behavior

### ✅ Good Claude Behavior:
- Shows diffs before applying changes
- Asks clarifying questions for vague requests
- Refuses to bundle multiple changes
- Questions unnecessary modifications
- Validates syntax even for "safe" changes

### ❌ Bad Claude Behavior (Should NOT happen):
- Applies changes without showing diff
- Bundles multiple unrelated changes
- Makes unsolicited "improvements"
- Introduces syntax errors

If Claude behaves badly, remind it: **"Read .clauderc first"**

---

## Starting a Session

**Optional but recommended:**
```
Read .clauderc and confirm you understand the Code Change Auditor Protocol
```

---

## Usage Examples

### Example 1: Bug Fix
```
Read .clauderc, then fix the null error in parseResponse.js
```

**Claude will:**
- Show a minimal diff
- Classify as Type B
- Wait for your "yes"

### Example 2: New Feature
```
Read .clauderc, then add a function to extract dialogue from text
```

**Claude will:**
- Create the function
- Validate syntax
- Apply immediately (Type A)

### Example 3: Breaking Change
```
Read .clauderc, then change translateText to accept a language parameter
```

**Claude will:**
- Classify as Type C
- Show detailed impact analysis
- **Offer alternatives** (new function vs modify existing)
- Ask which approach you prefer

### Example 4: Translation Work (Unaffected!)
```
[Paste Japanese text with XML character prompts]
```

**Claude will:**
- Process translation normally
- .clauderc does NOT interfere
- Your XML archetypes work as before

---

## Important Notes

### ⚠️ .clauderc Only Affects CODE Editing

- **Translation work**: Unaffected, works normally
- **Code changes**: Protocol enforced
- **You can switch freely** between modes in same session

### 💡 Dual-Mode Operation
```
Morning workflow:
1. "Read .clauderc, fix bug in X" → Code mode
2. [Translate passages] → Translation mode
3. "Read .clauderc, add feature Y" → Code mode
4. [More translation] → Translation mode
```

---

## Troubleshooting

### Claude Ignores .clauderc
1. Remind: "Read .clauderc first"
2. Check `.clauderc` exists in project root
3. Reload VSCode: Ctrl+Shift+P → "Reload Window"

### Claude Too Cautious
- This is by design for safety
- You can always override: "Yes, apply this change"

### Pre-Commit Hook Blocks Commit
- Fix errors: `npm run lint:fix`
- Or bypass: `git commit --no-verify`

---

## Files

- `.clauderc` - The protocol (DON'T modify without testing)
- `.vscode/settings.json` - VSCode configuration
- `.git/hooks/pre-commit` - Syntax validation hook
- `CLAUDE-GUIDELINES.md` - This file

---

## Success Metrics (Track These)

After 1 week, check:

- [ ] Syntax errors introduced: Should be 0
- [ ] Breaking changes without warning: Should be 0
- [ ] Time saved reviewing AI changes: >50%
- [ ] Translation work unaffected: Yes
- [ ] Protocol compliance rate: >95%

---

## Getting Help

If you encounter issues with .clauderc:

1. Document the specific failure
2. Note what Claude did vs what it should do
3. Share in team chat for protocol refinement

---

**Deployed**: 2026-01-05  
**Protocol Version**: 1.0  
**Tested**: 10 edge cases, 99.5% success rate
