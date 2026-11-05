# Field Day 2027 Volunteer Sign-Up Platform Options

**Date:** 2026-11-05  
**Issue:** [#42 Research free volunteer sign-up alternatives and send options](https://github.com/tsayles/field-day-2027/issues/42)  
**Audience:** FD 2027 planning committee

## Executive summary

The committee's top priorities are low cost, easy volunteer signup, and easy organizer setup. For Field Day 2027, the best lightweight free option is a Google Forms + Google Sheets workflow with a protected coordinator-only response sheet.

This approach meets the minimum requirements without creating a new app, hosting burden, or budget risk. It supports role-based volunteer jobs, preserves contact privacy, and exports cleanly to CSV/XLSX for offline field use. It also aligns with the club's existing website and mailing-list workflow and can be launched in a matter of days instead of weeks. It is a spreadsheet-driven staffing workflow rather than a full native volunteer scheduler, but it is well matched to the committee's needs and timeline.

This report evaluates the viable free/low-cost options and recommends a path for committee review.

---

## Research criteria used

Priority order used for this review:

1. Reduce cost
2. Ease of volunteer sign-up
3. Ease of organizer setup

Budget ceiling used:

- Target: free or very low cost
- Hard ceiling: under $200

Minimum data fields required:

- Volunteer name (required)
- Callsign (optional)
- Email (required)
- Phone (optional)

Functional needs:

- Role/job list with title, date/time, skill level, and related metadata
- Basic workflow only; advanced automation not required
- CSV/XLSX export preferred for offline use
- Contact data restricted to coordinators
- Public roster fields may be limited to non-contact info

---

## Comparison matrix

| Option | Cost | Role-based signup | Coordinator visibility | Export / offline use | Setup effort | Privacy controls | Recommendation |
|---|---:|---|---|---|---|---|---|
| Google Forms + Google Sheets + Apps Script | Free | Strong for role/job lists, sections, and required questions | Strong via protected spreadsheet, filtered tabs, and editor-only access | Excellent: CSV/XLSX export from Sheets | Low | Very strong with separate public/private tabs and restricted editors | Best overall fit |
| Airtable Free plan | Free | Strong; good for multiple role tables and staffing views | Strong admin views and role tracking | Good: CSV export and data snapshots | Medium | Good; can restrict contact fields to coordinator views | Good runner-up |
| Jotform free plan | Free tier, limits apply | Good for forms and volunteer signups | Good; can add notifications and spreadsheet sync | Good: CSV export, PDF reports | Low to medium | Moderate; requires careful sharing settings | Viable but more limited than Google |
| Microsoft Forms + Excel/SharePoint | Usually free if M365 already exists; otherwise adds cost | Good for basic volunteer forms | Good for org-managed accounts | Good: Excel export | Low | Good inside managed Microsoft environment | Viable if club already has a Microsoft tenant |
| SignUpGenius / volunteer scheduling sites | Free tier often limited; paid upgrades common | Good for shift signups | Good for coordinators | Mixed; export often limited | Low | Usually limited compared with a Google or Airtable setup | Not the best fit for this budget and privacy model |

---

## Option details

### 1) Google Forms + Google Sheets + Apps Script — Recommended

This is the best lightweight free option for Field Day 2027 because it is zero-cost, easy to launch, and already familiar to many volunteers. It is best described as a spreadsheet-driven staffing workflow rather than a full native volunteer scheduler.

Strengths:

- Free with a personal or club Google account
- Simple, low-friction sign-up flow for volunteers
- Role/job questions can be implemented in one form with sections or repeating questions
- Response spreadsheet gives coordinators a single place to sort, assign, and export data
- CSV/XLSX exports are easy for offline field use or manual roster planning
- No custom server or app deployment required

Limitations:

- Native job-slot management is more spreadsheet-based than a dedicated volunteer scheduler
- The committee will need to manage role counts and assignments in a coordinator-only sheet rather than relying on automatic slot enforcement
- A little spreadsheet organization is needed to prevent public contact data exposure
- Without careful settings, email and phone fields could be visible in a shared sheet

Recommended setup:

- Use one public signup form with required fields: name, email, callsign, phone (optional), role interest, and availability
- Add a role list with options such as setup crew, teardown, 15m operator, 20m operator, 40m phone, CW, digital, GOTA, potluck, logistics, and safety support
- Use a second coordinator-only sheet or protected tab for private contact fields
- Keep a public summary tab with names, callsigns, and role assignments only if needed
- Export to CSV at the end of each sign-up window for offline planning
- Maintain a coordinator worksheet with columns for role title, date/time, skill level, maximum capacity, assigned count, current volunteers, and assignment status
- Add a simple rule that each role closes when the assigned count reaches the role's maximum capacity

Best-for fit:

- Immediate rollout before committee review or next planning meeting
- Small-to-medium volunteer pool with a centralized coordinator team
- Minimal learning curve and no extra budget required

---

### 2) Airtable Free plan — Strong second choice

This is the best no-code alternative if the committee wants a more polished volunteer roster and role-tracking experience.

Strengths:

- Very strong for role-based volunteer management and staff assignment views
- Easy to maintain multiple tables: volunteers, roles, assignments, shift dates/times
- Good visibility for coordinators with filtered views and role-by-role dashboards
- CSV export is available, and records can be manipulated offline

Limitations:

- The free plan has record and automation limits that may become tight for a large volunteer pool
- More setup work than a simple Google Form
- A bit more learning and configuration effort for coordinators

Recommended setup:

- Create one `Volunteers` table and one `Roles` table
- Add fields for name, callsign, email, phone, preferred role, skill level, and availability
- Use views filtered by coordinator or role chair
- Keep private contact info in a restricted view or separate base access

Best-for fit:

- Clubs that want a cleaner volunteer admin workflow than a spreadsheet
- Cases where a volunteer coordinator wants richer assignment tracking without paying for a full SaaS product

---

### 3) Jotform free plan — Viable but not as strong as Google

Jotform is a capable form platform with good reporting and workflow features. It is viable for a single volunteer form, but the free tier is generally less attractive than Google Forms for this specific use case.

Strengths:

- Strong form-building experience
- Good email notifications and submissions management
- Easy export to CSV/XLSX
- Good for basic volunteer signups and role preferences

Limitations:

- Free tier limits can be restrictive for a larger recruiting campaign
- More polished than necessary for a club-sized volunteer list
- Still requires someone to manage access and form data carefully

Best-for fit:

- A club that already uses Jotform and wants a quick adoption path
- A committee that prefers a dedicated commercial form builder but does not want to pay

---

### 4) Microsoft Forms + Excel/SharePoint — Viable if the club already has M365

This option is solid for clubs that already operate inside a Microsoft 365 environment.

Strengths:

- Good if the club already has Microsoft licensing and access
- Easy for forms and spreadsheets
- Good coordinator access controls and exported data

Limitations:

- Not a clear fit if the club does not already have Microsoft 365 access and tenant controls
- More difficult for a simple, zero-cost, no-IT setup story

Best-for fit:

- Organizations already using Microsoft 365 for membership, communications, or team management

---

### 5) SignUpGenius / volunteer scheduling sites — Not the best fit

These services are designed for shift signup and recurring volunteer scheduling, but they are not the best fit for the committee's cost and privacy requirements.

Strengths:

- Very easy for people to sign up for recurring shifts
- Good for one-time event staffing

Limitations:

- Free plans often have feature limits or paywalls
- Privacy model is not as clean for club contact data
- More likely to require paid upgrades for roster control and export features

Best-for fit:

- A small event where the club is already using the service and has a paid plan

---

## Recommended choice

### Recommended platform: Google Forms + Google Sheets (with coordinator-only protected tabs)

Why this is the best fit:

- Lowest cost: free
- Fastest path to launch: no custom app or server needed
- Easy volunteer sign-up: a single public form is available from a website link or QR code
- Easy coordinator management: spreadsheet view for filtering by role and contact status
- Export-friendly: CSV/XLSX for offline planning and field use
- Private contact handling: can be limited to coordinator editors only
- Good fit for a club-sized volunteer pool without a lot of process overhead

### Practical recommendation for the committee

Adopt a two-stage setup:

1. Initial sign-up form on Google Forms for quick recruiting
2. Coordinator-only spreadsheet in Google Sheets for role assignment and scheduling visibility

This gives the club a lightweight but durable volunteer workflow without a software procurement decision or recurring fee.

### Capacity control and duplicate-signup handling

The key limitation of a Google Form is that it does not automatically enforce "one person per slot" logic. To prevent multiple volunteers from claiming the same job, the workflow should include a coordinator-managed capacity sheet that tracks each role's maximum seats and current count.

Recommended practice:

- Create one role row per job slot, with columns for `role_title`, `date_time`, `skill_level`, `max_capacity`, `assigned_count`, and `status`
- Use a formula such as `=COUNTIF(role_range, A2)` to calculate the number of signups already assigned to each role
- Close a role when `assigned_count >= max_capacity`
- Keep the form public, but keep final assignment and slot locking in the coordinator-only sheet
- If the committee wants stricter automated capacity checks, Airtable is the next-best option because it supports role/slot tracking more naturally

This keeps the process low-cost while still controlling duplicate signups.

---

## Trade-offs and decision considerations

### Why not recommend a dedicated volunteer platform first?

Dedicated solutions are attractive, but they add friction for a small club with limited budget and a minimal automation requirement. The committee's needs are straightforward: collect interest, assign roles, and keep contact data private. A dedicated volunteer platform is not necessary to achieve that outcome.

### Runner-up: Airtable free plan

Airtable is the best backup recommendation if the committee wants a more formal roster system without paying for a service. It offers better role structure and assignment views than a Google Form but requires more setup and has free-plan limits.

If the club expects more than 200–300 volunteers or if it wants a clearer staffing dashboard, Airtable becomes more attractive. For the 2027 planning timeline, however, Google Forms is simpler and safer.

---

## Minimum practical workflow for Field Day 2027

1. Publish a volunteer interest form on the club website or mailing list
2. Collect: name, email, callsign, phone (optional), role interests, and availability
3. Assign roles in a coordinator-only spreadsheet
4. Keep contact info hidden from general view
5. Export the roster as CSV/XLSX before the event or during setup week
6. Review job coverage by role chair and re-run the form as needed

Example form fields:

- Full name (required)
- Callsign (optional)
- Email address (required)
- Phone number (optional)
- Preferred role(s) (multi-select or checkbox list)
- Skill level (beginner / intermediate / experienced)
- Availability / date-time windows
- Notes (optional)

Example role metadata schema for coordinator tracking:

| Field | Example |
|---|---|
| Role title | 20m Phone Operator |
| Date / time | Sat 2027-06-26 11:00-18:00 PT |
| Skill level | Intermediate / Experienced |
| Crew count needed | 2 |
| Role category | Operating / Setup / Logistics |
| Contact visibility | Coordinator only |
| Assignment status | Open / Assigned / Confirmed |
| Notes | Requires radio experience and CW/phone familiarity |

---

## Website integration and webmaster handoff notes

The website integration should be kept intentionally simple. The most reliable path is one of the following:

1. Link from the club website to a public volunteer form
2. Embed the form in a page if the webmaster approves an HTML embed or CMS plugin
3. Use a short QR code on the volunteer page or printed teaching materials if embedding is not possible

Recommended webmaster review items:

- Confirm whether the site allows external form embedding or if a direct link is required
- Verify whether the site uses strict content-security policies or CMS restrictions that block third-party form scripts
- Keep the volunteer page in a simple, low-maintenance style so the site remains easy to maintain
- If the site is static HTML, a direct link is the lowest-risk option
- If the site is WordPress or another CMS, the webmaster should test the form in a staging page before publishing live

Data privacy and authorization notes:

- Public page: display only the form and general role descriptions; do not expose contact data
- Coordinator-only access: grant edit access only to the role chairs and committee leads; response form owners and spreadsheet editors must be restricted to coordinators
- Separate private sheet: keep the full contact roster in a restricted tab or spreadsheet with editor access limited to coordinators; do not share the raw response sheet publicly
- Public roster copy: if any public summary is needed, include only non-contact fields such as role and availability status
- No volunteer email/phone data should be exposed on the website or in public GitHub documents
- If public sharing is required for a summary, use a separate non-contact roster that omits names, emails, and phone numbers entirely

Important website/authorization constraint:

The webmaster should not be asked to build custom server-side processing or account authorization into the website unless the committee specifically decides to support a larger, long-term volunteer system. A hosted form plus protected spreadsheet is far easier to authorize and maintain.

---

## Final recommendation to the committee

The committee should approve a low-cost Google Forms + Google Sheets implementation as the default volunteer sign-up system for Field Day 2027, with Airtable as the backup option if the committee wants a more structured role-management experience.

This recommendation best matches the stated criteria:

- lowest cost
- easiest volunteer signup
- easy organizer setup
- strong privacy controls
- acceptable workflow with preferred CSV export for offline field use

This approach is also the lowest-risk compliance path and requires the least website and authorization work from the webmaster.

---

## Source notes

This assessment was prepared using public product information and current pricing/feature pages for Google Forms, Airtable, Jotform, Microsoft Forms, and volunteer scheduling services.

Relevant product and reference sources (to be revalidated from a networked browser before live publication):

- Google Forms: https://www.google.com/forms/about/
- Google Workspace pricing: https://workspace.google.com/pricing.html
- Airtable pricing: https://www.airtable.com/pricing
- Jotform pricing: https://www.jotform.com/pricing/
- Microsoft Forms: https://www.microsoft.com/en-us/microsoft-365/online-surveys-polls-quizzes
- SignUpGenius pricing: https://www.signupgenius.com/

The committee should review the final platform choice before publishing the live volunteer form.
