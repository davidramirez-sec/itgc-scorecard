ITGC Scorecard
A quick self-assessment tool I put together for evaluating IT General Controls readiness ahead of a SOC 1 engagement.
Live: https://davidramirez-sec.github.io/itgc-scorecard

Why I built this
Kept running into the same situation — clients or teams unsure of where they stood on basic ITGCs before starting an audit. Instead of walking through it verbally every time, I wanted something they could go through on their own and get a scored result from.
15 questions, one at a time. Takes about 3 minutes.
How it works
Walks you through questions across the three core SOC 1 domains:

Logical Access — provisioning, de-provisioning, access reviews, MFA, privileged accounts
Change Management — approval workflows, SoD, testing, emergency changes, record completeness
Computer Operations — backups, incident management, vulnerability scanning, log review, BCP/DR

At the end you get a scored report card per domain with a rating, specific findings, and a prioritised remediation list based on your answers.
Everything runs in the browser — no backend, no data sent anywhere.
What the ratings mean
ScoreRatingWhat it means85%+StrongControl environment is largely audit-ready65–84%ModerateCore controls in place, gaps need addressing40–64%Needs WorkSignificant remediation before SOC 1 engagement<40%High RiskCritical gaps — qualified opinion likely
Stack
Vanilla HTML, CSS, JavaScript. No frameworks or dependencies.
git clone https://github.com/davidramirez-sec/itgc-scorecard.git
open index.html
What I'd improve

Add scoring history so you can track improvement over time
Let users export a PDF version of the full report card
Add a fourth domain — Risk Management
Weight questions by SOC 1 audit frequency so higher-tested controls carry more impact on the score

About
Built by David Ramirez — IT audit and compliance, SSCP · CCSP · CySA+ · Security+ · ITIL v4.
📧 davidramirez.tech@gmail.com
For reference and awareness only. Not a formal audit opinion or compliance certification.


sss
For reference and awareness only. Not a f
