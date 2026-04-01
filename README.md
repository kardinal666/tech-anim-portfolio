# Technical Animator — Year 1 Study Roadmap
> Goal: Land a Technical Animator role at a AAA or senior-level studio within 12 months.
> Target roles: Kalypso Media, Cloud Chamber (2K), Certain Affinity, AGBO
> Hours/week: 15–20 hrs | **Start date: April 1, 2026** | **End date: March 31, 2027**

---

## Progress snapshot

| Phase | Weeks | Dates | Status | Completion |
|-------|-------|-------|--------|------------|
| Phase 1 — UE5 core systems | 1–12 | Apr 1 – Jun 23, 2026 | 🔄 In progress | 0 / 12 weeks |
| Phase 2 — Pipeline & motion matching | 13–24 | Jun 24 – Sep 15, 2026 | 🔲 Not started | 0 / 12 weeks |
| Phase 3 — Advanced systems & mocap | 25–40 | Sep 16 – Jan 5, 2027 | 🔲 Not started | 0 / 16 weeks |
| Phase 4 — Leadership & demo reel | 41–52 | Jan 6 – Mar 31, 2027 | 🔲 Not started | 0 / 12 weeks |

**Status key:** 🔲 Not started &nbsp; 🔄 In progress &nbsp; ✅ Done &nbsp; ⏸ Paused

---

## This week — Week 1 (Apr 1–7, 2026)

**Focus:** UE5 setup & Skeleton asset

| Task | Done |
|------|------|
| Install / verify UE5 latest version | 🔲 |
| Create a new Third Person template project | 🔲 |
| Open the Mannequin Skeleton asset — explore bone hierarchy | 🔲 |
| Open the default ABP (ABP_Manny) — trace the AnimGraph | 🔲 |
| Open the default ABP — trace the EventGraph | 🔲 |
| Write 5 questions you don't understand yet in `docs/breakdowns/week01.md` | 🔲 |

---

## Portfolio checklist

- [ ] **Locomotion state machine** — walk / run / jump / crouch with Motion Matching
- [ ] **Character rig breakdown** — biped with IK/FK, clean skinning, facial blend shapes
- [ ] **Python tool demo** — Maya pipeline or rigging tool with UI (link to repo below)
- [ ] **Non-biped rig** — quadruped or creature with custom spine (required by AGBO)
- [ ] **Mocap cleanup shot** — raw vs cleaned, retargeted to custom skeleton

---

## Repo structure

```
tech-anim-portfolio/
├── README.md                        ← you are here
├── WEEK_LOG.md                      ← update every Friday
├── ue5-projects/
│   ├── phase1-locomotion/           ← ABP, blend spaces, state machine, Control Rig
│   ├── phase2-motion-matching/      ← MM database, IK Rig, Cloth, Retargeter
│   ├── phase3-advanced-systems/     ← Mocap, Metahuman, weapon BP, quad, sharing
│   └── phase4-demo-reel/            ← Live Link, Niagara, final reel assets
├── maya-rigs/
│   ├── biped-rig-v1/                ← joint hierarchy, weights, FBX export
│   └── quadruped-rig-v1/           ← quad spine, limbs, weights, FBX export
├── python-tools/
│   ├── joint_orient_tool.py         ← wk 10
│   ├── batch_fbx_exporter.py        ← wk 22
│   ├── naming_validator.py          ← wk 23
│   └── skin_weight_exporter.py      ← wk 11
└── docs/
    ├── breakdowns/                  ← one .md per major checkpoint
    └── resources.md                 ← all courses and references
```

---

## Resources

### UE5 animation
- [Unreal Online Learning — Animation](https://dev.epicgames.com/community/learning)
- [UE5 Animation Blueprint docs](https://docs.unrealengine.com/5.0/en-US/animation-blueprints-in-unreal-engine/)
- [UE5 Control Rig docs](https://docs.unrealengine.com/5.0/en-US/control-rig-in-unreal-engine/)
- [UE5 Motion Matching sample project](https://www.unrealengine.com/marketplace/en-US/product/game-animation-sample)
- [UE5 IK Rig & Retargeter docs](https://docs.unrealengine.com/5.0/en-US/ik-rig-in-unreal-engine/)

### Maya rigging
- [Rigging Dojo](https://www.riggingdojo.com/)
- [CGCircuit — rigging courses](https://www.cgcircuit.com/)
- [Tech-Anim.com](https://tech-anim.com/)
- [Cult of Rig (YouTube)](https://www.youtube.com/c/CultOfRig)

### Python for Maya
- [Maya Python API docs (Autodesk)](https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=Maya_SDK_MERGED_MayaPythonAPI_html)
- [Python for Maya: Artist Friendly Programming](https://www.wiley.com/)

### Animation theory & GDC
- [GDC Vault — free animation talks](https://gdcvault.com/free)
- [The Animator's Survival Kit — Richard Williams](https://www.amazon.com/Animators-Survival-Kit-Richard-Williams/dp/0571202284)

### Free mocap data
- [Mixamo (Adobe)](https://www.mixamo.com/)
- [CMU Motion Capture Database](http://mocap.cs.cmu.edu/)
- [Rokoko Motion Library](https://www.rokoko.com/motion-library)

---

## Target job tracker

| Studio | Role | Req. exp | Target | Status |
|--------|------|----------|--------|--------|
| Kalypso Media (Claymore) | Technical Animator | 3+ yrs | Wk 52 — Mar 2027 | 🎯 Primary |
| Cloud Chamber (2K) | Senior Technical Animator | AAA preferred | Wk 52 — Mar 2027 | 🎯 Stretch |
| Certain Affinity | Senior Advanced Technical Animator | 8+ yrs | Year 2 | 🔲 Long-term |
| AGBO | Technical Animator | 10+ yrs | Year 2 | 🔲 Long-term |

---

*Last updated: April 1, 2026*
*Total hours logged: 0*
