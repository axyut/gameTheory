# Game Theory
    Be Nice, Be Forgiving but don't be a pushover.
[Inspired from Veritasium's Video on Prisoner's Dilemma.](https://www.youtube.com/watch?v=mScpHTIi-kM)
## About

### [This Project](https://github.com/axyut/gameTheory)
This project on Prisoner's Dilemma is my vision to original competition held by Prof. Axelrod. More on [Axelrod's Contest](https://en.wikipedia.org/wiki/Prisoner's_dilemma#Axelrod's_contest_and_successful_strategy_conditions). It's a CLI platform to test your strategies with other's and popular pre-written ones like `Tit for tat`. This game is capable of executing your strategies and competing with order's and providing statistics on yor rank, strategy and game.

### [Game Theory](https://en.wikipedia.org/wiki/Game_theory)
An Umbrella term for the science of logical decision making in humans, animals, as well as computers. Jon Von Neumann started the era of modern game theory which now covers more than just rational thinking & numerous games expanding in various fields.

### [The Prisoner's Dilemma](https://en.wikipedia.org/wiki/Prisoner's_dilemma)
| Original Dilemma |
|:---:|
|    Two members of a criminal gang are arrested and imprisoned. Each prisoner is in solitary confinement with no means of speaking to or exchanging messages with the other. The police admit they don't have enough evidence to convict the pair on the principal charge. |
|    They plan to sentence both to a year in prison on a lesser charge. Simultaneously, the police offer each prisoner a Faustian bargain. If he testifies against his partner, he will go free while the partner will get three years in prison on the main charge. Oh, yes, there is a catch ... If both prisoners testify against each other, both will be sentenced to two years in jail. |
|    The prisoners are given a little time to think this over, but in no case may either learn what the other has decided until he has irrevocably made his decision. Each is informed that the other prisoner is being offered the very same deal. Each prisoner is concerned only with his own welfare—with minimizing his own prison sentence. |

There are essentially 4 possible outcomes.
- If prisoner A and prisoner B both remain silent, they will each serve one year in prison.
- If A testifies against B but B remains silent, A will be set free while B serves three years in prison.
- If A remains silent but B testifies against A, A will serve three years in prison and B will be set free.
- If A and B testify against each other, they will each serve two years.

***`TLDR`***
It's a game theory thought experiment which models many real-world situations involving strategic behavior. In casual usage, the label "prisoner's dilemma" may be applied to any situation in which two entities could gain important benefits from cooperating or suffer from failing to do so, but find it difficult or expensive to coordinate their activities.
<!--Prisoner's Dilemma Reveals About Life, The Universe and Everything. -->
<!-- TODO
strategy rendering
game runner/platform
statistics general
data visualization
-->

## Your Strategy!
Write your ~~evil~~ winning strategy.

## How To Play?
Start testing & competing.

## Outcome.
Statistics on the game and your strategy

## Install
`go install github.com/axyut/gametheory@latest`

## Features
- [ ] Strategy Executing Engine
- [ ] Game Runner/Platform
- [ ] General Statistics
- [ ] Data Visualization

## Contributing
Contribute popular strategies and your own which does relatively well.

## How to Win.
Secret sauce to win is `Co-operation`. After analyzing the top-scoring strategies, Axelrod stated several conditions necessary for a strategy to succeed:

- `Nice`: The strategy will not defect before its opponent does (this is sometimes referred to as an "optimistic" algorithm). Almost all the top-scoring strategies were nice. A purely selfish strategy will not "cheat" on its opponent for purely self-interested reasons first.
- `Retaliating`: The strategy must sometimes retaliate. An example of a non-retaliating strategy is Always Cooperate, a very bad choice that will frequently be exploited by "nasty" strategies.
- `Forgiving`: Successful strategies must be forgiving. Though players will retaliate, they will cooperate again if the opponent does not continue to defect. This can stop long runs of revenge and counter-revenge, maximizing points.
- `Non-envious`: The strategy must not strive to score more than the opponent.








