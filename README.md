# UIUX Group Project – CCA3

Redesigning two cybersecurity experiences: the **Cybercrime Reporting Portal** and **Sentinel** (a redesign of the Cloudflare Dashboard).

## Group Members

| Name | PRN |
|------|-----|
| Varad Shelke | 1033240023 |
| Shreya Newaskar | 1032232776 |
| Jai Umadi | 1032240065 |
| Vijay Varia | 1032240015 |

## Links

- **Figma Prototype:** [CyberCrime Wireframe](https://www.figma.com/design/r5r1IdifdZKacGv3KSZpNh/CyberCrime-Wireframe?node-id=0-1&p=f&t=K62GyUFplXE09Xzl-0)
- **Demo Website:** [fakecyber.netlify.app](https://fakecyber.netlify.app)

## Deliverables

- **Think Aloud Recordings:** 5 raw audio recordings (`/audio_files`)
- **Transcripts:** Speech-to-text conversions of all 5 sessions (`/transcripts`)
- **Survey / Practical Data:** Previous exercises and supporting Word, Excel, PDF, and other relevant files (`/survey_data`)
- **Prototype:** Figma prototype linked above

## Repository Structure

```
├── README.md
├── audio_files/     # 5 raw audio recordings of the Think Aloud sessions
├── transcripts/     # Speech-to-text transcripts of the sessions
└── survey_data/     # Previous exercises/practical data (Word, Excel, PDF)
```

## Final Conclusion

**Projects.** We chose the cybersecurity domain and redesigned two products. The *Cybercrime Reporting Portal* redesign is for ordinary citizens reporting online fraud or harassment, often while stressed. *Sentinel* is a redesign of the Cloudflare Dashboard for security and IT administrators.

**Evidence.** Before peer review, the cybercrime redesign was assessed by its team, and Sentinel was analysed using 18 UX parameters, Shneiderman's 8 golden rules, Nielsen's 10 heuristics, personas, a journey map and an accessible version for low-vision and colour-blind users. Five peer reviewers (Arhaan Mulani, Mayank Rane, Kavya, Parshva Bora, Soham Pawar) then evaluated the prototypes against the originals through Think Aloud audio sessions and task walkthroughs.

**Common problems in both originals:**
1. Hard-to-understand language (cloud jargon, legal and crime terms)
2. Important options hidden or buried (rules menus, the anonymous reporting option)
3. Little feedback or protection (no save message, no warning before risky changes)
4. Too much information at once (dense settings, crowded homepage)

**What the redesigns changed:**
- **Cybercrime Portal:** cleaner homepage with helpline and anonymous option visible, a step indicator with a four-part form, searchable categories with plain examples, "I don't know" options, auto-save with Save & Exit, accepted file types shown, and an editable review page.
- **Sentinel:** plain-language mode with "i" tooltips, a unified live security overview, rule templates with Duplicate, a DNS safety check with a locked button, Undo on every action, risk-grouped settings, and an accessible high-contrast, colour-blind-safe interface.

**Result.** All five reviewers preferred the redesigned versions. The portal was called "clear, calm and quick"; one reviewer described the Sentinel redesign as more beginner-friendly, organised and reassuring.

**Limitations.** The sample is small and informal, reviewers are classmates rather than real target users, no quantitative measures (task time, errors, SUS) were collected, and both redesigns are limited-scope prototypes. The findings are encouraging, not conclusive.

**Next steps.** Test with real users (crime victims of varied age, language and digital skill; security admins), run moderated think-aloud sessions with at least five target users per project, use a common scale such as SUS, make the anonymous-report privacy promise explicit, move category examples earlier in the portal, and add missing Sentinel areas (Zero Trust, Analytics, mobile layout).

**Takeaway.** In stressful, high-stakes tasks, the interface should reduce uncertainty. Plain language, visible status, built-in safeguards and easy recovery turned both stressful tasks into manageable ones.
