## Play Online

[Play Moon & Mars Base Survival](https://sikiyan.github.io/moon-mars-base-survival/)

# Moon & Mars Base Survival

**NASA Space Apps Challenge 2026 — Build a Junior Astronaut Mission Trainer**  
An independent educational browser game. No NASA affiliation or endorsement is claimed.

## Run the game

Open `index.html` in an up-to-date Chrome or Edge browser. The HTML includes both base illustrations and all six event illustrations. No software installation, API key or internet connection is needed to play. External NASA science links need an internet connection. Sound starts off; switch it on inside the game if desired.

## What the player does

Choose a lunar or Martian outpost, then choose Cadet or Commander difficulty. Spend a limited number of actions each day managing power, oxygen, food and radiation-protection readiness. End the day to apply operating costs. On selected days an illustrated event asks the player to decide how to respond. The event choices show resource changes plus an explanation of the modeled effects. Completing science tasks earns science badges.

Survive through Day 10 with all four resource meters above zero to finish. The game reports a performance medal separately from the difficulty chosen at launch:

| Medal | Result threshold |
| --- | --- |
| Bronze | Finish the mission with every resource above zero |
| Silver | Finish with at least 4 science badges and average remaining resource reserve of at least 40/100 |
| Gold | Finish with at least 6 science badges and average remaining resource reserve of at least 55/100 |

Cadet gives three equipment actions each day and higher starting reserves. Commander gives two actions and lower starting reserves. The medal rules are the same across difficulties. The end screen states the destination, selected difficulty, medal, badge count and reserve average.

## Challenge fit

The official challenge requests an interactive game or app where students manage a lunar or Martian outpost and experience choices involving life support, radiation shielding, power and food production. This project implements those four systems in a short playable mission with decision events and immediate outcomes.

Challenge: https://www.spaceappschallenge.org/2026/challenges/junior-astronaut-mission-trainer/

## NASA science sources

The game's **NASA science** panel contains brief explanations and primary NASA links. Main references include:

- [NASA Life Support Baseline Values and Assumptions Document](https://ntrs.nasa.gov/api/citations/20210024855/downloads/BVAD_2.15.22-final.pdf) — crew metabolic requirements and life-support planning.
- [NASA-STD-3001 habitability](https://www.nasa.gov/reference/7-0-habit-ability-functions-vol-2/) — nutrition planning.
- [NASA Environmental Control and Life Support System](https://www.nasa.gov/reference/environmental-control-and-life-support-systems-eclss/) — oxygen generation and recovery systems.
- [NASA Artemis Science](https://www.nasa.gov/humans-in-space/artemis-science/) — examples of Moon research.
- [NASA lunar ice findings](https://science.nasa.gov/solar-system/moon/nasas-lro-lunar-ice-deposits-are-widespread/) — polar ice observations.
- [NASA Mars science objectives](https://science.nasa.gov/planetary-science/programs/mars-exploration/mars-science-objectives/) — Martian atmospheric and geologic studies.
- [NASA Perseverance science](https://science.nasa.gov/mission/mars-2020-perseverance/science-highlights/) — evidence of ancient Martian environments.
- [NASA Sounds of Mars](https://science.nasa.gov/mission/mars-2020-perseverance/sounds-of-mars/) — atmospheric sound on Mars.
- [NASA lunar exosphere](https://science.nasa.gov/moon/lunar-atmosphere/) — near-vacuum conditions on the Moon.
- [NASA Growing Plants in Space](https://www.nasa.gov/exploration-research-and-technology/growing-plants-in-space/) — plant-growth research for future space exploration.
- [NASA Adds New Science Investigations for Moon Base](https://www.nasa.gov/news-release/nasa-adds-new-science-investigations-for-moon-base/) — planned science investigations for lunar exploration.
- [NASA Radiation Environment — Working on the Moon](https://history.nasa.gov/wp-content/uploads/static/history/alsj/WOTM/WOTM-Radiation.html) — lunar radiation hazards and crew protection.

### Scientific scope

All power, food, oxygen and shield *points* use a fictional 0–100 game scale. Daily costs, event magnitudes and equipment gains were selected for a short educational mission; they were not measured by NASA in these units. The Shield meter tracks maintenance and response readiness; shielding material does not physically decay by a set number of points per day. Science badges represent completed gameplay tasks rather than real scientific output. Some scenario events compress physical processes into a single game day.

## AI use and provenance

- **AI-generated images:** Moon background, Mars background, six event illustrations. Each is visibly identified as `AI-generated illustration` in the interface. No video was generated.
- **AI-assisted code:** HTML, CSS, JavaScript, interface design, animated crew, sound synthesis and event logic.
- **AI-assisted data/text:** fictional game parameter values, event effects, science summaries, instructional text and project descriptions. Scientific facts were based on the linked NASA references; numerical game values remain fictional.
- **Branding:** no NASA insignia, wordmark, flags or mission emblems were intentionally incorporated. The project describes its participation without presenting NASA sponsorship.

The generated artwork and source code are included in the game HTML. Read `AI_DISCLOSURE.md` for the content inventory.

## Files

- `index.html` — complete playable game, with embedded illustrations
- `README.md` — instructions, mechanics and sources
- `SUBMISSION_TEXT.md` — ready-to-adapt project submission text
- `AI_DISCLOSURE.md` — AI contribution record

## Testing and limitations

The game is intended for a desktop browser. It supports smaller layouts, but the visual placement of equipment buttons depends on viewport size. Audio requires browser permission initiated by a player click. Game data is held in memory and resets when the page reloads. External source links require internet access. A final manual playthrough is recommended before submission.
