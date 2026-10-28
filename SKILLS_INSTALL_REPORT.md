# Skills Install Report

Target directory: `/projects/sandbox/.kiro/skills/`
(The originally-specified global target `/root/.kiro/skills` is on a read-only filesystem; per approval the install was redirected to the writable workspace `.kiro` directory.)

Method: each source repo was cloned with `git clone --depth 1 https://github.com/<owner>/<repo>.git` into `/projects/sandbox/_tmp_clones/`, the relevant SKILL.md folder was copied into the target, LICENSE files were preserved where present, and `NO_LICENSE.txt` was dropped for entries whose source repo had no license. Temp clones and the two `_idx_*` index repos were deleted during cleanup.

**Total skill folders installed: 57**

---

## From `neverbiasu/awesome-research-skills`

| # | Source repo (+ subpath) | Destination folder | License | Status |
|---|--------------------------|--------------------|---------|--------|
| 1 | nanoAgentTeam/research-claw `config/.skills/figure-drawing` | `research-claw-figure-drawing` | MIT | INSTALLED |
| 2 | yiyanli123/biorender-mechanism-figures-skill `biorender-mechanism-figures` | `biorender-mechanism-figures` | unverified | INSTALLED (see note A) |
| 3 | Deepshare-Official/CCF-Figure (whole repo) | `CCF-Figure` | MIT | INSTALLED |
| 4 | Agents365-ai/drawio-skill `skills/drawio-skill` | `drawio-skill` | MIT | INSTALLED |
| 5 | HKUSTDial/Supervisor-Skills `skills/drawio-reconstruction` | `drawio-reconstruction` | unverified | INSTALLED |
| 6 | wanshuiyin/Auto-claude-code-research-in-sleep `skills/mermaid-diagram` | `mermaid-diagram` | unverified | INSTALLED |
| 7 | opentikz/opentikz `skills/using-opentikz` | `using-opentikz` | unverified (repo ships LICENSE-CODE + LICENSE-CONTENT, both preserved) | INSTALLED |
| 8 | dwzhu-pku/PaperBanana `skill` | `paperbanana-dwzhu` | MIT-0 | INSTALLED |
| 9 | wentorai/research-plugins `skills/tools/diagram/scientific-illustration-guide` | `scientific-illustration-guide` | MIT | INSTALLED |
| 10 | K-Dense-AI/scientific-agent-skills `skills/scientific-schematics` | `scientific-schematics` | MIT | INSTALLED |
| 11 | HeshamFS/materials-simulation-skills `skills/ontology/ontology-explorer` | `materials-ontology-explorer` | Apache-2.0 | INSTALLED (single copy; same repo as entry 24 suite) |
| 12 | richard-kim-79/archora-skills `skills/figure` | `archora-figure` | MIT (listed) | INSTALLED (see note A) |
| 13 | ChenLiu-1996/figures4papers `scientific-figure-making` | `scientific-figure-making` | unverified | INSTALLED |
| 14 | Yuan1z0825/nature-skills `skills/nature-figure` | `nature-figure` | Apache-2.0 | INSTALLED |
| 15 | boom5426/nature-paper-skills `skills/core/figure-planner` | `nature-paper-figure-planner` | MIT | INSTALLED |
| 16 | Ar9av/PaperOrchestra `skills/plotting-agent` | `paperorchestra-plotting-agent` | unverified | INSTALLED |
| 17 | caylent/tufte-data-viz (whole repo) | `tufte-data-viz` | MIT | INSTALLED (once; appeared on both lists) |
| 18 | yaotingsun/academic-publishing-skills `plugins/research-disseminator/skills/research-disseminator` | `research-disseminator` | Apache-2.0 | INSTALLED |

## From `O0000-code/awesome-academic-skills`

| # | Source repo (+ subpath) | Destination folder | License | Status |
|---|--------------------------|--------------------|---------|--------|
| 19 | Dsadd4/AgentFigureGallery (whole repo; SKILL.md at `skills/agent-figure-gallery`) | `AgentFigureGallery` | MIT | INSTALLED |
| 20 | jaxonjp/beamer-skill (whole repo; SKILL.md at `beamer/`) | `beamer-skill-jaxonjp` | MIT | INSTALLED |
| 21 | Noi1r/beamer-skill (whole repo; SKILL.md at `beamer/`) | `beamer-skill-Noi1r` | MIT | INSTALLED |
| 22 | heyu-233/engineering-figure-agent (whole repo, root SKILL.md) | `engineering-figure-agent` | MIT | INSTALLED |
| 23 | huiyuli-2000/gen-pseudocode-skill (whole repo, root SKILL.md) | `gen-pseudocode-skill` | MIT | INSTALLED |
| 24 | heshamfs/materials-simulation-skills (whole repo = SUITE) | 23 sub-skill folders (see suite table below) + `materials-ontology-explorer` from entry 11 | Apache-2.0 | INSTALLED (suite) |
| 25 | mapika/nice-figures (whole repo; SKILL.md at `plugins/nice-figures/skills/nice-figures`) | `nice-figures` | MIT | INSTALLED |
| 26 | zsyggg/paper-craft-skills (whole repo, NO LICENSE; no root SKILL.md — 3 sub-skills) | `paper-analyzer`, `paper-comic`, `paper-deck` | No License | INSTALLED-NO-LICENSE (see note B) |
| 27 | freemty/paper-style (whole repo, root SKILL.md) | `paper-style` | MIT | INSTALLED |
| 28 | plutolei/paperbanana-skill (whole repo, root SKILL.md) | `paperbanana-skill-plutolei` | MIT | INSTALLED (kept separate from entry 8) |
| 29 | ydh0411/physics-lab-report-skill (whole repo, root SKILL.md) | `physics-lab-report-skill` | MIT | INSTALLED |
| 30 | c-narcissus/research-paper-figure-skill-factory (whole repo, root SKILL.md) | `research-paper-figure-skill-factory` | MIT-0 | INSTALLED |
| 31 | chingswy/skill-research-figure (whole repo, NO LICENSE; SKILL.md under `.claude/skills/research-figure`) | `skill-research-figure` | No License | INSTALLED-NO-LICENSE (best-match folder `research-figure`) |
| 32 | youngfujun/stata-graphics-skill (whole repo, NO LICENSE, root SKILL.md) | `stata-graphics-skill` | No License | INSTALLED-NO-LICENSE |
| 33 | 0xe1337/thesis-figure-skill (whole repo; SKILL.md at `skills/thesis-figure-skill`) | `thesis-figure-skill` | MIT | INSTALLED |

---

## Entry 24 — `materials-simulation-skills` suite sub-skills (Apache-2.0)

Each sub-skill installed as its own folder. The suite contains 24 `SKILL.md` folders; `ontology-explorer` was installed once as `materials-ontology-explorer` (entry 11), leaving 23 additional folders here. No name collisions occurred, so no `msim-` prefix was needed.

1. `convergence-study`
2. `differentiation-schemes`
3. `linear-solvers`
4. `mesh-generation`
5. `nonlinear-solvers`
6. `numerical-integration`
7. `numerical-stability`
8. `time-stepping`
9. `fair-simulation-packager`
10. `hpc-runtime-doctor`
11. `slurm-job-script-generator`
12. `skill-evaluator`
13. `ontology-mapper`
14. `ontology-validator`
15. `simulation-failure-triage`
16. `md-analysis-planner`
17. `parameter-optimization`
18. `performance-profiling`
19. `post-processing`
20. `simulation-orchestrator`
21. `simulation-validator`
22. `workflow-engine-mapper`
23. `benchmark-and-mms-planner`

Plus `materials-ontology-explorer` (= the suite's `ontology/ontology-explorer`, counted under entry 11) = 24 suite folders total.

---

## Notes

- **Note A — license discrepancy:** The authoritative list labeled entry 2 (biorender-mechanism-figures) "unverified" and entry 12 (archora-skills/figure) "MIT", but the cloned source repos `yiyanli123/biorender-mechanism-figures-skill` and `richard-kim-79/archora-skills` contain **no LICENSE file anywhere** in the repo. These skills were still installed (user approved installing everything), but no license text could be preserved because none exists upstream. They were not flagged as explicit "No License" entries in the list, so no `NO_LICENSE.txt` was added; this note records the finding.
- **Note B — paper-craft-skills:** This whole-repo entry has no root `SKILL.md`; it is a collection of three skills (`paper-analyzer`, `paper-comic`, `paper-deck`). All three were installed, each with a `NO_LICENSE.txt` naming `zsyggg/paper-craft-skills` as the source.
- **No-license notices added:** `stata-graphics-skill`, `skill-research-figure`, `paper-analyzer`, `paper-comic`, `paper-deck` each contain a `NO_LICENSE.txt`.
- **FAILED entries:** none. Every authoritative entry yielded at least one installed skill folder.
- **tufte-data-viz** appeared on both lists but from the same repo `caylent/tufte-data-viz`; installed exactly once.
