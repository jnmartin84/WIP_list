# stuff I'm doing behind the scenes as of 2026/10/04

1) Virtua Fighter 2 PC/Win95 decompilation + Dreamcast port
- Status: decomp is probably 75%, give or take. Most of the game modes are playable with both model types, high detail backgrounds and ring. Dreamcast Port: playable at 60 FPS with Model 2 models, no shadows, full sound and music.

2) Tetrisphere decompilation + Dreamcast port
- 62 days of work
- Status: decomp 100% code byte-match (IDO 5.3). Dreamcast Port: playable with graphics and sound, some bugs. See: https://www.youtube.com/live/2_U8ESwzGeo

3) N64Recomp-dc
- I modified the N64Recomp tooling to emit code more suited to a 32-bit platform. Some tricks to make memory access more efficient. Some HLE for audio and graphics. Several titles playable.
  - Dr Mario 64 - initial prototype, worst possible game to match to a Dreamcast (offscreen rendering/RTT to compose the entire full-screen background, active game piece is software rendered by poking pixels into framebuffer over the rest of the screen, other issues)
  - Automobili Lamborghini - almost perfect
  - Extreme G - horrible
  - Bomberman 64 - not great
  - Mega Man 64 - slightly better than not great
  - Aerogauge - decent in qualifying race, not great in grand prix

4) Sega Rally Dreamcast port
- Status: the very cool dude behind Sega Rally 64 allowed me access to his code and tooling and I have got this running on DC at full-speed with new baked course lighting, dynamic car lighting, working split screen and VMU saving.

5) Top Gear Rally decompilation + Dreamcast port
- 69 hours of work
- Status: decomp 100% code byte-match (IDO 5.3). Dreamcast Port: playable with graphics and sound.

6) Grand Theft Auto decompilation + Dreamcast port
- 96 hours of work
- Status: decomp 90% code byte-match, 10% equivalent except for register allocation  (Visual C++ 4.2). Dreamcast Port: playable with graphics and sound. 

7) World Driver Championship Dreamcast port
- decompilation completed and provided by an external party, full native port without display list interpretation, 60 fps graphics and hardware mixed sound

8) Beetle Adventure Racing decompilation + Dreamcast port
- 60 hours of work
- Status: decomp 100% code byte-match (IDO 5.3). Dreamcast Port: playable with graphics and sound.

9) Quake 64 decompilation + modernsdk/F3DEX2 update + Dreamcast port
- 16 (!) hours of work
- Status: decomp 100% code byte-match (IDO 5.3). Updated to build with GCC 12, modern libultra, F3DEX2. Also a Dreamcast port because of course there is.

10) Star Soldier : Vanishing Earth decompilation + Dreamcast port
- 11.5 hours of work
- Status: decomp 100% code byte-match (IDO 5.3). Dreamcast Port: playable with graphics and sound.

11) 32x thing
