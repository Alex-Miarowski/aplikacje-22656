## Zadania 2 i 3
### Przedstawienie rozwiązania
---------------------------------
---------------------------------
# Zadania z Lab2
---------------------------------

![](assets/screenshots/screen1.png)

Wygląd strony do logowania użytkownika.

![](assets/screenshots/screen2.png)

Po wejściu w 'register here' przechodzimy do formularzu z rejestracją.

![](assets/screenshots/screen3.png)

Po zarejestrowaniu widzimy widok witający nowego użytkownika. Po kliknięciu 'log in' wracamy do widoku logowania.

![](assets/screenshots/screen14.png)

W przypadku podania błędnych danych logowania dostajemy taki warrning.

![](assets/screenshots/screen4.png)

Gdy wprowadzone dane są poprawne przechodzimy do 'dashboarda', gdzie mamy możliwość edycji naszego profilu lub zmianę hasła.

![](assets/screenshots/screen5.png)

Po wejściu w edycję przechodzimy do widoku zmiany w koncie.

![](assets/screenshots/screen6.png)

Gdy wprowadzony format danych będzie błędny dostaniemy error.

![](assets/screenshots/screen7.png)

Jeżeli będą poprawne dostajemy informację o sukcesie.

![](assets/screenshots/screen8.png)

Gdy w dashboardzie wejdziemy w opcję zmiany hasła przechodzimy do podstrony z formularzem do tego przeznaczonym.

![](assets/screenshots/screen9.png)

Widok po poprawnej zmianie hasła.

![](assets/screenshots/screen10.png)

Widok po wylogowaniu.

![](assets/screenshots/screen11.png)

Widok przypomnienia hasła, wejście do formularza dostępne jest przy logowaniu.

![](assets/screenshots/screen12.png)

Informacja o wysłaniu wiadomości email prowadzącym do przypomnienia hasła.

![](assets/screenshots/screen13.png)

Widok z konsoli dotyczący wysłania maila.

---------------------------------
# Zadania z Lab3
---------------------------------

![](assets/screenshots/screen15.png)

Po prawej stronie widać nowe możliwości logowania: przez konto na facebooku i konto google.

![](assets/screenshots/screen16.png)

Po wybraniu pierwszego wariantu zostajemy przeniesieni na stronę facebooka, która spyta nas (jeżeli jesteśmy już zalogowani na koncie) czy chcemy kontynuować logowanie kontem facebooka.

![](assets/screenshots/screen17.png)

Po zalogowaniu widać w prawym górnym rogu, że zostałem zalogowany jako "Alex".

![](assets/screenshots/screen18.png)

Po wybraniu drugiej opcji logowania przeniesieni zostaniemy do widoku logowania google. W przypadku gdy jesteśmy zalogowani już musimy wybrać, z którego konta chcemy kontynuować.

![](assets/screenshots/screen19.png)

Po zalogowania z konta google widać, że na stronie jestem zalogowany jako "Alexacy".


---------------------------------
# Zadania z Lab4
---------------------------------
![](assets/screenshots/screenL4-1.png)

Panel admina, w którym widać dodane tokeny

![](assets/screenshots/screenL4-2.png)

Spis wszystkich książek dodanych pod /books/

![](assets/screenshots/screenL4-3.png)

Interfejs REST API
Widać w nim wszystkie dodane książki, możemu w nim również dodać kolejne

![](assets/screenshots/screenL4-4.png)

Każda z książek posiada swój tytuł, podtytuł, autora oraz numer ISBN

![](assets/screenshots/screenL4-5.png)

Każdą książkę można podejrzeć z osobna

![](assets/screenshots/screenL4-6.png)

Opcja GET pokazuje nam książkę (lub książki) jako obiekt typu JSON

![](assets/screenshots/screenL4-7.png)

Pod /api/users/ posiadamy listę wszystkich użytkowników. Jest ona dostępna jednak tylko osobom zarejestrowanym

![](assets/screenshots/screenL4-8.png)

Na dole widać formularz dodawania nowego użytkownika

![](assets/screenshots/screenL4-9.png)

Istnieje również możliwość podejrzenia konkretnego usera po dodaniu do URLa id

![](assets/screenshots/screenL4-10.png)

Dodany został też swagger dostępny pod /swagger-docs/, który jest narzędziem pomagającym tworzyć i dokumentować usługi REST API

---------------------------------
# Zadania z Lab6
---------------------------------

Użycie Viewsets __api/views.py__ :

![](assets/screenshots/screenL6-1.png)

Użycie Routers __api/urls.py__ :

![](assets/screenshots/screenL6-2.png)

Użycie Serializers __api/serializers.py__ :

![](assets/screenshots/screenL6-3.png)

Uwierzytelnianie __api/bookmarks/settings.py__ :

![](assets/screenshots/screenL6-4.png)

Dodanie __rest_framework.authtoken__ w __bookmarks/settings.py__ :

![](assets/screenshots/screenL6-5.png)

Dzięki temu w panelu admina widzimy, że została dodana zakładka z tokenami:

![](assets/screenshots/screenL6-6.png)

__Licznik odwiedzin na stronie wykorzystujący pliki cookies:__

Funkcja w __api/views.py__:

![](assets/screenshots/screenL6-7.png)

Dodany url do licznika:

![](assets/screenshots/screenL6-8.png)

__Komunikat przy pierwszej wizycie__:

![](assets/screenshots/screenL6-9.png)

__Komunikat przy następnych wizycie__:

![](assets/screenshots/screenL6-10.png)
