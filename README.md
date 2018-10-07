# setup
This is the Phaser.io starter / foundation needed to start making Phaser games. I did make a new repository but we can rename it if we decide to use this repository for the actual game. First off I want to note that the instructions on docs.dtml.org for phaser are outdated or wrong and they won't work. Follow this instead.

## Installation

You'll need to install
* node.js https://nodejs.org/en/
* Cesanta Web Server htps://cesanta.com/binary.html
* Git https://git-scm.com/downloads
Nodejs is needed for the npm package manager which will install all of Phaser's dependencies. Cesanta is a local web server that your game will run on. You need Git to pull and commit from github.

## Setup
1. Open a command prompt and cd into your project folder
2. Clone this repository `git clone https://github.com/BHSHack4Good/setup`
3. Run the cesanta exe file you downloaded earlier to start the web server
4. (assuming ur running windows) Click the cesanta icon (its blue) in your system tray and click advanced settings. Change the root directory to the folder where index.html is.
5. Open your web browser and go to localhost:8080 which is your local web server address.

If all goes well you should see a black box with the phaser logo bouncing around.
index.html is where the game code goes.
