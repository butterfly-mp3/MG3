# MG3
## Devlog
1. What are the default values for floats, ints, bools, and strings? To find out, try adding one variable of each type as a member variable to the Timer class, and see what default value for each variable shows up in the Inspector.
    float: 0.0f  int: 0  bool: false  string: ""
2. How does the Update method get called- is your code supposed to call it in this assignment, or does it get called some other way?
    The update method gets called every frame automatically, and is never supposed to be called by you (it just doesn't need to be at all)
3. Explain how either the KickWeapon or TimerText class use the timer. Mention the Update() method.
    The TimerText class uses the timer to check when the player no longer has time left to gain points. It uses the Update() method to check every frame if the timer has run out, and if it has, to run a game over and not allow the player to collect any more points.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)