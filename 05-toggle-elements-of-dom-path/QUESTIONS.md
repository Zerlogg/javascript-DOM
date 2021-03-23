# DOM Atomic 05: Toggle Elements of DOM Path

## Questions

---

> Describe the contract you used for finding the movies to toggle in the DOM. How is this function different from other functions that find elements in the DOM?

Your reply here...

Es izmantoju .getElementsByClassName (), un .querySelectorAll (). .getElementsByClassName () aizņem tikai vienu argumentu, tāpēc jūs nevarat īsti strādāt ar to. Tomēr .querySelectorAll () ļauj būt precizākam. Šajā gadījumā argumentu, kuru mēs ievietojām "ul.second_five li", sadaloties, tas liek datoram atrast visus tagus (tag) ar klasi "ul", tad no šiem tagiem ņem tikai tos, kas ir apzīmēti ar "second_five", atstarpe ir pēctecis, kas liek tālāk ņemt tikai tos elementus ar pirmajiem diviem atribūtiem, kas ir apzīmēti kā saraksta vienumi.