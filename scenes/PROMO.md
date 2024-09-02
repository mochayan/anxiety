# intro

`SceneSetup.intro();`

# intro-play-button

(...51)

[USIBA!](#intro-start) `publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`

# intro-start

(...500)

`clearText()`

n3: Ayha kita magsugod, unhon *mo* ba pagbasa?

`publish("show_options_bottom")`

# intro-start-2

n3: Sigi, magsugod na kita...

```
publish("hide_tabs");
clearText();
```

(...1000)

`publish("intro-to-game-2")`

n2: TAO INI

(...600)

`clearText()`

(...300)

`publish("intro-to-game-3")`

# act1

```
SceneSetup.act1();
publish("hide_tabs");
music('battle', {volume:0.5});
```

(...300)

n: AMO INI ANG ANXIETY HONG TAO

n: _IKAW_ ANG ANXIETY

(#act1_normal)


# act1_normal

```
hong({body:"putaway"});
sfx("rustle");
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Ha? Atodon ko na-a ang cellphone ko.

```
sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
```

n: ANG TUMONG MO SALIPDAN ANG TAO MO HONG *PILIGRO*

`bb({eyes:"look", mouth:"small_lock", body:"fear"})`

b: Hala! GaFacebook na sab kaw!

```
bb({eyes:"normal", mouth:"normal", body:"normal"});
hong({eyes:"annoyed"});
```

h: Ngansi taya nga dii na lang gani ako makaingkod hong kalinaw.

`hong({eyes:"neutral"});`

n: DALI, TAPAT WAA PA MODANGAT ANG *PILIGRO!*

```
bb({eyes:"look"});
```

[Aduy, pagkagrabi haning balita!](#act1d_news)

[Hala, kita taya ang pigaisturyahan haong post?](#act1d_subtweet)

[Piya ba iyan, gainom hong litsi](#act1d_milk)

# act1d_milk

`hong({mouth:"smile", eyes:"surprise"});`

h: Cute lagi, atoda ang--

```
hong({mouth:"shock", eyes:"shock"});
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
```

b: DII BA MAKAINOM HONG LITSI ANG MGA PIYA! TAO PA BA KAW TAYA? ANIMAL ABUSE!

(...200)

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
attack("20p", "bad");
publish("hp_show");
```



