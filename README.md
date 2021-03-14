# NahamCon-2021-CTF
Friday, 12 March 12:00 PT — Sunday, 14 March 12:00 PT 48-hour Competition <br>

Table of contents
- [Warmups](#Warmups)
  - [Read The Rules](#Read-The-Rules)
  - [Car Keys](#Car-Keys)
  - [esab64](#esab64)
  - [Shoelaces](#Shoelaces)
  - [Veebee](#Veebee)
- [Cryptography](#Cryptography)
  - [Treasure](#Treasure)
- [mobile](#mobile)
  - [Andra](#Andra)
- [Miscellaneous](#Miscellaneous)
  - [Abyss](#Abyss)
- [mission](#mission)
  - [the mission](#the-mission)
  - [Bionic](#Bionic)
- [nahamcon](#nahamcon)
- 
# **Warmups**

# **Read The Rules**<br>
Please follow the rules for this CTF!<br>

**Solution** : ctrl+u at the Rules page<br>
_**flag{90bc54705794a62015369fd8e86e557b**}_<br>
![](https://github.com/darknezs/NahamCon-2021-CTF/blob/main/source/readRules.png)

# **Car Keys**
We found this note on someone's key chain! It reads... **ygqa{6y980e0101e8qq361977eqe06508q3rt}**? There was another key that was engraved with the word **QWERTY**, too… <br>
**Solution**: keyed-caesar-cipher <br>
message: ygqa{6y980e0101e8qq361977eqe06508q3rt}<br>
keyword : QWERTY<br>
_**flag{6f980c0101c8aa361977cac06508a3de}**_ <br>
![](https://github.com/darknezs/NahamCon-2021-CTF/blob/main/source/car_key.png)
# **esab64**
Was it a car or a cat I saw? <br>
_MxWYntnZiVjMxEjY0kDOhZWZ4cjYxIGZwQmY2ATMxEzNlFjNl13X_ <br>
**Solution**: esab64 is reverse of “base64” then bring string to reverse and then decode with base64 and reverse again.<br>
_**flag{fb5211b498afe87b1bd0db601117e16e}**_
![](https://github.com/darknezs/NahamCon-2021-CTF/blob/main/source/base64.png)
# **Shoelaces**
Do you double-knot your shoelaces? You gotta keep'em tied! <br>
![](https://github.com/darknezs/NahamCon-2021-CTF/blob/main/source/shoelaces.png)
**Solution**: strings shoelaces.jpg | grep flag{.*} <br>
_**flag{137288e960a3ae9b148e8a7db16a69b0}**_
![](https://github.com/darknezs/NahamCon-2021-CTF/blob/main/source/shoe_solve.png)
# **Veebee** 
Buzz buzz, can you find the honey? <br>
**Solution** : decode with vbe-decoder<br>
_**flag{f805593d933f5433f2a04f082f400d8c**_ }<br>
![](https://github.com/darknezs/NahamCon-2021-CTF/blob/main/source/veebee.png)
# **Cryptography**
# **Treasure**
# **mobile**
# **Andra**
# **Miscellaneous**
# **Abyss**
# **mission**
# **the mission**
# **Bionic**
# **nahamcon**
