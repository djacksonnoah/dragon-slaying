# dragon-slaying
[ ] Yak Shaving
  - [ ] Create a fork of the [dragon-slaying](https://github.com/wcci-summer-2016/dragon-slaying) repository and clone the fork onto your machine.
  - [ ] Create a README.md file explaining what this project will involve and how someone could run it.
- [ ] The `Die` class
  - [ ] `public Die(int NumberOfSides)`
  - [ ] `public int Roll()`
- [ ] The `Dragon` class
  - [ ] `public bool IsAlive()`
- [ ] The `Hero` class
  - [ ] Add any necessary field(s)
  - [ ] `public int HitPoints` `get` and `set` methods
  - [ ] `public override string ToString()`
  - [ ] `public bool IsAlive()`
  - [ ] `public void Attack(Dragon opponent, int diceRoll)`
  - [ ] `public void Defend(Dragon opponent, int diceRoll)`


### Stretch Tasks

- [ ] UI enhancements
  - [ ] Give better feedback to the user during the `Battle`
  - [ ] Use colors to improve the console interface
  - [ ] Put the stats of the Hero and the Dragon side by side as the `Battle` rages on
- [ ] Multiple enemies (_!!!_)
  - [ ] Modify the `Battle` method to take a `List` of enemies and fight multiple dragons
  - [ ] Give the user a choice of which enemy to attack each turn
