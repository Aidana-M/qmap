# qmap

### Your future is not a list. It's a route.

QMAP is a university admission planning platform designed to help students understand their current profile, explore suitable universities, find opportunities to strengthen their applications, and build a personalized admission roadmap.

Instead of showing students a simple list of universities, QMAP connects:

**Profile → Gaps → Opportunities → Improvement → Roadmap**

---

## Problem

University admissions require students to manage many different factors at once: academic results, standardized tests, extracurricular activities, university requirements, deadlines, financial considerations, and application routes.

This information is often spread across different websites, making it difficult for students to understand what they should focus on next.

## Solution

QMAP brings these elements together into one interactive platform.

The user can create a profile, explore universities, identify areas for improvement, find relevant opportunities, compare universities, simulate possible profile improvements, and follow a personalized roadmap.

---

## Main Features

### University Map

Universities are organized into three categories:

- **Reach**
- **Target**
- **Strong Fit**

These categories describe the relationship between the user's profile and the university's requirements. They are not admission probability predictions.

Each university page provides information such as:

- location
- intended major
- application route
- tuition
- financial aid
- deadlines
- language requirements
- profile gaps
- relevant information sources

### Dream List

Users can save universities they are interested in and use them as part of their admission planning.

### Opportunity Finder

QMAP connects a student's profile with opportunities that could help strengthen their application.

The recommendation logic follows:

**Dream University → Profile → Gap → Relevant Opportunity**

The prototype includes opportunities such as research programs, competitions, hackathons, entrepreneurship programs, volunteering, and other extracurricular activities.

### University Comparison

Users can compare universities based on factors such as:

- major fit
- location
- budget
- language requirements
- research environment
- application route

The comparison presents differences between universities rather than selecting a single "best" university.

### What-if Simulator

Users can change hypothetical values such as:

- SAT score
- IELTS score
- extracurricular profile

The simulator shows how these changes affect the user's available routes within the prototype.

It is not an admission probability calculator.

### Admission Roadmap

QMAP converts the user's profile and identified gaps into actionable steps.

Examples include:

- improving IELTS
- preparing for the SAT
- developing a STEM project
- gaining research experience
- preparing application materials

Users can mark actions as completed as they progress.

### Onboarding

The onboarding process collects basic information about the student's:

- education
- intended field
- dream university
- current priority

This information is then used to personalize the initial experience.

---

## Tech Stack

| Component | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 |
| Application logic | Vanilla JavaScript |
| Fonts | Google Fonts |
| Backend | None |
| Database | None |
| External APIs | None |

The current version is a client-side web prototype and does not require a backend server.

---

## Architecture

The project consists of three main files:

```text
QMAP
├── index.html
├── styles.css
└── app.js
