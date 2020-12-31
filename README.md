# Verumequus

![xkcd 936](https://imgs.xkcd.com/comics/password_strength.png)

Generates **Latin** passphrases which are secure, easy to type and, perhaps, easy to remember and communicate orally, depending on your cultural and educational background (e.g. if you're an Italian who was compelled to study Latin for 5 years in high school).

## Install

```
wget -O ~/.local/bin/verumequus https://raw.githubusercontent.com/natema/verumequus/master/verumequus
sudo chmod +x ~/.local/bin/verumequus
```

## Examples

```
$ verumequus
AtQuaeDoctorPotestas
```
```
$ verumequus 6
TabulaInfletusNatalisTotiesMortuusGestum
```
```
$ verumequus 5 '-'
Supplicium-Satura-Labor-Frequentia-Sino
```
```
$ verumequus 5 '+'
Sufficio+Purgamentum+Fodio+Bis+Suus
```
```
$ verumequus 5 '*'
Quater*Bellum*Requiro*Gravitas*Opto
```

## Credits

This work is heavily based on [Anton Polonskiy's `correcthorse`][1], released under MIT License in 2017.

[1]: https://github.com/polonskiy/correcthorse "CorrectHorse Github repository (accessed 2020-12-31)"
