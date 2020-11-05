---
id: 379
title: Miliardáři
date: 2014-10-23T07:00:07+01:00
author: Martin Maly
layout: post
guid: http://kcc.uelectronics.info/?p=379
permalink: /2014/10/23/miliardari/
xyz_lnap:
  - "1"
categories:
  - Kuřecí
---
Jsme tuhle spustili web [Forbes.cz](http://www.forbes.cz), a otevřeli jsme ho [webovou podobou žebříčku miliardářů](http://www.forbes.cz/miliardari/). Kdosi mi pak psal: &#8222;No, to bude makačka to aktualizovat&#8230;&#8220; (Kdosi jiný zase psal, že _to je celý nesmysl, protože to je spočítaný podle toho, co kdo přizná do daní, takže je to jen na oko, šmejdi, Kalousek rozkradl republiku, Babiš si hrabe, práce není&#8230;_, ale takovými se nemá cenu zabývat.)

Jenže aktualizace je docela brnkačka. Máme na to takový fígl už z Economie. Tam jsme totiž s Marcelem přišli na to, že nejlepší redakční systém pro takovéhle věci je&#8230;

&#8230; víte co&#8230;?

&#8230; obyčejná excelová tabulka! Lépe řečeno Google Spreadsheet.

Novinářům je to blízké a srozumitelné, s Excelem umí pracovat skoro všichni, snad i vedoucí kulturní rubriky, takže tam zádrhel není. A stačí vysvětlit: _Tajhle je tabulka, co do ní napíšeš, to se ukáže na tom webu, o nic se nestaráš, takže bacha, ať tam nepíšeš nesmysly, ty sloupečky takhle musej zůstat_ &#8211; a funguje to! Googlí spreadsheet umožňuje i to, že tam v jednu chvíli píše víc novinářů, takže v tomhle směru je to naprostá pohoda, nedohadujete se, kdo dělá úpravy, oni vám to neposílají mailem, prostě paráda. No a my máme takový proxy skript, co si na tu googlí tabulku šáhne, stáhne data, přechroupe je do JSONu a pošle jako skript s callbackem, takže i pro nás je to pohodlné.

A na takovéhle workflow žádný redakční systém, natož takový, co se používá v českých online médiích, nemá. Nebo si dovedete představit, jak si pro to píšete webové rozhraní nad databází? (No, vy možná ano, já ale ne&#8230;) V Economii jsme to použili pro kde co, od tabulky povodní přes Mapu moci po nějaké infografiky typu &#8222;Sto pilířů důchodového systému&#8220;&#8230;

Odpověď tedy zní: Aktualizace? Prostě ten novinář, který dotyčného zpracovává, zapíše do Matky Všech Tabulek správné údaje (on si je tam stejně zapisuje, protože je potřebuje pro sebe). A o víc se nestará. Mám tendenci to považovat za geniálně jednoduché řešení.