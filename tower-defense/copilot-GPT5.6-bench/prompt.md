# Tower Defense Benchmark Prompt

Build a complete, single-file HTML5 canvas tower defense game. Use no external assets or libraries. Draw all graphics in code.

## Required features

- **Path:** a non-straight path, with enemies following it via waypoints.
- **Towers:** at least 4 tower types with distinct mechanics, not just different damage numbers. Each tower has 2 upgrade levels.
- **Enemies:** at least 3 enemy types that each demand a different counter (e.g. armored, fast, splits on death).
- **Waves:** 10 waves with escalating difficulty and a boss on wave 10.
- **Economy:** a gold economy and lives. Towers can be sold back at a partial refund.
- **Twist 1, overheating:** towers overheat if they fire continuously and must cool down, so placement and spacing matter.
- **Twist 2, modifiers:** every 3 waves, the player chooses one of 3 random global modifiers. Some are purely beneficial and some are trade-offs.
- **Game flow:** a start screen, pause, win and lose screens, and restart without a page reload.

## Design goals

- The game should be winnable but not trivial on the first try.
- Prioritize game feel: visible feedback on hits, clear range indicators when placing or selecting towers, and a readable UI showing gold, lives, wave, and tower heat.
- Towers, enemies, and modifiers should create meaningful strategic choices. Avoid options that are strictly better or worse than others.

## Output

Return the entire game as one HTML file in a single code block, ready to save and open in a browser.