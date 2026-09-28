Michael "Tchella" Ordor

Manager, Audio, Voice & Dialogue — Miva Open University / uLesson Group Abuja, Nigeria

I lead the Audio and Sound Design team, covering post-production for educational video, AI voice workflows, and music and sound design for advertising. Most of what I build sits at the point where audio production meets automation: internal tools that take slow, manual studio work and make it something a non-technical team member can do in a few minutes.

Alongside that I work as a recording artist and songwriter under the name Tchella, with a catalogue spanning 30M+ streams across personal and co-written work.

Accentuate https://accentuate-xi.vercel.app/

An internal AI speech generation and localisation tool, built for Miva's content production workflow.

Production teams needed lecturer audio re-recorded constantly — a mispronounced name, a changed sentence, a correction three weeks after the shoot. Each fix meant getting a lecturer back into a studio. Accentuate removes that step.

A team member uploads or records a voice sample, pastes a script, and gets audio back in that lecturer's voice with authentic Nigerian delivery — correct pronunciation of Nigerian names, places and context-specific terms, plus natural pacing and intonation.

What it does

Generate Script — long-form scripts to speech in a cloned voice
Voice Swap / ADR — replace a take's voice while keeping the performance
Convert Audio — transcribe existing audio and regenerate it in another voice
Podcast — multi-speaker dialogue from a script, up to four distinct voices
Voice Library — a shared, searchable set of saved voices for the whole team
Speed control with a "Match 100 WPM" function, matching the pace the instructional design team specifies for scripts

Built with React, Vite, Vercel, the ElevenLabs API, Google Apps Script (for usage and access logging), SoundTouchJS (pitch-preserving time-stretch), pdf.js (script ingestion).

My role — product direction, interface design, and implementation. Scoped the problem with the production team, built the tool, and ran the internal pilot through to team adoption.
<img width="1473" height="768" alt="Screenshot 2026-09-28 at 14 19 13" src="https://github.com/user-attachments/assets/b4dabefc-f461-4716-af86-95f6ffc1dc40" />
<img width="1489" height="766" alt="Screenshot 2026-09-28 at 14 15 10" src="https://github.com/user-attachments/assets/e16afff0-38e1-4572-b8fc-67ad24be0a49" />
<img width="1494" height="756" alt="Screenshot 2026-09-28 at 14 14 48" src="https://github.com/user-attachments/assets/38044f78-e91f-4c1b-9727-452bde482638" />
<img width="1492" height="768" alt="Screenshot 2026-09-28 at 14 16 41" src="https://github.com/user-attachments/assets/55905866-22b2-4466-b1a9-8e9629b4776f" />

Miva Engage

A case-study learning platform that lets students work through a business case six different ways.

Built around the idea that people engage with the same material differently. One case study — Shell's Niger Delta dilemma — presented as six parallel paths:

A generated podcast discussion of the case
A conversational AI tutor students can interrupt and question by voice
An immersive audio experience
A branching decision simulation
The source document itself
An understanding check that grades spoken answers on reasoning quality rather than fact recall, and coaches where the reasoning is thin

Built with React, Vite, the ElevenLabs Agents SDK (custom voice interface, not the off-the-shelf widget), Google Gemini for grading, the Web Speech API.

My role — concept, learning design, and build.

Accentuate Usage Dashboard

A small internal analytics site tracking Accentuate usage across the team — characters generated, audio duration processed, active accounts, and a breakdown by team member and by feature. Built so the decision to move the tool onto company infrastructure could be argued with actual numbers.

Built with React, Vite, Vercel, Google Sheets as the data layer.
<img width="958" height="765" alt="Screenshot 2026-09-28 at 14 21 01" src="https://github.com/user-attachments/assets/86048348-4674-4204-9072-bc1e379d4714" />



Other work
Interactive course modules for Miva — lesson materials and learning experiences built for the university's content library
Serenaid Entertainment — a CAC-registered venture; booking and vendor platform work (serenaid.co)
Music — releases as Tchella, an Afro Soul sound, plus co-writing credits
Background

B.Eng. Electrical and Electronics Engineering, Covenant University (2016). Working independently as a recording artist, songwriter and creative entrepreneur since 2017.

The engineering background is why these tools exist: I keep running into production problems that are really systems problems, and it's usually faster to build the fix than to schedule around it.

Most of the repositories here are private — they're internal university tools and several contain credentials. Happy to walk through any of them, or give a live demo, on request.
