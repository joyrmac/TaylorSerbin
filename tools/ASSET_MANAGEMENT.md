# Asset Management System
**Purpose:** Organize and track all photos, videos, and creative assets  
**Status:** Framework Ready (assets to be added Phase 1)  
**Version:** 1.0

---

## Directory Structure

```
assets/
├── images/
│   ├── logos/
│   │   ├── alligator-primary.png
│   │   ├── alligator-icon-variations/
│   │   └── [Other logo files]
│   ├── mockups/
│   │   └── [Design mockups, reference images]
│   ├── riders-life/
│   │   ├── 2026-05-15_Asheville-ride.jpg
│   │   ├── 2026-05-18_Bike-maintenance.jpg
│   │   └── [Organized by date]
│   ├── cooking/
│   │   ├── 2026-05-10_Escargot-prep.jpg
│   │   ├── 2026-05-10_Escargot-plating.jpg
│   │   └── [Organized by date]
│   ├── shooting/
│   │   ├── 2026-05-12_Five-stand-competition.jpg
│   │   └── [Organized by date]
│   └── cigars/
│       ├── 2026-05-09_Cigar-collection.jpg
│       └── [Organized by date]
├── videos/
│   ├── riders-life/
│   │   ├── 2026-05-15_Riding-mountain-road.mp4
│   │   └── [Short clips for Reels]
│   ├── cooking/
│   │   ├── 2026-05-10_Escargot-cooking-process.mp4
│   │   └── [Process videos]
│   ├── shooting/
│   │   └── [Event footage]
│   └── reels/
│       ├── 2026-05-15_Legal-tip-30sec.mp4
│       └── [Edited, ready to post]
└── graphics/
    ├── templates/
    │   ├── Instagram-post-template.psd
    │   ├── LinkedIn-carousel-template.psd
    │   └── [Design templates]
    └── overlays/
        ├── Text-overlay-legal-tips.png
        └── [Text overlays, graphics]
```

---

## Naming Convention

### Images
```
Format: YYYY-MM-DD_Pillar_Description.ext

Examples:
2026-05-15_Riders-Life_Blue-Ridge-Sunset.jpg
2026-05-10_Cooking_Escargot-Prep.jpg
2026-05-12_Shooting_Five-Stand-Match.jpg
2026-05-09_Cigars_Collection-Detail.jpg
```

### Videos
```
Format: YYYY-MM-DD_Pillar_Description-LENGTH.mp4

Examples:
2026-05-15_Riders-Life_Mountain-Road-15sec.mp4
2026-05-10_Cooking_Escargot-Process-45sec.mp4
```

### Resolution Guidelines
- **Images:** Minimum 1080px (for Instagram)
- **Videos:** 1080p minimum
- **Stories:** 9:16 ratio preferred
- **Reels:** 9:16 ratio required
- **LinkedIn:** 1200x627 or square

---

## Metadata File

Each asset should have metadata recorded. Create a CSV or Notion database with:

| Filename | Date | Pillar | Platform | Description | Status | Posted? | Engagement |
|----------|------|--------|----------|-------------|--------|---------|------------|
| 2026-05-15_Riders-Life_Blue-Ridge.jpg | 2026-05-15 | Rider's Life | Instagram | Sunset ride in Blue Ridge | READY | Yes | High |
| 2026-05-10_Cooking_Escargot-Prep.jpg | 2026-05-10 | Gourmet | Instagram | Prep work for escargot | READY | Yes | Medium |

---

## Workflow: Capture → Store → Use

### 1. Capture
- Jason captures photo/video
- Stores with brief context ("riding in mountains," "escargot prep")
- Sends to social manager

### 2. Organize
- Social manager receives asset
- Renames using convention: `YYYY-MM-DD_Pillar_Description.ext`
- Stores in appropriate `/assets/` folder
- Adds metadata to tracking file

### 3. Plan
- Social manager reviews available assets
- Decides which platform, which pillar
- Assigns to posting schedule
- Drafts caption

### 4. Use
- Asset pulled from `/assets/`
- Caption written (references asset)
- Posted to platform(s)
- Link recorded in POSTING_CALENDAR.md

### 5. Retire
- Asset remains in `/assets/` (never delete)
- Marked as "POSTED" in metadata
- Archived if unused (moved to `/archived/`)

---

## Storage Locations

### Primary Storage
**Location:** `/assets/` in this git repository  
**Backup:** [Specify backup location - Google Drive? AWS S3?]  
**Access:** [How do team members access? Password? Shared link?]  

### Cloud Backup (Optional)
**Service:** [Google Drive / Dropbox / AWS / OneDrive]  
**Folder:** [Specify structure]  
**Sync:** [Automatic / Manual / Scheduled]  
**Access:** [Who has access?]  

---

## Quality Standards

### Photos
- ✅ Natural lighting preferred
- ✅ High quality but "real" feeling (not overly filtered)
- ✅ In-the-moment authenticity
- ✅ Clear composition (not overly cluttered)
- ❌ Stock photos
- ❌ Heavy filters or effects
- ❌ Obviously staged moments

### Videos
- ✅ Clear audio (if dialogue/music)
- ✅ Stable footage (use tripod for cooking)
- ✅ Under 60 seconds for Reels
- ✅ 9:16 ratio for vertical content
- ❌ Shaky/out-of-focus content
- ❌ Poor audio quality
- ❌ Overly produced feel

### Graphics
- ✅ Alligator logo visible (for Wisdom posts)
- ✅ Brand colors (dark gray, white, green)
- ✅ Readable text overlays
- ✅ Professional appearance without being corporate
- ❌ Trendy colors or fonts
- ❌ Overly designed feel
- ❌ Off-brand logo versions

---

## Archiving & Retention

### What to Keep
- ✅ All original photos/videos (never delete)
- ✅ All posted content
- ✅ All unused but good-quality assets
- ✅ Brand logos and templates

### What to Archive
- Duplicate photos (keep best version)
- Blurry or poor-quality takes
- Content that didn't perform well (keep for reference)
- Old design templates (replace with current)

**Archive location:** `/assets/archived/`

### Deletion Policy
- Never delete original assets
- Only delete duplicates after archiving
- Keep all posted content indefinitely
- Review quarterly for archival candidates

---

## Permission & Credit

### Using Assets
- All Jason photos: Jason owns, free use by firm
- Community photos (if shared): Get permission before posting
- Design mockups: Verify artist permissions
- Third-party images: Never use without rights

### Crediting
- Community contributions: Tag/credit in caption
- Designer/artist work: Credit in caption or comments
- External sources: Always link source

---

## Checklist Before Publishing

- [ ] Asset is high quality (no blurry/poor quality)
- [ ] Asset is on-brand (matches BRANDING_GUIDE.md)
- [ ] Asset is authentic (real moment, not manufactured)
- [ ] Metadata is complete (filename, pillar, platform)
- [ ] Asset is right resolution for platform
- [ ] Caption is ready and approved
- [ ] All elements meet doctrine standards

---

## Troubleshooting

**Asset is missing:** Check `/assets/archived/` or recovery backup

**Asset quality is poor:** Document why and archive (don't post)

**Asset needs editing:** Use [specified tool] and save as new version

**Asset copyright unclear:** Get permission before posting

---

**Status:** System ready. Assets will be organized during Phase 1 as Jason provides content.
