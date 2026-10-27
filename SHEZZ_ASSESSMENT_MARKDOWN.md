# Shezz-App — Agile Assessment Portfolio

**Student:** Sinazo Ntsimbi · **Student number:** 222765208 · **Assessment:** PRP370/371/372S, October 2026

> This is an individual portfolio of evidence for a team project. Proposed tasks and draft stand-up notes are not evidence of completed work. Confirm all draft entries against Trello, GitHub and dated records before submission.

## Evidence and project links

- [Shezz-App source code](https://github.com/Sinazo35/Shezz-App)
- [Trello board](https://trello.com/b/DmrNiPvG/shezz-salon-pp)
- [Live Shezz-App deployment](https://shezz-app.onrender.com/)
- [GitHub portfolio](https://222765208.github.io/)

## 1. Agile Team Charter

### Evidence — Team purpose and vision
**Mission:** Develop Shezz-App, a salon service platform that makes it easier for customers to book beauty appointments, submit hairstyle references and price offers, and access loyalty rewards.

**Success:** A usable responsive application with working core customer flows, verified testing, successful deployment and clear documentation.

### Team members and responsibilities

| Team member | Role | Responsibilities |
|---|---|---|
| Sinazo Ntsimbi | Software Developer / Agile Lead | Backend, database integration, testing, debugging, deployment, technical documentation |
| Vumani Kamanga | Frontend Developer | Responsive screens, frontend components, service integration, frontend testing |
| Aliziwe Ncoko | UI/UX Designer / Product Owner representative | User flows, layouts, visual design, accessibility, usability review |

Agile Lead and Product Owner representation are **proposed** and require team confirmation.

**Framework:** Scrum-inspired short sprints managed through Trello. Daily WhatsApp stand-ups, sprint planning, end-of-sprint demos and retrospectives.

**Working agreements:** Be prepared and punctual; update Trello; raise blockers early; give constructive feedback; review changes; test before marking work done; share evidence.

**Communication:** WhatsApp for coordination, Trello for tasks, GitHub for code and history. Routine messages should be acknowledged within one working day, subject to availability.

**Decisions:** Aim for consensus, otherwise majority vote; unresolved issues go to the lecturer/supervisor.

**Definition of Done:** Acceptance criteria met; code integrated and tested; responsive interface checked; documentation and Trello updated; team demonstration/acceptance; deployment where applicable.

**Values:** Respect, transparency, accountability, trust and learning.

**Risks:** Tight deadlines, unequal workload, integration bugs, deployment problems, connectivity and delayed feedback. Mitigate through clear ownership, small increments, backups and early testing.

**Review:** At each retrospective or when responsibilities change. Last updated 27 October 2026.

**Commitment:** Signatures/agreements for Sinazo Ntsimbi, Vumani Kamanga and Aliziwe Ncoko remain pending confirmation.

### Personal reflection — Team Charter (draft for review)
The charter helped me understand why clear responsibilities, communication and shared expectations matter. My technical role involved integration, testing and deployment. I learned that assigning responsibilities on paper is not enough: the team also needs regular progress updates and evidence of contributions. In future I would agree on deliverables and review workload at every sprint planning meeting.

## 2. User Stories and Tasks

### Evidence — Prioritised user stories

| ID | User story | Primary owner |
|---|---|---|
| US01 | As a customer, I want to register and sign in so I can access my bookings securely. | Sinazo |
| US02 | As a customer, I want to browse services and prices so I can choose a suitable service. | Vumani |
| US03 | As a customer, I want to book an available appointment so I can reserve a time. | Sinazo |
| US04 | As a customer, I want a mobile-friendly interface so I can book from my phone. | Aliziwe |
| US05 | As a customer, I want to upload a hairstyle photo and propose a price so I can request a custom style. | Vumani |
| US06 | As a stylist, I want to accept, counter or decline offers so I can respond to requests. | Sinazo |
| US07 | As a customer, I want to view booking and offer statuses so I can track requests. | Vumani |
| US08 | As a customer, I want rewards for verified completed visits so I benefit from repeat visits. | Sinazo |
| US09 | As a customer, I want to install the app on my phone for convenient access. | Vumani |
| US10 | As a customer, I want accessible and consistent screens to navigate easily. | Aliziwe |
| US11 | As a team, we want to test the booking journey to find defects before release. | Sinazo |
| US12 | As a team, we want to publish and document the application to demonstrate our work. | Sinazo |

**Task breakdown:** Sinazo — backend logic, database, API integration, testing and deployment; Vumani — forms, service cards, status screens and responsive PWA frontend; Aliziwe — wireframes, layouts, usability, accessibility and visual checks.

### Personal reflection — User Stories and Tasks (draft for review)
Writing features from the customer's perspective made the technical requirements easier to understand. Breaking each story into design, frontend and backend tasks also showed where our work depended on one another. I learned to connect each feature to an acceptance criterion rather than treating coding alone as proof that a feature is finished.

## 3. Product Backlog

### Evidence
The 12 prioritised stories above form the Product Backlog. The supplied document's **Taskboard** lists US01–US12 under **Product Backlog**, with **In Progress** and **Completed** left empty. This is a planned backlog, not a claim that all stories were completed.

**Acceptance criteria:** Booking must handle valid and unavailable slots; offers must capture a photo and proposed price and display a stylist response; only verified completed visits count toward demo loyalty rewards; key screens must work on mobile; release requires integration tests, documentation and deployment checks.

### Personal reflection — Product Backlog (draft for review)
The Product Backlog helped organise a large application into manageable priorities. Booking and offers were important customer journeys, while testing, deployment and documentation supported the release. I learned to keep unfinished work visible instead of moving cards to Completed without evidence.

## 4. Sprint Backlog

### Evidence — Proposed allocation, 12–16 October 2026

| Date | Sinazo — Developer | Vumani — Frontend | Aliziwe — UI/UX |
|---|---|---|---|
| 12 Oct | Requirements, authentication design, endpoints | Services page structure, navigation | User journey, wireframes, design tokens |
| 13 Oct | Booking models, validation, API integration | Booking form, responsive service cards | Booking and service screen designs |
| 14 Oct | Offer handling, database integration | Photo upload and offer form | Offer mockups and error states |
| 15 Oct | Loyalty/status logic, integration tests | Status screens, mobile testing | Usability and accessibility review |
| 16 Oct | End-to-end tests, deployment checks, README | PWA checks, UI fixes | Final UI QA and screenshots |

These are **proposed sprint assignments** from the supplied document. They should not be presented as completed without corroboration.

### Personal reflection — Sprint Backlog (draft for review)
The sprint allocation showed how work could be shared across development, frontend and UI/UX. It also showed that integration could become a bottleneck if dependent tasks were delayed. I learned the importance of realistic estimates, daily updates and reviewing blockers early.

## 5. Agile Logbook

### Evidence — Draft stand-up notes requiring verification

| Date | Since previous stand-up | Next action | Risk / blocker |
|---|---|---|---|
| 12 Oct | Reviewed features and backlog tasks | Plan booking/authentication and agree interfaces | API endpoints and final UI screens |
| 13 Oct | Outlined authentication and booking data | Booking validation and frontend integration | Form/backend payload mismatch |
| 14 Oct | Worked on booking and offer integration | Test flows and fix errors | Database credentials and environment setup |
| 15 Oct | Reviewed booking, offers and loyalty tests | End-to-end checks and bug records | Device/browser differences |
| 16 Oct | Prepared deployment/documentation checklist | Verify live app, collect evidence, update README | Deployment configuration and bugs |

**Important:** Every row above is a draft from the supplied Agile document, not a verified contemporaneous record. Check the actual day and date labels and replace draft claims with real dated stand-up evidence.

**Walkthrough questions:** What is needed to advance the work? Prioritise booking and offers, connect design to frontend/backend tasks and test the customer journey. Is untracked work happening? Compare WhatsApp updates to Trello cards. What remains? Integration, responsive testing, deployment checks and screenshots. What blocks progress? Potential API/database configuration, integration, device compatibility and time limitations.

### Personal reflection — Agile Logbook (draft for review)
The logbook format helped me think about progress, next steps and obstacles rather than only the final result. I learned that short, accurate daily notes can make delays easier to understand and support sprint retrospectives. I would improve my record keeping by attaching dates and links to commits, screenshots or Trello updates as the work happens.

## Evidence gallery — links and records

- **Trello:** [Shezz Salon PP board](https://trello.com/b/DmrNiPvG/shezz-salon-pp) — backlog and sprint tracking. Add dated screenshots to the repository when available.
- **GitHub:** [Shezz-App repository](https://github.com/Sinazo35/Shezz-App) — source code and commit history.
- **Deployment:** [Shezz-App on Render](https://shezz-app.onrender.com/) — deployment URL; a screenshot of the Render dashboard was supplied for the portfolio and should be uploaded with private details redacted.
- **Documents:** The original completed charter and product backlog/logbook Word files should be uploaded to a `documents/` folder for download links.

## Overall reflection (draft for review)
Shezz-App gave me experience connecting Agile planning to software development and deployment. I worked on technical integration and saw why user experience, frontend implementation and backend behaviour must fit together. The most important lesson was to support each portfolio claim with evidence and to be transparent about planned work versus completed work. My next improvement would be to maintain clearer daily records and collect screenshots and testing results throughout each sprint.
