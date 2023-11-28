# [karty.kodziaki.pl](https://karty.kodziaki.pl/)

+ [DANE](DANE/README.md)
  
## Elementy

### Input
- Klawiatura ekranowa
- Mikrofon
- Kamera
- Pamięć trwała

### Output
- Głośnik
- Wyświetlacz
- Dioda LED


### Objects
- Plik muzyczny
- Plik graficzny
- Plik tekstowy
- Treść wiadomości
   - nadawca
   - odbiorca
   - wiadomość
   - temat
- Poziom jasności
- Poziom głośności

### Functions
- zapisz
- edytuj
- utwórz
- usuń
- wyślij
  

## Komponenty

### Wysyłanie e-maili
- Input: Klawiatura ekranowa
- Output: Wyświetlacz
- Objects: Treść e-mail
- Functions: Tworzenie i wysyłanie e-maila
   


### Odtwarzanie muzyki
- Input: Aplikacja muzyczna
- Output: Głośnik
- Objects: Plik muzyczny
- Functions: Odtwarzanie wybranej piosenki

### Robienie zdjęć
- Input: Kamera
- Output: Wyświetlacz
- Objects: Zdjęcie cyfrowe
- Functions: Uchwyć i zapisz obraz

### Pisanie wiadomości tekstowych
- Input: Klawiatura ekranowa
- Output: Wyświetlacz
- Objects: Tekst wiadomości
- Functions: Tworzenie i wysyłanie wiadomości

### Nawigacja GPS
- Input: Odbiornik sygnału (GPS) z satelit
- Output: Wyświetlacz
- Objects: Dane lokalizacyjne
- Functions: Wskazywanie drogi

### Regulacja jasności ekranu
- Input: Ustawienia systemowe
- Output: Wyświetlacz
- Objects: Poziom jasności
- Functions: Dopasowanie jasności ekranu

### Głosowe wyszukiwanie w internecie
- Input: Mikrofon
- Output: Wyświetlacz
- Objects: Zapytanie wyszukiwarki
- Functions: Rozpoznawanie i przetwarzanie komend głosowych

### Oglądanie filmów
- Input: Dysk
- Output: Wyświetlacz
- Objects: Strumień wideo
- Functions: Odtwarzanie, zatrzymanie filmu

### Sprawdzanie powiadomień
- Input: Czujnik zbliżeniowy
- Output: Wyświetlacz
- Objects: Lista powiadomień
- Functions: Wyświetlanie najnowszych powiadomień

### Gra komputerowa na smartfonie
- Input: Ekran dotykowy
- Output: Wyświetlacz
- Objects: Gra komputerowa
- Functions: Interakcja z grą poprzez dotyk


### Aktywacja latarki
- Input: Włącznik latarki
- Output: Dioda LED
- Objects: Sygnał włącz/wyłącz
- Functions: Oświetlenie otoczenia
   
### Zmiana głośności dzwonka
- Input: Ustawienia dźwięku
- Output: Głośnik
- Objects: Poziom głośności dzwonka
- Functions: Ustawianie głośności dzwonka      



### Telefonowanie

- Input: Mikrofon
- Output: Głośnik
- Objects: poziom głośności
- Functions: Przeprowadzanie rozmowy


Rozmowa rozbudowana na trzy oddzielne procesy z wykorzystaniem różnych interfejsów: logik i obiektów danych

1. **Wybieranie numeru telefonu:**
   - Input: Klawiatura ekranowa
   - Output: Wyświetlacz (prezentujący wpisany numer)
   - Objects: Numer telefonu
   - Functions: Wprowadzanie i walidacja numeru telefonu

2. **Rozmowa telefoniczna:**
   - Input: Mikrofon (do przechwytywania głosu użytkownika) i Głośnik (do odtwarzania głosu rozmówcy)
   - Output: Głośnik (do odtwarzania głosu rozmówcy) i Mikrofon (przesyłający głos użytkownika)
   - Objects: Zakodowany strumień dźwięku (głos użytkownika i rozmówcy)
   - Functions: Kompresja (kodowanie) głosu użytkownika do przesłania i dekompresja (odkodowanie) przychodzącego głosu rozmówcy

3. **Zakończenie rozmowy:**
   - Input: Przycisk zakończenia połączenia na ekranie dotykowym
   - Output: Sygnał do sieci komórkowej o zakończeniu połączenia
   - Objects: Sygnał zakończenia połączenia
   - Functions: Odcięcie aktywnego połączenia i potwierdzenie zakończenia użytkownikowi

Takie rozłożenie pozwala lepiej zrozumieć złożoność procesu rozmowy telefonicznej i w jaki sposób różne komponenty smartfona są wykorzystywane do wykonania poszczególnych czynności. Części te są ze sobą powiązane i sekwencyjne, co oznacza, że wywołanie kolejnych akcji jest zależne od poprzednich, np. odebranie głosu rozmówcy jest możliwe po wcześniejszym wybraniu numeru i nawiązaniu połączenia.




