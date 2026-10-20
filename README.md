# MG3
## Devlog
- float: 0.0, int: 0, bool: null, string: null 

- Update is called with every frame, and is a built-in method within Unity. In the Timer class, Update() subtracts Time.deltaTime from timeLeft every frame to make the timer count down.

- KickWeapon uses the timer to see how long the kick is enabled for. When activated, the timer is started using BeginTimer(). While Update() method checks every frame whether the timer finished with IsFinished method(), and once it is finished KickWeapon is finally diabled
TimeText uses the timer as a countdown for how much time is left in the game. Time timer is started also using BeginTimer(). Update() checks every frame if the timer is finished with IsFinished(), and when it is finished it calls GameOver(). Update() also updates the timer with GetTimeLeft() in order to display how much time is remaning 

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)