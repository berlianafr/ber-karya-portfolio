---
layout: default
title: "SEAT: Seat Allocation & Electoral Candidate Selection"
permalink: /projects/seat/
---

[Back to portfolio]({{ '/' | relative_url }})

# SEAT: Seat Allocation & Electoral Candidate Selection

**Personal project | Ongoing**
_Technologies: Google Apps Script, Google Sheets, Gemini API, Automation_

## Problem

Seat allocation from scanned election result forms (Formulir D Hasil) was done by hand, which took days.

## Solution

An end-to-end tool that turns scanned result forms (PDF) into parliamentary seat allocations and elected-candidate lists.

- Gemini API extracts vote counts from uploaded PDFs.
- Users verify the extracted data before any calculation runs.
- The Sainte-Laguë method calculates seat allocations for political parties.
- Elected candidates are selected automatically from candidate vote counts.
- Results export to a central Google Drive folder, with a per-user calculation history.

**Key concept:** AI extracts. Humans verify. The system calculates and generates.

## Outcome

Processing time dropped from days to hours. Three rounds of testing added API error handling, retry, and a manual data-entry fallback.

<details markdown="1">
<summary>How I built it</summary>

Describe your architecture, prompts, validation steps, and testing here.

</details>
