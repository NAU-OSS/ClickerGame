# ClickerGame

**ClickerGame** is an open-source idle clicker game where players
generate resources by clicking, unlock upgrades, automate production,
and steadily build a growing resource empire. The project is designed to
be lightweight, beginner-friendly, and easy to modify.

Repository: **NAU-OSS/ClickerGame.git**

------------------------------------------------------------------------

## Features

-   Classic click-to-earn gameplay\
-   Upgrade and automation systems\
-   Scaling progression mechanics\
-   Save/load support\
-   Easy to extend and customize

------------------------------------------------------------------------

## Installation

### Option 1 --- Run from Source

1.  Clone the repository:

git clone https://github.com/NAU-OSS/ClickerGame.git\
cd ClickerGame

2.  Install dependencies:

npm install

3.  Start the game locally:

npm run dev

------------------------------------------------------------------------

### Option 2 --- Production Build

npm run build\
npm start

------------------------------------------------------------------------

## Usage

### Playing the Game

1.  Click the main resource button to generate currency.\
2.  Purchase upgrades to increase click power.\
3.  Unlock auto-generators for passive income.\
4.  Optimize upgrades to progress faster.

------------------------------------------------------------------------

### Example: Adding a Custom Upgrade

addUpgrade({ name: "Mega Click", cost: 500, effect: () =\>
player.clickPower \*= 2 });

------------------------------------------------------------------------

## Project Status

**Status:** Actively maintained

Core gameplay systems are complete and stable. Improvements and
contributions are ongoing.

------------------------------------------------------------------------

## Contributing

Contributions are welcome!

1.  Fork the repository\
2.  Create a feature branch\
3.  Submit a pull request

------------------------------------------------------------------------

## 💬 Contact & Community

-   GitHub Issues --- bug reports & feature requests\
-   GitHub Discussions --- questions and ideas\
-   Email: **car723@nau.edu**
