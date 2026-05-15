# .github
Description of SWMMEnablement

# SWMMEnablement

**Enabling and enhancing SWMM for the future and the present.**

I started coding SWMM in 1974 on punch cards at the University of Florida with Wayne Huber. I co-authored the SWMM4 User's Manual in 1988. I designed the .xp and .xpx file formats at XP Software in the 1990s. I coded the RTK/RDII unit hydrograph (rdii.c) during the EPA SWMM5 CRADA at CDM Smith. I spent 18 years at Innovyze as Product Sector Leader for InfoSWMM and InfoSewer.

This organization is where I put the work that should outlive any one company or any one engineer. Open source. Browser-runnable. Free to fork.

## What you'll find here

**Interactive single-file apps.** SWMM5 Runoff Explorer (Cash-Karp RK5 solver with full SCS and Chicago storm libraries). RDII Rosetta Stone (RTK translation across SWMM5, ICM, InfoSWMM, XPSWMM). EPANET↔SWMM5 Comparator (120+ concept pairs across nine mapping categories). HEC-22 Inlet Explorer. ReSWMM CFL Analyzer. The SWMM5 Lego Builder (Minecraft-style browser editor with a JavaScript SWMM5 engine and 21 element types).

**Legacy preservation.** SWMM 4.4H Fortran source. The 1,729 OWA SWMM5 test models. SWMM4 documentation in Markdown.

**SWMM5+ work.** Prototype Fortran 2008 engine fork from CIMM-ORG/SWMM5plus. I chair the SWMM5+ Technical Advisory Committee at CIMM.org.

**Migration toolkits.** InfoSewer→ICM and InfoSWMM→ICM Ruby scripts for the post-ArcMap world.

## Why this exists

ArcMap reached end-of-life in March 2026. SWMM5 is the EPA reference engine but most practitioners learn it through proprietary front-ends. The dynamic wave solver in `dynwave.c` descends from EXTRAN Fortran code written in the 1970s, and almost nobody under 40 has read either. The math hasn't changed. The teaching tools have, or should.

Every app in this org runs in a browser. No install. No license. View source on the conduit you're standing in.

## Where to go from here

- SWMM5.org (1,700+ posts, the long-running blog)
- SWMM2000.com (the older archive)
- @SWMM5 on YouTube (video walkthroughs)
- LinkedIn newsletter (two-article curated bundles)
- X: [@RDickinson](https://twitter.com/RDickinson)
- The Dickinsonre personal account (where smaller experiments live before they graduate here)

## A note on contributions

Fork freely. File issues. If you build something useful with one of these tools, tell me and I'll point at it. If you find a bug in the SWMM5 engine itself, also tell Lew Rossman at EPA, the OWA team, and the SWMM5+ TAC.

The goal is that this work survives me. Star what helps you. That signal tells the next person where to look.

---

*Robert (Bob) Dickinson. Autodesk Water Technologist, soon Autodesk Expert Elite. EWRI Stormwater Modeling Committee. CIMM.org SWMM5+ TAC chair.*
