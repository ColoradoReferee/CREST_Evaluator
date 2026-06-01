CREST Referee Evaluator

The C.R.E.S.T. (Colorado Referee Education & Supplemental Training) in-moment evaluation tool for referee coaches and evaluators.

Live app: https://coloradoreferee.github.io/CREST_Evaluator
Developed by: JAReferee LLC
Licensed to: Colorado Soccer Association

What it does
The CREST Referee Evaluator is an in-moment note-taking and evaluation application built for the Colorado Soccer Association's CREST program. It supports referee coaches and evaluators working with officials at every level — youth, adult, collegiate, and national-track.
It is not an observation-with-feedback platform. It sits at the front of the workflow, helping the ref coach capture detailed notes during the match, prioritize the verbal debrief in real time, and generate a polished evaluation report for follow-up.
Key capabilities:

Live event logging — Fouls (with direction-of-play attribution), offsides, misconduct (cautions and send-offs), goals, penalty kicks, substitutions, injury time, goal kicks, corner kicks, and free-text notes.
Structured notes — Tap-to-tag notes by official, tone (Excellent / Good / Adequate / Below Standard), and category (Positioning, Movement, Teamwork, Interaction with Participants, Match Control, Game Management). Optional phrase library suggests common debrief language per tone and category. Voice notes via the phone keyboard's built-in microphone.
Direction-of-play tracking — Big visual banner with team colors and arrows. Auto-flips at halftime. Coin toss capture with attack-direction selection.
Match clock — Soccer-correct timing (45+45 with injury time accumulator). Wall-clock anchoring with Page Visibility API resync — survives phone screen sleep without drift.
Score management — Tap-to-edit score with manual-increase confirmation. Goals logged via the GOAL button auto-update the score.
Post-match evaluation — Per-official sections for Referee, AR1, AR2, and 4th Official with feeling scores, positive areas, areas for development, and 9-band score grids.
CMI / CRE tracking — Critical Match Incidents auto-suggested across all involved officials per the U.S. Soccer manual (PK → Referee + AR1 + AR2; RC → Referee + AR1 + AR2 + 4th). Manual entry available for additional CMIs and all CREs.
Coach consolidated summary — A dedicated email recipient on the export screen generates a single comprehensive summary covering all officials, key events, CMI/CRE list, and development notes.
PDF export — Client-side, fully offline. CSA-branded report with embedded fonts.


About CREST
C.R.E.S.T. stands for Colorado Referee Education & Supplemental Training. The program is operated by the Colorado Soccer Association to provide structured coaching, evaluation, and ongoing development for soccer referees throughout Colorado.
This Evaluator is one component of a broader CREST toolkit being developed for the CSA referee community.

Architecture
The application is a single-file HTML application with no server, no backend, and no external dependencies at runtime.

Vanilla JavaScript (no frameworks)
Vanilla CSS (no preprocessors)
localStorage for persistence
Embedded fonts (Bebas Neue, DM Sans) as base64 — fully offline
Client-side PDF generation via blob URL
Page Visibility API for clock resync
Manifest for PWA install

This is a deliberate constraint, not a limitation. The app must run on a referee coach's phone or tablet on an outdoor field with intermittent or no connectivity, survive screen sleep without losing state, and export a polished report that does not depend on cloud services.

For CSA Referee Coaches
To get started:

Open the live app at https://coloradoreferee.github.io/CREST_Evaluator
(Optional) Install it to your home screen as a PWA for faster access
On the Setup screen, enter match details, officials, and coach name
(Optional) Record the coin toss to auto-set direction of play
Tap Start Match to begin logging
After the match, navigate to Post-Match to rate each official
Generate a PDF or email the evaluation from the Export screen

For CREST program questions, contact CSA directly.

Status
This software is under active development as part of the CREST program rollout. Releases are deployed automatically to GitHub Pages from the main branch.

License & Use
This software is proprietary, owned by JAReferee LLC, and licensed to the Colorado Soccer Association for use within the CREST program. See LICENSE and NOTICE.md for the full terms.
Use by parties other than CSA (acting within the scope of the CREST program) requires a separate written license agreement from JAReferee LLC.
Public visibility of source does not imply public license.

Contact
For CSA / CREST program questions:

Colorado Soccer Association — https://coloradosoccer.org

For software licensing or development questions:

JAReferee LLC — https://jareferee.com
Principal: Jeff Arthurholtz


© 2026 JAReferee LLC. All rights reserved.
Licensed to the Colorado Soccer Association for use within the CREST program.
