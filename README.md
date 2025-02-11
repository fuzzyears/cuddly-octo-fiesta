# cuddly-octo-fiesta
A containerized Python environment.

I'm always anxious when someone sends me a script and asks me for help (or vice versa). What if my personal machine is set up in a way I don't remember and influences me in a weird way? This is an attempt to alleviate those concerns and get up to speed together a little quicker.

I don't know if this is useful or a very obtuse solution, but it was nice to learn about lol.

## Instructions
1. Add dependencies to requirements.txt.
2. Modify src as desired.
3. `docker build -t image-name`
4. `docker run -v "$PWD/src:/code" image-name`
5. Re-run step 4 to see any updates to src.
