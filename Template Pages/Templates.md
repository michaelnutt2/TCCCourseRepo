# Canvas Course Page Templates

A collection of ready-to-use HTML templates for building polished, consistent pages inside Canvas LMS. Each template is self-contained, fully commented with `<!-- INSTRUCTION: -->` markers, and designed to be pasted directly into the Canvas HTML Editor.

## How to Use Any Template

1. Open your Canvas course and create or navigate to the appropriate item (Page, Assignment, etc.).
2. Switch to the **HTML Editor** view.
3. Copy and paste the entire contents of the template file into the editor.
4. Switch back to the **Rich Content Editor** to fill in your content, or continue editing in the HTML view.
5. Follow the inline `<!-- INSTRUCTION: -->` comments to replace every placeholder with your actual content.
6. Update all `href="#"` placeholder links to point to your real course pages and assignments.

---

## Template Index

### Course Setup & Navigation

---

#### `Home_Page.html`
The course **Front Page** — the first thing students see when they open the course. Features a dark header banner with the course name and subtitle, a two-column layout with a welcoming introduction on the left and a "Getting Started" quick-launch panel on the right. Designed to orient new students and provide immediate links to the most important course resources.

**Key sections:** Course header banner · Welcome message · Getting Started checklist · Quick-link navigation panel

---

#### `Syllabus.html`
A clean, lightweight **syllabus page** intended for courses that store detailed policies elsewhere (e.g., a "Start Here" module). Includes a table of contents with anchor links, an instructor overview section, a learning philosophy section, a course policies callout that directs students to the Start Here module, and a responsive weekly schedule table.

**Key sections:** Table of Contents · Class Focus / Instructor Overview · Learning Philosophy · Course Policies (linked externally) · Tentative Weekly Schedule

---

#### `Syllabus_Full.html`
A comprehensive **all-in-one syllabus page** with a dark header and every section an instructor needs. Uses ALL_CAPS placeholders for easy find-and-replace. Suitable for courses where the full syllabus lives on a single Canvas page.

**Key sections:** Instructor Information · Course Description & Objectives · Required Materials · Grading & Assignments · Course Policies · Weekly Schedule

---

### Weekly Content Pages

---

#### `Weekly_Overview.html`
The standard **week overview page**. Presents a two-column layout: learning objectives and introduction on the left, a green "To-Do This Week" checklist (reading, homework submission, quiz) on the right. The in-class agenda section below shows side-by-side Day 1 and Day 2 panels, each with Warm-up, Conceptual Activities, and In-Class Lab sub-sections.

**Key sections:** Week header · Learning Objectives · To-Do Checklist · Day 1 & Day 2 In-Class Agendas

---

#### `Weekly_Overview_with_Vocabulary.html`
Identical layout to `Weekly_Overview.html` with one addition: each day panel includes a collapsible **📚 New Vocabulary** accordion. Instructors can list key terms and definitions that expand inline without cluttering the page. Ideal for introductory or terminology-heavy courses.

**Key sections:** Week header · Learning Objectives · To-Do Checklist · Day 1 & Day 2 Agendas · Collapsible Vocabulary lists per day

---

#### `Weekly_Overview_Reveal_Accordian.html`
A more **interactive variant** of the weekly overview where every in-class agenda item (warm-up, activities, lab) is individually wrapped in a `<details>`/`<summary>` accordion. Students can expand only what they need, keeping the page clean and reducing cognitive load. Best for content-heavy weeks.

**Key sections:** Week header · Learning Objectives · To-Do Checklist · Day 1 & Day 2 Agendas (all items collapsible)

---

#### `Weekly_Overview_Resources.html`
A weekly overview variant built for **resource-rich weeks**. Adds a dedicated supplemental resources panel alongside the standard agenda. Uses named placeholder tokens (e.g., `DATE1`, `WARMUP_LINK`) for rapid bulk find-and-replace rather than prose instructions. Suited for instructors who copy and reuse a master template each week.

**Key sections:** Week header · Learning Objectives · To-Do Checklist · Day 1 & Day 2 Agendas · Supplemental Resources panel

---

#### `Weekly_Overview_Special.html`
A weekly overview designed for **weeks with project milestones or non-standard deliverables**. The To-Do sidebar is split into two callout boxes: the standard green "To-Do This Week" panel and a red "🚀 Project Milestones Due" panel. Useful for weeks that coincide with major project check-ins or presentations.

**Key sections:** Week header · Learning Objectives · To-Do Checklist · Project Milestones Due callout · Day 1 & Day 2 Agendas

---

### Assignment Pages

---

#### `Assignment.html`
The standard **assignment description page**. Provides a consistent, professional layout for any Canvas assignment. Includes a large header with an emoji icon, an overview paragraph, a blue learning-objectives callout, detailed task instructions, a grading rubric or criteria section, and submission/resource links at the bottom.

**Key sections:** Assignment header · Overview · Learning Objectives · Task Instructions · Grading Criteria · Submission links & Resources

---

#### `Assignment_Reveal_Accordian.html`
An **accordion-style assignment page** where every major section (Learning Objectives, Instructions, Rubric, Resources, etc.) is hidden inside a collapsible `<details>` element. The overview paragraph is always visible; everything else expands on demand. Reduces page length and lets students focus on one section at a time.

**Key sections:** Assignment header · Always-visible Overview · Collapsible: Learning Objectives · Instructions · Rubric · Resources & Submission

---

### Project Pages

---

#### `Project_Hub.html`
A **central hub page for a multi-milestone project**. Features a prominent project title header, a project overview paragraph, a learning-objectives callout, and a series of milestone cards — each showing the milestone name, description, due date, and a link to the corresponding assignment. Includes a sidebar with supplemental resources. Instructors add or remove milestone cards as needed.

**Key sections:** Project header · Project Overview · Learning Objectives · Milestone cards (repeatable) · Resources sidebar

---

#### `Case_Study.html`
A structured **case study briefing page** designed for Socratic seminar or research-and-discuss workflows. Presents a real-world incident (e.g., a security breach, business failure, ethical dilemma) with a narrative, guiding questions, and starter resources. Includes a two-column panel showing written prep requirements and discussion expectations, plus submission buttons for the written report and the Canvas discussion.

**Key sections:** Incident header with tagline · Incident Narrative · Guiding Questions · Starter Resources · Written Prep Requirements · Discussion Expectations · Submit / Discussion buttons · Previous/Next week navigation

---

### Informational & Reference Pages

---

#### `Development_Env_Rust.html`
A **developer environment setup guide** specific to Rust and GitHub Codespaces. Walks students through a one-time initial setup (GitHub account, GitHub Classroom, Home repository, Codespace creation, Rust toolchain, git-cliff, pre-commit hooks) and then explains the professional Git workflow for both individual assignments and group projects, including branching, committing, changelog generation, pull requests, and peer code review.

**Key sections:** One-Time Setup (step-by-step) · Professional Git Workflow · Individual Assignment Workflow · Group Project Workflow (with Peer Code Review)

---

#### `How_to_ask_for_help.html`
A **student help guide** explaining how to get unstuck professionally. Introduces the course norm of using GitHub Issues instead of email, then walks through a 3-step process: (1) investigate independently for at least 15 minutes using rubber duck debugging and documentation, (2) open a detailed GitHub Issue using the Bug Report template, and (3) tag teammates or the instructor for escalation.

**Key sections:** The Golden Rule · GitHub Issues as the help system · 3-Step Process: Investigate → Create Issue → Tag for Help

---

#### `Student_Resources.html`
A **two-column reference page** consolidating external learning resources and campus support services. The left column lists programming and technical resources (language documentation, Git guides, diagramming tools). The right column covers TCC and campus resources such as academic support, tutoring, and library services.

**Key sections:** Programming & Technical Resources (with sub-categories) · TCC & Campus Resources

---

## Template Conventions

All templates share these design conventions so your course looks cohesive across every page:

- **Max width:** 900px, centered, with a light border and rounded corners
- **Font:** System sans-serif
- **Primary text color:** `#1f2937` (headings), `#4b5563` (body)
- **Accent callouts:** Blue (`#eff6ff` / `#60a5fa`) for learning objectives; green (`#f0fdf4` / `#22c55e`) for to-do lists; amber (`#fffbeb` / `#f59e0b`) for warnings or guiding questions; red (`#fef2f2` / `#ef4444`) for deadlines
- **Accordion / collapsible sections:** Use native HTML `<details>`/`<summary>` — no JavaScript required
- **Navigation buttons:** Dark gray (`#4b5563`) for Previous/Next week links; blue or green for primary action buttons
