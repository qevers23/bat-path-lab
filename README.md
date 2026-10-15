# Bat Path Lab

An interactive 3D teaching tool for how bat path variables work together to set ball direction and flight. Move bat speed, attack angle, horizontal attack angle (where the path moves), horizontal bat angle (where the barrel faces), swing tilt and contact point, and watch the batted ball.

It is a teaching tool, not a ball flight simulator. Results are kept inside what real batted balls did:

- Exit velocity is capped at the hardest 2025 MLB ball for that launch angle.
- Carry is anchored to the 2025 Statcast median for that exit velocity, launch angle and direction. Flight follows Alan Nathan's trajectory calculator.
- Face vs path figures come from Driveline lab motion capture hitting assessments.
- Spin is described in words, not rpm.

Single static page, no build step: open `index.html`.

`title-16x9.png` and `title-4x5.png` are social title cards.
