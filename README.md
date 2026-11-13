# TAC ATTACK assets

Sprite sheets, stills and music for the TAC ATTACK tic-tac-toe game on battleVS.ai, served through jsDelivr.

- player/player.json + player-N.webp: the boy, Phaser multiatlas, 14 poses (P01 to P14), 12 fps
- player/stills/: one small still per pose, player/stills.json: anchor and scale
- agent/agent.json + agent-N.webp: the robot, same format, 14 poses (R01 to R14); each texture entry carries its anchor, scale and loop modes ("tac")
- agent/stills/, agent/stills.json: one small still per robot pose
- music/music.mp3 + music.json: the game music; the intro plays once, then it loops between loopStart and loopEnd (seconds)

Tags: v1 is the boy only; v2 adds the robot and the music. The game pins a tag, so later changes here never change a released version.
