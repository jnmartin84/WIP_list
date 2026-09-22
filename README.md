# stuff I'm doing behind the scenes

1) Virtua Fighter 2 PC/Win95 decompilation + Dreamcast port
- Status: decomp is probably 75%, give or take. Most of the game modes are playable with both model types, high detail backgrounds and ring. Dreamcast Port: playable at 60 FPS with Model 2 models, no shadows, full sound and music.

2) Tetrisphere decompilation + Dreamcast port
- Status: decomp 100% code byte-match (IDO 5.3). Dreamcast Port: playable with graphics and sound, some bugs. See: https://www.youtube.com/live/2_U8ESwzGeo

3) N64Recomp-dc
- I modified the N64Recomp tooling to emit code more suited to a 32-bit platform. Some tricks to make memory access more efficient. Some HLE for audio and graphics. Several titles playable.
  - Automobili Lamborghini - almost perfect
  - Extreme G - horrible
  - Bomberman 64 - not great
  - Mega Man 64 - slightly better than not great
  - Aerogauge - decent in qualifying race, not great in grand prix

4) Sega Rally Dreamcast port
- Status: the very cool dude behind Sega Rally 64 allowed me access to his code and tooling and I have got this running on DC at full-speed with new baked course lighting, dynamic car lighting, working split screen and VMU saving.
