# CCVFD Website — Group Overview

Clear Creek Volunteer Fire Department's website provides department information, news, events, safety resources, and ways to volunteer or contribute.

This review covers the eight HTML files in `CCVFD-client ver/CCVFD/Source Code (Legacy)` as of October 18, 2026. 

## What each file does

| File | Purpose and current features |
| --- | --- |
| `index.html` | Homepage: department introduction, featured news, safety reminders, emergency contact information, and links to news, events, membership, and donations. |
| `about.html` | Department background, mission, services, coverage area, and 13 expandable FAQs about volunteering, stations, funding, and response. |
| `community.html` | Membership benefits, parcel-based dues, mailing instructions, and an embedded Google Form for volunteer interest. |
| `contact.html` | Department contact details and website feedback email. Three popup windows contain Google Forms for general contact, community directory opt-in, and newsletter/report signup.|
| `donate.html` | Explains ways to support the department. Links to membership information and an email contact for donations/fundraiser support; no online checkout is implemented. |
| `events.html` | Manually written event announcements, a recent fundraiser recap, and an embedded Google Calendar combining two calendars in agenda view. |
| `news.html` | Full news articles, safety updates, and an archive. Article IDs let homepage buttons link directly to individual stories. |
| `resources.html` | Burn-rule information, preparedness guidance, official agency links, and an embedded Google Drive folder for forms and public documents. |

## How the code works

Each file is a complete page with three parts:

- **HTML:** page text, headings, links, buttons, and embedded content.
- **CSS (`<style>`):** colors, cards, spacing, and layouts that adapt to screen width.
- **JavaScript (`<script>`):** fills in the copyright year, expands FAQs, and opens/closes form popups.

## Maintenance and current gaps

- Keep the eight files together for local previews.
- Update page content in HTML. Update form questions, calendar entries, and shared documents in their respective Google services. Static event/news text does not update automatically from Calendar.
- Shared styling, the seasonal alert, and footer information are copied across all eight pages, so changes must be repeated consistently. No shared navigation menu is included.
- In `about.html`, fix the opening `<h1>` closed as `</h2>` and the inconsistent `503(c)(3)` nonprofit reference.
- Review dated safety notices and event announcements before republishing. Verify public access to intended forms, calendars, and documents, and check FAQ/popup behavior on mobile and with a keyboard.
