# Commands

## [Math Remastered](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/math-remastered.yaml)

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

## [QR Encoder](https://github.com/toxicscientist/Better-Robotop/blob/master/commands/QR-Encoder)

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
