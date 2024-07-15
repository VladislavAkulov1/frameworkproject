# Dokumentacja projektu: Aplikacja internetowa z wykorzystaniem MongoDB, Express, React i Node.js

## Opis

Ten projekt zawiera dwa główne komponenty:

### Frontend
Zbudowany przy użyciu React.js do tworzenia dynamicznego interfejsu użytkownika.

### Backend
Używa Node.js i Express.js do obsługi żądań i interakcji z bazą danych MongoDB, zapewniając niezawodne zarządzanie danymi i bezproblemową komunikację między serwerem a klientem.

## Struktura projektu

- `client`: zawiera kod źródłowy aplikacji React.
- `backend`: zawiera kod źródłowy serwera w Node.js z wykorzystaniem Express.js i MongoDB do zarządzania danymi.

## Używane technologie i narzędzia

- **React.js**: do tworzenia komponentów interfejsu użytkownika i zarządzania stanem aplikacji.
- **React Router**: do routingu i zarządzania przejściami między stronami.
- **Redux (jeśli używany)**: do globalnego zarządzania stanem aplikacji.
- **Axios**: do wykonywania żądań HTTP do serwera.
- **Node.js i Express.js**: do tworzenia RESTful API i obsługi logiki serwerowej.
- **MongoDB**: do przechowywania danych w bazie danych NoSQL.
- **Mongoose**: do interakcji z MongoDB za pomocą obiektowo-dokumentowego mapowania (ODM).

## Problemy i ich rozwiązania

### Routing
Użycie React Router do tworzenia tras w aplikacji i obsługi przejść między stronami.

### Zarządzanie stanem
Integracja Redux do scentralizowanego zarządzania stanem i zapewnienia przewidywalności danych.

### Obsługa żądań do API
Użycie Axios do wykonywania asynchronicznych żądań HTTP i obsługi odpowiedzi od serwera.

### Interakcja z bazą danych
Użycie Mongoose do uproszczenia pracy z MongoDB i implementacji schematów danych.


# Rozpoczęcie pracy z Create React App

Ten projekt został zainicjowany przy użyciu [Create React App](https://github.com/facebook/create-react-app).

## Dostępne skrypty

W katalogu projektu można uruchomić:

### `npm start`

Uruchamia aplikację w trybie deweloperskim.\
Otwórz [http://localhost:3000](http://localhost:3000), aby zobaczyć ją w przeglądarce.

Strona zostanie przeładowana po wprowadzeniu zmian.\
Możesz również zobaczyć błędy lintowania w konsoli.

### `npm test`

Uruchamia testy w trybie interaktywnego podglądu.\
Zobacz sekcję o [uruchamianiu testów](https://facebook.github.io/create-react-app/docs/running-tests) aby uzyskać więcej informacji.

### `npm run build`

Buduje aplikację do produkcji w folderze `build`.\
Poprawnie bundluje React w trybie produkcyjnym i optymalizuje build dla najlepszej wydajności.

Build jest zminimalizowany, a nazwy plików zawierają hashe.\
Twoja aplikacja jest gotowa do wdrożenia!

Zobacz sekcję o [wdrażaniu](https://facebook.github.io/create-react-app/docs/deployment) aby uzyskać więcej informacji.

### `npm run eject`

**Uwaga: to jest operacja nieodwracalna. Raz wykonana, nie można jej cofnąć!**

Jeśli nie jesteś zadowolony z narzędzi budowania i wyborów konfiguracyjnych, możesz je wycofać w dowolnym momencie. To polecenie usunie pojedyncze zależności budowania z projektu.

Zamiast tego skopiuje wszystkie pliki konfiguracyjne i zależności pośrednie (webpack, Babel, ESLint itp.) bezpośrednio do projektu, abyś miał pełną kontrolę nad nimi. Wszystkie polecenia oprócz `eject` będą nadal działać, ale będą wskazywać na skopiowane skrypty, więc możesz je dostosować. Na tym etapie jesteś na własną rękę.

Nie musisz nigdy używać `eject`. Wyselekcjonowany zestaw funkcji jest odpowiedni dla małych i średnich wdrożeń, i nie powinieneś czuć się zobowiązany do użycia tej funkcji. Rozumiemy jednak, że to narzędzie nie byłoby użyteczne, gdybyś nie mógł go dostosować, gdy będziesz na to gotowy.

## Dowiedz się więcej

Możesz dowiedzieć się więcej w [dokumentacji Create React App](https://facebook.github.io/create-react-app/docs/getting-started).

Aby nauczyć się React, sprawdź [dokumentację React](https://reactjs.org/).

### Code Splitting

Ta sekcja została przeniesiona tutaj: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analiza rozmiaru bundla

Ta sekcja została przeniesiona tutaj: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Tworzenie Progressive Web App

Ta sekcja została przeniesiona tutaj: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Zaawansowana konfiguracja

Ta sekcja została przeniesiona tutaj: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Wdrażanie

Ta sekcja została przeniesiona tutaj: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` nie udaje się zminimalizować

Ta sekcja została przeniesiona tutaj: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
