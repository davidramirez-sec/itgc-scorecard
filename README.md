ITGC Scorecard
A quick self-assessment I put together for evaluating IT General Controls readiness before a SOC 1 engagement.
Live: https://davidramirez-sec.github.io/itgc-scorecard

Why I built this
Kept running into the same situation where people weren't sure where they stood on basic ITGCs before starting an audit. Instead of walking through it verbally every time I wanted something they could go through on their own.
15 questions, one at a time. Takes about 3 minutes.
How it works
Questions cover the three domains auditors actually test — Logical Access, Change Management, and Computer Operations. At the end you get a scored report card with a rating per domain, specific findings, and a remediation list based on your answers.
Runs entirely in the browser. Nothing is stored or sent anywhere.
Ratings
85% and above is Strong, 65 to 84 is Moderate, 40 to 64 is Needs Work, below 40 is High Risk.
Stack
Vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies.
git clone https://github.com/davidramirez-sec/itgc-scorecard.git
open index.html
What I'd add next
Scoring history to track improvement over time, PDF export for the full report card, a fourth domain for Risk Management, and weighting questions by how frequently each control gets tested in a real SOC 1 so the score reflects actual audit exposure better.
About
Built by David Ramirez — SSCP · CCSP · CySA+ · Security+ · ITIL v4
davidramirez.tech@gmail.com
For reference only. Not a formal audit opinion.
