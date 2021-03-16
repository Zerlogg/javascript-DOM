# DOM Atomic 01: Show One Element

## Questions

---

> If you click the link to reveal more text and then refresh the page, does the text remain revealed, or is it hidden again? Why?

Your reply here...

Tekts ir paslēpts, jo atsvaidzinot šo mājaslapu, tā tiek atjaunota stāvoklī, kurā šis klikšķis vēl nav noticis.

> Remove `window.addEventListener("load", function(){` (and the closing `})`) from **global.js**. Does the link still reveal the text? What is the purpose of this code that you've removed?

Your reply here...

Jūs noņemat koda daļu, kas ielādē visu, kas tam seko. Šajā gadījumā window.addEventListener ielādē visu java script, kad lapa ir pabeigta. Bez šī koda daļas tā ir tikai nenosaukta funkcija.

> Describe the the `addEventListener` method. (Remember that there is a specific, technical, methodical way to describe methods. Your reply should match that format.)

Your reply here...

Jāpasaka, kuru notikumu tā klausās un kas jādara, kad tas notikums notiek.