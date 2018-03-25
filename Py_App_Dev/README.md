# Python Application Development

## Pseudo code for Chapter 1 code

While the user wishes to keep playing the game.
* Print the game mission
* Create a huts list
* Randomly place 'enemy' or 'friend' or 'unoccupied' in 5 huts
* Prompt the player to select a hut number
* if enemy. print "you lose"
* else. print "you win"

## Refactoring into functions
Page 20

1. show_theme_message
2. show_game_mission
3. occupy_huts
4. process_user_choice
5. reveal_occupants
6. enter_hut

## Using OOP
Here is a partial list of the requested features:
1. New mission to acquire all the huts and defeat all the enemies. This also
means the hut occupants should be revealed right at the beginning of the
game.
2. Ability to get healed in a friendly or unoccupied hut.
3. Ability to abandon combat (or run away from the enemy). This is a strategic
move to run away, get healed in a friendly hut, and resume combat.
4. Introduce one or more horse riders to assist Sir Foo. They can take turns to
acquire huts. Ideally, a user-configurable option.
5. Ability to configure the maximum hit points for each enemy unit and each of
the horse riders.
6. Configurable total number of huts; for example, increase it to 10.
7. Each hut can have either some gold or a weapon inside that Sir Foo and his
friends can pick up.
8. Have an elf rider join Sir Foo. His abilities give him a very high chance of
winning with fewer attacks.

