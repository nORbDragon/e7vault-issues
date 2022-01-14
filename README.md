# e7vault-issues

E7 Vault Issue Tracker / Трекер проблем и предложений по E7 Vault

## English

This is Issue Tracker for **E7 Vault** - https://www.e7vau.lt/

Of course, you will not find source codes for decoding sct and scsp files here. I'm greedy, yes! But here you can let me know about any bugs you find on my site. Remember to indicate which device and browser you were using to get this error.

You can offer your ideas for filling the site. But this does not mean that I will implement them. But the main thing in our business is to express an idea? And there is a chance that it will interest me too.

### About «E7 Vault»

**«E7 Vault»** is planned as a replacement for the departed **e7herder.com**. Therefore, its design style and functionality may seem like "copy-paste" to some. That's how it was intended. And I don't hide that my site is just a replacement for **e7herder**.

### Reasons for abandoning the «e7herder» engine:
- Very hardcoded javascript code. It is very difficult to make changes to the code and site pages. For me.
- There is no support for models from spine v3.8.xx in the model viewer (spine v2.1.27 only).
- Other pages with character info, calculator, etc. are very hardcoded. At the moment there is no chance of updating the information on these pages. It is better to remove them altogether for now.

But in any case, I am grateful to https://github.com/zklm for the fact that he posted a dump of his **«e7herder»** for free access - https://github.com/zklm/e7herder-issues/releases/tag/dump


## Тоже самое, но на русском языке

Это - трекер проблем и предложений по мини-сайту **E7 Vault** - https://www.e7vau.lt/

Исходных кодов по декодированию sct и scsp файлов здесь вы, конечно же, не найдёте. Я жадный, да! Но здесь вы можете сообщать мне напрямую о найденных на моём мини-сайте ошибках. Не забывайте только указывать, какое устройство и браузер вы использовали для получения этой ошибки.

Можно предлагать свои идеи по наполнению сайта. Но это не значит, что я их буду реализовывать. Но ведь главное в нашем деле: высказать идею? И есть шанс, что она меня тоже заинтересует.

### О сайте

**E7 Vault** писался в первую очередь в качестве замены ушедшего на покой **e7herder.com**. Поэтому его стиль оформления и функционал может некоторым показаться "копи-пастой". Так и было задумано. И я не скрываю, что мой сайт просто замена для **e7herder**.

### Причины отказа от движка сайта «e7herder»:
- Огромное количество хардкода и сложных построений в ява-скриптах. По этим причинам довольно сложно вносить изменения в существующий код движка и обновлять содержимое страниц. Это я о своих возможностях и силах, если чего.
- В движке нет поддержки для портретов/моделей, сделанных через использование Spine версии 3.8.xx. Поддерживается только устаревший формат Spine v2.1.27.
- Страницы с информацией о персонажах, калькулятор и т.д. перенасыщены хардкодом. На данный момент я не вижу никакой возможности их обновлять. Поэтому решил даже не думать над их переносом на этот сайт.

Но даже с учётом всех своих мелочных претензий, я очень благодарен https://github.com/zklm за то, что он выложил полный дамп своего **«e7herder»** в открытый доступ для всех желающих - https://github.com/zklm/e7herder-issues/releases/tag/dump 

### О странице «Просмотр портретов»

Сначала я пытался перевести все портреты персонажей из игры из формата Spine v2.1.27 и v.3.8.xx в один общий, и использовать для их отображения на сайте официальный **Spine Web Player**. Но из-за огромного количества мелких и несовсем проблем при конверсии формата из v2.1.27 в формат v4.1 пришёл к выводу, что оно не стоит того. И решил сделать "гибридный" вариант: для v2.1.27 использовать движок от сайта **«e7herder»**, а для v3.8.xx - **Spine Web Player**.

Постарался "гибридность" сделать как можно незаметнее. Поэтому, если у вас будут проблемы с каким-то определённым персонажем, указывайте его имя в баг-репорте. А ещё лучше - его **ID**. Я его показываю в верхнем-правом углу карточки персонажа. Обычно имеет вид как **cXXXX** или **npcYYYY**.
