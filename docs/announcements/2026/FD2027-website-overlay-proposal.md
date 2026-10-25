# Field Day 2027 Website Overlay Proposal

## Overview
This proposal suggests replacing or overlaying the current ARRL2026.png image on https://mikeandkey.org/fday1.php with FD 2027 content that prominently features volunteer recruitment and engagement opportunities.

The overlay would appear at the top of the page (where ARRL2026.png currently appears) and drive early recruitment and planning participation.

---

## Proposed Overlay Design

### Visual Layout
A horizontal banner/card (similar to current image dimensions) containing:

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                   │
│           Field Day 2027 — 50+ Years Strong!                    │
│                                                                   │
│  🎯 We're planning FD 2027 — and we need your help!             │
│                                                                   │
│  ☑️  Join our planning meetings (1st & 3rd Wednesdays, 8 PM)    │
│  ☑️  Sign up to volunteer (operators, setup, equipment)          │
│  ☑️  Share your ideas on GitHub                                  │
│  ☑️  Connect on our mailing list                                 │
│                                                                   │
│  👉 Get Involved: https://github.com/tsayles/field-day-2027     │
│  📧 Mailing List: FieldDay@mkarc.groups.io                       │
│                                                                   │
└─────────────────────────────────────────────────────────────────┘
```

### Content Elements to Include

1. **Headline:** "Field Day 2027 — 50+ Years Strong!"
   - Acknowledges the milestone of 50+ consecutive years at Fort Flagler

2. **Call-to-Action:** "We're planning FD 2027 — and we need your help!"
   - Creates urgency and inclusivity

3. **Four Key Actions** (with checkboxes for visual interest):
   - Join our planning meetings (1st & 3rd Wednesdays, 8 PM)
   - Sign up to volunteer (operators, setup, teardown, equipment)
   - Share your ideas on GitHub
   - Connect on our mailing list

4. **Two Primary Links:**
   - **GitHub Repository:** https://github.com/tsayles/field-day-2027
   - **Mailing List:** FieldDay@mkarc.groups.io

### Design Considerations

- **Color Scheme:** Use M&K club colors (suggest checking club branding)
- **Font:** Clean, readable sans-serif for web
- **Accessibility:** High contrast for visibility; alt-text for any graphics
- **Mobile Responsive:** Must work well on phones and tablets
- **Placement:** Above the existing FD description text, replacing or adjacent to ARRL2026.png

---

## Why This Works

1. **Early Engagement:** Directs site visitors to planning activities (not just event day info)
2. **Multiple Entry Points:** Offers mailing list, GitHub, meetings, and volunteering paths
3. **Inclusive Language:** No membership/license requirement mentioned
4. **Actionable:** Clear dates, links, and next steps
5. **Timely:** Promotes November 2026 – January 2027 planning sprint

---

## Implementation Options

### Option A: Static Image (Recommended for quick deployment)
- Create a PNG graphic (same dimensions as ARRL2026.png) with the overlay content
- Replace or supplement ARRL2026.png on fday1.php
- Requires minimal website changes

### Option B: HTML Card (More flexible)
- Add an HTML section to fday1.php with the content
- Use CSS for styling and responsiveness
- Allows easier updates without creating new images

### Option C: Both
- Temporary image overlay for immediate visibility
- Transition to HTML card for ongoing updates

---

## Next Steps

1. **Design Phase:** Create mockup in Figma or similar tool
2. **Review:** Circulate to M&K board for approval (colors, tone, messaging)
3. **Production:** Generate web-optimized image or implement HTML
4. **Deploy:** Add to fday1.php before November planning meetings
5. **Measure:** Track click-through rates to GitHub and mailing list signup

---

## Related Resources

- Repository: https://github.com/tsayles/field-day-2027
- Mailing List: https://mkarc.groups.io/g/FieldDay
- Planning README: docs/meetings/README.md
- M&K Website: https://mikeandkey.org/
