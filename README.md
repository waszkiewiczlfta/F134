F134 - Katalog Filmowy

//opis
katalog filmowy umozliwiajacy dodawnie, przegladanie, edycje i usuwanie filmow z dodatkowa rejestracja.

//autor
Krzysztof Waszkiewicz 4F

//funkcjonalności
1.Dodawanie, edycja, usuwanie i podgląd filmów.
2.Wyszukiwanie po tytule, sortowanie po roku/ocenie (GET).
3.Formularz zakładania konta.
4.Node.js, Express, MongoDB, Docker.


//instalacja
1. uruchom baze: `docker run -d -p 27017:27017 --name f134-mongo mongo`
2. Otworz terminal CMD w VSC i wpisz npm init -y
2. zainstaluj pakiety: `npm install nodejs express mongodb ejs`
3. uruchom serwer: `npm start`
4. adres: `http://localhost:3000`

//endpointy
- `GET /movies` = lista
- `GET /movies/new` = formularzz dodawania
- `POST /movies` = dodawanie
- `GET /movies/:id` = szczegoly
- `PUT /movies/:id` - edycja
- `DELETE /movies/:id` - usuwanie
- `POST /users/register` - rejestracja

//
Licencja MIT
