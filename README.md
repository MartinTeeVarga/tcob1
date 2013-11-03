# TCOB1

This game was made for [GameDev.StackExchange Game Jam.](http://meta.gamedev.stackexchange.com/questions/1356/the-first-gdse-gamejam) The theme was "There can only be one" (sic). The game genre is "endless" space racing where players are eliminated by asteroids. The last player in the game wins.

The game can be played in both single player and multiplayer. Up to 4 players can compete at one computer. Player controls a ship with 4 directional keys. The movement consumes energy. Energy bar in player's color is displayed at the bottom. Energy recharges over time. Flying without energy is much slower. Only head-on collision is fatal. You can push the asteroid left and right with wings.

## Keyboard controls

*   Red: W, S, A, D
*   Green: I, J, K, L
*   Blue: Arrows
*   Yellow: Numpad keys 5, 1, 2, 3

Press any of the keys to gain control of the ship at any time.

## Known issues

*   The collisions are not very precise. Phaser works with rectangles.
*   Explosion sound in Firefox is bugged - but hey, there's no sound in space!
*   No window resize and scaling is very naive - refresh the page if you see any glitches
*   Music is not paused on lost focus and looping is broken
*   My Javascript sucks

## Credits

*   [Phaser - JavaScript game engine](http://phaser.io/)
*   [AbikK - background image "Outsider"](http://abikk.deviantart.com/art/Outsider-191631196)
*   [Torque2D tutorial - the asteroid image](https://github.com/GarageGames/Torque2D/wiki/Getting-Started-Guide)
*   [Kenney Vleugels (www.kenney.nl) - spaceship parts](http://www.kenney.nl)
*   [NOSOAPRADIO.US - music](http://www.nosoapradio.us/)
*   [bfxr - sound generator](http://www.bfxr.net/)
*   [and me, sm4 - everything else](http://android.kul.is/)

Thank you for playing! 

## License

MIT
