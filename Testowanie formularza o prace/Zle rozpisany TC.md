A tutaj przyklad zle rozpisanego TC. 

![Imgur](https://i.imgur.com/D6YGIee.png)

Jesli tworzymy TC dla danej funkcjonalnosci moze sie zdarzyc ze bledy beda nakladac sie na siebie
i zamaskuja inne bugi. W ponizszym przypadku zostala podjeta proba wyslania formularza z wieloma blednie wypelnionymi polami. System zwrocil informacje i wyszczegolnil pola na czerwono gdzie walidacja wykryla bledy. 

![Imgur](https://i.imgur.com/k0jkA8e.png)

Gdy poprawimy wyszczegolnione pola formularz powinien zostac poprawnie wyslany.
Dla przykladu poprawilismy adres e-mail na: abc@gmail.com i stwierdzamy, ze wszystko jest w porzadku.
Niestety nasze zalozenie jest bledne gdyz mozemy wpisac taki oto adres:

![Imgur](https://i.imgur.com/g4P7hFJ.png)

Lub taki:

![Imgur](https://i.imgur.com/VOHgNrv.png)


Dlatego nalezy zachowac szczegolna ostroznosc aby nie doprowadzic do takiej sytuacji. 
Gdy przyjrzymy sie uwaznie mozemy zauwazyc, ze walidacja nie 
dziala poprawnie dla pola: Name. W specyfikacji mamy informacje, ze pole nie moze byc puste, wiec warto sprawdzic czy pole przyjmuje inne wartosci jak np. liczby, znaki specjalne, twarda spacja.




