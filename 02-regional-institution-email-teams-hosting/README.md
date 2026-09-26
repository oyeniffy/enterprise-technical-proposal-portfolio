# Technical Proposal — Hosting of E-Mails and Microsoft Teams for Regional Institutions and Agencies

**Submitted by:** Task Systems Limited (Microsoft Licensing Solution Partner)
**Submitted to:** [Confidential Client — Regional Intergovernmental Institution]
**Bid reference:** PP-2026-ADD-GOODS-018

---

Technical Proposal | PP-2026-ADD-GOODS-018

## Task Systems Limited

                                                    Microsoft Licensing Solution Partner (LSP)

## Technical Proposal

                        Hosting of E-Mails and Microsoft Teams Application for [Client] Institutions and Agencies

## Invitation To Bid

                                                      Bid Reference: PP-2026-ADD-GOODS-018

## Submitted To

                                                              The [Confidential Client — Regional Intergovernmental Institution]

                    Procurement Division, Directorate of Administration and General Services, Airport Road, Abuja, Nigeria

## Submitted By:

                                                                 Task Systems Limited
                                   Yudala Heights Building, 13 Idowu Martins Street, Victoria Island, Lagos, Nigeria

## Confidentiality Statement

             This document and its contents are confidential and constitute the proprietary and intellectual property of Task Systems
             Limited. It has been prepared exclusively for the [Confidential Client — Regional Intergovernmental Institution] in response to Invitation to Bid PP-2026-ADD-GOODS-
             018 and is submitted solely for the purpose of bid evaluation. It shall not be disclosed, reproduced, copied, distributed or used,
             in whole or in part, for any purpose other than the evaluation of this bid, nor shared with any third party including competing
             bidders without the prior written consent of Task Systems Limited, except where disclosure is required by applicable
             procurement law or regulation.

                                                     © 2026 Task Systems Limited. All Rights Reserved.

                                                                                                                             July 2026

                                                                                                                                         1

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                                                                                       Table of Contents

### 1. Executive Summary ............................................................................................................................................ 3

### 2. Understanding of [Client]’s Requirements and Site Visit Insights ....................................................................... 4

#### 2.1 Strategic Context .......................................................................................................................................... 4

#### 2.1 Key Outcome of the Bid Site Visit ([Confidential Client — Regional Intergovernmental Institution] Abuja) .................................................................... 4

#### 2.3 Current EOWAS ICT Environment .................................................................................................................. 5

### 3. Proposed Technical Solution and Architecture .................................................................................................... 6

#### 3.1 Multi-Tenant Enterprise Agreement Architect ............................................................................................... 6

#### 3.2 Hybrid Infrastructure Architecture ................................................................................................................ 7

#### 3.3 CSP-to-EA Transition Strategy ....................................................................................................................... 8

### 4. Microsoft Licensing Structured for [Client]'s Digital Transformation .................................................................. 9

### 5. Unified Support (Task Systems-Led Delivery, Powered by Microsoft) ................................................................. 11

#### 5.1 Unified Support Offer Structure .................................................................................................................. 12

#### 5.2 Unified Support Response-Time Commitments ........................................................................................... 13

#### 5.3 Microsoft Teams Multilingual Interpretation ............................................................................................... 13

### 6. Phased Azure Adoption and Three-Year Implementation Roadmap ................................................................... 14

#### 6.1 Milestones and Deliverables ....................................................................................................................... 15

### 7. Service Level Agreements and Support Model................................................................................................... 15

### 8. Business Continuity Plan (BCP) .......................................................................................................................... 16

#### 8.1 General Prerequisites (Digital-First Resilience) ............................................................................................ 16

#### 8.2 Human Resources Continuity ...................................................................................................................... 17

#### 8.3 Client Engagement Continuity ..................................................................................................................... 17

                        8,4 Procurement and Supply Chain Continuity .................................................................................................. 17

#### 8.5 Finance and Audit Continuity ...................................................................................................................... 17

#### 8.6 Technology Enablement Summary .............................................................................................................. 18

#### 8.7 Proven Track Record: COVID-19 Continuity ................................................................................................. 18

### 9. Company Profile, Technical Prowess and Track Record...................................................................................... 19

#### 9.1 Track Record............................................................................................................................................... 19

#### 9.2 Vision and Strategic Direction ..................................................................................................................... 20

#### 9.3 Solutions Area of Focus............................................................................................................................... 20

#### 9.4 Technical Prowess Development ................................................................................................................. 21

#### 9.5 Market Position .......................................................................................................................................... 21

### 10. Skills Transfer, Training and Knowledge Management ..................................................................................... 21

### 11. Risk Management ........................................................................................................................................... 22

### 12. Compliance Matrix.......................................................................................................................................... 23

### 13. Conclusion ...................................................................................................................................................... 23

                                                                                                                                                                                        2

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

### 1. Executive Summary

                  Task Systems Limited is pleased to submit this Technical Proposal in response to Invitation to Bid PP-2026-ADD-
                  GOODS-018, issued by the [Confidential Client — Regional Intergovernmental Institution] for the Hosting of E-Mails and Microsoft Teams Application for
                  [Client] Institutions and Agencies. As a Microsoft Licensing Solution Partner (LSP) with over decades of authorised
                  reseller standing and deep technical experience across Azure, Modern Workplace, Security, Business Application,
                  Artificial Intelligence and Machine Learning, Task Systems is uniquely positioned to deliver the secure, hybrid, multi-
                  tenant Microsoft environment that [Client] requires.
                  This proposal is informed directly by the Terms of Reference contained in the Bidding Document and by the
                  outcomes of the Bid Site Visit conducted at the [Confidential Client — Regional Intergovernmental Institution]'s headquarters in Abuja. The insights gathered
                  during that engagement on the planned CSP-to-Enterprise Agreement (EA) migration, the hybrid infrastructure
                  target state, the phased Azure adoption strategy, the delivery of Unified Support, and the mandatory Business
                  Continuity Plan have each been deliberately built into the solution set out in this document.

                  Our proposed solution is structured around four pillars:

                        ●    A secure, hybrid Microsoft architecture that bridges [Client]'s existing on-premises Active Directory,
                             Windows Server 2022 and VMware/Hyper-V estate with Microsoft's cloud platform through Azure AD
                             Connect and Azure AD Application Proxy.

                        ●    A robust, low-risk CSP-to-EA migration strategy that guarantees continuity of email, Teams and
                             collaboration services throughout the transition, with the [Confidential Client — Regional Intergovernmental Institution] established as the Lead
                             Enterprise Tenant across a 13-institution multi-tenant Enterprise Agreement.

                        ●    A phased Azure adoption roadmap that begins at the Commission and extends systematically to [Client]
                             Institutions and Agencies over the three-year contract term.

                        ●    A comprehensive, previously tested Business Continuity Plan (BCP), demonstrating our organisation's
                             proven ability to sustain delivery service

                  Task Systems commits to a three-year engagement covering licence renewal from Microsoft Open CSP to a
                  consolidated multi-tenant Enterprise Agreement (upgrading from E3/E5 to E7), comprehensive technical
                  maintenance, and full alignment with the [Client] Service Level Agreement (SLA) matrix.

                  We are confident that this proposal demonstrates not only full compliance with the Bidding Document but a genuine,
                  evidence-based understanding of [Client]'s digital transformation journey and we look forward to the opportunity
                  to serve as [Client]'s trusted Microsoft partner for the next three years and above.

                                                                                                                                       3

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

### 2. Understanding of [Client]’s Requirements and Site Visit Insights

#### 2.1 Strategic Context

                  The Economic Community of West African States ([Client]) was established by treaty on 28 May 1975 and
                  revised on 24 July 1993, comprising twelve Member States and a family of specialised institutions and agencies.
                  Following the construction of its new Abuja headquarters, the [Confidential Client — Regional Intergovernmental Institution] is consolidating the
                  Microsoft requirements of all its institutions and agencies into a single, centralised, service-oriented
                  subscription framework, in support of [Client]'s broader IT strategy of security, availability, mobility and
                  compliance.

                  The objective of this procurement is to select a highly specialised Microsoft partner for a three-year period to
                  serve the following institutions and agencies: the [Confidential Client — Regional Intergovernmental Institution] (as Lead Enterprise Tenant), the
                  [Client] Parliament, GIABA, the Community Court of Justice, the West African Health Organisation (WAHO),
                  the Office of the Auditor-General, the [Client] Regional Electricity Regulatory Authority (ERERA), the [Client]
                  Regional Agency for Agriculture and Food (ARAA), ECREEE, WRMC, EGDC, EYSDC and RAHC.

#### 2.1 Key Outcome of the Bid Site Visit ([Confidential Client — Regional Intergovernmental Institution] Abuja)

                  Task Systems Limited participated in the [Client] Bid Site Visit alongside representatives of the [Confidential Client — Regional Intergovernmental Institution] and Microsoft. The objective of our attendance was to listen directly to [Client]'s
                  expectations, understand the existing ICT environment and commercial gaps, gain insight into key
                  business and technical challenges, and define what success looks like on delivery of this project. The
                  following outcomes, captured in our formal site visit report, have directly shaped every section of this
                  technical proposal.

                                             Site Visit Outcome                                  How This Proposal Responds

                       Enterprise Agreement (EA) Transition: [Client] will                Section 3.1 sets out the full multi-tenant EA
                        migrate from its current Microsoft CSP environment to a           architecture, with the Commission as Lead
                        multi-tenant Microsoft EA, with the [Confidential Client — Regional Intergovernmental Institution]             Enterprise Tenant across all 13 institutions and
                        as Lead Tenant.                                                   agencies.

                       Hybrid Infrastructure: The target environment integrates         Section 3.2 details the hybrid architecture bridging
                        Microsoft Cloud services with existing on-premises                [Client]'s on-premises Active Directory estate with
                        infrastructure.                                                   Microsoft's cloud platform.

                                                                                                                                  4

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                                             Site Visit Outcome                                How This Proposal Responds

                       Digital Transformation: Phased modernisation with Azure        Section 3.3 and Section 6 present the phased CSP-
                        adoption beginning at the Commission before extending           to-EA migration and 3-year Azure adoption
                        to other Institutions and Agencies.                             roadmap.

                       Microsoft Teams Interpreter: Native real-time                  Section 8 sets out our continued engagement
                        multilingual interpretation/transcription is outside            approach and interim collaboration alternatives
                        current commercial scope; Microsoft will engage                 while this capability matures on Microsoft's
                        [Client] separately on roadmap and options.                       roadmap.

                       Unified Support: EA licensing, implementation and              Section 5 clearly delineate Unified Support scope
                        project delivery.                                               implementation and project delivery scope.

                       Windows Server Licensing: The existing commercial              Section 4 confirms Windows Server Datacenter and
                        proposal adequately covers required Windows Server              Standard Core licensing is retained within the
                        Standard and Datacenter licensing.                              Section 1 licence schedule.

                       Business Continuity: A comprehensive BCP is mandatory          Section 9 presents our full, previously tested
                        and forms part of the evaluation criteria.                      Business Continuity Plan.

                                                                                       Noted and reflected in our Bid Submission Letter;
                       Bid Security: Waived for all bidders.
                                                                                        no bid security is enclosed.

#### 2.3 Current EOWAS ICT Environment

                  [Client] currently operates a hybrid deployment of Microsoft Office 365 Business, with Windows Server 2022
                  as the operating system across physical machines and VMware/Hyper-V virtualisation managed through
                  vSphere. The environment includes Azure AD Application Proxy, on-premises Active Directory, Azure AD
                  Connect, Active Directory Certificate Services (AD CS) and WSUS. This proposal is engineered to build directly
                  on this existing footprint rather than replace it protecting [Client]'s existing investment while extending its
                  capability through the E7 licence upgrade and hybrid Azure integration described in Section 3.

                                                                                                                                5

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

### 3. Proposed Technical Solution and Architecture

#### 3.1 Multi-Tenant Enterprise Agreement Architect

                  At the heart of this proposal is a multi-tenant Microsoft Enterprise Agreement (EA) architecture in which
                  the [Confidential Client — Regional Intergovernmental Institution] acts as the Lead Enterprise Tenant, consolidating licensing authority,
                  governance and billing oversight for the entire [Client] institutional family, while each institution and
                  agency retains its own logically separate Microsoft 365 tenant for data sovereignty, administrative
                  autonomy and security isolation. Task Systems, as the appointed Microsoft LSP partner, sits between
                  Microsoft's Global Enterprise Agreement Program and the [Confidential Client — Regional Intergovernmental Institution], administering the EA
                  enrollment, coordinating license renewal and provisioning, and delivering implementation and project
                  management services across all tenants.

                  Our review of the current Microsoft footprint confirms 1,564 Microsoft 365 E7 seats are already active
                  across eight institutions in Phase 1 of the rollout, with the [Confidential Client — Regional Intergovernmental Institution] carrying the largest share

                  (879 seats) consistent with its role as Lead Tenant. A further five institutions and agencies the Office of
                  the Auditor-General, WRMC, EGDC, EYSDC and RAHC are positioned for Phase 2 onboarding, in direct
                  alignment with [Client]'s own stated intent that Azure adoption and modernisation begin at the
                  Commission before extending to other Institutions and Agencies.

                  Figure 1: [Client] Multi-Tenant Enterprise Agreement Architecture
                                                                                                                           6

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                  Why this Architecture matters

                        ●    Single point of governance: the Commission retains enrolment-level control and consolidated visibility
                             over licence consumption and compliance across all institutions.

                        ●    Tenant-level autonomy: each institution keeps its own Microsoft Entra ID directory, mailbox
                             environment and Teams tenant, preserving administrative independence and data boundaries
                             required by bodies such as the Community Court of Justice and the Office of the Auditor-General.

                        ●    Phased, low-risk rollout: institutions already transacting under CSP move into the EA in Phase 1;
                             institutions not yet onboarded move in a controlled Phase 2, preventing a disruptive “big bang”
                             cutover.

                        ●    Single Microsoft LSP relationship: Task Systems acts as the sole point of accountability to Microsoft for
                             the entire [Client] family, simplifying escalation, renewal and support coordination.

#### 3.2 Hybrid Infrastructure Architecture

                  Figure 2: [Client] Hybrid Microsoft Cloud Architecture

                                                                                                                                    7

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                  [Client]'s target environment is explicitly hybrid: Microsoft Cloud services integrated with the existing on-
                  premises infrastructure at the Commission's Abuja headquarters. Our architecture preserves and builds on the
                  Commission's existing Active Directory Domain Services, Active Directory Certificate Services (AD CS), WSUS
                  and VMware/Hyper-V (vSphere) virtualisation estate, bridging it to Microsoft Entra ID via Azure AD Connect
                  and Azure AD Application Proxy. This ensures identities, certificates and patch management remain centrally
                  governed on-premises while collaboration, mail and security services are delivered from Microsoft's cloud.

                  This hybrid design directly supports the technical maintenance obligations set out in the Terms of Reference:
                  regular software updates and patching, quarterly system checks and performance monitoring, comprehensive
                  backup and recovery, rapid incident troubleshooting, security update and vulnerability management, user
                  support and training, and continuous capacity planning all delivered without disrupting existing on-premises
                  operations.

#### 3.3 CSP-to-EA Transition Strategy

                  [Client]'s move from its current Microsoft CSP environment to a consolidated, multi-tenant Enterprise
                  Agreement is, first and foremost a business transition, the license and platform mechanics that follow are
                  simply how that transition is executed safely. Task Systems' approach is therefore built around continuity
                  of service as the governing principle, not around the speed of the technical cutover. Our transition
                  strategy is structured into four sequential phases, each with its own entry and exit criteria, so that
                  [Client] retains full visibility and control at every step.

                        ●    Phase 1 (Discovery & Readiness Assessment): Validate current tenant configurations, license
                             assignments, mailbox and Teams usage across all institutions; confirm the Commission's Lead
                             Tenant enrolment parameters with Microsoft; agree with the transition governance model,
                             communication plan and success criteria with [Client] before any technical work begins.

                        ●    Phase 2 (EA Enrolment & Parallel Operation): Establish the multi-tenant EA enrolment under the
                             Commission and provision E7 licences alongside not instead of the active CSP subscriptions, so
                             that both environments operate in parallel and no user experiences any interruption to e-mail,
                             Teams or identity services during the transition window.

                        ●    Phase 3 (Controlled, Institution-by-Institution Cutover): Move license assignment from CSP to EA
                             one institution at a time, beginning with the Commission, using out-of-hours cutover windows,

                                                                                                                               8

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                             defined rollback checkpoints at every stage, and joint sign-off with each institution's IT focal point
                             before proceeding to the next.

                        ●    Phase 4 (Stabilisation, Decommission & Formal Handover): Retire legacy CSP subscriptions only
                             once mail flow, Teams, authentication and security policy have been fully validated on the EA
                             tenant; run a stabilisation period per institution to confirm steady-state operation; and issue a
                             signed-off transition completion report to [Client] closing out each institution's move.

### 4. Microsoft Licensing Structured for [Client]'s Digital Transformation

                  [Client]'s licensing requirement is not simply a renewal exercise; it is the technical foundation of the
                  Commission's digital transformation strategy. We have therefore structured the licence portfolio (as
                  reflected in the commercial schedule) around four digital-transformation pillars, so that the evaluator can
                  see precisely how each licence category advances a specific strategic objective. Commercial pricing for
                  each line item is presented separately in our Commercial Proposal, in line with [Client]'s evaluation
                  process; the structure below deliberately shows scope and capability only.

                            Pillar A: Modern Workplace & Collaboration (core to the e-mail and Teams hosting requirement)

                                                                         Total Seats (8
                        Licence / SKU               Part Number                                       Digital Transformation Role
                                                                      active tenants)

                                                                                          Core E5/E3→E7 upgrade mandated by the ToR;
        Microsoft 365 E7 (Full User SL, w/o
                                                   EP2-79437        1,564                 unifies e-mail (Exchange Online), Teams, security
        Audio Conferencing)
                                                                                          and compliance in one license.

                                                                                          Extends Teams, Outlook and collaboration access
        Microsoft 365 F3 (Frontline Worker)        JFX-00003        291                   to frontline/field staff at lower cost, widening
                                                                                          digital inclusion across agencies.

                                                                                          Cost-efficient mailbox tier for lower-intensity users,
        Exchange Online Kiosk (P1 SU)              TRA-00065        291                   keeping the whole institution on a governed,
                                                                                          centrally hosted mail platform.

                                                                                          Selective mailbox capacity upgrade for users
        Exchange Online P1→P2 step-up              TQA-00005        74
                                                                                          needing larger mailboxes/archiving.

                                                                                                                                     9

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                                                                            Total Seats (8
                          Licence / SKU              Part Number                                           Digital Transformation Role
                                                                          active tenants)

                                                                                              Advanced Teams meeting intelligence, branding
                                                                                              and security a stepping stone toward the
        Teams Premium                                WFI-00005         50
                                                                                              multilingual interpretation roadmap discussed in
                                                                                              Section 8.

        Planner & Project Plan 3 / Planner           7LS-00002 /                              Structured project and task management
                                                                       9 / 13
        Plan 1                                       TRS-00002                                embedded directly in Teams.

                             Pillar B: Security, Identity & Compliance

                           Licence / SKU               Part Number              Total Seats                Digital Transformation Role

                                                                                                Unified threat protection across identity,
                                                                                                endpoint, e-mail and cloud apps directly
           Microsoft Defender Suite (Per User)       PEJ-00002              515
                                                                                                satisfies the ToR's vulnerability management
                                                                                                and security-update obligations.

                                                                                                Extends the same protection baseline to F3
           Microsoft Defender Suite (Frontline
                                                     8RQ-00005              286                 frontline users, closing security gaps across the
           Worker Add-on)
                                                                                                whole workforce.

                                                                                                Central hybrid identity bridge; foundation of
           Azure AD Connect + Azure AD               existing
                                                                            All tenants         the Zero-Trust and conditional-access posture
           Application Proxy                         infrastructure
                                                                                                described in Section 3.2.

                             Pillar C: Data, AI & Process Automation (Digital Transformation Enablers)

                        Licence / SKU           Part Number            Total Seats                    Digital Transformation Role

                                                                                      Low-code AI agent and automation platform positions
           Copilot Studio (Legacy USL +      SYS-00001 / YFI-                         [Client] to build custom AI-assisted workflows on top of its
                                                                      1,855 / 8
           Messages)                         00001                                    own data, in line with the Commission's digital
                                                                                      transformation ambitions.

                                                                                                                                        10

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                        Licence / SKU            Part Number           Total Seats                          Digital Transformation Role

                                                                                        Self-service analytics and reporting across institutions
           Power BI Pro                      NK4-00002                31
                                                                                        enables data-driven decision-making at the agency level.

                                                                                        Low-code application development for institution-specific
           Power Apps Premium                SEJ-00002                10
                                                                                        digital services.

                                                                                        Workflow automation to digitize manual administrative
           Power Automate                    SPU-00002                10
                                                                                        processes.

                             Pillar D: Cloud Infrastructure (Phased Azure Adoption)

                         Licence / SKU              Part Number                      Scope                           Digital Transformation Role

                                                                                                            Funds the Commission's Azure workloads as
           Azure Prepayment                                             [Confidential Client — Regional Intergovernmental Institution]                   the anchor for phased cloud adoption, ahead

## 6Qk-00001

           (Consumption Commitment)                                     (Phase 1 anchor tenant)             of extension to other institutions in Years 2–3
                                                                                                            (see Section 6).

                                                                                                            Confirmed by [Client] at the site visit as
                                                                                                            adequately covered by the existing
           Windows Server Datacenter /           9EA-00271 / 9EM-       [Confidential Client — Regional Intergovernmental Institution] on-
                                                                                                            commercial proposal; retained unchanged to
           Standard Core licensing               00265                  premises estate
                                                                                                            protect the on-premises hybrid layer
                                                                                                            described in Section 3.2.

         Note: Quantities above reflect the Year-1 license schedule for the eight institutions currently commercially scoped ([Confidential Client — Regional Intergovernmental Institution], Parliament,
         Community Court of Justice, GIABA, WAHO, ERERA, ARAA and ECREEE). Licence quantities for the five Phase-2 institutions (Office of the Auditor-General,
         WRMC, EGDC, EYSDC, RAHC) will be established on onboarding, following the same E7-centred structure. All pricing details are reserved for the
         Commercial Proposal.

### 5. Unified Support (Task Systems-Led Delivery, Powered by Microsoft)

                  Task Systems Limited is [Client]'s single accountable delivery partner for support across the entire
                  Microsoft estate, the Commission's IT Directorate raises everything through Task Systems, and Task
                  Systems owns the outcome. What sits behind that single relationship is Microsoft's own Unified Support
                  organisation, whose global engineering bench, Customer Success Account Manager (CSAM) and
                                                                                                         11

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                  Designated Engineering hours we draw on as the backend engine that powers our delivery. In practice this
                  means: one point of contact, one escalation path, and one party, Task Systems accountable to [Client]
                  for the outcome, while Microsoft's global support infrastructure does the heavy lifting behind the scenes.

                  We set out below exactly how this front-to-back model works, so [Client]'s evaluators can see precisely
                  how Task Systems' client-facing delivery and Microsoft's backend entitlement interlock without any gap
                  in accountability.

#### 5.1 Unified Support Offer Structure

                  The Unified Support entitlement is scoped for the [Confidential Client — Regional Intergovernmental Institution] over a three-year term (25 June
                  2026 – 24 June 2029). Task Systems administers and delivers this entitlement to [Client] as three
                  coordinated service components, each powered on the backend by Microsoft's Customer Success and
                  Unified Support organisation:

        Service Component                    How Task Systems Delivers It to [Client] (Powered by Microsoft)

                                                    Task Systems manages [Client]'s relationship with a dedicated Technical Account Manager,
                                                     Sales Account Manager and Customer Success Account Manager (CSAM) on [Client]'s behalf,
                                                     coordinates as-needed 24x7 troubleshooting across all Microsoft products against defined

### 1. Unified Enterprise                        severity-based response times, schedules on-demand assessments, draws on advisory support

                                                     (up to six hours per incident) for our own engineers, curates on-demand education, hands-on
                                                     labs and webcasts for [Client] staff, and administers the Services Hub portal so [Client]
                                                     always has one place to raise, track and review support activity.

                                                    Task Systems directs a dedicated Microsoft Engineer, backed by 800 hours per year of

### 2.     Enhanced       Designated             designated engineering time, against an agreed [Client] security roadmap directly reinforcing

        Engineering for Security                     the security posture described in Section 4, Pillar B, with Task Systems setting priorities and
                                                     reporting progress to [Client].

                                                    Task Systems plans and directs a structured annual package of 4 services and 100 hours of
                                                     designated engineering per year. In Years 1 and 2 this is scoped to “Migrate and Modernize

### 3. Designated Engineering                    Infrastructure & Workloads” directly supporting the phased Azure adoption roadmap in

        Tier 2                                       Section 6; in Year 3 it pivots to “Power Platform PACE”, supporting [Client]'s move into the
                                                     automation and analytics capabilities described in Section 4, Pillar C. Task Systems owns the
                                                     annual scoping conversation with [Client] and translates it into Microsoft's delivery plan.

                                                                                                                                      12

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

#### 5.2 Unified Support Response-Time Commitments

                  Task Systems tracks every incident raised by [Client] against the following backend commitments from
                  Microsoft's Unified Support engine, and takes ownership of chasing, escalating and reporting on them so
                  [Client] never has to:

                                  Severity                           Response Time                                  Coverage

                    Critical Sev 1                   15 minutes (Azure) / 1 hour (all other products)   24x7

                    Sev A                            1 hour                                             24x7

                    Sev B                            2 hours                                            24x7, available upon request

                    Sev C                            4 hours                                            Business hours

#### 5.3 Microsoft Teams Multilingual Interpretation

                  A major requirement identified during the Bid Site Visit is native real-time multilingual interpretation and
                  transcription within Microsoft Teams a natural priority for [Client] given its official working languages of
                  English, French and Portuguese. Microsoft confirmed at the site visit that this capability falls outside the
                  current commercial scope of this procurement and that Microsoft will engage [Client] separately to
                  discuss available options and the product roadmap.

                  Task Systems' position is to treat this as a live, tracked work-stream rather than a closed item. Our
                  approach is as follows:

                        ●    Continued engagement: We will maintain an active liaison channel with Microsoft's account team
                             throughout the contract term specifically on this requirement and will formally relay any roadmap
                             updates to [Client] as they become available.

                        ●    Interim capability bridge: Teams Premium (already reflected in our licence structure in Section 4,
                             Pillar A) delivers intelligent meeting recap, live translated captions in select languages, and AI-
                             generated notes providing a meaningful interim capability while native real-time interpretation
                             matures.

                        ●    Third-party interoperability: Where [Client] requires certified simultaneous interpretation for
                             high-stakes multilingual sessions (e.g. Council of Ministers, Parliament sittings) ahead of native
                             Teams capability, we will support integration with [Client]-approved interpretation service
                             providers operating alongside Teams, without compromising the platform's core security posture.

                                                                                                                                       13

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                        ●    Reflected updates: Any change to Microsoft's roadmap or commercial position on this capability
                             during the contract term will be reflected in our quarterly service reviews and, where material, in
                             a formal change request to the Contracting Authority.

### 6. Phased Azure Adoption and Three-Year Implementation Roadmap

                  In line with [Client]'s stated intent that “Azure adoption begin at the Commission before extending to
                  other Institutions and Agencies,” Task Systems proposes a disciplined, three-year phased roadmap that
                  sequences the CSP-to-EA transition, security hardening, and cloud/automation adoption so that value is
                  delivered continuously rather than backloaded to contract end.

                                             Figure 3: Three-year phased CSP-to-EA transition and Azure adoption roadmap.

                                                                                                                             14

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

#### 6.1 Milestones and Deliverables

        Year                                 Milestone                                           Key Deliverable

                                                                     Signed-off transition completion report; Phase 1 tenants (8
     Year 1         Mobilisation, EA transition & E7 upgrade
                                                                     institutions) fully on EA/E7; BCP activation test completed.

                                                                     Remaining 5 institutions onboarded to EA; Zero-Trust/Conditional
     Year 2         Phase 2 onboarding & security hardening
                                                                     Access rollout; Power Platform pilot enablement.

                                                                     Full 13-tenant hybrid maturity; Power Platform PACE engagement
     Year 3         Optimisation & Power Platform PACE               delivered via Task Systems-directed Designated Engineering; renewal-
                                                                     readiness report to [Client].

### 7. Service Level Agreements and Support Model

                  Task Systems commits unconditionally to the Service Level Agreement matrix specified in the Terms of
                  Reference. Our incident management process covering logging, prioritisation, tracking and resolution will
                  be operated through the Services Hub portal in coordination with Microsoft Unified Support, ensuring
                  every incident is classified, routed and resolved within the following bounds:

                               Incident Severity                   Response Time                          Resolution Time

                    Critical                             15 minutes / 30 minutes               4 hours

                    High                                 30 minutes / 1 hour                   8 hours

                    Medium                               2 hours / 4 hours                     24 hours

                    Low                                  8 hours / 24 hours                    48 hours

                  Beyond incident response, our maintenance commitment covers: regular software updates, patches and
                  service packs; quarterly system checks and performance monitoring; comprehensive data backup and
                  recovery procedures; security update and vulnerability management; user support and training on the E7
                  platform; ongoing capacity planning and optimisation; and structured skills transfer to [Client]'s
                  technical teams, each mapped one-to-one to the obligations set out in the Terms of Reference, Section B
                  (Comprehensive Technical Maintenance).
                                                                                                                                    15

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                  All software, hardware and configuration changes will be tested and certified in collaboration with the
                  [Client] technical team before being placed into full production, and all data handling will comply with
                  applicable data protection and privacy requirements, particularly for confidential [Client] institutional
                  data.

### 8. Business Continuity Plan (BCP)

                  [Client] confirmed at the Bid Site Visit that a comprehensive Business Continuity Plan is a mandatory
                  component of the technical proposal and will form part of the evaluation criteria. Task Systems maintains
                  a live, previously activated Business Continuity Plan, first issued 1 April 2024 and proven operationally
                  during the COVID-19 pandemic. We present it below, tailored to the scope of this contract, as evidence
                  of a business continuity capability that has already been tested under real disruption, not merely a
                  document produced for this bid.

                  Our BCP is designed to ensure that Task Systems can sustain its obligations to [Client] including SLA-
                  bound incident response, licence administration and Unified Support coordination through disruptive
                  events including loss of premises, loss of information, loss of personnel, natural disasters, terrorist
                  incidents and pandemics, by heavily leveraging the same Microsoft technology stack we deploy for our
                  clients.

#### 8.1 General Prerequisites (Digital-First Resilience)

                  All Task Systems documents, templates and workflows are digitised and centrally retained, so that no
                  single point of failure (a person, an office, or a device) can interrupt service to [Client]:

                        ●    Documents & Templates: All standard documents (proposal templates, invoicing, purchase order
                             issuance, profitability analysis) are digitised and stored in a common Microsoft SharePoint Online
                             repository.

                        ●    Cloud Work Folders (Microsoft OneDrive): Every employee including the team assigned to
                             [Client] works from cloud-based individual, departmental and executive folders, enabling work
                             from any location or device, with access rigorously restricted by role.

                        ●    Workflow & Approval Digitisation: Document workflow and approvals run through Microsoft
                             Dynamics 365, with electronic signature for digital sign-off, removing dependency on physical
                             presence for authorisation of [Client]-related transactions.

                                                                                                                            16

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                        ●    Payment, Purchasing & Invoicing: Supplier payments, purchase order issuance and invoicing are
                             conducted through digital channels (Microsoft Dynamics 365 and secure online banking), ensuring
                             financial continuity in support of [Client] engagements.

                        ●    Data, Bandwidth & Work Tools: Every team member is equipped with a laptop, mobile device and
                             data allocation, with a minimum throughput of 5 Mbps and at least 5 GB per week, ensuring the
                             [Client] support team remains productive from any location during disruption.

#### 8.2 Human Resources Continuity

                  In the event of disruption, HR functions continue uninterrupted via Microsoft Teams: daily attendance
                  monitoring (staff log in by 8am with HRMS App through the day), employee engagement (one-on-one,
                  one-to-many and many-to-many sessions between 8am–5pm, Monday to Friday), and staff training and
                  empowerment sessions (present, collaborate, whiteboard and co-author), ensuring the engineers and
                  support staff assigned to [Client] remain trained, engaged and accountable at all times.

#### 8.3 Client Engagement Continuity

                  Customer and sales engagement including meetings, RFP/RFQ clarifications, bid meetings and product
                  knowledge updates moves fully onto Microsoft Teams (or an [Client]-preferred alternative such as Cisco
                  WebEx or Zoom, both of which are compatible with our systems) during any disruption. Our Company
                  Weekly General Meeting (every Monday, 9am) and Weekly Sales Meeting (every Monday, 10am) continue
                  without disruption via Teams, ensuring [Client] account status, escalations and delivery risks always
                  remain visible to our leadership, even during a crisis.

                  8,4 Procurement and Supply Chain Continuity
                  Our procurement team processes purchase orders and supplier engagement through SharePoint,
                  Microsoft Dynamics 365 and Power Automate including for Microsoft licence renewal and provisioning
                  relevant to this contract. During disruption we commit to providing [Client] with constant status updates
                  on any pending licence or hardware orders, engaging suppliers to understand their own contingency
                  plans, and leveraging licensed third-party logistics partners where physical delivery is required.

#### 8.5 Finance and Audit Continuity

                  Finance and Audit functions remain fully operational through Microsoft Dynamics 365 and online payment
                  channels, ensuring Task Systems can continue to meet its financial obligations to Microsoft critical to
                  preventing any interruption of [Client]'s licensing continuity, exactly as required by the Administrative
                  Requirements of the Terms of Reference. Daily dashboard reporting on the company's financial position

                                                                                                                         17

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                  ensures management maintains full visibility of the business's ability to sustain its Microsoft financial
                  commitments throughout the contract term.

#### 8.6 Technology Enablement Summary

                                             Function                                  Current Continuity Tool

                    Work Folder / Repository                            SharePoint Online, OneDrive

                                                                        SharePoint, Microsoft Dynamics 365, OneNote,
                    Document Management & Control
                                                                        OneDrive

                    HR Attendance & Engagement                          Microsoft Teams, HRMS App

                    Sales & Client Engagement                           Microsoft Teams, Email

                    Procurement & Supply Chain                          Microsoft Dynamics 365, Power Automate

                    Finance                                             Microsoft Dynamics 365, SharePoint

                    Audit                                               Microsoft Dynamics 365

                    Meeting Management                                  Microsoft Teams, Email

#### 8.7 Proven Track Record: COVID-19 Continuity

                  This BCP is not theoretical. During the COVID-19 pandemic, Task Systems activated this same plan to
                  protect employees, suppliers, customers, subcontractors, agents and OEM partners: maintaining
                  stakeholder communication via email, phone and Teams; monitoring government, WHO and NCDC
                  guidance; implementing travel restrictions; and sustaining all customer and business partner meetings
                  remotely via Microsoft Teams until in-person interaction was unavoidable (e.g. physical product delivery).
                  This real-world activation is direct evidence that Task Systems' Business Continuity Plan will protect
                  [Client]'s service continuity, not merely satisfy a bid requirement.

                                                                                                                         18

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

### 9. Company Profile, Technical Prowess and Track Record

                  Task Systems Limited is a leading technology and digital transformation company with over 38 years of
                  proven excellence in delivering end-to-end ICT solutions, enterprise systems integration, cloud services,
                  cybersecurity, data and AI, and managed services. Driven by innovation and backed by a world-class
                  Technology Experience Centre, we help public and private sector organizations modernize their IT
                  environments, enhance operational efficiency, and accelerate digital transformation through secure,
                  scalable, and resilient technology solutions.

                  As a long-standing Microsoft Solutions Partner and authorized Microsoft reseller, Task Systems Limited
                  has extensive experience delivering Microsoft-based enterprise solutions across Nigeria and the West
                  African region. With fully operational offices in Lagos (Victoria Island), Abuja (Garki), and Port Harcourt,
                  we maintain a strong nationwide presence in Nigeria the host country of the [Confidential Client — Regional Intergovernmental Institution]
                  providing the technical expertise, local support, and logistical capability required to successfully deliver
                  and sustain technology initiatives for the [Confidential Client — Regional Intergovernmental Institution] and its institutions.

#### 9.1 Track Record

                  Task Systems' credibility on this bid rests on more than capability statements: we have already delivered
                  large-scale, enterprise-grade Microsoft and ICT engagements for some of Nigeria and the region's most
                  demanding organisations institutions that, like [Client], operate across multiple locations, carry stringent
                  security and regulatory expectations, and cannot tolerate service disruption. Our portfolio of enterprise
                  and public-sector clients includes:

                    Sector                               Representative Clients

                                                         Central Bank of Nigeria (CBN) · Central Bank of Ghana · Access Holdings Plc ·
                    FSI, Manufacturing & Public Sector
                                                         Nigeria Commodity Exchange (NCX) · Dangote Group · Zenith Bank Plc

                    Telecommunications                   MTN Nigeria

                    Oil, Gas & Energy                    Nigeria LNG (NLNG) · Seplat Energy · NNPC Limited · Chevron Nigeria Limited

                                                         A broad portfolio of enterprise and public sector clients across the financial
                    Wider Enterprise Portfolio           services, telecommunications, energy, manufacturing, and government
                                                         sectors, for whom Task Systems Limited has successfully delivered Microsoft

                                                                                                                                     19

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                    Sector                             Representative Clients

                                                       licensing, cloud, cybersecurity, digital workplace, and systems integration
                                                       solutions of comparable scale and complexity to the [Client] engagement.

                  These engagements directly demonstrate the qualification criteria set out in the Bidding Document
                  evidence of having previously supplied and installed similar Microsoft systems for globally recognised
                  organisations with users spread across geographically distant locations, and at least two similar contracts
                  delivered in the last five years. Full reference letters and contract evidence for these engagements are
                  provided in our Bid Submission Forms.

#### 9.2 Vision and Strategic Direction

                  Task Systems' 3-Year Strategic Business Plan (FY25–FY27) sets out a clear ambition: to be recognised as a
                  leading IT services provider distinguished by technical excellence, a customer-centric approach, and the
                  ability to drive genuine business transformation through Microsoft solutions. This ambition is
                  underpinned by planned investment of $10 million across FY25–FY27 in talent acquisition, technology
                  development, marketing and strategic partnerships directly building the capacity required to serve large,
                  multi-institution engagements such as this one.

#### 9.3 Solutions Area of Focus

                             Solution Area                                Relevance to This Engagement

                                                Active practice in Azure migration and modernisation, Azure AI/Machine
                    Azure (Cloud Services)      Learning, and cloud security via Azure Security Center directly underpinning the
                                                phased Azure adoption roadmap in Section 6.

                                                Established Microsoft 365 deployment practice, including advanced
                                                security/compliance features (Microsoft Information Protection, Compliance
                    Modern Workplace
                                                Manager) and Microsoft Teams integration for custom workflows the core of
                                                this bid's scope.

                                                Dedicated cybersecurity practice covering Microsoft Defender, Azure Security
                    Security                    Center and Sentinel, with a roadmap toward Zero-Trust architecture and 24/7
                                                managed security services.

                                                In-house engineering experience with ERP solutions including SAP, ATLAS and
                    Dynamics 365 / ERP
                                                IRIS, satisfying the Terms of Reference requirement for a team with solid ERP

                                                                                                                                20

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                             Solution Area                                  Relevance to This Engagement

                                                   deployment and support experience (Dynamics 365 itself is confirmed out of
                                                   scope for this specific procurement).

#### 9.4 Technical Prowess Development

                  Task Systems is actively expanding its technical bench strength in AI, machine learning and cybersecurity,
                  and is pursuing advanced Microsoft certifications including Azure Expert MSP and Security Advanced
                  Specialisation directly relevant to the Enhanced Designated Engineering for Security and Designated
                  Engineering Tier 2 workstreams described in Section 5. Our medium-term roadmap includes establishing
                  a Centre of Excellence (CoE) in AI, machine learning and cybersecurity to support exactly the kind of large-
                  scale, multi-tenant public-sector engagement represented by this [Client] contract.

#### 9.5 Market Position

                  Task Systems operates across the full Microsoft partner spectrum as a Licensing Solution Partner (LSP),
                  Cloud Solution Provider (CSP), Value-Added Reseller (VAR), System Integrator (SI) and Managed Service
                  Provider (MSP) giving [Client] a single partner capable of covering licensing, cloud consumption,
                  integration and ongoing managed operations without the coordination overhead of multiple vendors.

### 10. Skills Transfer, Training and Knowledge Management

                  The Terms of Reference explicitly require the facilitation of skills transfer to [Client] technical teams to
                  strengthen internal capacity. Task Systems will deliver this through a structured programme rather than
                  ad hoc knowledge-sharing:

                        ●    Quarterly hands-on workshops for [Client] IT Directorate staff covering hybrid identity
                             administration, Teams governance, security/Defender configuration and license management
                             within the EA.

                        ●    Shadowing and co-delivery: [Client] technical staff are paired with Task Systems engineers
                             during Phase 3 (Controlled, Institution-by-Institution Cutover) of the transition described in
                             Section 3.3, ensuring institutional knowledge is transferred during, not after implementation.

                                                                                                                                21

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                        ●    Access to Microsoft's on-demand education, hands-on labs and expert-led webcasts included
                             under Unified Support (Section 5.1), curated and contextualised for [Client] by our team.

                        ●    A living knowledge base, hosted on SharePoint Online, documenting [Client]-specific
                             configurations, escalation paths and runbooks owned jointly by Task Systems and the [Client] IT
                             Directorate.

                        ●    End-of-year capability reviews aligned to the roadmap milestones in Section 6, formally assessing
                             and reporting on [Client] staff readiness to assume greater operational ownership as the
                             contract matures.

### 11. Risk Management

                                     Risk                                                     Mitigation

                                                           Parallel operation and staged cutover methodology (Section 3.3) with rollback
             Service interruption during CSP-to-EA
                                                           checkpoints at every phase; Task Systems acts as sole interface with Microsoft
             transition
                                                           to prevent license lapses.

                                                           Phase 1/Phase 2 architecture (Section 3.1) decouples the Commission's core
             Delay to Phase 2 institution onboarding       rollout from dependent institutions, so Phase 2 delays do not block Phase 1
                                                           value delivery.

             Coordination gap between Task Systems'        Task Systems owns the end-to-end relationship as [Client]'s single
             client-facing delivery and Microsoft's        accountable partner (Section 5.3), with delivery responsibilities agreed with
             backend Unified Support engine                Microsoft at contract start and reviewed quarterly.

             Delay in native Teams multilingual            Interim capability bridge via Teams Premium and optional third-party
             interpretation capability                     interoperability, with continuous roadmap tracking (Section 7).

             Business disruption to Task Systems' own
                                                           Task Systems' digitally native, previously activated Business Continuity Plan
             operations affecting [Client] service
                                                           (Section 8), tested during COVID-19.
             delivery

             Security incidents across a 13-tenant,        Microsoft Defender Suite across all seats, Enhanced Designated Engineering
             multi-country environment                     for Security (800 hrs/year), and SLA-bound incident response (Section 7).

                                                                                                                                   22

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

### 12. Compliance Matrix

                  The table below maps Task Systems' response against the key administrative and technical requirements
                  of the Bidding Document and Bid Data Sheet.

                                                  Requirement                                                      Status

                                                                                             Compliant (confirmed by Microsoft
                    Authorised Microsoft reseller for 10+ years
                                                                                             partnership documentation)

                                                                                             Compliant (offices in Lagos, Abuja and Port
                    After-sales service logistics in an [Client] Member State
                                                                                             Harcourt, Nigeria).

                    Proof of Microsoft Partnership                                           Compliant (enclosed)

                    Business Continuity Plan (mandatory)                                     Compliant (full BCP presented in Section 9)

                    Hybrid architecture integrating Microsoft Cloud with on-premises
                                                                                             Compliant (Section 3.2)
                    infrastructure

                    Multi-tenant EA with [Confidential Client — Regional Intergovernmental Institution] as Lead Tenant                    Compliant (Section 3.1)

                                                                                             Compliant (Section 7, adopted without
                    SLA Matrix (Critical/High/Medium/Low response & resolution times)
                                                                                             deviation)

                    Skills transfer to [Client] technical teams                                Compliant (Section 11)

                                                                                             This proposal is submitted in English, per IB
                    Bid Language
                                                                                             Clause 10.1

                    Prices firm for 3 years                                                  Confirmed in the Commercial Proposal.

### 13. Conclusion

                  This Technical Proposal has been built, deliberately and methodically, from three sources: the formal Terms of
                  Reference in the [Client] Bidding Document, the first-hand outcomes of the [Client] Bid Site Visit in Abuja, and
                  Task Systems' own proven operational and technical capability including a Business Continuity Plan that has already
                  been tested in a real crisis, not merely drafted for this bid.

                                                                                                                                   23

## Technical Proposal

Strictly Confidential

*— page break —*

Technical Proposal | PP-2026-ADD-GOODS-018

                  Task Systems Limited offers [Client] a single, accountable Microsoft LSP partner capable of executing a secure,
                  hybrid, multi-tenant Enterprise Agreement transition; structuring licensing directly around [Client]'s digital
                  transformation priorities; leading the delivery of Unified Support as [Client]'s single point of contact, powered by
                  Microsoft's own global support organisation on the backend; and sustaining service delivery under our own tested
                  Business Continuity Plan all delivered under an unconditional commitment to the [Client] SLA matrix over a
                  disciplined three-year roadmap.

                  We respectfully conclude that this proposal demonstrates both full compliance with the Bidding Document and a
                  genuine, evidence-based understanding of what will make this project succeed for [Client], its Commission, and its
                  family of institutions and agencies across West Africa. We look forward to the opportunity to serve as [Client]'s
                  Microsoft partner for the years ahead.

                                                                                                                                 24

## Technical Proposal

Strictly Confidential

*— page break —*

