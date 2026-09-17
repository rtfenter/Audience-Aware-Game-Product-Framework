# Research Findings

This document summarizes the research behind the Audience-Aware Game Product Framework. It separates established findings from the product interpretation developed in the main study.

## 1. Non-playing game audiences are real

Stephanie Orme's research on "just watchers" studied people who rarely or never play video games but routinely watch others play, both virtually and in person.

Participants described barriers to playing including the work involved, lack of skill, access and negative gaming environments. Watching still provided a distinct form of narrative engagement, and participants often considered themselves part of gaming culture despite not actively playing.

### What this supports

Playing is not the only meaningful way someone can experience a game or participate in gaming culture.

### What it does not support

It does not establish that all game spectators are non-players or that watchers and players should be treated as equivalent audiences.

---

## 2. People watch games for different reasons

Research across livestreaming, YouTube gameplay and esports identifies overlapping motivations including:

- entertainment
- learning and information seeking
- skill appreciation
- suspense and drama
- novelty
- relaxation and escapism
- social interaction
- community and belonging
- creator or player attachment
- narrative and vicarious experience

These motivations can coexist within the same person.

This is more useful than treating spectators as a single permanent audience segment.

### Product implication

The relevant question may be less:

> What type of spectator is this person?

and more:

> What experience are they seeking in this viewing context?

---

## 3. Context and intent are different

The initial framework mixed viewing contexts with viewing motivations.

For example:

- watching a partner play in person is a **context**
- watching for entertainment is an **intent**
- watching to learn is an **intent**
- watching because of a creator/community is an **intent**

The same context can support several different motivations.

### Product implication

Audience research should avoid assigning people permanently to categories such as "social viewer" or "competitive viewer" when their motivation may change between sessions.

---

## 4. Gameplay legibility matters

Spectator research consistently identifies comprehension and information management as important.

Spectators need enough information to understand what is happening, but more information is not automatically better.

Research on esports interfaces and spectator systems emphasizes:

- readable game state
- controlled information revelation
- cognitive-load management
- understandable performance signals
- sufficient context to recognize important events

Prior game knowledge changes how much information a spectator can interpret.

### Product implication

Legibility can be useful to both audiences and players.

A spectator struggling to understand an encounter does not automatically indicate a game-design problem.

But if players and audiences struggle with the same feedback or state communication, the overlap may expose a broader quality issue.

---

## 5. Expertise changes what spectators can see

Research suggests experienced players process game information differently from novices and can recognize strategic or performance information that less knowledgeable viewers may miss.

Spectator research similarly finds that prior knowledge affects the ability to recognize mastery and understand game state.

The specific hypothesis that low-knowledge viewers perceive repeated encounters as more repetitive than experts remains insufficiently tested.

### Product implication

Two spectators can watch identical gameplay and perceive very different amounts of meaningful variation.

---

## 6. Suspense and uncertainty are important spectator mechanisms

Spectator research identifies uncertainty and information asymmetry as important sources of entertainment.

A spectator does not need complete mechanical knowledge to understand:

- someone is close to winning
- the player is running out of health or recovery options
- an attack is dangerous
- a comeback is happening
- the outcome remains uncertain

### Product implication

Readable stakes may matter as much as complete mechanical comprehension.

---

## 7. Aesthetics matter differently by context

Research does not support treating aesthetics as equally important across all game spectatorship.

Competitive esports studies have found aesthetics to be less predictive of viewing frequency than motivations such as knowledge acquisition, novelty, drama or escapism.

Other qualitative and game-studies research supports games as aesthetic spectacles and identifies visual experience as a legitimate source of spectator value.

### Product implication

Aesthetic value should be treated as context-dependent.

It may matter substantially more for narrative, atmospheric or ambient gameplay viewing than for competitive spectatorship.

---

## 8. Ambient gameplay viewing exists, but evidence is limited

Qualitative research on YouTube gameplay has documented people using gameplay videos as background media while completing other activities, including comparisons to podcast-like consumption.

However, dedicated research on ambient gameplay viewing remains limited.

There is not enough evidence to conclude that long gameplay watch time reliably corresponds to low attention.

### Product implication

Watch time alone should not be interpreted as evidence of active attention or deep engagement.

Ambient viewing is a credible behavior worth researching further rather than a settled measurement model.

---

# Industry Practice

## 9. Spectator-aware design is established in competitive games

Competitive games and esports have mature spectator practices including:

- observer interfaces
- spectator cameras
- broadcast HUDs
- game-state visualization
- automated observer systems
- spectator-specific information design

In these contexts, the audience is an explicit part of the product ecosystem.

---

## 10. Spectator-aware design also exists outside esports

The practice is not exclusive to competitive games.

Developers associated with games such as Nuclear Throne, Overland and Hades have publicly discussed the needs of people watching games.

A particularly relevant example is Hades.

Supergiant's Greg Kasavin publicly described the team considering questions such as what the game is like for someone watching and whether that person can understand what is happening.

### Why this matters

Considering a non-playing audience does not inherently require turning a game into an esport or optimizing it for streaming metrics.

---

## 11. Narrative/aesthetic single-player practice is less documented

An adversarial search specifically investigated whether studios developing narrative and aesthetic single-player games publicly describe non-playing audiences as a design input.

The research found extensive discussion of:

- cinematic presentation
- environments
- combat spectacle
- animation
- readability
- immersion
- narrative

But these decisions were overwhelmingly explained in terms of the **player experience**.

For the narrative/aesthetic studios and games investigated, little public evidence was found showing teams explicitly asking how those systems work for people primarily watching the game.

### Important limitation

Absence of public documentation is not proof that studios do not conduct this work internally.

The responsible conclusion is:

> Explicit spectator-aware design is well documented in competitive games and exists in some action/roguelike development, while it is much less visible in the documented product practice of narrative and aesthetic single-player games.

---

## 12. Audience evidence is already used by game teams, but usually for different purposes

Documented examples show studios using streams and audience behavior for:

### Playtesting

Watching streams can expose:

- UI problems
- onboarding friction
- confusion
- localization issues
- unexpected player behavior

### Marketing and discovery

Creators and streams can influence:

- awareness
- acquisition
- localization priorities
- community growth
- sales

### Community

Audience activity provides information about:

- discussion
- fandom
- creator ecosystems
- cultural reach

What is much less publicly documented is:

> audience experience being combined with player evidence specifically to inform core narrative/single-player game design.

---

# The Product Gap

## 13. The research does not establish a new audience

Non-playing game audiences were already documented.

Spectator-aware design already existed.

The contribution of this project is therefore not:

> Games have spectators.

Nor is it:

> Game developers should optimize games for people watching.

The narrower opportunity identified through the research is:

> **How should a game PM use audience evidence when player and audience experiences align or diverge, without turning audience metrics into game-design targets?**

That is the problem addressed by the Audience-Aware Game Product Framework.

---

# Product Principle

## 14. Audience experience can be evidence without becoming the optimization target

Existing design practice around legibility provides an important precedent.

Improving clarity can help someone watching understand what happened while simultaneously helping a player understand feedback, state or consequences.

But audience and player value can also conflict.

A boss may require repeated attempts because mastery is fundamental to the intended player experience even if repetition becomes less compelling to watch.

The framework therefore uses the guardrail:

> **Audience experience should inform game quality, not become a reason to distort the game for audience metrics.**

---

# Measurement Implications

## 15. Different evidence sources answer different questions

### Game telemetry

Can tell us what players did:

- attempts
- deaths
- builds
- progression
- completion
- retention
- drop-off

### Audience evidence

Can tell us what happened around the game:

- viewing behavior
- creator/community activity
- discussion
- audience comprehension
- aesthetic response
- qualitative spectator experiences

### Research

Can help explain why those behaviors occurred.

None should automatically substitute for the others.

A player attempting a boss twenty times tells us what happened.

A viewer watching for three hours tells us what happened.

Neither behavior alone establishes what the experience meant.

---

# Open Questions

Public evidence did not resolve several important questions:

1. Do major narrative-game studios conduct internal user research specifically with non-playing viewers?
2. Do narrative-game product teams combine gameplay telemetry with VOD or audience evidence to influence core game design?
3. How common is ambient/no-commentary gameplay consumption?
4. How do player and audience perceptions of the same encounter differ?
5. How does expertise affect perceived repetition and mastery recognition?
6. When does audience legibility expose a genuine game-quality problem versus an audience-specific comprehension problem?

These remain research questions rather than findings.

---

# Selected Sources

## Non-playing audiences and spectator motivation

Stephanie Orme (2022), **"Just watching": A qualitative analysis of non-players' motivations for video game spectatorship.**  
*New Media & Society*, 24(10), 2252–2269.  
https://doi.org/10.1177/1461444821989350

M. Sjöblom & J. Hamari (2017), **Why do people watch others play video games? An empirical study on the motivations of Twitch users.**  
*Computers in Human Behavior*, 75, 985–996.  
https://doi.org/10.1016/j.chb.2016.10.019

Z. Hilvert-Bruce, J. T. Neill, M. Sjöblom & J. Hamari (2018), **Social motivations of live-streaming viewer engagement on Twitch.**  
*Computers in Human Behavior*, 84, 58–67.  
https://doi.org/10.1016/j.chb.2018.02.013

J. Hamari & M. Sjöblom (2017), **What is eSports and why do people watch it?**  
*Internet Research*, 27(2), 211–232.  
https://doi.org/10.1108/IntR-04-2016-0085

T. Y. Qian, J. J. Wang, J. J. Zhang & L. Z. Lu (2020), **It is in the game: dimensions of esports online spectator motivation and development of a scale.**  
*European Sport Management Quarterly*, 20(4).  
https://doi.org/10.1080/16184742.2019.1630464

## Spectator experience and legibility

G. Cheung & J. Huang (2011), **StarCraft from the stands: understanding the game spectator.**  
CHI '11.  
https://doi.org/10.1145/1978942.1979053

S. Charleer et al. (2018), **Real-time dashboards to support eSports spectating.**  
CHI PLAY '18.  
https://doi.org/10.1145/3242671.3242680

F. Block et al. (2018), **Narrative Bytes: Data-driven content production in esports.**  
TVX '18.  
https://doi.org/10.1145/3210825.3210833

## Gameplay viewing

U. Golob, M. Kraševec & T. Oblak Črnič (2021), **Video gaming spectatorship: What drives gameplay watching on YouTube?**  
*Media Studies*, 12(23), 40–56.  
https://doi.org/10.20901/ms.12.23.3

## Industry-practice research

Additional developer interviews, studio material and industry sources were reviewed for spectator-aware design practices across competitive, action/roguelike and narrative single-player development.

The detailed research process and limitations are documented in the accompanying reasoning log.