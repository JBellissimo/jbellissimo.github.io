# Jess Bellissimo - Personal Website Context

## Overview
Personal website and portfolio for Jess Bellissimo (jessbellissimo.com / jbellissimo.github.io)

**Current transition:** Former COO/CEO → Technical operator building civic tech projects

**Focus:** Building efficiencies for citizens and businesses
- Geographic scope: Huntington, NY → NYC → New York State → US
- Current brand: "GreenLights Civic Tech"

## Projects - GreenLights Civic Tech

### 1. GreenLights Civic Tech Portfolio
**URL:** https://greenlights-civic-te-n82v.bolt.host/
**Status:** Live
**Description:** Portfolio landing page showcasing all civic tech projects
**Tech:** Bolt.new prototype
**Brand:** Amber (#F5A623) + Teal (#4A90A4) color scheme, "Making NYC Transparent" tagline

### 2. GreenLight NYC - Permit Transparency
**URL:** https://open-doors-wait-tax-md08.bolt.host
**Status:** Live prototype
**Description:** NYC building permit transparency tool. Shows ALT-2 permit processing to expose the "wait tax" that costs small businesses.
**Originally:** "Open Doors" (rebranded to GreenLight NYC)
**Tech:** Bolt.new
**Key learning:** Initial hypothesis was wrong - most permits process quickly (86%). Only 14% experience severe delays (~7K/year vs. expected 50K)

### 3. Beacon Pulse - Block-by-Block Transparency
**URL:** https://beacon-pulse-nyc-tra-74m4.bolt.host
**Status:** Live prototype (visualizations working, interactions not yet wired)
**Description:** Hyper-local transparency map showing which NYC blocks get city services fast and which are ignored. 550+ blocks mapped with 311, crime, air quality data.
**Tech:** Bolt.new, Leaflet.js maps
**Differentiator:** Block-level (not neighborhood-level) granularity
**Vision:** Phase 1: Public data → Phase 2: Community organizing → Phase 3: Sensor network → Phase 4: Revenue model

### 4. Democracy Scorecard - Congressional Stock Trading
**URL:** https://democracy-scorecard.streamlit.app/
**Status:** Live
**Description:** Scores members of Congress on corruption risk based on stock trading activity
**Tech:** Streamlit, Python

## Site Structure & Goals

### Current Issues (Priority)
1. **Broken links:** /start/, /projects/, /writing/, /about/, /contact/ don't exist
2. **Navigation mismatch:** Left sidebar ≠ Footer links
3. **Missing Projects section:** Need to showcase civic tech work

### Desired Navigation Structure
**Both sidebar and footer should have:**
- Home
- Projects (new page needed)
- Blog (exists at /blog/)
- About (new page needed)
- Contact (new section needed)

### Content Priorities
1. **Projects page:** Showcase 4 GreenLights projects with descriptions, links, tech stack
2. **About page:** Journey from operator to technical, focus on civic efficiency
3. **Writing/Blog:** Exists but needs integration with main nav
4. **Homepage:** Update to reflect current focus (civic tech projects)

## Tech Stack
- **Hosting:** GitHub Pages (jbellissimo.github.io)
- **Domain:** jessbellissimo.com (via CNAME)
- **Site generator:** Jekyll (blog posts in _posts/)
- **Styling:** Custom CSS in /stylesheets/
- **Projects:** Hosted on Bolt.new and Streamlit

## Development Approach
- Keep it simple - static HTML/CSS (no complex frameworks)
- Mobile-responsive
- Clean, professional design
- Easy to update/maintain
- Focus: Portfolio presentation > complex functionality

## Writing Goals
- Start documenting project learnings
- Create case studies for each civic tech project
- Build thought leadership in civic tech space
- Template: Problem → Solution → What I Built → What I Learned → What's Next

## Files to Preserve
- **Blog posts:** Keep all _posts/*.md files (existing content)
- **CNAME:** jessbellissimo.com domain config
- **Stylesheets:** Existing CSS can be updated but don't delete

## Files to Update/Create
- **index.html:** Update homepage to reflect civic tech focus
- **Create:** projects.html (showcase GreenLights work)
- **Create:** about.html (personal journey/bio)
- **Update:** Navigation in all pages to be consistent
- **Optional:** Create writing/ landing page or redirect to /blog/

## Notes for Future Sessions
- All civic tech projects are Bolt.new prototypes (not production apps)
- Focus is on building portfolio to demonstrate capabilities
- Long-term: May move projects to custom domains
- GitHub workflow: Make changes locally → commit → push to deploy

---

Last updated: January 2026
