# 2027 Season Plan

How TorBots plans to design, build, and compete in 2027, based on where the team stands as of November 2026. It applies the team-wide [Robot Design Philosophy](../../team/design-philosophy.md) to this season's people, space, and budget.

## Slide Deck

The original presentation is embedded below. Click it, then use the arrow keys or the on-screen buttons to move between slides, or [open the deck full screen](plan-deck.html){ target=_blank }.

<div class="deck-embed">
  <iframe src="../plan-deck.html" title="2027 Season Design Philosophy and Execution Plan" loading="lazy"></iframe>
</div>

The rest of this page has the same content as text, so it can be searched and linked to.

!!! info "Scope"
    This plan is set by our current constraints. We'll revisit it each season as people, space, and budget change.

## Where We Stand

### FRC Robot Capability Map

How mentors and students rate on FRC robot work specifically:

| Area | Mentors | Students |
|---|---|---|
| Strategic design | Strength | Neutral |
| Autonomous & software | Strength | Weakness |
| Mechanical design | Weakness | Weakness |
| Manufacturing & assembly | Weakness | Strength |
| Electrical | Strength | Strength |

- Electrical is strong on both sides.
- Software and manufacturing each have one strong group, on opposite sides.

!!! warning "Gap"
    Mechanical design is weak on both sides. It is the only area neither group covers.

### Constraints

Resource limits that apply to the whole team:

| Resource | Status | Impact |
|---|---|---|
| Shop space | Limited | Not enough room to practice driving well for teleop. |
| Budget | Limited | Caps what we can buy for parts, mechanisms, and spares. |
| Manpower | Limited | Limited students and mentors. Shop hours are capped by how many mentors are available to supervise. |
| Manufacturing tolerance | Limited | Parts we make in-house can only hold so tight a tolerance. |

## Design Language

### Autonomous Drives Matches

Since 2022, the alliance that wins auto has won the match about 4 times in 5.

- **77.9%** auto winner's match win rate across all 77,997 decided matches, 2022–2026.
- Quals 78.6%, playoffs 74.6%.
- Every season since 2022 sits between 76% and 79% overall.

*Official events only. Matches tied in auto or final score are excluded. Data: The Blue Alliance.*

### Built Around Autonomous

> FRC matches are shaped by autonomous, and our team is set up to deliver on it.

Mentors bring depth in strategy and autonomous software. Students bring strength in manufacturing and assembly, so we can build, repair, and deliver the robots autonomous testing depends on. Together we design a robot built for its auto paths, deliver the prototype and final robots as early as possible, and test autos on an accurate field in our own shop.

This is built on:

- Mentor depth in strategy and autonomous software.
- Student strength in manufacturing and assembly.
- Auto outcomes carrying into the rest of the match.
- Auto testing that fits the shop space we have.

### How We Deliver It

- **The robot: built for auto paths.** Mechanism layout is chosen around the autonomous routine. Intake and shooter, or intake and end effector, face the directions that make auto paths shortest and cleanest.
- **The schedule: robots early.** Deliver a software-testable prototype early, then the final robot as early as possible, for weeks of software work and auto tuning. Mechanical focuses on 1–1.5 mechanisms' worth of robot, so the team ships a simple robot that can be tested for a long time.
- **The field: accurate shop field.** Build high-quality, accurate field elements sized to fit our shop, so autonomous is tested as close to the real field as possible.

### One Elite Mechanism

We focus on 1–1.5 mechanisms' worth of robot. We deliver one elite mechanism, and that mechanism handles and delivers the autonomous performance we're after.

- We have traditionally not had success focusing on multiple mechanisms at once.
- More can be added later. We leave room for upgrades throughout the season.

!!! tip "Rule"
    Complex enough to enable software. Simple enough to deliver on time.

## Before Kickoff

Get the shop ready for vision and auto work before the game is revealed on **Jan 9**. All four items get done across two work days: **Sat Nov 14** and **Sat Dec 12**.

- **Working drive base:** a drive base that runs, ready for software and auto work.
- **Protocube running:** the protocube is up and running for prototyping.
- **Strip current robot:** strip the current robot down to what vision work needs.
- **Clear field elements:** take down the field elements except the trench, to open space for vision.

## Kickoff and Kitbot

Get hands on game pieces and a driving robot as fast as possible.

- **1–2 hour game breakdown.** We compress the day-one game breakdown to 1–2 hours, down from our traditional multi-hour session. The time we save goes straight into prototyping and studying how the robot interacts with game pieces.
- **Kitbot on swerve** *(pending kitbot review)*. If the 2027 kitbot design looks promising, we build it on a swerve drivetrain over kickoff weekend. Students bring up a working robot that bootstraps prototyping, and the team gains a second robot to use throughout the season as needed.

## Alpha Bot and CAD Hell

Prove the geometry on a driving robot, then release CAD that fabrication can trust.

- **Week 2: Alpha bot.** A robot that is accurate in geometry and materials, without most of the moving parts. It drives, with some actuation, so we can confirm how the robot interacts with the field and game pieces before committing to the final design. Some prototyping can bleed over into this week; what it teaches us can still inform the CAD.
- **Week 3: CAD hell.** Moving parts and packaging get worked out until the CAD is high fidelity. Releasing high-fidelity CAD lets fabrication and assembly stay focused, which plays to the students' strength in manufacturing and assembly.

## Six-Week Build Schedule

The timeline is aggressive on purpose, with a one-week buffer and software testing the whole way.

| Phase | Dates | Focus |
|---|---|---|
| Kickoff weekend | Jan 9–10 | **Kitbot.** Kitbot on swerve, built over the first weekend. |
| Week 1 | Jan 11–17 | **Prototyping.** Mechanisms and game piece interaction worked out, with the kitbot as a starting point. |
| Week 2 | Jan 18–24 | **Alpha bot.** Confirms geometry and material choices. Mostly wood and static parts. Some prototyping bleeds over. |
| Week 3 | Jan 25–31 | **CAD hell.** Moving parts and packaging for the final robot. |
| Week 4 | Feb 1–7 | **Fabrication.** Design released to fab; parts start. |
| Week 5 | Feb 8–14 | **Assembly & wiring.** Final robot built and wired. |
| Week 6 | Feb 15–21 | **Final bot.** Final robot delivered. Can slip up to 1 week. |
| Week 6+ | Feb 22 on | **Tuning.** Auto and software tuning, mechanical fixes as they come up. Runs into the competition season. |

- **Field:** main field elements are done before the alpha bot. Mentor-led, with students as bandwidth allows.
- **Software:** tests continuously on the alpha bot to learn what software needs, and feeds that back into the design.

!!! note "1-week buffer"
    The schedule can slip by one week if needed for:

    - WCP's week 2 concept bot release, as a reference for more prototyping before the alpha bot.
    - CAD hell not progressing fast enough.
    - Manufacturing or supply chain delays.

## Competition Season

Tuning continues between events, with one optional window to install an upgrade mechanism.

| When | Dates | Event | Status |
|---|---|---|---|
| After week 6 | Feb 22 – Mar 18 | **Tuning.** Auto and software tuning, mechanical fixes. Driver practice ramps up. | |
| Comp week 3 | Mar 19–21 | **CA District Los Angeles Event**, El Segundo | Attending |
| Option A | Mar 22 – Apr 1 | **Upgrade window** after LA | Optional |
| Comp week 5 | Apr 2–4 | **CA District Hueneme Port Event**, Port Hueneme | Attending |
| Option B | Apr 5–14 | **Upgrade window** after Hueneme | Optional |
| Comp week 7 | Apr 15–18 | **FIRST California Southern State Championship (DCMP)**, Anaheim | If points qualify |
| Championship | Apr 28 – May 1 | **FIRST Championship (Worlds)**, Houston | If we qualify |

An upgrade mechanism is optional. If we add one, it goes in after either LA or Hueneme, not both.

## Shop Hours

28 hours a week to start, set by mentor availability. Hours are flexible, and we add more as needed.

| Day | Hours | Time |
|---|---|---|
| Mon | 5 h | 3:30–8:30 PM |
| Tue | — | Possible swap later |
| Wed | 5 h | 3:30–8:30 PM |
| Thu | — | Possible swap later |
| Fri | 5 h | 3:30–8:30 PM |
| Sat | 8 h | 10 AM–6 PM |
| Sun | 5 h | 1–6 PM |

**Sunday first.** Early in the season, Sunday gives us mentor support while we're designing. Later, if it's more productive for students doing manufacturing and assembly, we can trade Sunday for a Tuesday or Thursday.

## Strategy

### Consistency Is the Game

A TorBots robot wins on consistency. We go for a consistent autonomous, and that usually means a highly automated teleop robot too. The robot is built to do the same thing well every match.

Driver practice:

- Is built around consistency, not peak performance.
- Ramps up as auto and software get tuned and competition gets closer.
- Without a full practice field, we don't plan on an explosive driver performance.

### Alliance Selection

A consistent robot needs partners who can raise the ceiling.

- **Default pick: consistent + high upside.** Pick higher-upside, riskier teams. Our consistency sets the floor, and their variance gives the alliance a real chance to win the event.
- **Default to avoid: consistent + consistent.** We don't play in a high-variance way that can turn a match on our own, so pairing with another consistent team caps how high the alliance can go. *Exception:* if a consistent partner is enough to win the event, take it.

!!! tip "Scouting"
    Scout and build pick lists with this in mind: look for each team's ceiling and upside, not only its average.
