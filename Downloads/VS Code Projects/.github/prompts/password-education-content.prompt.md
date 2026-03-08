---
name: Password Education Content
description: "Create educational password-security blog content from defined content pillars and core principles."
argument-hint: "topic, audience, outputType (calendar|outline|draft), platform(optional)"
agent: "agent"
---
Create educational password-security content for a blog using the content pillars and principles below.

Interpret the user argument as:
- `topic`: the primary angle to cover
- `audience`: who the content is for
- `outputType`: `calendar`, `outline`, or `draft`
- `platform`: optional platform name for 2FA or migration guides
If one of these inputs is missing, use these defaults and state assumptions in one short line:
- `outputType`: `draft`
- `audience`: security-conscious adults using web and mobile accounts
- `topic`: pick the highest-impact beginner-safe topic from the pillars

Use these content pillars:
- How-To Educational Series
  - Create a strong master password (use memorable passphrases with 4-6 random words)
  - Set up 2FA/MFA on a named platform
  - Use password generators and autofill safely
  - Import passwords from major browsers to a secure vault
- Common Mistakes and Myth-Busting
  - Why "Password123" and similar passwords fail quickly
  - Length vs complexity (long passphrases beat short complex strings)
  - Why password reuse enables credential stuffing
  - Why frequent forced password changes are often unnecessary when passwords are unique and strong
- Scenario-Based Content
  - What to do after a data breach
  - How to securely share passwords with family
  - Protecting digital legacy with emergency access
- Comparisons and Reviews
  - Password manager A vs B
  - Browser managers vs dedicated password managers
- News and Trends
  - Lessons from recent breaches
  - Passkeys, biometrics, and the future of authentication

Apply these core themes consistently:
- Long > Complex: prefer 3+ random words.
- Unique > Same: never reuse credentials.
- Managed > Handwritten: use a secure vault.

Generate exactly one deliverable based on `outputType`:
- `calendar`: a 4-week content calendar with 2 posts per week
- `outline`: a complete outline for one post
- `draft`: a full post draft (about 900-1200 words)

Style and quality requirements:
- Use practical and plain language.
- Keep the tone professional, calm, and educational (not fear-based).
- Include actionable steps and checklists where relevant.
- Avoid unverifiable hard numbers; if needed, label them as examples.
- End with one clear call to action.

Output format:
1. Title
2. Audience + objective
3. Main output (`calendar`, `outline`, or `draft`)
4. Key takeaway (one sentence)
