---
name: Błąd logowania - komunikat 'Logowanie nie powiodło się' przy poprawnych danych
about: Użytkownik z rolą 'nauczyciel' nie może się zalogować do systemu pomimo wprowadzenia
  prawidłowego loginu i hasła. System wyświetla błąd 'Logowanie nie powiodło się'."
title: ''
labels: bug, critical, login
assignees: ''

---

Błąd logowania - komunikat 'Logowanie nie powiodło się' przy poprawnych danych

Użytkownik z rolą 'nauczyciel' nie może się zalogować do systemu pomimo wprowadzenia prawidłowego loginu i hasła. System wyświetla błąd 'Logowanie nie powiodło się'.

1. Otwórz stronę logowania (https://schoolmanager.example.com/login)
2. Wpisz login: jan.kowalski@szkola.pl
3. Wpisz hasło: Test123!
4. Kliknij przycisk "Zaloguj"

Oczekiwany rezultat: Użytkownik zostaje zalogowany i przekierowany do panelu nauczyciela
Rzeczywisty rezultat: Wyświetla się komunikat "Logowanie nie powiodło się" i użytkownik pozostaje na stronie
logowania

Środowisko: Windows 11, Chrome 120, Wersja aplikacji: 2.3.1
Priorytet: Krytyczny
