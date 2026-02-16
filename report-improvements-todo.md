# SEO Impact Report — Improvement Todo List

**Created:** January 7, 2026  
**Status:** Planning  
**Report:** `seo-impact-report.html`

---

## Priority: High (Before April Launch)

### 1. Risk Assessment Matrix
- [ ] Create risk matrix with probability/impact scores
- [ ] Include mitigation strategies for each risk
- [ ] Add visual risk cards to Executive Summary section
- **Location:** After "Key Findings" section

| Risk | Probability | Impact | Mitigation |
|------|-------------|--------|------------|
| Organic traffic drop post-launch | Medium | High | 301 redirects + 90-day monitoring |
| MPS content not indexed in time | High | Critical | Publish by March 2026 |
| Competitor captures "mps degree" first | Medium | Medium | First-mover content priority |
| DPS positioning unclear to users | Medium | Medium | "DPS vs PhD" comparison content |
| Internal linking gaps | Low | Medium | Linking audit pre-launch |

---

### 2. RACI Responsibility Matrix
- [ ] Define ownership for each workstream
- [ ] Add to Execution (Part 4) section
- **Location:** Before Runbook section

| Task | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| Write 10 DPS/MPS blog pieces | Content Team | Marketing Lead | SEO Team | Stakeholders |
| Keyword targeting & optimization | SEO Team | SEO Lead | Content Team | Marketing |
| Schema markup implementation | Dev Team | Tech Lead | SEO Team | Content |
| Redirect setup (if needed) | Dev Team | Tech Lead | SEO Team | Marketing |
| Performance monitoring | SEO Team | SEO Lead | Analytics | All |
| Final content approval | Marketing Lead | VP Marketing | Legal | All |

---

### 3. Success Metrics with Specific Targets
- [ ] Add quantified KPIs to Decisions section
- [ ] Create monitoring dashboard spec
- **Location:** Update existing Success Criteria

| Metric | Current Baseline | Target | Timeline |
|--------|------------------|--------|----------|
| "mps degree" ranking | Not ranking | Page 1 (top 10) | 90 days post-publish |
| "doctorate in organizational leadership" | Position 15 | Position 5-8 | 120 days |
| DPS/MPS blog combined traffic | 0 | 1,000 sessions/month | July 2026 |
| Overall organic traffic | 1.62M YTD | No decline (-0% to +5%) | 90 days post-launch |
| Conversion rate on new pages | N/A | Match site average (1.6%) | 60 days post-launch |
| Content indexing | N/A | 100% indexed | 14 days post-publish |

---

### 4. Visual Timeline / Gantt Chart
- [ ] Create visual timeline graphic
- [ ] Update Runbook phases with new dates
- [ ] Add critical path indicators
- **Location:** Runbook section

```
Timeline: Feb 2026 — July 2026

Feb 2026 ━━━━━━━━━ Mar 2026 ━━━━━━━━━ Apr 2026 ━━━━━━━━━ May-Jul 2026
    │                   │                   │                   │
    └─Write 10 blogs    └─Publish & Index   └─DPS/MPS LAUNCH    └─Monitor & Optimize
    └─Create hub pages  └─Internal linking  └─Go live           └─Expand content
    └─Schema prep       └─Final QA          └─Daily monitoring  └─Weekly reporting
```

**Key Milestones:**
- **Feb 15:** All 10 blog drafts complete
- **Mar 1:** All content published
- **Mar 15:** Confirm indexing in GSC
- **Apr 1:** DPS & MPS program pages launch
- **Jul 1:** 90-day post-launch review

---

### 5. FAQ Content Bank
- [ ] Create ready-to-use FAQ content for schema markup
- [ ] Organize by program type (DPS, MPS)
- **Location:** New section after Templates

#### DPS FAQs (for schema)
1. **What is a Doctor of Professional Studies (DPS)?**
   > A Doctor of Professional Studies is an applied doctoral degree designed for working professionals who want to advance their careers through advanced study without pursuing traditional academic research.

2. **How is a DPS different from a PhD?**
   > A PhD focuses on original theoretical research and academic careers, while a DPS emphasizes applied research and practical leadership skills for professional advancement.

3. **What is an Applied Doctoral Project?**
   > An Applied Doctoral Project (ADP) is a practice-based capstone that solves a real organizational problem, replacing the traditional dissertation.

4. **Can I work full-time while earning a DPS?**
   > Yes, DPS programs are designed for working professionals with flexible online formats and part-time options.

5. **What careers can I pursue with a DPS in Organizational Leadership?**
   > Graduates pursue roles such as Chief Learning Officer, VP of Organizational Development, Executive Coach, and Senior Consultant.

#### MPS FAQs (for schema)
1. **What is a Master of Professional Studies (MPS)?**
   > A Master of Professional Studies is a graduate degree focused on applied, career-ready skills rather than academic research.

2. **Is an MPS the same as an MBA?**
   > No. An MPS focuses on specialized professional skills (like leadership or technology), while an MBA covers broad business management topics.

3. **Is an MPS degree worth it?**
   > Yes, for professionals seeking career advancement in specialized fields without the research focus of traditional master's degrees.

4. **What can I do with an MPS in Leadership?**
   > Graduates pursue roles in management, HR leadership, organizational consulting, and executive positions.

5. **How long does an MPS take to complete?**
   > Most MPS programs take 1-2 years to complete, depending on enrollment status.

---

## Priority: Medium (Post-Launch)

### 6. DPS/MPS Competitor Analysis
- [ ] Research universities offering DPS programs
- [ ] Identify who ranks for "professional doctorate" terms
- [ ] Analyze competitor content strategies
- **Location:** Add to Competitive Intelligence section

**Research needed:**
- [ ] University of Pennsylvania (DPS programs?)
- [ ] Creighton University (professional doctorate)
- [ ] Vanderbilt (professional doctorates)
- [ ] Search "doctor of professional studies" in GSC competitors
- [ ] Analyze top 10 ranking pages for target keywords

---

### 7. Rollback / Contingency Plan
- [ ] Define rollback triggers
- [ ] Document reversal steps
- [ ] Assign decision authority
- **Location:** After Runbook section

**Rollback Triggers:**
- Organic traffic drops >20% for 14+ consecutive days
- Conversion rate drops >30% on affected pages
- Critical indexing issues not resolved within 7 days
- Major redirect chain/loop issues

**Contingency Actions:**
1. Pause further changes immediately
2. Notify stakeholders within 24 hours
3. Revert to previous page versions (if URL changes made)
4. Implement emergency redirects
5. Conduct root cause analysis

---

### 8. Technical SEO Checklist
- [ ] Create detailed technical requirements
- [ ] Add to Runbook as pre-launch checklist
- **Location:** Phase 1 of Runbook

#### Pre-Launch Technical Checklist
- [ ] FAQ schema implemented on all hub pages
- [ ] Organization schema on program pages
- [ ] Canonical tags (self-referencing) verified
- [ ] XML sitemap updated with new pages
- [ ] Robots.txt allows crawling
- [ ] Core Web Vitals passing (LCP < 2.5s, CLS < 0.1)
- [ ] Mobile-friendly test passing
- [ ] Internal links audited and updated
- [ ] Old page references updated (if URLs change)
- [ ] 301 redirects tested (if applicable)

---

### 9. Internal Linking Strategy
- [ ] Create site architecture diagram
- [ ] Define linking rules
- [ ] Document hub-and-spoke model
- **Location:** New subsection in Content Strategy

**Linking Architecture:**
```
Homepage
├── /online-degrees/
│   ├── /doctoral/ (existing)
│   │   └── DPS Program Page (new)
│   │       └── Links to: DPS Hub, DPS vs PhD, Career content
│   └── /masters/ (existing)
│       └── MPS Program Page (new)
│           └── Links to: MPS Hub, MPS vs MBA, Career content
└── /blog/
    ├── DPS Blog Posts (5 pieces)
    │   └── All link to: DPS Hub + DPS Program Page
    └── MPS Blog Posts (5 pieces)
        └── All link to: MPS Hub + MPS Program Page
```

**Linking Rules:**
1. Every blog post links to relevant hub page (1-2 links)
2. Every blog post has CTA to program page
3. Hub pages link to all related blog content
4. Comparison pages link to both options
5. No orphan pages (every page has ≥3 internal links)

---

### 10. Enhanced Content Brief Templates
- [ ] Add word count targets
- [ ] Include detailed outlines
- [ ] Add reference links
- **Location:** Update existing Templates section

**Template Enhancement Spec:**
| Element | Requirement |
|---------|-------------|
| Word count | 1,500-2,000 words (hub pages), 1,000-1,500 (blog) |
| H1 | Include primary keyword |
| H2s | 4-6 sections minimum |
| FAQ section | 5-8 questions with schema |
| Comparison table | Required for "vs" content |
| CTA | 2-3 per page (above fold, mid-page, footer) |
| Internal links | 3-5 per page |
| External citations | 2-3 authoritative sources |
| Meta description | 150-160 characters, include keyword |

---

## Priority: Low (Ongoing Maintenance)

### 11. Monitoring Dashboard Specification
- [ ] Define tracking frequency
- [ ] Set up alerts
- [ ] Create reporting template
- **Location:** New section in Execution

**Monitoring Schedule:**
| Timeframe | Metrics | Tool | Owner |
|-----------|---------|------|-------|
| Daily (first 14 days) | Index status, 404s, crawl errors | GSC | SEO Team |
| Daily (first 14 days) | Traffic to new pages | GA4 | SEO Team |
| Weekly | Keyword rankings (target 15) | Rank tracker | SEO Team |
| Weekly | Conversion rates | GA4 | Marketing |
| Monthly | Content performance report | GA4 + GSC | SEO Lead |
| Quarterly | Full SEO audit | All tools | SEO Team |

**Alert Thresholds:**
- 🔴 Critical: >20% traffic drop, indexing failure
- 🟡 Warning: >10% traffic drop, ranking drops >5 positions
- 🟢 Normal: Fluctuations within ±10%

---

### 12. Date Freshness & Version Control
- [ ] Add "Last updated" timestamps to data sections
- [ ] Create version history log
- **Location:** Throughout report + footer

**Section Timestamps:**
- GSC Data: "As of December 10, 2025"
- GA4 Data: "As of December 12, 2025"
- Keywords Everywhere: "Pulled January 7, 2026"
- Competitor Research: "Reviewed January 2026"

---

## Implementation Order

### Phase 1: Pre-Content Creation (Feb 2026)
1. ✅ Update timeline to Feb-Mar start
2. [ ] Add Risk Assessment Matrix
3. [ ] Add RACI table
4. [ ] Add quantified KPIs
5. [ ] Create FAQ Content Bank

### Phase 2: Content Production (Feb-Mar 2026)
6. [ ] Add Technical SEO Checklist
7. [ ] Add Internal Linking Strategy
8. [ ] Enhance Content Brief Templates

### Phase 3: Launch Prep (Mar 2026)
9. [ ] Add Rollback Plan
10. [ ] Add Monitoring Dashboard Spec

### Phase 4: Post-Launch (Apr+ 2026)
11. [ ] Add DPS/MPS Competitor Analysis
12. [ ] Add Date Freshness tracking

---

## Notes

- All additions should match existing report styling
- Use same color coding (red=priority, green=success, purple=execute)
- Maintain mobile responsiveness
- Test print/PDF output after major changes

---

*Last updated: January 7, 2026*
