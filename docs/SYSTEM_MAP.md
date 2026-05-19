# Repository Map: Quick Reference
**Purpose:** Visual guide to the structure and how everything connects  
**Status:** Live

---

## What We've Built

### Foundation Layer (The Rules)
```
docs/
├── OPERATING_MANUAL.md ........... North Star & decision hierarchy
├── EXECUTION_STANDARDS.md ....... Tone, length, publishing rules
├── BRAND_AUTHORITY.md ........... Authority protection & creative trust
└── SEO_LOCATION_STRATEGY.md ..... Geographic & SEO discipline
```

**Use When:** Making any decision. These override everything else.

---

### Strategy Layer (The Plans)
```
strategy/
├── firm-website/
│   └── CRITICAL_ISSUES.md ........ Website audit & problems (location pages 0.14% CTR)
├── personal-brand/
│   ├── JASON_TAYLOR_STRATEGY.md .. Overview & launch plan
│   ├── PLATFORMS.md .............. Per-platform guidance (Insta, LinkedIn, Facebook)
│   └── [to add: 90-day timeline]
└── [to add: firm-website roadmap]
```

**Use When:** Planning an initiative. These guide execution but can evolve.

---

### Information Layer (What We Know)
```
info/
├── WHAT_WE_KNOW.md .............. Inventory of documented information
├── WHAT_WE_NEED.md .............. Master list of information gaps (prioritized)
├── [to add: jason-details.md] ... Personal info (bikes, recipes, events)
├── [to add: jason-assets.md] .... Photos & videos
└── [to add: firm-details.md] .... Firm information
```

**Use When:** You need facts or context. These are living documents.

---

### Execution Layer (How We Do It)
```
content/
├── CONTENT_REVIEW_CHECKLIST.md .. Pre-publish verification
└── templates/
    ├── POST_TEMPLATE.md ......... Standard post format with metadata
    └── [to add: pillar-specific templates]

team/
├── ROLES.md ..................... Who does what (roles matrix)
├── [to add: WORKFLOWS.md] ...... How work flows
└── [to add: CONTACTS.md] ....... Team member contact info

tools/
├── [to add: INTEGRATIONS.md] ... Social platforms & scheduling
├── [to add: POSTING_CALENDAR.md] Master content schedule
└── [to add: ASSET_MANAGEMENT.md] Photo/video organization
```

**Use When:** Creating content, managing workflow, tracking performance.

---

## The Content Creation Workflow

```
1. RAW CONTENT
   Jason captures photos/videos
        ↓
2. ORGANIZE
   Social manager receives, sorts by pillar
        ↓
3. PLAN
   Reference PLATFORMS.md, WHAT_WE_KNOW.md
   Decide: which platform? which pillar?
        ↓
4. CREATE
   Use POST_TEMPLATE.md
   Write caption in Jason's voice
        ↓
5. REVIEW
   Check CONTENT_REVIEW_CHECKLIST.md
   Run through EXECUTION_STANDARDS.md
   Confirm no doctrine violations
        ↓
6. APPROVE
   Reviewer signs off
        ↓
7. PUBLISH
   Schedule on platform(s)
   Log in POSTING_CALENDAR.md
        ↓
8. TRACK
   Monitor engagement
   Log in SOCIAL_METRICS.md
```

---

## What You Have Right Now

✅ **COMPLETE:**
- Operating doctrine (5 docs)
- Strategy overview for Jason's brand
- Critical issues audit for firm website
- System architecture map
- Information inventory (what we know / what we need)
- Post template with review process
- Per-platform strategy guide
- Team roles template

⏳ **TO BUILD NEXT:**
1. Fill in WHAT_WE_NEED.md (gather info from Jason)
2. Create POSTING_CALENDAR.md (12-week plan)
3. Create platform-specific content templates
4. Set up team roles with actual names
5. Document workflows (who does what, when)
6. Configure tools/integrations
7. Build initial content buffer
8. Launch (start posting)
9. Monitor & optimize

---

## How to Navigate This Repo

### "I need to understand the big picture"
→ Start here, then read `/docs/OPERATING_MANUAL.md`

### "I need to create a social post"
→ Read `/strategy/personal-brand/PLATFORMS.md` (which platform?)
→ Read `/docs/EXECUTION_STANDARDS.md` (tone rules)
→ Copy `/content/templates/POST_TEMPLATE.md`
→ Check `/content/CONTENT_REVIEW_CHECKLIST.md`

### "I need information about Jason"
→ Check `/info/WHAT_WE_KNOW.md` first
→ If not there, check `/info/WHAT_WE_NEED.md`
→ If missing, add to appropriate "TO ADD" file

### "I need to know who does what"
→ Read `/team/ROLES.md`

### "I need to understand the strategy"
→ Read `/strategy/personal-brand/JASON_TAYLOR_STRATEGY.md`
→ Then read `/strategy/personal-brand/PLATFORMS.md`

### "I need to know what's not working"
→ Read `/strategy/firm-website/CRITICAL_ISSUES.md`

---

## File Dependencies

```
OPERATING_MANUAL.md (foundation)
    ├── → EXECUTION_STANDARDS.md
    ├── → BRAND_AUTHORITY.md
    ├── → SEO_LOCATION_STRATEGY.md
    └── → Every other decision

JASON_TAYLOR_STRATEGY.md (overview)
    ├── → PLATFORMS.md (specific tactics)
    ├── → WHAT_WE_KNOW.md (context)
    ├── → WHAT_WE_NEED.md (gaps)
    └── → POST_TEMPLATE.md (execution)

WHAT_WE_NEED.md (fill this in)
    └── → WHAT_WE_KNOW.md (moves to here)

POST_TEMPLATE.md (creating content)
    ├── → EXECUTION_STANDARDS.md (rules)
    ├── → CONTENT_REVIEW_CHECKLIST.md (validation)
    └── → BRAND_AUTHORITY.md (tone)

PLATFORMS.md (strategy per platform)
    ├── → CONTENT_REVIEW_CHECKLIST.md (per-platform checks)
    └── → POSTING_CALENDAR.md (tracking)
```

---

## File Sizes & Reading Time

| File | Lines | Read Time | Purpose |
|------|-------|-----------|---------|
| OPERATING_MANUAL.md | 280 | 15 min | Foundation |
| EXECUTION_STANDARDS.md | 180 | 10 min | Rules |
| BRAND_AUTHORITY.md | 150 | 8 min | Authority |
| JASON_TAYLOR_STRATEGY.md | 450 | 20 min | Overview |
| PLATFORMS.md | 380 | 20 min | Tactics |
| WHAT_WE_KNOW.md | 280 | 15 min | Reference |
| WHAT_WE_NEED.md | 200 | 10 min | Checklist |
| CONTENT_REVIEW_CHECKLIST.md | 120 | 5 min | Quick check |
| POST_TEMPLATE.md | 110 | 5 min | Template |
| ROLES.md | 200 | 10 min | Team |

**Total:** ~2,300 lines, ~118 minutes to fully read

---

## Next Steps (What You Asked For)

### Phase 1: Get Information
- [ ] Distribute `/info/WHAT_WE_NEED.md` to Jason
- [ ] Schedule info-gathering session (1–2 hours)
- [ ] Collect photos/videos (initial 15–20 assets)
- [ ] Fill `/info/jason-details.md` and `/info/jason-assets.md`
- [ ] Confirm social account setup (Instagram, LinkedIn, Facebook)

### Phase 2: Plan Content
- [ ] Create `/tools/POSTING_CALENDAR.md` (12-week plan)
- [ ] Build platform-specific content templates
- [ ] Create 2-week content buffer
- [ ] Document team workflows

### Phase 3: Launch
- [ ] Final review of first posts
- [ ] Schedule and publish
- [ ] Monitor engagement
- [ ] Begin tracking metrics

---

## Questions This Repo Answers

**Where do I start?**
→ SYSTEM.md (you're here), then README.md

**What are the rules?**
→ `/docs/` (non-negotiable)

**What's the strategy?**
→ `/strategy/` (initiatives and plans)

**What do I need to know about Jason?**
→ `/info/WHAT_WE_KNOW.md` (facts) + `/info/WHAT_WE_NEED.md` (gaps)

**How do I create a post?**
→ `/content/templates/POST_TEMPLATE.md` + `/docs/EXECUTION_STANDARDS.md`

**What's different on each platform?**
→ `/strategy/personal-brand/PLATFORMS.md`

**Who's responsible for what?**
→ `/team/ROLES.md`

**Is this ready to launch?**
→ No. Need to fill information gaps first (Phase 1).

---

**Status:** System is organized. Ready for information gathering and content creation.
