UCAN Lesson 08 — Harmonized HTML Preview Candidate
Runtime candidate: v1.1 Harmonized PreRelease
Classification: Controlled PreRelease Preview / Partner Review Candidate
Previous baseline: UCAN_Lesson_08_HTML_Preview_v1.0_PreRelease — preserved
Lesson ID: UCAN-L08
GitHub: NOT USED
Publication: NOT PERFORMED

AUTHORITY
Content successor: UCAN_Lesson_08_Editorial_v2.2_UserReview_Harmonized.docx
Assessment Authority: UCAN_Lesson_08_Assessment_Authority_Decision_v1.0 — PASS 5/5, unlimited retry, dirty-state relock
Designer/Visual Handoff: UCAN_Lesson_08_Designer_Visual_Integration_Handoff_v1.0
User Review Harmonization authorization: 2026-08-16

HARMONIZED CHANGES
- Narrative bridges and a single hypothetical-municipality spine across Routes 1–5.
- Copenhagen learner link repaired to official municipal climate-adaptation landing page: https://www.kk.dk/politik/politikker-og-indsatser/klima-og-miljoe/klimatilpasning
- Case synthesis added.
- Route order changed: Formative → Inspiration/Resources → Portfolio+AI → Final Assessment → Completion.
- Resource route renamed “Де шукати натхнення” and uses controlled official resources without repeating city-case links.
- Portfolio live HTML preview added; five canonical fields unchanged.
- Exactly two optional AI tasks added; explicit copy workflow; no automatic data transmission.
- Final Assessment wording/distractors harmonized; keys remain B/A/C/B/D; pass remains 5/5.
- Completion strengthened; pending Next Lesson control visible only on Route 9 and remains disabled.
- Static Lesson title header preserved; visual-only spacing/wrapping polish applied.

RUNTIME FILES
index.html
css/style.css
js/script.js
assets/L08-A01_Blue_Green_Network_v1.0.svg
README.txt

STATE
Portfolio namespace: ucan_l08_portfolio_v1 (preserved across preview successor)
Route namespace: ucan_l08_route_v2
Assessment namespace: ucan_l08_assessment_v2 (new because exact question wording changed)
Formative namespace: ucan_l08_formative_v1
Normal reset preserves Portfolio. Separate explicit Portfolio deletion remains.

ASSESSMENT
Questions: 5
Keys: B / A / C / B / D
Pass: 5/5
Retry: unlimited
Completion gating: yes
Dirty-state relock: yes

AI
Task 1: Перевірити логіку ескізу
Task 2: Уточнити перший управлінський крок
Copy only after learner action; fixed official external links; no learner data in URLs; no API.

VISUAL
assets/L08-A01_Blue_Green_Network_v1.0.svg is preserved byte-for-byte from v1.0 and remains in Route 2 at the approved position.

ROUTING
Previous Lesson: controlled L07 reservation URL retained.
Next Lesson: CONTROLLED ROUTE BOUND — https://clusterceu-crypto.github.io/UCAN-Lesson09/; visible disabled control on Route 9 only until L09 deployment validation.

DOWNSTREAM NOTE
Course-wide Header Harmonization Pass required later for Lessons 01–08. No Lessons 01–07 modified in this sprint.


FINAL USER REVIEW COMPLETION MICROFIX — v1.1.1
Runtime successor: UCAN_Lesson_08_HTML_Preview_v1.1.1_PartnerReview_PreRelease
Baseline v1.1 preserved: YES
Scope: Route 9 CTA placement + navigation regression repair only.
Removed learner-facing publication-process sentence from «Що далі».
Route 9 ordinary forward button is hidden; dedicated disabled «Наступне заняття →» is placed inside Completion content after «Що далі».
L09 route bound; CTA activation pending L09 deployment validation.
Future activation requires only removing the disabled state / click prevention from the existing CTA; no URL change or layout redesign is required.
GitHub: NOT USED. Publication: NOT PERFORMED.

BROWSER QA STATUS
Browser automation: PENDING — current execution environment does not provide the Playwright package required by the attempted headless check.
Static regression verification: PASS.
Manual/normal-browser validation remains required before deployment.

FINAL BOTTOM NAVIGATION MICROFIX — v1.1.2
Runtime successor: UCAN_Lesson_08_HTML_Preview_v1.1.2_PartnerReview_PreRelease
Baseline v1.1.1 preserved: YES
Scope: restore standard shared bottom-navigation placement for the disabled Next Lesson CTA.
Route 9 learner content now ends after «Що далі»; no in-content Next Lesson CTA or learner-facing pending-status helper text remains.
Bottom navigation on Route 9: ← Назад | 9 / 9 | Наступне заняття →.
Routes 1–7 retain Далі →; Route 8 retains До завершення → under the existing assessment gate.
Exactly one #nextLessonPending control exists inside .bottom-nav-inner. Controlled route is bound as data-href=https://clusterceu-crypto.github.io/UCAN-Lesson09/; the control remains disabled until L09 deployment validation.
L09 route bound; CTA activation pending L09 deployment validation.
Future activation requires only removing the disabled state / click prevention from the existing bottom-navigation CTA; no URL change or layout redesign is required.
Editorial remains UCAN_Lesson_08_Editorial_v2.2.1_PartnerReview_Microfix.docx.
GitHub: NOT USED. Publication: NOT PERFORMED.


Routing Contract Microfix — v1.1.3 Partner Review PreRelease
Controlled L09 URL: https://clusterceu-crypto.github.io/UCAN-Lesson09/
Routing state: KNOWN.
CTA activation state: DISABLED UNTIL L09 DEPLOYMENT VALIDATION.
Implementation contract: target URL is bound in runtime configuration and on #nextLessonPending via data-href; current disabled/aria-disabled state prevents navigation. Future activation requires only removing the disabled state / click prevention. No URL change, layout redesign, or learner-content rewrite is required.
L09 route bound; CTA activation pending L09 deployment validation.
GitHub: NOT USED.
Lesson 09 production: NOT STARTED.
