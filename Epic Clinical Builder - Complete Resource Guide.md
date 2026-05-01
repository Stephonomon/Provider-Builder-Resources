# Epic Clinical Builder: Complete Resource Guide

---

> **📌 Important Note for Readers Outside CHOP**
>
> This document was originally developed at the **Children's Hospital of Philadelphia (CHOP)** for its Epic Clinical Builder program. Many references throughout are specific to CHOP — including environment URLs, ticketing systems (ServiceNow), internal contacts, organizational names (DTS), SharePoint sites, and builder tier names ("Padawans," "Jedi Knights," etc.).
>
> **Before sharing or adopting this guide at another organization, review and update the following:**
> - Environment URLs and access methods (e.g., `[redacted]`)
> - Ticketing and workflow systems (ServiceNow references, Content Management setup)
> - Internal contact names and email addresses
> - Naming convention prefixes (e.g., "CHOP" → your organization's prefix)
> - Builder tier names and governance structures (CDS Committee, ACMIO roles, etc.)
> - Analytics/CDW access pathways
> - Epic training course registration processes
>
> The core principles, Epic build concepts, and governance frameworks are broadly applicable and should require only targeted updates to reflect your organization's specifics.

---

## Table of Contents

1. [Introduction to Epic Clinical Building](#1-introduction-to-epic-clinical-building)
2. [Choosing Your Training Path](#2-choosing-your-training-path)
3. [Program Policy and Governance](#3-program-policy-and-governance)
4. [Getting Started as a New Builder](#4-getting-started-as-a-new-builder)
5. [Training and Certification](#5-training-and-certification)
6. [Maintaining Your Certification](#6-maintaining-your-certification)
7. [Accessing Epic Environments](#7-accessing-epic-environments)
8. [Building in Epic: Standards and Style](#8-building-in-epic-standards-and-style)
9. [Tracking, Submitting, and Migrating Build](#9-tracking-submitting-and-migrating-build)
10. [Clinical Decision Support: OPA Standards](#10-clinical-decision-support-opa-standards)
11. [Advanced Tools: Epic Studio and Lookitt](#11-advanced-tools-epic-studio-and-lookitt)
12. [Pathways to Clinical Informatics](#12-pathways-to-clinical-informatics)

---

## 1. Introduction to Epic Clinical Building

Epic Systems offers builder courses and certifications for providers that allow them to configure tools in Epic. The potential benefits of active clinical builders include:

- Increased provider build engagement
- Efficiency in request processing
- Reduced workload for project teams
- Improved usability of the EHR

Clinical Builders are clinicians who are engaged with Epic processes and understand the enterprise goal of organizational improvement. Builders are considered from across specialties and settings. The time builders spend in the role will vary and includes collaborating with lead specialty analysts and other users, in addition to time for building content.

### Who Makes a Good Builder?

Potential builders should have the following prior experience and interests:

- Minimum 3 years of recent clinical patient care (training and other settings included)
- Clinical workflow redesign or quality improvement interest and/or experience
- Exceptional communication, organization, critical thinking, and analytical abilities
- Knowledge of Best Practice or Evidence-Based guidelines in their specialty
- Interest in translating technical terminology for understanding by non-technical audiences
- Interest in collaborating between DTS and clinical leadership
- Advocacy for the use of technology in the clinical setting
- Implementation, optimization, and support of the electronic health record

### Program Purpose

- Support provider engagement in design, build, and improvement of Epic
- Improve efficiency of change implementation to Epic content
- Improve the usability of Epic
- Define the credentials, role, and responsibilities of Clinical Builders

---

## 2. Choosing Your Training Path

At CHOP, clinicians have two main training options to enhance their Epic skills: **Physician Builder Training** and **STAR WARS** (SmartTool Training and Review for Willing And Ready Specialists). Both pathways give providers more control over their workflows and reduce ticket turnaround times, but they serve different needs.

### Side-by-Side Comparison

| Feature | Physician Builder | STAR WARS |
|---|---|---|
| Depth | Advanced, broad Epic build | Targeted SmartTools only |
| Certification | Required — Epic class + IS onboarding | Not required — videos + meeting |
| Commitment | Ongoing, ~0.1 FTE recommended | Short training (~82 min) |
| Skill Level | Experienced Epic user, leadership bridge | Everyday clinician, workflow-focused |
| Tools | SmartTools + Navigators, Advisories, Orders, Reporting | SmartLists, SmartTexts, SmartPhrases, Preference Lists |
| Best For | Providers who want to lead system-level improvements | Providers who want quick, practical documentation fixes |

### Physician Builder Training

**Scope:** Broad, advanced Epic build capabilities for clinicians who want to design and maintain tools for themselves and their colleagues.

**Who it's for:**
- Physicians and other providers (NPs, fellows, psychiatrists, etc.)
- Clinicians with 2+ years of Epic experience
- People interested in advanced customization and governance-level building

**Training Content:**
- SmartTools (SmartPhrases, SmartLists, SmartTexts)
- BestPractice Advisories
- Visit Navigators
- Reports (Chart Review, Snapshot, Sidebar, Schedule)
- Doc Flowsheets
- SmartForms
- Orders/SmartSets
- Preference Lists
- Reporting Workbench

**Commitment & Structure:**
- Epic-provided classes (virtual or in-person; free except travel/lodging)
- Certification required
- Work with Information Services for access and policies
- Estimated 0.1 FTE time commitment (may increase)
- Departmental support recommended but not required

**Skills Needed:**
- Strong communication, organization, and analytical skills
- Experience bridging IT and clinical leadership
- Understanding of Best Practice or Evidence-Based guidelines
- Ability to translate technical terms for non-technical audiences

**Impact:**
- Faster ticket turnaround
- Greater autonomy in creating and supporting specialty-specific workflows
- Broader influence across departments

### STAR WARS (SmartTool Training and Review)

**Scope:** Focused, practical training on a limited set of Epic SmartTools.

**Who it's for:**
- Clinicians familiar with their workflow
- Specialists who want targeted SmartTool skills without full Builder responsibilities

**Training Content:**
- SmartLists
- SmartTexts (letters, forms, templates)
- SmartPhrases
- Editing Preference Lists
- Content Management (moving build from DEV to PROD)

**Commitment & Structure:**
- Four online modules + ~82 minutes of video training
- Access to development environment (DEV) after completion
- Script and resource packet provided
- Participation survey required to enroll

**Skills Needed:**
- Interest in customizing documentation and workflow tools
- Basic comfort with Epic (no advanced build expertise required)

**Impact:**
- Faster fixes for documentation tools within your clinic or specialty
- Practical build access without larger system responsibilities
- Lower barrier to entry compared to Physician Builder Training

### Decision Guide

Use the following framework to decide:

- **Choose STAR WARS if:** You want to quickly improve documentation templates, SmartPhrases, and SmartLists specific to your practice, with minimal ongoing commitment.
- **Choose Physician Builder if:** You want to take on an ongoing role in system-level building, work on BestPractice Advisories, Navigators, Order Sets, or Analytics, and are prepared for certification and collaboration with IS analysts.

---

## 3. Program Policy and Governance

### Definitions

- **Clinical Content** – Epic content in documentation, workflows, and actions in the process of patient care.
- **Clinical Builder Leads** – Experienced provider mentors who are certified in Epic and can provide support to Clinical Builders as well as help develop and review policies and procedures. Clinical Builder Leads review and approve all build performed by Clinical Builders.
- **Certification** – Requires a demonstration of mastery-level knowledge in an area of the software. Reserved for trainees who receive the best possible learning experience by attending class in Verona, WI.
- **Accreditation** – Requires a demonstration of mastery-level knowledge in an area of the software. Indicates the trainee has been trained by Epic staff on the content but has not received training at Epic in Verona, WI (includes Virtual).
- **Proficiency** – Recognizes individuals that receive Epic training and demonstrate a basic understanding of an area of the software. Proficiency status alone will not be sufficient to have access to build environments.

### Builder Tier Structure

There are tiered groups of Clinical Builders in Epic:

#### Tier 1 — SmartTool Only (aka Younglings)
- Complete CHOP's STAR WARS training, **OR**
- Completion of Epic's NoteCraft Training

#### Tier 2 — Beginner Builders (aka Padawans)
- Receive certification or accreditation in Builder Analytics, Builder Healthy Planet, or Clinical Content Builder
- Adhere to approved processes for ticket requests, design, building, testing, training, and release into Production
- Translate clinical workflow needs to advanced builders
- Participate in monthly builder meetings, Slack Channel discussions, and Clinical Builder presentations

#### Tier 3 — Intermediate Builders (aka Jedi Knights)
- Receive certification or accreditation as Physician Builder
- Work directly with IS analyst partner and consult with Clinical Builder Lead
- Adhere to approved processes for ticket requests, design, building, testing, training, and release into Production
- Mentor Beginner Builders on appropriate design and build based on workflow requirements
- Participate in monthly builder meetings, Slack Channel discussions, and Clinical Builder presentations

#### Tier 4 — Advanced Builders (aka Jedi Masters)
- **Prerequisite:** Intermediate Builder experience for at least 2 years and approval from a Clinical Builder Lead
- Work directly with IS analyst partner and consult with Clinical Builder Lead
- Adhere to approved processes for ticket requests, design, building, testing, training, and release into Production
- Mentor Beginner Builders on appropriate design and build based on workflow requirements
- Participate in monthly builder meetings, Slack Channel discussions, and Clinical Builder presentations

### General Build Principles

- All build shall be done in accordance with the rules and restrictions from Information Services (IS) and organizational guidelines with regards to naming and structure.
- Builders are expected to document and maintain an inventory of all content built (see [Style Guide and Build Considerations](#8-building-in-epic-standards-and-style)).
- Metadata (who built the record, reasons for change, and date of change) should be recorded in all SmartTool build records (e.g., comments section).
- Review of existing content should occur prior to initiating build of new content. New build should be reviewed and discussed with the respective Analyst and Provider Lead to ensure there is not existing content that could satisfy the need.
- All requests to modify or create new content must be documented and submitted through the established migration process. Only clinical content approved through this process may be implemented in PRD.
- Set aside protected time to do build so projects can be completed in a timely fashion.
- Builders are expected to maintain certification and complete training with each subsequent Epic upgrade. Failure to do so may lead to a suspension of builder security until completed.
- If Builders exhibit a pattern of disregard for the policies and principles outlined, their access to Development environments will be revoked.

### Approval Process

1. To obtain certification or accreditation, a potential candidate must discuss their interest with a Clinical Builder Lead for approval.
2. Candidates must also obtain approval from their Division Chief. Builders may require support from their Division including protected time and may require travel/hotel financial reimbursement for required Epic training courses.
3. The Associate Chief Medical Information Officers (ACMIOs) and Clinical Builder Leads will be responsible for both identifying and managing Clinical Builders.

### Security Access by Builder Tier

#### SmartTool/Notecraft Only

| Content/Item | Security Access | Analyst Support Required |
|---|---|---|
| SmartText, SmartLists, SmartLinks | Yes | No |
| SmartPhrases | Yes | No |

#### Physician Builder Certification

| Content/Item | Security Access | Analyst Support Required |
|---|---|---|
| SmartText, SmartLists, SmartLinks | Yes | Yes |
| SmartGroups/Order Panels | Yes | Yes |
| SmartSets/Order Sets | Yes | Yes |
| Documentation Flowsheets | Yes | Yes |
| Review Flowsheets | Yes | Yes |
| BestPractice Advisories | Yes | Yes |
| Notewriter | Yes* | Yes |
| Synopsis | Yes | Yes |
| Workflow Engine Build | View Only | Yes |
| Navigators | Yes | Yes |
| Order Transmittal | View Only | Yes |
| Profiles | View Only | Yes |
| Print Groups/Reports | Yes | Yes |
| Chronicles | View Only | No |
| Text | Yes* | Yes |
| Data Courier | No | No |
| Security (User Roles, Menus, Templates, Security Class) | No | No |
| SmartData Elements, Smartforms | Yes | Yes |
| SmartPhrases | Yes | Yes |
| Preference Lists | Yes | Yes |
| Groupers | Yes | Yes |
| Columns | Yes | Yes |

> *Yes\* = May view, but never build without analyst and provider lead support first*

#### Healthy Planet, Data Analytics, or Clinical Data Model Certification Required

| Content/Item | Security Access | Analyst Support Required |
|---|---|---|
| Reporting Workbench Reports | Yes | No |
| Reporting Workbench Templates | Yes | Yes |
| Registry Editor | Yes* | Yes |
| Registry Monitor | View Only | Yes |
| Groupers | Yes | No |
| SlicerDicer | Yes | Yes |
| Radar Dashboards | Yes* | Yes |
| Patient-entered Questionnaires | Yes* | Yes |
| Health Maintenance | Yes* | Yes |

### Epic Environments

#### Non-Build Environments

- **PROD (Production)** – Environment used for direct patient care. No build should occur directly in this environment.
- **Support (SUP)** – Non-production environment used for troubleshooting, refreshed daily with a copy of PROD. Any content built will be wiped clean the next day. Contains real patient data — take care not to access PHI unless absolutely necessary. Access may be granted to Advanced builders only based on IS analyst determination.
- **Development Verification (DC VER)** – Similar to SUP; refreshed every two months with a copy of PROD. Contains real patient data. Content built here cannot be migrated to other environments. Access may be granted to Advanced builders only based on IS analyst determination.
- **TST** – Intermediate step in the Path to PROD. Once content is moved from DEV to TST, it must be validated before moving to PROD. No changes to content should be done in TST — go back to DEV for any changes. Change management requirements exist for this environment.

#### Build Environments

- **Development (DEV)** – Build environment that allows IS teams and builders access to configuration that has the potential to be migrated to Production. Because many analysts use this environment, there is a risk that anything built could get changed by others at any time. DEV is one environment in which Clinical Builders will have access to analyst tools.
- **DC DEV** – A copy of DEV for preliminary investigations and configuration without change management requirements. Refreshed monthly with a copy of DEV. Build in DC DEV cannot be migrated to DEV or Production. Ideal for new Builders to try out new ideas or demo them for other users.

### Builder Accounts

#### SmartTool/Notecraft Only

**Hyperspace/EMP Build in DEV and DC DEV ONLY:**
- Username: `(Epicusername)EDIT`
- Template: `CHOP CLINICAL SMARTTOOL EDITOR — DO NOT MIGRATE [T200211]`

#### Beginner, Intermediate, and Advanced Builders

**Hyperspace/EMP Build in DEV and DC DEV ONLY:**
- Username: `(Epic Username)EDIT`
- Template: `CHOP Clinical Builder — DO NOT MIGRATE [T00078]`

#### Account Creation Timeline

| Builder Type | Process | Estimated Time |
|---|---|---|
| Clinical Builder | Two tickets to Security Account Administration (edit account + e_account elevation); third ticket to DBA team for TEXT access connection | ~2 weeks (longer during Epic upgrades) |
| SmartTool/Notecraft | One ticket to Security Account Administration to create edit account | ~1 week |

### Measuring Program Value

Evaluating the impact of your builder program requires thinking across two dimensions: **who your builders are** and **what they are building**.

#### Tracking Your Builder Population

Start by maintaining a clear picture of the builder community itself. Key metrics to track include:

- Total number of active builders
- Specialties and departments represented
- Provider types (physicians, NPs, fellows, nurses, etc.)
- Years since initial certification (to identify those approaching recertification or needing additional support)

**Recommended approaches:**
- **Clarity extract** — Use the provider builder EMP template as your source to identify current builders in your system
- **Reporting Workbench** — Build reports to monitor builder counts and attributes over time
- **Radar Dashboards** — Consider building a dedicated dashboard to give leadership a live view of program size and composition

> **Note:** Because builder activity occurs in the development environment, you may need to partner with your Data and Analytics team to establish a reliable pipeline for extracting this data.

#### Tracking Build Activity and Quality

**Quantitative tracking:**
Content Management system reports can provide a granular view of build activity by INI type (e.g., SmartTexts, SmartForms, BPAs). This gives a useful sense of the volume and categories of build occurring across the program.

**Qualitative tracking:**
Volume alone does not reflect build quality. To get a fuller picture, consider:

- **Regular builder meetings** where builders share work in progress — these create accountability and natural peer review
- **Build purpose and outcome tracking** — document what each build was intended to address and what the measurable or intended outcome is
- **Annual "Year in Review"** — a summary of build activity across the program, organized by specialty and patient population impact. This is a powerful tool for communicating program value to clinical and administrative leadership

#### Framing the Value Case

Conversations about financial return on investment — such as quantifying hours saved relative to analyst-only workflows — can be difficult to make rigorously and often distract from the program's more meaningful value proposition.

A more productive framing is: **What do clinical builders bring to your IS team that would be absent without them?**

Builders are subject matter experts with deep clinical expertise and firsthand workflow knowledge. This positions them to implement build that is not only technically sound but clinically meaningful — a combination that is difficult to achieve through analyst work alone. Their involvement elevates the quality and relevance of the EHR for the patient populations they serve.

---

## 4. Getting Started as a New Builder

Congratulations on getting your Build Certification! You are now on your first steps to becoming a Clinical Builder. As a Clinical Builder, you will play a crucial role in developing and maintaining Epic to support your organization's informatics needs.

### Initial Onboarding Tasks

1. **Submit an IS ticket** to request your builder account.
2. While your account is being provisioned, familiarize yourself with the **Guidelines & Policies** in this document. These will help guide you on standards for building in Epic. Having builder access to development environments is a privilege — these standards must be followed to ensure the proper functioning of your and others' build.
3. *(Analytics Certification only)* Request CDW and/or Clarity access via your IS service desk.
4. Ensure you can access the relevant team collaboration tools (e.g., Teams, Slack).
5. Add the monthly builders meetings to your calendar.

### After Receiving Your Builder Account

After receiving your build account name and password, review the following:

1. [Accessing DEV Environments](#7-accessing-epic-environments)
2. [Accessing TEXT](#accessing-text-reflections-terminal-environment) (an additional ticket is required)
3. [Tracking and Submitting Build via Content Management](#9-tracking-submitting-and-migrating-build)

We encourage new builders to communicate their ideas with other builders. It will help reinforce guidelines and approach to building, build great working relationships, and foster collaboration and knowledge sharing.

---

## 5. Training and Certification

### Physician Builder Certifications

> **Note:** Course requirements are subject to change each year. Always check the Epic Course Catalogue for the most up-to-date class offerings.

#### Physician Builder

**Prerequisites:** Notecraft for Physicians
- **Physician Build Basic (CLN150):** Core build items that a typical builder works on, including SmartTools needed for beginners
- **Physician Build Advanced (CLN160):** Topics such as the Workflow Engine, order transmittal, profile structure, and navigator configuration

#### Physician Builder Analytics

**Prerequisites:** Notecraft for Physicians
- **Physician Build Basic (CLN150)**
- **Physician Build Analytics (CLN171):** Topics such as Reporting Workbench, patient registries, and Radar Dashboards

#### Physician Builder Healthy Planet

- **Physician Build Analytics (CLN171)**
- **Physician Builder Healthy Planet (CLN173):** Topics such as Reporting Workbench, patient registries, Radar Dashboards, patient scoring rules, and health maintenance

#### Clinical Content Builder

Designed for users who are not within Epic's definition of providers (can include nurses).
- **Clinical Content Build Basic (CLN110):** Same content as Physician Build Basic, but does not include BestPractice Advisories
- **Clinical Content Build Advanced (CLN120):** Same content as Physician Build Advanced, but does not include Procedure Smartforms

#### Specialty Tracks (Additional Options)

- Physician Builder Radiology
- Physician Builder Anesthesia
- Pathologist Builder
- Revenue Data Model for Physician Builder

#### Optional Certifications (Requires Prior Physician Builder Certification)

- **Clinical Data Model for Physician Builders** — Builds upon knowledge from Analytics or Healthy Planet classes and prepares a technically advanced physician to understand the Clarity and Caboodle data models and query data using SQL.

### How to Register for Physician Builder Training

1. **Epic UserWeb:** If you don't already have access, visit [https://userweb.epic.com](https://userweb.epic.com)
2. **Training Home:** Once logged in, navigate to the Training Home tab at [https://training.epic.com](https://training.epic.com)
3. **Course Catalogue:** Available at [https://training.epic.com/CourseCatalog](https://training.epic.com/CourseCatalog)
   - Change the **Role Field** to `Physician Builder` or `Clinical Builder`
   - Select courses from the highest version level offered during that year
4. **Registration:** Select your class dates to add them to the cart. Leave the PO/Cost Center blank when completing registration.
5. **Exams:** Schedule with a proctor. Request someone assigned to proctor for you on a specific date/time of your choosing before completing Epic's exam scheduling. For CHOP-specific exam scheduling, open a Service Now ticket.

Questions can be directed to [registrations@epic.com](mailto:registrations@epic.com)

### STAR WARS SmartTool Training

STAR WARS will train you in creating Epic SmartLists, SmartTexts (including forms, letters, and documentation templates), and department-level SmartPhrases. Upon completion, you will be given access to the Development Environment (DEV).

**Epic weLearning courses to watch before enrolling:**
- Introduction to SmartTool Configuration: SmartLists [GEN650]
- Introduction to SmartTool Configuration: SmartTexts [GEN651]
- Introduction to SmartTool Configuration: SmartPhrases [GEN652]
- Introduction to SmartTool Configurations: Editing Preference Lists [GEN316]

**Steps to DEV access via STAR WARS:**
1. Watch the four Epic "weLearning" videos listed above about SmartTool structure and basic editing
2. Complete the REDCap STAR WARS Participant Survey to enroll
3. Receive a link to the STAR WARS Videos (Episodes 1–6; approximately 82 minutes total)
4. Meet with the program coordinator to review questions and receive the script with important links
5. Complete the STAR WARS completion form

> Training is available anytime, anywhere. It all begins with the introduction weLearning links above and the REDCap survey.

---

## 6. Maintaining Your Certification

Certificates are granted on a particular version of Epic. Once completed, trainees maintain their certificates on new versions using the **Continuing Epic Education (CEE)** program, which has two parts:

### Recommended New Version Training (NVT)

Ensures trainees learn about new functionality in a timely way, and aids in maximizing the use of the Epic software. NVTs are only created for an application when the amount of new development in a given version necessitates it.

To complete an NVT:
- Read an NVT document and take an online quiz for each new release
- **Passing score:** 80% or higher
- No limit on the number of attempts
- Trainees are notified of their score via email after taking the quiz

### Application Essentials (AE) Exam

*(Required)* Reinforces knowledge of core application concepts currently covered in training.

- Completed approximately every three years
- Outstanding CEE requirements are visible in the Certifications section on the Training Home page
- To complete: review an Epic-supplied study guide and take a proctored exam
- **Passing score:** 80% or higher for certifications/accreditations; 70% or higher for proficiencies
- Since this is a proctored exam, there is a limit on the number of attempts
- Trainees are notified of their score via email after taking the exam

---

## 7. Accessing Epic Environments

### Accessing the Development Environment (DEV and DC DEV)

To access Epic Development, visit your organization's QA/Development portal.

If you are not seeing a Development or Data Courier (DC) folder, confirm that all tasks in your Request for a Builder Account are complete.

**Steps:**
1. Log in using your regular AD account (e.g., `DOEJ`)
2. Click the **Epic Build Folder**
3. Your build will be done in the **DEVELOPMENT** icon
4. Log into DEV and DC DEV using your **edit account** by adding `EDIT` to the end of your usual login (e.g., `DOEJEDIT`)
   - Default password is your regular AD account password

### Accessing TEXT (Reflections Terminal Environment)

Reflections TEXT provides access to Epic's underlying database via a terminal interface. Access requires an elevated account (e_account).

**Prerequisites:**
- You must have an elevated (e_account) — request one via your IS service desk if you don't have one
- Reset your e_account first to set a password before attempting access

**If access is not working:** Open a ticket specifying that you are a Clinical Builder who cannot access Reflections Text.

**Access portal:** `[redacted]` (works both on-network and off-network; off-network requires MFA)

**Loading TEXT:**
1. Log in using your regular AD account (e.g., `tylerd`)
2. Click **Apps** and filter to **Attachmate**
3. Choose the environment:
   - **Epic Unix QA1** = DEV
   - **Epic Unix QA2** = DC DEV
4. Log in using your elevated account (e.g., `e_tylerd`)
5. Once logged in, use your edit account to access tools:
   1. Type `2` to open `EPIC_Epic_Application_Menu`
   2. Enter your non-elevated account name and password (e.g., `tyleredit`)
   3. Press `F7` and scroll down to favorite apps such as Epic Ambulatory
   4. Epic Ambulatory is good enough for all tools and will not limit what you need for building in TEXT

> **Internal Note:** Access to TEXT is controlled by membership in the CPA Reflection AD group.

### Accessing SUP (Support Environment)

SUP (aka Epic Support) is an environment that is a copy of Epic Production, updated 3–4 times per week. It is often used by analysts to solve problems found in Production without making changes to Production data.

Builders sometimes request access to SUP to verify build that was already in Production for a specific patient. Certain tools like the rule and BPA editors are also unlocked in SUP, allowing real-time modifications to figure out what changes need to be made in DEV.

**To request access to SUP:**
1. Open your IS Service Desk and place a ticket
2. Select **Modify Existing Epic Access**
3. Request subtemplate `CHOP NON-PRODUCTION ACCESS SUBTEMPLATE [T00268]` be added to your regular Epic account (not your edit account)
4. Request access to the SUP icon in Citrix

Once you have access, log in using your regular non-edit Epic name and password.

### Epic Foundation Hosted Environment

Epic Foundations (the Foundation System or Foundation Hosted environments) is Epic's out-of-the-box reference build. It includes Epic's recommended configuration, workflows, content, and sample data. Organizations and project teams use it to:
- See current development
- Preview upcoming features
- Understand Epic's preferred build patterns

Epic maintains region-specific versions (US, Canada, UK, Australia) adjusted for local workflows and regulatory needs. These environments are hosted by Epic, **refreshed daily**, and intended for exploration rather than permanent build. They contain sample patients, recommended workflows, and pilot features, but no interfaces or production-grade customizations.

**Steps to access:**
1. You must have an Epic UserWeb Account
2. Go to [https://access.epic.com](https://access.epic.com) — you may need to request access, which will send a verification email
3. Look for the latest version of the **FS Hosted Hyperspace**

The version order is: **August → November → February → May → (repeats)**

Contact your Builder Lead for the shared user-account login spreadsheet for your organization.

---

## 8. Building in Epic: Standards and Style

### Preparing a Build Project

Before embarking on Epic build, ask yourself and the relevant stakeholders these questions:

- What problem are you trying to solve with your build?
- Who are the key stakeholders (who will be using what you build)?
- What are your tool options, and how do you know you are using the right tool?
- What is the potential impact of your build vs. the build time?
- How will your build fit into existing workflows, or does the build necessitate a new process?
- Does your build involve the capture of discrete data?

### General Build Considerations

1. **Only modify records within your scope of build training.**
2. **Only modify records within your specialty.** If your build is shared with other areas, contact your Build Provider Leads for guidance. You may need to coordinate with other stakeholders including Information Services.
3. **Maintain clear records of the changes you made**, both on your own and within the records themselves where applicable. Many build tools include a comments section or description where you can add information about why the record was built/modified, by whom, and when.
4. **Test, Test, Test.** Test your build with a variety of different test patients, users, and situations. If you need to test with different Epic users, reach out to your Provider Leads.
5. **When in doubt, reach out to your Provider Leads.**

### Epic Naming Conventions

Consistent naming is essential for record identification, tracking, and organization across the hundreds of thousands of records that exist in Epic.

**Standard naming format:**
1. Add your organization's prefix first (e.g., `CHOP`) — capitalized — to differentiate your records from Epic-baseline records
2. Follow with an abbreviation of the department/specialty (e.g., `GI`, `ORTHO`, `BH`)
3. If the records are specifically for inpatient or outpatient only, consider adding `AMB` or `IP`
4. Include a short description of the record's purpose or contents

**Examples:**
- `CHOP BH CPT 90792 CODING TEMPLATE`
- `CHOP GI AMB NAUSEA SYMPTOMS`
- `CHOP ORTHO IP POST-OP NAVIGATOR`

> **Note:** Some record names (as opposed to display names, such as in BPAs) are visible directly to end-users — consider what may be easier for them to understand. Users accessing records in the future should also have a good idea of what the record is from the name alone.

**Full naming conventions:** Refer to your organization's comprehensive build naming conventions document (available on your internal knowledge base or SharePoint).

### Record Keeping

It is crucial to maintain accurate build records. These help you keep track of what records you have created or modified, and help convey what records need to be moved across environments by IS.

Any record-keeping tool works — consider using **Microsoft Excel** or **Microsoft OneNote** for their tabular format capabilities.

**When tracking records, use the following format:**

| INI | ID | Name | Notes |
|---|---|---|---|
| ETX | 999 | CHOP GI NOTE | new build |
| HLX | CHOPGI#3332 | Nausea Symptoms Adolescent | |
| LPR | 23242 | CHOP PARTIAL DEP CHILD DEV | Items: 34002, 96043 |

Where:
- **INI** = The 3-digit Masterfile of the record
- **ID** = The unique numerical/alphanumerical identifier for the record
- **Name** = The name that accompanies the ID

### Retiring Records

Sometimes records were created in error or are no longer in use.

- Before retiring, check which other records may be using them and what users may be impacted. A communication plan is highly recommended.
- To retire records: open the record(s) and add **`ZZ`** in front of the Record Name(s)
- For records that have the option to be Released (e.g., ETX, ELT, LGL, LQL): release **ALL** versions of the record to make it completely inaccessible
- Add the retired records to a build tracker and submit a ticket to have them moved to Production

### SmartData Elements (SDEs)

Only users who received training on SmartForms should access the SmartData Manager.

**SDE Organization:**
- All SDEs in the SmartData Manager are accessible by IS analysts and Provider Builders — be mindful of the organizational scheme
- SDEs should be created within a hierarchy starting at the highest Division Level down to a Department Specialty
- Consider creating a department-specific prefix to make it easier to locate your SDEs and reduce record conflicts
- If you created an SDE at the wrong level, you can drag it to another node
- If unsure where to start building your branch, reach out to your Provider Build Leads

### Epic Master Files Reference

The following master files are covered in Physician Build CLN150, CLN160, CLN171, and CLN173:

| Master File | INI |
|---|---|
| BestPractice Advisory | LGL |
| Component | IDB |
| Dashboard | IDM |
| Extension | LPP |
| Flowsheet Row/Group | FLO |
| Flowsheet Template | FLT |
| Groupers | VCG |
| Macros | HMA |
| Navigator | LVN |
| Navigator Configuration | VCN |
| Preference List Composer | LPF |
| Print Group | LPG |
| Profile | LPR |
| Property | LRC |
| Registry | HFR |
| Report | LRP |
| Report Columns | PAF |
| Report Info (My Reports activity) | HRX |
| Report Template | HGR |
| Resource | IDK |
| Review Flowsheet (Synopsis and Review Flowsheet activity) | FSH |
| Rule | CER |
| SmartData Element | HLX |
| SmartForm | LQF |
| SmartGroup/Order Panel | OSQ |
| SmartLink | HHS |
| SmartList | ELT |
| SmartPhrase | HH1 |
| SmartSet/Order Set | PRL |
| SmartText | ETX |
| Text Generation | HGN |
| Workflow Engine Rule | LOR |

---

## 9. Tracking, Submitting, and Migrating Build

### Overview

Keeping track of your build is one of the most important parts of developing, testing, and troubleshooting. Good build tracking also facilitates communication and Data Courier (DC) moves by IS Analysts.

> **Contact your analyst team with questions about submitting build:**
> - Inpatient builds: contact your Inpatient IS analyst
> - Ambulatory builds: contact your Ambulatory IS analyst team

### Content Management

Content Management is a tool within Epic for preparing your ticket to be moved to another environment like Production. Through Content Management, you can indicate each record you want to move. If a record is already in another user's Content Management ticket, it will be flagged — preventing users from inadvertently moving each other's records.

**Opening Content Management:**
Access from Chart Search or the Provider Builder Tools Radar Dashboard while logged into the Information Services Login context using your **EDIT** account.

**Completing a CM Ticket:**

1. **Create a New Ticket**
   - Builders need to complete only: **Basic Info**, **Stakeholders**, and **Records/Items**
   - Everything else is handled by the analyst

2. **For first-timers — set your Preferences (quick buttons):**
   - Status = `Ready to Move`
   - Reason = `Provider Builder`
   - Priority = `Medium`
   - Responsible Team = `Epic Ambulatory` (outpatient) | `Epic Inpatient` (inpatient) | `ASAP` (ED)
   - Provide a generic Title and Change Details
   - Leave the Reference Number blank — analysts will add the ticket number

3. **Adding Records:**
   - Enter each record individually, or paste them all at once using **Multi-Entry** from a format like an Excel table:

   | INI | ID |
   |---|---|
   | ETX | 999 |
   | HLX | CHOPGI#3332 |
   | LPR | 23242 |

   - If Epic cannot find a record, an error will pop up — verify you used the correct INI and/or ID
   - Always track both the **Record ID** and **Record Name** — the Record ID can automatically change between environments

4. **Completing Your Ticket:**
   - When finished, use the **Accept** button
   - Note: Builders do not send the ticket to another environment — analysts perform the actual move
   - After accepting the CM ticket, create your build migration ticket and submit the CM number/ID

**Copy Forward:** Content Management has a **Copy** button on the main page. Select a previous CM ticket (click **My Tickets**) and Epic will create a new ticket with some fields already filled in — useful to avoid re-entering Stakeholders each time.

> **Internal Note:** EMP Content Management Class item `91010 - CONTENT MANAGEMENT USER SECURITY CLASS` should be `CHOP CONTENT MANAGEMENT BUILDER [1059999]`

### Pre-Migration Checklist

Before submitting a migration request, verify:

- [ ] Reviewed the Style Guide and Build Considerations
- [ ] Records comply with your organization's naming conventions
- [ ] Content Management ticket created and tracked
- [ ] Both Record ID and Record Name documented (IDs can change between environments)
- [ ] All records are released (or purposefully unreleased if retiring records)
- [ ] Build has been tested:
  - [ ] Tested with a variety of patients and situations
  - [ ] Restrictions work correctly (e.g., BPAs, Rules, SmartTexts, SmartPhrases)
  - [ ] If Production-like patient data is needed for testing, coordinated with an analyst to move build to DC VER first
  - [ ] Testing was **not** done in Production

### Migration Request Types

#### Complete Build

If your build is complete (requires no further testing or analyst intervention):
- Use the **Champion Build Migration** ticket
- Indicate which environment your build should be moved to
- Include your Content Management Ticket ID

#### Partial Build

If your build is partially complete and requires an analyst to do additional work:
- Do **not** enter it as a 'Migration to Production' request
- Instead, enter an **Other Clinical Care** request ticket
- Note the work completed, list all records built, and specify exactly what is still needed

### Migration Process

- Migration requests are batched and done **once per week** (typically Thursday mornings, but may vary)
- If a request is received after the batch is created, it will be included in the next batch
- Urgent or date-specific requests can be coordinated individually
- Provider build is **not** migrated during an Epic Build Freeze — all build will be batched and migrated once the freeze is lifted
- Some build will require additional IS approvals before it can be processed
  - An analyst will notify you and request additional information
  - A testing script will be required (blank script will be provided)
  - The analyst will present build for approval and run additional testing
  - The approval process may take up to 2 weeks

- You will receive a notification as soon as your build is migrated — **validate the build as soon as possible** and reply to the notification if there are any issues

> ⚠️ **If there is an issue with build that has been moved to Production**, reach out to your analyst immediately. They will assess the impact and determine whether it can be changed immediately or must wait.

---

## 10. Clinical Decision Support: OPA Standards

*This section establishes institutional standards for designing and implementing OurPractice Advisories (OPAs) in Epic. It is intended for all staff involved in clinical decision support, including clinical informaticists, nurse informaticists, analysts, and clinical champions.*

> **Reminder:** All interruptive OPAs should come to the CDS Committee for review and approval. For questions, concerns, or to be added to an agenda, contact your CDS Committee (at CHOP: DL-[redacted]).

### Background

Clinical Decision Support (CDS) offers intelligently filtered information to healthcare workers at the time when it is most needed in their workflow. While CDS can take many forms (note templates, care pathways, Order Sets), one of the most common forms of CDS are alerts — known as OPAs (OurPractice Advisories, formerly BestPractice Advisories or BPAs) in Epic.

Despite their prevalence, alerts are overridden >90% of the time, partially due to poor design. Well-designed CDS effectively assists healthcare providers, and it is the responsibility of those involved in informatics to ensure adherence to current best practices.

CDS may be:
- **Interruptive** — a pop-up alert that stops a user from continuing their workflow
- **Non-interruptive** — a banner or notification that doesn't interrupt the workflow

Whenever possible and appropriate, **non-interruptive CDS techniques are preferred**.

### Choosing an Appropriate Alert Type

Not every situation requires an alert. Consider:
- What the person(s) receiving it should do
- The timing of the required actions
- How often the alert should be displayed

If no immediate action is required, other forms of CDS outside of alerts should be strongly considered (e.g., order set suggestions, navigator sections, Storyboard elements).

### Design Standards

#### General Best Practices

- The intrusiveness of the alert and strength of the recommendation should always correlate with the **precision of the alert** and **severity of the potential outcome** you want to avoid.
- Upstream passive decision support (e.g., default selections in order sets, row information) should be provided when most appropriate, to educate the user and/or allow them to intervene before being stopped by an OPA. This can reduce alert fatigue.
- End-user feedback should be **enabled for all OPAs** unless a specific reason is provided to disable this feature.
- Alert design should align with the **Five Rights of CDS**: Right Information, Right Person, Right Format, Right Channel, Right Time.

#### Alert Importance Levels

Use only the following Importance Levels (the level changes color, icons, and hierarchy):

| Level | Color/Style | Use Case | Examples |
|---|---|---|---|
| **Critical** | Highest priority | Action or lack of action may cause death or permanent harm; must be interruptive; use sparingly | Sepsis Screen Positive |
| **Urgent** | High priority | Potential harm to patient, lower severity than Critical; interruptive; use sparingly | Metabolic Emergency Management, MIBG Notification, Initial Sepsis Screen |
| **Advisory** | Default warning | Appropriate for many advisories; consider non-interruptive workflow | Asthma Action Plan needed, PDMP Reminder, Ambulatory Abuse Screen |
| **Information** | Lowest priority | Reminders, suggestions, specific patient info without direct safety implications; should be non-interruptive | Insurance OPAs, Transition of Care |
| **Clinical Pathway** | Pathway variants | Pathway Advisory, Pathway Information or Suggestion | — |
| **Research** | Research variants | Research Advisory, Research Information or Recruitment | — |

#### Alert Content and Language

**General Tips:**
- Avoid abbreviations and acronyms; if acronyms are used, define them
- Use clear language to guide your intended user
- Provide actionable steps whenever possible (e.g., "Enter order," "Discontinue order," "Open order set," "Document flowsheets")
- Include a formatted header row, body text, and summary text for all advisories

**Formatted Header Row:**
- Should be succinct and contain the domain of the alert and specific problem
- Examples: `Allergies – Not Assessed`, `Plan – Not Signed`

**Body Text:**
- Aim for brevity — include only necessary information
- Start with a description of the reason for the alert, followed by supporting patient-specific information
- Example: *"This patient has a diagnosis of asthma and is missing an Asthma Action Plan."*
- Provide additional information about risk with consideration of clinical consequences, but minimize information intended strictly for review
- Link to areas of the chart if more extensive review is needed
- Include actions with direct links or buttons whenever possible

**Summary Text:**
- Appears when an advisory is displayed in the Storyboard OPA Section and with push notification actions

#### Acknowledgment Reasons

- Intended primarily for **suppressing** an OPA for a set period — not for verifying that an action was taken
- Use the **minimum number of reasons** possible. Recommended maximum: **3 choices**
- Use succinct language (e.g., *"Not my patient," "Remind me in 30 minutes"*)
- Use acknowledgment reason comments sparingly — only when the user needs to expand on their choice

**Suppression Settings:**
To avoid excessive re-firing and alert fatigue, suppressing an OPA can rely on settings at the following levels: **User**, **Encounter**, **Lockout Time**. Leveraging more than one setting provides more control over the frequency of OPA firing.

**Removing the Dismiss button:**
- Have at least 1 acknowledgment reason
- Set Acknowledge Reason Requirement to either "Always Required" or "Required if No Action Taken"

**Deferring to Storyboard:** The option to defer an alert to the StoryBoard should be disabled in the Acknowledge Reasons section.

#### OPA Template Design

Use your organization's OPA Design Template Builder to enter sample header and body text, actions, and acknowledge reasons to see a prototype of what your proposed OPA might look like before building.

#### Alert Audience

- Your alert's audience should be **specific and direct**
- Do not use an alert to instruct one group of clinicians to remind or modify the behavior of a second group
- Consider leveraging an existing OPA with a similar target audience as a template
- Leverage **Restrictions and/or Criteria Records** to focus the OPA:
  - Restrictions (Include/Exclude): Service Area, Department, Encounter Type, Provider Type
  - Criteria Record: for cases where restrictions are insufficient (e.g., Treatment Team)

#### Alert Triggers

OPA triggers determine when an OPA should be activated.

- **For Critical, Urgent, and Advisory OPAs:** Triggers should be an immediate workflow action executed by the user (e.g., opening the orders activity), further tailored by criteria logic
  - `"Open Patient Encounter"` is the most interruptive trigger — use with caution
  - `"Sign orders"` can cause issues if the dismiss button is available — see Acknowledgment Reasons for how to address
- **For Informational OPAs:** Assess which part of a user's workflow would be most appropriate (e.g., accessing the general OPA section, entering an order or diagnosis)

### Governance

#### What Alerts Should Be Reviewed at CDS?

Alerts meeting **any** of the following criteria should be reviewed:
- **Interruptive alerts**, regardless of clinical setting and anticipated Importance Level
- **Non-interruptive alerts** that touch multiple clinical settings or involve "high risk" content (e.g., ECMO, blood product ordering, NPO status)

The CDS Committee is willing to evaluate alerts at any point in the development process.

#### After Approval: Re-Review Expectations

- Annual review of a selection of OPAs as determined by CDS co-chairs
- Subject matter expert owners will be responsible for reviewing firing rates, dismissal rates, and design compliance
- Data on OPA compliance and firing rates is available using the Epic SlicerDicer OPA data model

**OPA Ownership Requirements:**
- 2 OPA owners must be identified and documented in the OPA editor Contact Comment box
- If a trainee is included as an owner, identify a 3rd owner
- Identified OPA owners will be the first point of contact for any questions related to the OPA

#### Standards Review Cadence

This standards document is expected to be reviewed **annually** by the CDS co-chairs and designated representatives across the enterprise.

### Troubleshooting OPAs

For advanced troubleshooting of OPAs that don't appear as expected, enable OurPractice Advisory troubleshooting mode within Epic.

### OPA Pre-Build Checklist

Before submitting an OPA to the CDS Committee, complete this checklist:

**OPA Name:** ___________________________  
**OPA Owners (2):** ___________________________

- [ ] Awareness/agreement provided by affected end users/key stakeholders regarding the problem being addressed and alert as an appropriate CDS tool
- [ ] Follows institutional OPA design standards
- [ ] For interruptive alerts — upstream passive decision support recognized as insufficient in the workflow
- [ ] Alerts in navigator left at system default (collapsed). If decision to display default open, documentation in alert for rationale and reviewed with clinical/technical oversight body
- [ ] Appropriate Importance Level chosen
- [ ] Alert text (header and body):
  - [ ] Avoids abbreviations/acronyms and is brief and succinct
  - [ ] Includes an explanation as to why the OPA has fired in the header and summary text
  - [ ] Is actionable, if possible; any hyperlinks have been whitelisted and tested
- [ ] Alert trigger and suppression tailored to audience workflow using restrictors/criteria records
- [ ] (Optional) Run alert in background to review alert firing rates
- [ ] Maximum of 3 Acknowledge Reasons (or rationale documented if more are necessary)
- [ ] Success Tracking defaulted to Action Taken
- [ ] Certain Acknowledge Reason Selected (check all acknowledge reasons that = success if chosen)
- [ ] End-user feedback is enabled
- [ ] Reviewed any notifications displayed in Epic Build Inspector sidebar and addressed as needed
- [ ] Implementation plan established
- [ ] Monitoring and maintenance plan developed for post-go-live review
- [ ] 2 subject matter expert OPA owners identified and documented in Contact Comment box
- [ ] Need for CDS Committee approval confirmed
- [ ] This completed checklist included with CDS submission (if applicable)

### Approved OPA Charms

The following Charms are approved for use in OPAs (use Charm or ClipArt, not both; neither is required):

| Charm Name | Approved Indication |
|---|---|
| ABNORMAL_LAB_CHARM | Abnormal Lab |
| ALLERGIES_CHARM | Allergies |
| AMBULANCE_CHARM | External transfer/transport |
| BLOOD_ADMINISTRATION_CHARM | Blood products |
| CARDIOLOGY_CHARM | Cardiac related |
| CHEMOTHERAPY_CHARM | Chemotherapy |
| CODE_STATUS_DNR_LETTERS_CHARM | DNR |
| DIFFICULT_AIRWAY_CHARM | Critical/Difficult airway |
| FALL_RISK_RED_CHARM | Fall Risk |
| GENOMICS_CHARM | Genomics |
| GYNECOLOGY_CHARM | Gynecology related |
| IMMUNIZATION_CHARM | Immunizations |
| INFECTION_CHARM | Infection/isolation |
| LUNGS_CHARM | Respiratory related |
| KIDNEY_CHARM | Renal related |
| LABOR_AND_DELIVERY_CHARM | Pregnancy |
| NPO_TEXT_CHARM | NPO |
| OPHTHALMOLOGY_CHARM | Ophthalmology related |
| QUESTIONNAIRE_CHARM | Questionnaire |
| RESEARCH_CHARM | Research |
| TOOTH_CHARM | Dental related |
| TRANSLATION_CHARM | Translation |
| WEIGHT_CHARM | Weight |
| X_RAY_CHARM | Imaging |

For additional Charm approvals, email your CDS Committee with the proposed Charm and indication for use.

---

## 11. Advanced Tools: Epic Studio and Lookitt

> ⚠️ **Warning:** Create Caché routines at your own risk. You are responsible for maintaining and supporting any routines you create and must perform regression testing on them prior to upgrades to ensure they still work.

### Prerequisites

- Completion of Chronicles Database Programmer (CHR310)
- Access to TEXT environment

### Epic Studio

Epic Studio allows you to access and edit M Routines in Epic's Caché database.

**Setup:**
1. Request a Caché login from your IS DBA contact
2. Download the latest version of Epic Studio (request the download link from your IS DBA)
3. Install the software
   - If you have administrative access to your computer, you can install Epic Studio on Windows. macOS users will need to consider virtual machine options.
   - If you do not have administrative access, open a ticket requesting that IS install the `.msi` file remotely
4. Add the configuration files:
   - Download the Epic Studio Environments zip from your shared resources
   - Open **Tools > Management Environments > Environment List > Import**
5. Enter your credentials:
   - In the **Environment Manager**: use your Hyperspace Edit account under **Epic Edit User Login** (e.g., `jdoeedit`)
   - Use your Caché User ID (e.g., `e_jdoe`) for the second credential
   - Note: The Caché password is **not** the same as your elevated account password

### Lookitt

Lookitt is a terminal-based tool for exploring Epic's Caché database.

**Access:**
- Physician Builders already have access to Lookitt via their template (`EMP Chronicles Security = CHOP CHRONICLES ADMIN [100069]`)
- Open DEV (regular) or DC DEV in TEXT; after selecting your environment, Lookitt is named `%ZeW_Lookitt` (currently #15)

### Lookitt Macro Cheatsheet

| Key/Macro | Description |
|---|---|
| `?` | Help for Lookitt |
| `;??` | List macros available |
| `.` (single period) | Exit Lookitt |
| `p TAG^ROUTINE` or `p ^ROUTINE` | See the code for a routine. Within a routine, type `/` for a case-insensitive search; press `f` to find the next occurrence. |
| `;eg` | Log a server process. Requires the process ID from Hyperspace (search "about hyperspace"). Right-click after typing `s` to search by user. |
| `//` | Search code base. Leave "Use executable code?" at default "No". For "Routine," entering `*` will search all available routines (can be slow). |
| `d ^%ZdTOOLS` | System Utilities (search and examine jobs) |
| `d ^%ZMSP` | Open the Breeze Editor (F4 to close) |
| `e INI` | Enter chronicle for the specified masterfile (e.g., `e HNO`) |
| `;V` | Open chronicles database for a specific masterfile |

### Managing Long-Running or Runaway Processes

Run the following from Lookitt to access the System Utilities menu:

```
d ^%ZdTOOLS
```

- View running jobs from **3. Examine Jobs**
- To search: use **7. Search Jobs** — try part or all of your username (e.g., `beusj`); can also search for routines

> **Important:** Before terminating any job, confirm it is yours. Check with a more experienced builder the first time you do this.

- Examine the job first (type `E`, then `P` followed by the process ID) — this is also helpful for troubleshooting
- To terminate: type `T`, then `P` followed by the process ID

### Creating and Migrating Routines

> This is advanced territory. IS prefers that you edit and test routines in DC DEV first, then work with your IS contact before proceeding toward a PRD migration.

**Process:**
1. Start with a **Change Request** in your IT service management system so the proposed functionality can be reviewed (Epic Internal Change Control)
2. The change request will require:
   - Test plan
   - Implementation plan
   - Backout plan
3. If approved, discuss loading the routine, data, and testing with your IS contact

**Required information for a routine change request:**
1. Name of routine
2. Purpose/functionality of routine
3. Is this new or enhanced functionality?
4. Is this related to a project (if so, name/PMO number)?
5. Which Epic application team are you working with to validate this routine?
6. Who will perform ongoing SU/Upgrade testing and maintenance to support this customization/routine?
7. Into which environments are you requesting this routine to be loaded?
8. How much data are you looking to load with this routine?
9. Where is the data located?

### Troubleshooting Access

**Roster Error:** If you receive a message indicating a roster issue, your e_account needs to be added to the Lookitt roster. Contact your IS DBA.

**Cannot Edit in Environment:** Contact your IS DBA — the environment may need a configuration change to allow developer editing.

### Helpful Resources

- Chronicles Database Programmer Training Companion (Epic Galaxy)
- Lookitt User Guide (Epic Galaxy)
- Breeze Program Editor documentation
- PAC20: The Other MUMPS — Physician Programmers Explain Their Code (epic.com)

---

## 12. Pathways to Clinical Informatics

*Whether you're interested in becoming an Epic Physician Builder or pursuing advanced training in clinical informatics, this section provides comprehensive pathways for professional development.*

### Formal Graduate Degree Programs

Graduate programs provide comprehensive foundational training in health informatics, preparing graduates for leadership roles in the field.

#### Master's Programs

| Program | Format | Focus |
|---|---|---|
| **University of Pennsylvania — MBMI** | 2-year, in-person, ends with capstone | Informatics, data science, quality improvement |
| **Columbia University — MS in Biomedical Informatics** | On-campus full-time (3 terms) or part-time (up to 4 years) | Clinical databases, decision support, NLP, machine learning |
| **Duke University — MMCi** | 12-month, one weekend per month on campus | Blends informatics with business and management |
| **University of Illinois Chicago — MSHI** | 100% online asynchronous, 30-month, CAHIIM accredited | Digital health, data science, leadership |
| **Johns Hopkins University — MS Applied HI** | Online (36-month) or on-campus (12-month), CAHIIM accredited | Practical competencies in biomedical informatics and data science |
| **OHSU — MS in Biomedical Informatics** | Online or on-campus, thesis or non-thesis, CAHIIM accredited | Health & Clinical Informatics; one of the oldest programs in the US |

#### Fellowship Programs (For Physicians)

- **ACGME Clinical Informatics Fellowships** — 2-year full-time; leads to board certification through ABPM
- See the AMIA list of accredited programs

### Certificate Programs

| Program | Details |
|---|---|
| **Penn — Graduate Certificate** | For Penn faculty, staff, and current graduate students; 4 courses within 2 years from MHCI curriculum |
| **Duke — Clinical Informatics Certificate** | 12-month program for technology-enabled healthcare solutions |
| **HIMSS Applied Health Informatics Certificate** | Focus: Real-world informatics, interoperability, analytics, leadership |
| **Harvard Global Clinical Scholars** | Includes informatics, data science, and quality improvement |
| **AMIA 10x10 Program** | 10-week online introductory course; offered 3x/year; up to 46.5 CME credits; excellent starting point before committing to a full degree |

### Professional Certification

**AMIA ACHIP Certification**
- Mid-career certification for practitioners with various degrees
- Requires: Bachelor's or higher in Health Informatics or a health-related field + documented field experience
- 150-item multiple choice exam at Pearson Vue centers
- Recertification every 4 years

### Internal Organizational Training Programs

*(CHOP-specific — adapt for your organization)*

| Program | Description |
|---|---|
| **Epic Physician Builder Program** | Flagship informatics pathway; requires employer sponsorship; one of the most powerful credentials for internal informatics roles |
| **Data & Analytics (DnA) University** | Foundational data literacy skills; available across CHOP |
| **DnA University Data Fellowship** | 9-week cohort-based training for data-driven decision making |
| **Clinical Analytics Champion Training** | For clinicians to develop analytics skills for quality improvement |
| **CHOP Quality Improvement — Leading Improvement Course** | QI and informatics are closely intertwined |
| **IHI Open School** | Strong overlap with informatics, quality, and safety |

### Data, Analytics, and Technical Skills

**Online Learning Platforms:**
- Coursera: Search Health Informatics, Clinical Data Analytics, FHIR
- edX: Programs from Harvard, MIT, UCSF
- SQL Training: Mode SQL Tutorial, Khan Academy SQL
- HL7 FHIR Fundamentals: FHIR Training by Firely

**Quality Improvement:**
- Lean Six Sigma Healthcare Certifications (Yellow, Green, Black Belt)

**Industry Programs:**
- Stanford Medicine — Clinical Informatics Short Courses
- MIT Professional Education — Healthcare Analytics

### AMIA Membership and Professional Development

AMIA membership provides:
- Access to JAMIA journal
- Discounted conference registration (save $400+)
- AMIA Connect online communities
- Career resources and continuing education

**AMIA Conferences:**
- **Annual Symposium** — November annually (2,000+ attendees, 600+ presentations); 90% of members say it advanced their careers
- **Amplify Informatics Conference** (Spring) — Combines Clinical Informatics Conference and Informatics Summit

### Recommended Pathways by Career Stage

#### Getting Started

| General Track | Academic Track |
|---|---|
| 1. Start with AMIA 10x10 | 1. Consider Penn MHCI (local) or UIC/JHU online MS |
| 2. Join AMIA | 2. Complete 10x10 first |
| 3. Take DnA University classes | 3. Pursue ACHIP after degree |
| 4. Attend Annual Symposium | 4. Stay active in AMIA |
| 5. Apply for Epic Builder | — |

#### Working Professional

| Working Professional Track | Physician Fellowship Track |
|---|---|
| 1. Epic Builder at your organization | 1. Complete AMIA 10x10 |
| 2. DnA Champion Training | 2. Apply for ACGME Fellowship |
| 3. AMIA 10x10 + HIMSS Certificate | 3. Or pursue Duke MMCi |
| 4. Penn MHCI (3-year option) | 4. Get board certified |
| 5. Work toward ACHIP | 5. Consider ACHIP credential |

---

*This document was compiled from resources developed by the CHOP DTS Epic Clinical Builder program by Stephon Proctor, PhD, MBI [proctors@chop.edu](mailto:proctors@chop.edu)*
