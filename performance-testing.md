## Performance testing
All tests have been run while connected to a **dedicated server**. These measurements **do not** apply to singleplayer mode.

Per the server settings, render distance will be set at 10 chunks for all tests. FOV is set at 85.

FPS measurements are taken using Sodium Extra's FPS Extended option.

### Machine 1: Very low end
CPU: Intel Celeron N4000  
Graphics: Integrated Intel UHD 600  
Resolution: 1366x768  
RAM: 4GB total, 2500MB allocated  
OS: Debian Linux  

- Situation 1:  
  Wooded area on an island 

  - RenderScale at 1.00, Fancy Graphics  
    Average: ~50FPS, Lows: ~40FPS

  - RenderScale at 0.75, Fancy Graphics  
    Average: ~60FPS, Lows: ~50FPS

  - RenderScale at 1.00, Fast Graphics  
    Average: ~60FPS, Lows: ~45FPS

  - RenderScale at 0.75, Fast Graphics  
    Average: ~70FPS, Lows: ~50FPS

- Situation 2:  
  Same area, but raining

  - RenderScale at 1.00, Fancy Graphics  
    Average: ~50FPS, Lows: ~35FPS

  - RenderScale at 0.75, Fancy Graphics  
    Average: ~55FPS, Lows: ~40FPS

  - RenderScale at 1.00, Fast Graphics  
    Average: ~60FPS, Lows: ~45FPS

  - RenderScale at 0.75, Fast Graphics  
    Average: ~65FPS, Lows: ~30FPS

- Situation 3:  
  The Nether (Nether Wastes)  
  Fast/Fancy didn't make a noticable difference  

   - RenderScale at 1.00  
    Average: ~100FPS, Lows: ~80FPS

  - RenderScale at 0.75  
    Average: ~120FPS, Lows: ~90FPS

### Machine 2: My daily driver  
CPU: AMD AI 9 365  
Graphics: Integrated Radeon 880M  
Resolution: 2880x1800  
RAM: 20GB total, 6200MB allocated  
OS: Arch Linux (btw)  


- Situation 1:

  - RenderScale at 1.00, Fancy Graphics  
    Average: ~350FPS, Lows: ~240FPS

  - RenderScale at 0.75, Fancy Graphics  
    Average: ~450FPS, Lows: ~370FPS

  - RenderScale at 1.00, Fast Graphics  
    Average: ~380FPS, Lows: ~325FPS

  - RenderScale at 0.75, Fast Graphics  
    Average: ~520FPS, Lows: ~380FPS

- Situation 2:

  - RenderScale at 1.00, Fancy Graphics  
    Average: ~300FPS, Lows: ~250FPS

  - RenderScale at 0.75, Fancy Graphics  
    Average: ~380FPS, Lows: ~290FPS

  - RenderScale at 1.00, Fast Graphics  
    Average: ~350FPS, Lows: ~300FPS

  - RenderScale at 0.75, Fast Graphics  
    Average: ~450FPS, Lows: ~370FPS

- Situation 3:

  - RenderScale at 1.00  
    Average: ~580FPS, Lows: ~530FPS

  - RenderScale at 0.75  
    Average: ~750FPS, Lows: ~650FPS

