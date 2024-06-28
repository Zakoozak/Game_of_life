
Usage: gol.py [OPTIONS]
Options:
  --width=INT          framebuffer width (default: 1280)
  --height=INT         framebuffer height (default: 720)
  --vsync=BOOL         enable vsync (default: True)
  --fullscreen         enable fullscreen
  --drylife=BOOL       use the non-standard "drylife" algorithm (default: True)
  --slow               use the very slow implementation (for benchmark comparisons)
  --frameskip=INT      only render 1-in-n frames to the screen (default: 1)
  --num-procs=INT      degree of parallelism (NB: number of actual threads will be 2n+1) (default: 8)
  --bench-frames=INT   render a certain number of frames and then exit (default: 0)

Other actions:
  -h, --help           Show the help
