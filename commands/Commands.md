# Commands

## [Math Remastered](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/math-remastered.yaml) by [IxNoah](https://www.reddit.com/user/ixNoah), [WolfPlays013](https://twitter.com/WolfPlay_Posts) and Me

Basically the old _r!math_ Robotop command but remade with custom commands. Only useful for binomials.

*Syntax:*
`r!CommandName Number Symbol Number`

_Note: The spaces are necessary, otherwise you'll get a "No Symbol Found" error_

*Symbols:*

```
+ : Add
- : Subtract
/ : Divide
* : Multiply
^ : Power
% : Modulo Divide
= : Round to
```

## [QR Encoder](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/QR-Encoder) by [Hexagon8899](https://twitter.com/Hexagon8899)

I'm actually not quite sure how this works so hopefully @hexagon8899 can explain(He made the command) but it encodes URLs into QR codes

*Syntax:*
`r!CommandName URL/Text`

_Note: It sorta works on text but you have to use `%20` instead of a space if you want to put more than one word_

## [GD Icon Finder](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/GD%20Icon%20Finder)

Uses the [GDBrowser API](https://gdbrowser.com/API) to find and show people's icons

*Syntax:*
`r!CommandName GDusername IconType`

_Note 1: This returns "Colon" and "Cube" for both arguments respectively if they aren't filled_

_Note 2: Glow can be removed by removing "&glow=1"_

_Note 3: The size of the image will be automatically resized to fit the icon. This can be removed by changing "auto" in "&size=auto" to the amount of pixels you want(it will always be square)_

## [Random GD Icon Generator](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/Random%20GD%20Icon%20Generator) by [Hexagon8899](https://twitter.com/Hexagon8899)

Generates a random GD icon using the [GDBrowser API](https://gdbrowser.com/API) without needing any syntax.

## [Rock Paper Scissors(Without Answers)](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/Rock%20Paper%20Scissors(without%20answers)) by [WolfPlays013](https://twitter.com/WolfPlay_Posts)

Plays a game of Rock Paper Scissors against Robotop(who answers randomly). Acts like it's Canary counterpart, [RockPaperScissors](https://github.com/toxicscientist/Better-Robotop/blob/Canary/commands/RockPaperScissors) but doesn't have answers.

*Syntax:*
`r!CommandName Answer`

*Possible answers:*

```
"r" - Rock

"p" - Paper

"s" - Scissors
```

## [Optifine Cape](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/Optifine%20Cape) by [ItsEmpa](https://twitter.com/Empa48630605)

Shows the Minecraft cape of the stated user

*Syntax:*
`r!CommandName User`

## [Newgrounds Search](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/Newgrounds%20Search) by [IxNoah](https://www.reddit.com/user/ixNoah)

Searches Nergrounds for the given search terms. It even accepts spaces

*Syntax:*
`r!CommandName SearchTerms`

## [Dancify](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/Dancify) by [ItsEmpa](https://twitter.com/Empa48630605)

Converts plain text to a dancing text. Supports all alphanumeric characters(and $&!?). Emojis yoinked from http://dance.cavifax.com/

*Syntax:*
`r!CommandName Message`

_Note: This is completely untested by me but it had so much effort in it that I couldn't put it in the Canary Build_

## [Random Place](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/Random%20Place) by [Hexagon8899](https://twitter.com/Hexagon8899)

Places a random pixel on the _r!place_ canvas. Acts a little bit weird from other commands as it has to be put in the "run command" section.
NSN

## [Bug Logger](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/Bug%20Logger)

Explained [here](https://github.com/toxicscientist/Better-Robotop/wiki/Bug-Logger). Just know that you need it to make bug reports
NSN

## [Calender](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/Calender) by [Hexagon8899](https://twitter.com/Hexagon8899)

A calender command that gives you the date in UTC with emoji formatted in a similar way to a calender with the past days crossed out, the current day highlighted and the future days also highlighted with different emoji.
NSN

## [8Ball Remade](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/8ball%20Remade)

A near-perfect replica of `r!8ball` for Update 2.0: The Remake Update

Missing Features:
```
Editing the message to show a negative result
```

_Note: Thank you Colon for making [all r!8ball responses public](https://drive.google.com/drive/u/0/folders/17RhXEoyArDClTDyiPsim9fc544eZsiqH)_

## [Dunsparce Remade](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/Dunsparce%20Remade)

A near-perfect replica of `r!dunsparce` for Update 2.0: The Remake Update

Missing Features:
```
Good empty argument detection
The Colon Easter egg
```

## [Percent Remade](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/Percent%20Remade)

A near-perfect replica of `r!percent` for Update 2.0: The Remake Update

Missing Features:
```
Multiple person detection
Multiple things to rank detection
```

## [Rate Remade](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/Rate%20Remade)

A near-perfect replica of `r!rate` for Update 2.0: The Remake Update

Missing Features:
```
5 stars not causing a weird bug
Half stars
Plural detection
```
