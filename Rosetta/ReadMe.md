# Rosetta

In the "Strings" folder you'll find the files the game uses for localization. You can help me on this one, if you speak a language I do not know.
The easiest way to make me a new translation is by cannibalizing an existing language file.

Basically you just need to translate all "X=Y" fields.
## The \[AAA] category
Here you need to put in the name of your language in the language you translate to. For example if you were to translate to German that would be "LANGUAGE=Deutsch". The "TRANSLATOR" field should contain your name as credit to you for your translation.
## The \[^SYS^] category
Leave it alone, or remove it entirely. I used a quick tool for my translations, but the game itself won't use it.



## Special characters
The game only allows pure ASCII codes, which are the values 0-127. If that's too hard for ya, let's suffice to say all regular letters and numbers. If you want special characters you do need to use the pipe( | ) mark and to enter two characters and that will create the special character.
- |uu = ü
- |ue = ë
- |uo = ö
- |ua = ä
- |ui = ï
- |'a = á
- |'e = é
- |'i = í
- |'o = ó
- |'u = ú
- |\`a = à
- |\`e = è
- |\`i = ì
- |\`o = ò
- |\`u = ù
- |^a = â
- |^e = ê
- |^i = î
- |^o = ô
- |^u = û
- |sz = ß
- |tm = ™
- |in = ∞
- |cc = Copyright logo

If you need any characters I don't have here, please let me know. It's quite easy to add any new characters.


# HSV not translated in Dutch and German? Why?
Because the Dutch terms Kleurtoon(Hue), Verzadiging(Saturation) en Waarde(Value) did not make sense to me at all until I looked stuff up. 
Of course, I ain't a professional in this field, but it appears that many Dutch users who are working a lot with graphic software just use the English term.
In German Farbton(Hue), Sättigung(Saturation) and Helligkeit(Value) could be used, but are apparently not very common in the German community either as far as I could find out.
I merely put those keys into the localisation files so translators in other languages have the option for themselves to translate it or not, as I can't speak for all language groups all over the world.
It is possible you'll find other terms left in English in some translations for similar reasons. 


