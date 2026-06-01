# Rachel Atkeison Portfolio

A polished software engineering and creative technology portfolio for Rachel Atkeison. The site is built as a single-page recruiter experience that presents technical projects, visual work, music, role fit, and contact information in one cohesive flow.

## Current hero

**Software with a living pulse.**

This headline frames the portfolio around reliable technical systems with creative energy, interaction, and human-facing polish.

## What this portfolio is meant to show

This portfolio is designed to make Rachel easy to understand and easy to evaluate for software engineering, creative technology, front-end, UI/product, and audio software roles.

It highlights:

- Real-time and distributed system thinking through Aureine Live.
- C++ audio development through LumenBloom.
- Unity and spatial interaction through CloudStage MR Studio.
- Audio-reactive visualization through Aureine Visual Engine.
- MIDI and creative tool design through Aureine Music Box.
- Product presentation, visual design, writing, and communication through the portfolio itself.

## Main sections

1. **Prologue**  
   Fast recruiter-facing introduction, direct contact, resume actions, proof buttons, and portrait card.

2. **Spark**  
   Rachel's working style: curiosity, systems thinking, explanation, revision, and learning through building.

3. **Project Atelier**  
   The strongest technical work, organized around real interfaces, architecture, screenshots, proof blooms, and expanded project reads.

4. **Art Garden**  
   A visual design section showing how years of art practice support hierarchy, polish, composition, motion, and interface instincts.

5. **Music Garden**  
   AUREINE music work, including First Frost, Vol. I and Bloom Circuit positioning, used to show audio intuition, release discipline, and product empathy.

6. **Capability Garden**  
   Skills grouped by what they help Rachel build, so the section reads as evidence rather than a generic tool list.

7. **Path**  
   Resume kit and role compass connecting the same project foundation to software engineering, creative technology, UI/front-end, and music technology roles.

8. **Contact**  
   Direct email, GitHub, LinkedIn, resume, YouTube, and music links.

## Featured projects

### Aureine Live
A real-time distributed music collaboration engine built with Python, PySide6, asyncio, WebSockets, NumPy, and sounddevice. It shows networking, synchronization, shared state, timing, replay visualization, and interface design.

### LumenBloom
A polyphonic C++/JUCE synthesizer plugin with MIDI input, voices, oscillators, envelopes, filters, modulation, effects, presets, and DAW-facing plugin structure.

### CloudStage MR Studio
A Unity and spatial audio environment with playable instruments, performer/listener modes, reactive lighting, in-world controls, and a JUCE synthesis bridge.

### Aureine Visual Engine
A real-time audio-reactive visualization system that maps audio features into particles, waveforms, spectrum visuals, bloom behavior, and responsive visual states.

### Aureine Music Box
A creative MIDI and harmony tool focused on musical interaction, generative patterns, visual polish, and a clear interface for exploring sound.

## File structure

```text
PORTFOLIO SUPREME/
├── index.html
├── resume.pdf
├── README.md
└── assets/
    ├── art/
    ├── aureine-live/
    ├── cloudstage/
    ├── lumenbloom/
    ├── music-box/
    ├── portrait/
    └── visual-engine/
```

## How to preview locally

Open `index.html` directly in a browser.

For the most reliable local preview, run a tiny local server from inside the `PORTFOLIO SUPREME` folder:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## How to deploy to GitHub Pages

1. Create or open the repository used for the portfolio.
2. Upload the contents of the `PORTFOLIO SUPREME` folder, not the zip file itself.
3. Make sure `index.html`, `resume.pdf`, `README.md`, and the `assets` folder are at the repository root.
4. In GitHub, go to **Settings** then **Pages**.
5. Set the source to the main branch and root folder.
6. Save and open the published GitHub Pages link after GitHub finishes deploying.

## Resume integration

The portfolio includes `resume.pdf` at the root of the site folder. Resume buttons in the portfolio point to:

```text
resume.pdf
```

The download name is set as:

```text
Rachel_Atkeison_Resume.pdf
```

When replacing the resume later, keep the file name as `resume.pdf` unless the HTML links are also updated.

## Recent consolidated updates

This cleaned version replaces the scattered update notes with one cohesive README. It includes the latest portfolio state:

- Hero updated to **Software with a living pulse.**
- Current resume integrated as `resume.pdf`.
- Resume buttons preserved with correct download behavior.
- Hero spacing expanded so punctuation and gradient text do not clip.
- Art buttons adjusted for readability while keeping the soft glowing visual style.
- Music, art, project, skills, path, and contact sections preserved.

## Maintenance notes

- Keep image file paths unchanged unless the matching references in `index.html` are updated.
- Keep `resume.pdf` in the root folder for download buttons.
- Keep project images inside their existing asset folders so the galleries and modals continue to work.
- Use the README for all future change notes instead of creating separate README update files.

## Contact

Rachel Atkeison  
rachel.atkeison@gmail.com  
Portfolio: rachelatkeison.github.io  
GitHub: github.com/rachelatkeison
