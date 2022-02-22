# 🎓 The School

## Members of the team

\- He Jin <small>(coded day 2)

\- Angel Zhou <small>(coded day 1)

## Things I have learned

How to code a visual novel game through renpy:

1. Menus

2. Backgrounds

3. Characters

4. Dialogues

5. Inputs

6. Conditional statements

## Things I can teach

I can teach someone how to code a renpy game that contains:

\- An input for player's name
```Python
$ player_name = renpy.input("What is my name?")
$ player_name = player_name.strip()

if player_name == "":
$ player_name = "Player"
```

\- A exam with conditional statements
```Python
$ answer1 = renpy.input("What is 2+2?")
if answer1 == "4":
    $ test += 1
    x "This is so easy for me."
else:
    x "GRRRR"
```

\- Pause statements
```Python
scene black
"No university wanted to accept you due to your horrible grades. Your mom kicked you out of the house for scoring so bad in your exam and accused you to be adopted. Maybe you should have studied." 
"You become a street beggar."
scene bg died
with fade
pause 2 # It stops the game for 2 seconds
```

## Bibliography
Backgrounds are taken from: https://lemmasoft.renai.us/forums/viewtopic.php?f=52&t=17302

Character designs are taken from: https://emily2.itch.io/sutemo

Inputs tutorial: https://www.renpy.org/wiki/renpy/doc/cookbook/Letting_players_choose_their_own_name

Conditional statements tutorial: https://www.renpy.org/doc/html/conditional.html
