# BoldSign — Merge PDF Online (SEO-Optimized Landing Page)

Redesigned landing page for [boldsign.com/merge-pdf-online/](https://boldsign.com/merge-pdf-online/) incorporating findings from the SERP Recovery Pilot audit and Reddit backlink strategy.

## Live Preview

Open `index.html` in any browser, or deploy to GitHub Pages:

```
Settings → Pages → Deploy from branch → main / root
```

## Files

```
├── index.html   ← Complete page (self-contained, zero build step, ~55KB)
└── README.md    ← This file
```

---

## Before vs After — Summary

### What was added (from SERP audit)

| # | Change | Audit Priority | Status |
|---|---|---|---|
| 1 | **Comparison table** — BoldSign vs iLovePDF vs Smallpdf vs Adobe vs PDF24 | Fix #1 (High) | ✅ Added |
| 2 | **Use-case sections** — Legal, Medical, Finance, Education | Fix #2 (High) | ✅ Added |
| 3 | **WebApplication JSON-LD** — applicationCategory: UtilityApplication | Fix #3 (Medium) | ✅ Added |
| 4 | **Internal linking** — 9 strategic links to blogs, tools, hub | Fix #5 (High) | ✅ Added |
| 5 | **Direct answer block** — Featured snippet target below H1 | High | ✅ Added |
| 6 | **Key Takeaways box** — Scannable summary | Medium | ✅ Added |
| 7 | **Trust signals surfaced** — "1.5M+ users · 50,000+ businesses" in badge | High | ✅ Added |
| 8 | **SERP competitor phrases in H2s** | Medium | ✅ Added |
| 9 | **Content depth** — ~350 words → ~1,500+ words | High | ✅ Done |
| 10 | **Reddit backlinks** — Page content now supports privacy-angle sharing | Fix #4 (High) | Ready |

### Meta & Schema Changes

| Element | Before (Live) | After (New) |
|---|---|---|
| Title tag | `Merge PDF Files Online – Combine PDFs into One File for Free ` (has trailing nbsp) | `Merge PDF Online \| Free PDF Merger - Easily Combine PDFs` |
| Meta description | Generic tool description | Privacy-first: "Files never leave your device" |
| JSON-LD: WebApplication | ❌ Missing | ✅ Added |
| JSON-LD: HowTo | ✅ Exists | ✅ Refined (added totalTime) |
| JSON-LD: FAQPage | ✅ 10 Qs | ✅ 8 SEO-targeted Qs |
| JSON-LD: BreadcrumbList | 2 levels | 3 levels (added Free Tools hub) |

### Content Structure Changes

| Section | Before | After |
|---|---|---|
| Trust badge | "1.5M users" only | "1.5M+ users · 50,000+ businesses" |
| Subtitle | Generic description | Uses SERP competitor phrase + privacy angle |
| Direct answer block | ❌ Missing | ✅ Featured snippet target |
| How-to H2 | "How to merge PDF files online?" | "How to combine multiple PDF files into one document" |
| Why-use H2 | "Why use our PDF merging tool?" | "Merge PDFs fast and securely — right in your browser" |
| Comparison table | ❌ Missing | ✅ 6-row table, 5 competitors |
| Use cases | ❌ Missing | ✅ 4 cards (Legal, Medical, Finance, Education) |
| Key Takeaways | ❌ Missing | ✅ 5-point summary box |
| Content depth | ~350 words | ~1,500+ words |

### New FAQ Questions (SEO-Targeted)

| Question | Targets |
|---|---|
| "How do I merge PDF files without Adobe Acrobat?" | "merge PDF without Adobe" queries |
| "What makes BoldSign's merger different?" | Commercial investigation intent |
| "Is it safe to merge confidential PDFs online?" | Privacy keyword cluster |
| "How do I put PDF files together?" | SERP competitor natural language |
| "Why choose BoldSign over iLovePDF, Smallpdf, or Adobe?" | Direct competitor comparison queries |

### Internal Links Added

| Anchor Text | Destination | Purpose |
|---|---|---|
| "Learn why browser-based tools are safer" | `/blogs/why-browser-based-pdf-tools-are-safer/` | Privacy differentiator depth |
| "Compare the top free PDF merging tools" | `/blogs/top-5-free-online-pdf-merge-tools/` | Commercial investigation |
| "medical records" | `/blogs/merge-pdf-free-for-medical-professionals/` | Healthcare vertical |
| "Sign your merged PDF electronically" | `/sign-pdf-online/` | Natural next-step |
| "generate a professional signature" | `/online-signature-generator/` | Free tools authority |
| "Explore all our free PDF tools" | `/free-tools/` | Hub page architecture |
| Split / Rotate / Extract cards | Respective tool pages | Topical cluster |
| "Sign your merged PDF electronically" (use cases) | `/sign-pdf-online/` | Conversion path |
| "HIPAA-friendly processing" | `/blogs/merge-pdf-free-for-medical-professionals/` | Healthcare authority |

---

## Reddit Backlink Strategy (from audit)

The page content now supports the privacy angle needed for Reddit engagement:

**Target subreddits:** r/pdf, r/software, r/privacy, r/techsupport, r/productivity, r/InternetIsBeautiful, r/sysadmin, r/freelance, r/smallbusiness, r/Teachers

**Core angle:** "Browser-based — your files never leave your device"

**90-day projections:**
- 45-60 Reddit threads engaged
- 500-1,000 referral visits
- 30-40 backlinks (DA 91)

See the full SERP Recovery Pilot audit document for thread templates and engagement rules.

---

## Technical Notes

- Zero dependencies — single HTML file with inline CSS
- Google Fonts — Poppins (headings) + Inter (body) via CDN
- Responsive — 3 breakpoints (mobile 767px, tablet 1024px, desktop)
- Accessible — semantic HTML, ARIA labels, keyboard-navigable FAQ
- All links point to boldsign.com production URLs
- ~55KB total page weight
