# HackTitan 2027 — Official Event Website
## Author: Hirat Rahman
***Date: May 21st, 2026 ***

> **Build the Future** — Illinois Wesleyan University's flagship 24-hour hackathon.
> March 20–21, 2027 · The Patrick Idea Center, IWU · 150 Hackers · $8,000+ in Prizes

---

## About the Event

HackTitan is IWU's premier student-run hackathon, a 24-hour sprint where builders, designers, and dreamers across all majors ship real projects from scratch. No CS degree required. Just curiosity, caffeine, and a problem worth solving.

| Detail | Info |
|---|---|
| **Date** | March 20–21, 2027 |
| **Venue** | The Patrick Idea Center, Illinois Wesleyan University |
| **Duration** | 24 hours |
| **Capacity** | 150 hackers |
| **Team Size** | 1–4 people |
| **Cost** | Free - including all meals, swag, and API credits |
| **Registration** | January 1 – March 15, 2027 |
| **Contact** 

---

## Tracks

| # | Track | Focus |
|---|---|---|
| 01 | **AI & Machine Learning** | LLM apps, computer vision, autonomous agents |
| 02 | **HealthTech** | Digital health, wearables, patient care AI |
| 03 | **Sustainability** | Climate tech, carbon tracking, green energy |
| 04 | **Open Innovation** | Anything that solves a real problem |

---

## Prize Pool — $8,000+ Total

### Track Champions
Each of the 4 tracks awards **$1,000** to the top team.

### Company Challenges
Compete for additional prizes by tackling sponsor-defined problems on top of your track submission.

| Sponsor | Challenge | Prize |
|---|---|---|


### Special Awards


---

## Judging Criteria

Projects are scored across four dimensions by a dedicated panel of industry judges per track:

| Criteria | Weight |
|---|---|
| Innovation | 30% |
| Technical Depth | 25% |
| Impact | 25% |
| Presentation | 20% |

---

## Organizing Team

| Name | Major |
|---|---|
| Hirat Rahman | CS & Neuroscience |
| Ethan Godsey | Computer Science |
| Yohance Williams | Computer Science |
| Zhansen Shingis | Computer Science |

**Advisors:** Dr. Mark Liffiton · Dr. Andrew Shallue (CS Department Chair), Patrick Zajac (Hart Career Center)

---

## Website

The event website is a single self-contained HTML file — no build tools, no framework, no bundler. Everything ships in `hacktitan.html`.

### Stack

| Layer | Choice | Notes |
|---|---|---|
| Markup | Semantic HTML5 | Single file, zero dependencies |
| Styling | Vanilla CSS | CSS custom properties, no preprocessor |
| Logic | Vanilla JS | Inline `<script>`, no libraries |
| Icons | [Lucide](https://lucide.dev) | Loaded via unpkg CDN, rendered client-side |
| Fonts | `system-ui` / Segoe UI stack | Zero web font requests |

### Design System

The visual language is a **dark hacker terminal aesthetic** — deep forest greens, neon accents, PCB textures, and glowing edges.


### Interactive Features

Every interactive element is built with pure CSS and vanilla JS, no external animation libraries.


### Responsive Breakpoints

| Breakpoint | Changes |
|---|---|
| `≤ 1200px` | Laptop/hardware decorations scale down |
| `≤ 960px` | Hero side decorations hidden entirely |
| `≤ 768px` | Nav collapses to burger menu, grids go single-column |
| `≤ 480px` | Countdown shrinks, all grids go 1-col, hero buttons stack |

---

## Running Locally

No build step required. Open the file directly in any modern browser:

```

Requires an internet connection to load Lucide icons from the unpkg CDN. All other assets are inline.

---

## File Structure

```
HackTitan Web/
└── hacktitan.html    # entire website — HTML + CSS + JS, single file
```
