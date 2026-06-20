# Power Analysis

*Created by Megan Spielberg, last modified on May 25, 2026*

## 📝 Introduction

This document presents a comprehensive power analysis conducted to
determine the required sample size for an experimental study comparing
game-based learning (GBL) against traditional instructional methods. The
analysis draws on evidence from eleven peer-reviewed studies and follows
two complementary power analysis approaches: one targeting
within-condition learning gains and one targeting between-condition
differences in effectiveness.

Both analyses were conducted using G\*Power with a one-way ANOVA (fixed
effects, omnibus) design, four conditions, a significance level of α =
0.05, and a desired statistical power of 0.80, consistent with standards
in experimental educational research.

## 📚 Review of GBL Studies

Eleven studies were reviewed to ground the power analysis in empirical
evidence. The studies span multiple disciplines and compare GBL to
various traditional or active learning methods. A summary is presented
in Table 1.

| Source | Topic | Sample (N) | Primary Finding | Sig. (p) | Effect Size |
|----|----|----|----|----|----|
| Dardeer et al., 2025 | Dental Trauma | 88 | GBL = Traditional Lecture | p = 0.393 | Not reported |
| Gudadappanavar et al., 2021 | Pharmacology | 98 | GBL \> Tutorials (+21.1%) | p \< 0.001 | Not reported |
| Wachdani & Thohir, 2022 | Mathematics | 29 | Significant improvement | p \< 0.05 | Not reported |
| Ciptadi et al., 2025 | Volleyball | 36 | GBL = Direct Instruction (interaction effect for low arm strength) | p = 0.553 | p = 0.002 (interaction) |
| Shyamala et al., 2025 | Microbiology | 30 | GBL = PBL | p = 0.3 | Not reported |
| Gordillo et al., 2022 | Software Eng. | 180 | GBL \> Video-based learning | p = 0.04 | r = 0.13 (between); r = 0.54 (within-GBL) |
| López-Fernández et al., 2021 | Computer Sci. | 124 | GBL = Traditional (knowledge) | p \> 0.05 | d ≥ 1.4 (within) |
| Fernandez Galeote et al., 2023 | Climate Change | 105 | GBL = Text (all conditions improved) | p = 0.522 | d = 0.95–1.0 (within) |
| Eckardt & Robra-Bissantz, 2018 | Info Literacy | 44 | GBL = Face-to-Face (knowledge) GBL \> F2F (engagement) | p = 0.729 / p = 0.034 | r = 0.32–0.48 (engagement) |
| Rezaei et al., 2025 | Self-Efficacy | 30 | GBL \> Traditional (self-efficacy) | p \< 0.001 | η² = 0.80 (large) |
| Rondon et al., 2013 | Knowledge Ret. | 25 | GBL = Traditional (short-term) Traditional \> GBL (long-term) | p = 0.176 / p = 0.021 | Not reported |

*Table 1. Summary of reviewed GBL studies with key results and effect
sizes.*

### 🔍 Key Findings Across Studies

**The literature yields several consistent patterns:**

#### 💡 Learning Outcomes (Knowledge Acquisition)

- Between-group comparisons are mostly non-significant (p \> 0.05), with
  one exception (Gordillo et al., 2022; p = 0.04, r = 0.13).

- Within-group learning gains are consistently large (Cohen’s d ≥
  0.95–1.4), indicating that GBL does teach effectively.

- Long-term retention may favour traditional methods; one study found
  only the traditional group maintained gains after six months (Rondon
  et al., 2013).

#### ✨ Engagement and Motivation

- GBL consistently outperforms traditional methods on motivation, fun,
  attitude, and satisfaction, with medium to large effect sizes (r =
  0.32–0.48; d = 0.8–1.4).

- Self-efficacy showed a very large effect favouring GBL (η² = 0.80;
  Rezaei et al., 2025).

#### ⚙️ Moderating Factors

- Learner characteristics matter: GBL was more effective for students
  with lower arm strength in a volleyball study, suggesting
  aptitude-treatment interactions (Ciptadi et al., 2025).

- Subject domain influences results: pharmacology showed a clear GBL
  advantage (+21.1% gain); dental trauma and microbiology did not.

Overall, the evidence supports GBL as consistently effective for
learning and engagement, though it is not universally superior. Effect
sizes for between-group knowledge differences are small to negligible,
while within-group gains are large.

## 📈 Power Analysis

Two separate power analyses were conducted to address distinct research
questions. The first targets within-condition improvement (did
participants learn?), and the second targets between-condition
differences (did one condition produce greater learning than another?).

### ↔️ Within-Condition Analysis

This analysis determines the minimum sample needed to detect significant
pre-test to post-test improvement within each condition. Based on prior
literature, a large effect size (f = 0.40) is appropriate, reflecting
the consistently large within-group gains observed across studies.

Parameters:

- Statistical test: One-way ANOVA (fixed effects, omnibus)

- Effect size f: 0.40 (large)

- Significance level (α): 0.05

- Power (1 − β): 0.80

- Number of groups: 4

Result: A total sample of 76 participants (19 per condition) is
sufficient to detect within-condition learning gains. Actual power
achieved: 0.823.

> ⚠️ **Warning:** Limitation: This sample size is not sufficient to detect differences
> between conditions. It answers only the question of whether learning
> occurred, not which condition was more effective.

### 🔄 Between-Condition Analysis

This analysis determines the sample needed to detect differences in
learning outcomes across conditions. Between-group effects in GBL
research are typically smaller than within-group gains; accordingly, a
medium effect size (f = 0.25) was used.

Parameters:

- Statistical test: One-way ANOVA (fixed effects, omnibus)

- Effect size f: 0.25 (medium)

- Significance level (α): 0.05

- Power (1 − β): 0.80

- Number of groups: 4

Result: A total sample of 180 participants (45 per condition) is
required to detect medium between-condition differences. Actual power
achieved: 0.804.

> ℹ️ **Note:** Sensitivity to effect size: The required sample size increases
> dramatically at smaller effect sizes. For f = 0.10 (small), 1,096
> participants would be required — not feasible within one semester.

### 📊 Summary of Power Analysis Results

| Analysis Type | Effect Size (f) | Groups | Power | Required N |
|----|----|----|----|----|
| Within-Condition (pre→post learning gains) | 0.40 (Large) | 4 | 0.80 | 76 |
| Between-Condition (group differences) | 0.25 (Medium) | 4 | 0.80 | **180** |
| Between-Condition – Small effect scenario | 0.10 (Small) | 4 | 0.80 | 1,096 |

*Table 2. Summary of G\*Power analyses across effect size scenarios. The
target sample is highlighted.*

## 📌 Chosen Sample Size and Rationale

The study targets a minimum sample of 80 participants across four
conditions (20 per condition). This decision balances statistical rigour
with practical feasibility within a one-semester timeline.

This sample is simultaneously sufficient for within-condition analyses
(which require only n = 76). However, the following limitations must be
acknowledged:

- Non-significant between-condition results may reflect insufficient
  power rather than a true absence of differences, especially if the
  true effect size is small (f \< 0.25).

- A sample of 80 provides no protection against attrition; dropout
  should be anticipated and may reduce effective power.

- The analyses assume balanced groups. An imbalanced allocation will
  reduce power and should be corrected during recruitment.

## ✅ Conclusion

Based on a systematic review of eleven GBL studies and two G\*Power
analyses, a sample size of 180 participants is recommended for this
experimental GBL study. This is sufficient to detect medium
between-condition differences and large within-condition learning gains,
and represents a principled compromise between statistical ideal and
practical constraint.

Researchers should exercise caution when interpreting null results: the
study may be underpowered to detect small between-condition effects.
Within-condition analyses remain well-powered regardless of any
attrition up to approximately 57%.

## 📃 References

Ciptadi, Z. D. P., Nugroho, S., Adriani, D., & Singh, L. T. (2025). The
impact of teaching games for understanding and direct instruction models
on volleyball passing skills based on arm strength. Tanjungpura Journal
of Coaching Research, 3(2), 102–111.
[https://doi.org/10.26418/tajor.v3i2.89687](https://doi.org/10.26418/tajor.v3i2.89687)

Dardeer, F. M., et al. (2025). Comparison between game-based learning
and traditional learning methods in traumatic dental management among
dental interns at KAUFD. Clinical, Cosmetic and Investigational
Dentistry, 17, 381–390.

Eckardt, L., & Robra-Bissantz, S. (2018). Learning success: A
comparative analysis of a digital game-based approach and a face-to-face
approach. Proceedings of GamiFIN Conference.

Fernández Galeote, D., Legaki, N., & Hamari, J. (2023). From traditional
to game-based learning of climate change: A media comparison experiment.
Computers & Education.

Gordillo, A., López-Fernández, D., & Tovar, E. (2022). Comparing the
effectiveness of video-based learning and game-based learning using
teacher-authored video games for online software engineering education.
IEEE Access, 10, 12552–12565.

Gudadappanavar, A. M., Benni, J. M., & Javali, S. B. (2021).
Effectiveness of the game-based learning over traditional
teaching–learning strategy to instruct pharmacology for Phase II medical
students. Journal of Education and Health Promotion, 10(1), 91.

López-Fernández, D., et al. (2021). Comparing traditional teaching and
game-based learning using teacher-authored games on computer science
education. IEEE Transactions on Education, 64(4), 372–379.

Rezaei, M., et al. (2025). Comparing the effect of traditional
educational model and game-based learning approach on self-efficacy in
adolescent boys. Journal of Educational Research.

Rondon, S., Sassi, F., & Furquim de Andrade, C. (2013). Computer
game-based and traditional learning method: a comparison regarding
students’ knowledge retention. BMC Medical Education, 13(1), 30.

Shyamala, R., et al. (2025). Effectiveness of game-based learning versus
problem-based learning approaches in teaching microbiology to Phase II
medical students. Cureus, 17(9), e92330.

Wachdani, R. A., & Thohir, M. A. (2022). The influence of the
application of game-based learning (GBL) models assisted by the math
games platform on the mathematics learning outcomes of fifth grade
elementary school students. Indonesian Journal of Primary Education,
6(1), 78–87.
