# 85th-and-15th-Left-Turn-Lane-Feasibility
15th Ave NW & NW 85th St, Seattle, WA

An independent geometry check of whether the shared through/left lane on eastbound (EB) and westbound (WB) NW 85th St could become a left-turn-only lane beside one through/right lane, within the existing curbs.

**Independent personal academic project.** Not an engineering plan, not for construction, and no agency involvement. There are no traffic volumes, no survey, no signal analysis and no agency review.

## Result
Needed width is 11 ft (left-turn lane) + 11 ft (through/right lane) = 22 ft. A 10 + 11 = 21 ft case is also shown. Approaches are named by traffic direction, and widths run from curb face to double yellow.

| Approach | Existing curb to double yellow | Short at 22 ft | Short at 21 ft | Curb shift drawn |
|---|---|---|---|---|
| EB 85th | 19.65 ft | 2.34 ft | 1.34 ft | 2.4 ft |
| WB 85th | 19.80 ft | 2.20 ft | 1.20 ft | 2.2 ft |

Both approaches are short by more than the aerial imagery's accuracy of about 0.5 ft, in both cases. The proposed sheet moves the curbs outward into the planting strips (3.4 ft EB, 9.6 ft WB), which leaves about 1.0 ft EB and about 7.4 ft WB. Two EB utility poles would sit about 1.6 ft behind the new curb, so relocation is likely.

## Files
- `plans/85th-15th_existing_conditions`: Sheet 1 (existing conditions) 1" = 20', ANSI D
- `85th-15th_proposed_conditions` Sheet 2 (proposed), 1" = 20', ANSI D
- `memo/85th-15th_memo.pdf`: one-page memo with findings, constraints, options and limits
- `data/signs.csv`, `data/access_points.csv`: keys for the S and A labels on the sheets

## Method
Existing conditions were traced on Nov 14, 2026 from aerial imagery using QGIS and AutoCAD. Lane use was observed in the field on Nov 16, 2026, and bus stops and routes on Nov 22, 2026 from a passing vehicle. Proposed curbs are nominal offsets of the traced curbs.

## Limits
- Measurements come from aerial imagery, accurate to about 0.5 ft, and are not surveyed. A survey is needed before any firm claim.
- The 100 ft left-turn pocket is an assumed minimum with no volume analysis.
- The upstream transition, ramps, crosswalk ends, entrance aprons, signs and poles are not designed.

## Sources
- SDOT Streets Illustrated, Roadway Width (last updated Jan 6, 2017; read Nov 22, 2026)
- SDOT Frequent Transit Network page (checked Nov 21, 2026)
- WSDOT Design Manual M 22-01.23, Chapter 1310 (Sept 2024), used as a reference only
- SDOT Route 40 Transit-Plus Multimodal Corridor documents
- King County Metro schedules and maps

## Not included
The AutoCAD file is not published because it references third-party aerial imagery. The sheets show linework only.
