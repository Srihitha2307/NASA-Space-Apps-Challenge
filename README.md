# NASA-Space-Apps-Challenge
# Off-World Odyssey

**Abandoned but Not Forgotten** · NASA Space Apps Challenge 2026 · Team: Srisashi

An interactive 3D web guide that lets kids explore 15 abandoned spacecraft on the Moon, Mars and in deep space: zoom in from a world map, spin each machine, learn what its parts do, watch how it launched, and find out why it stopped.

**Live app:** `<paste your public link>`
**Demo (ppt):** https://docs.google.com/presentation/d/1oSpuAnil3wMMlaEvDuGvE27btUT0BOEM/edit?usp=sharing&ouid=105524767659124107532&rtpof=true&sd=true

**Full walkthrough :** https://youtu.be/wu-qC-_o4XY

**Project video:** https://youtu.be/0EtDlt8f3Pg

## What it does
- **World to mission zoom:** choose the Moon, Mars or Deep Space, then dive into a mission.
- **Spin and learn:** drag to rotate the machine (it only turns when you drag), tap glowing dots to learn each part, and play "find the part".
- **Launch scene:** rocket, staging, and the trip to the destination, with a stage timeline and mission clock.
- **Why it stopped:** signal and power meters fade as the story shows what ended the mission.
- **Stories with voice:** a short narrated story for every mission. Six use real voice recordings (Apollo 11, Luna 9, Pioneer 10, Sojourner, Viking 1, Voyager 1). The rest fall back to browser text-to-speech with captions.
- **Game layer:** quizzes, stars, badges, levels, a level map, and a printable certificate.

## Missions
- **Moon:** Apollo 11, Luna 9, Apollo 17, Chandrayaan-3, Chang'e 4
- **Mars:** Viking 1, Sojourner, Spirit, Opportunity, Perseverance
- **Deep space:** Voyager 1, Voyager 2, Pioneer 10, Cassini, New Horizons

## How to run
No install needed. Open `index.html` in any modern browser, or open the live link. Works on phone and desktop. An internet connection is needed for Three.js and fonts (loaded from CDNs).

## Tech
HTML, CSS, JavaScript, [Three.js r128](https://threejs.org/) (WebGL), Web Speech API (fallback narration), Google Fonts (Fredoka, Nunito, Press Start 2P). All 3D models, textures and animations are generated in code. Progress is saved in the browser (localStorage).

## Data and resources
**NASA**
- NASA mission pages and archives: https://science.nasa.gov/
- NASA Space Science Data Coordinated Archive: https://nssdc.gsfc.nasa.gov/

**Other**
- Three.js: https://threejs.org/
- Google Fonts: https://fonts.google.com/
- Voiceover recordings: recorded by a friend of the team, used with permission

## Use of Super Intelligence (SI)
- **Code:** written with the help of Claude (Anthropic), then tested and directed by the team.
- **Text:** mission summaries, quiz questions and the voiceover script were drafted with Claude and reviewed against NASA sources.
- **Audio:** voice recordings are human-made, not SI-generated. Fallback narration uses the browser's built-in text-to-speech.
- **Images and video:** no SI-generated images or video. All visuals are drawn in code.
- No NASA logos, flags or mission identifiers are used. The certificate states it is not an official NASA certificate.

## Repository contents
```
index.html          the whole app (single file, includes the voice recordings)
docs/walkthrough    7-minute walkthrough video or link
README.md           this file
```

## Known limits
- Only Opportunity and Spirit have the detailed rover model; other models are simpler.
- Nine missions use text-to-speech instead of recordings.
- Mission facts should be checked against the linked NASA pages.

## Credits
Built by Srihitha Reddy (BTech Aerospace Engineering, VIT Bhopal), Ojaswita Jaiswal(BTech Aerospace Engineering, VIT Bhopal) and Antara Verma(BTech CSE- Cybersecurity Engineering, VIT Bhopal) for NASA Space Apps Challenge 2026. NASA and the other agencies are not affiliated with this project.
