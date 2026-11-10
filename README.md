# Automatyczna Recepcja hotelowa

1. Opis projektu
Głównym celem projektu jest stworzenie systemu odwzorowującego działanie nowoczesnej, automatycznej recepcji hotelowej, która pozwala na obsługę gości bez konieczności kontaktu z pracownikiem recepcji.

System nie umożliwia dokonywania wcześniejszych rezerwacji. Utworzenie rezerwacji jest integralną częścią procesu zameldowania i odbywa się bezpośrednio w automacie. Gość podaje swoje dane, wybiera dostępny pokój, określa długość pobytu, a następnie dokonuje symulowanej płatności. Po pomyślnym zakończeniu procesu system automatycznie tworzy rezerwację, generuje indywidualny kod PIN i przyznaje dostęp do pokoju.

Aplikacja umożliwia również przeprowadzenie procesu wymeldowania, podczas którego kod PIN zostaje dezaktywowany, a pokój zmienia swój status.

2. Główne funkcjonalności
2.1. Automatyczne zameldowanie
Rozpoczęcie procesu zameldowania przez gościa.
Wprowadzanie danych osobowych, takich jak imię, nazwisko i adres e-mail.
Wyświetlanie aktualnie dostępnych pokoi.
Wybór rodzaju pokoju.
Określenie długości pobytu.
Automatyczne sprawdzanie dostępności wybranego pokoju.
Utworzenie rezerwacji w ramach procesu zameldowania.
Automatyczne przypisanie pokoju do gościa.
2.2. Zarządzanie pokojami hotelowymi
Przechowywanie informacji o pokojach hotelowych.
Obsługa różnych rodzajów pokoi, np. jednoosobowych, dwuosobowych i apartamentów.
Przechowywanie numeru pokoju, ceny oraz rodzaju pokoju.
Sprawdzanie dostępności pokoi.
Kontrolowanie aktualnego statusu pokoju.
Zmiana statusu pokoju po zameldowaniu i wymeldowaniu.
2.3. Obsługa gości
Rejestrowanie danych gościa podczas zameldowania.
Przypisywanie gościa do wybranego pokoju.
Powiązanie danych gościa z aktualną rezerwacją.
Wyświetlanie informacji o bieżącym pobycie.
System nie przechowuje historii zakończonych pobytów. Dane dotyczące pobytu są wykorzystywane do obsługi aktualnego zameldowania i rozliczenia wymeldowania.

2.4. System płatności
Obliczanie całkowitego kosztu pobytu.
Uwzględnianie liczby noclegów i rodzaju pokoju.
Obsługa różnych metod płatności, np. kartą i gotówką.
Symulowanie procesu płatności.
Sprawdzanie wyniku płatności.
Zatwierdzanie zameldowania po pomyślnej płatności.
W przypadku nieudanej płatności system nie powinien aktywować kodu PIN ani zatwierdzać zameldowania.

2.5. Generowanie i obsługa kodów PIN
Automatyczne generowanie indywidualnego kodu PIN dla gościa.
Przypisywanie kodu do konkretnego pokoju i pobytu.
Kontrolowanie poprawności wprowadzonego kodu.
Sprawdzanie ważności kodu PIN.
Ograniczenie ważności kodu do okresu pobytu.
Dezaktywowanie kodu po zakończeniu pobytu.
2.6. Symulacja elektronicznego zamka
Wprowadzanie kodu PIN w symulowanym panelu dostępu.
Weryfikacja poprawności kodu.
Symulowanie otwierania drzwi po wpisaniu prawidłowego PIN-u.
Odrzucanie nieprawidłowych i wygasłych kodów.
Symulowanie zamykania drzwi.
2.7. Automatyczne wymeldowanie (Check-out)
Rozpoczęcie procesu wymeldowania.
Weryfikacja informacji o aktualnym pobycie.
Rozliczenie ewentualnych należności.
Dezaktywacja kodu PIN.
Zakończenie aktualnego pobytu.
2.8. Panel administracyjny hotelu
Wyświetlanie listy wszystkich pokoi.
Dodawanie i zarządzanie pokojami.
Sprawdzanie aktualnych statusów pokoi.
Wyświetlanie aktualnie zajętych i dostępnych pokoi.
Przeglądanie aktualnych pobytów.
Kontrolowanie dostępności pokoi.
Panel administracyjny nie zawiera historii zakończonych pobytów ani archiwum rezerwacji.

3. Zasady działania systemu
System działa w oparciu o kilka podstawowych zasad:

Rezerwacja nie może zostać utworzona bezpośrednio z menu głównego. Powstaje wyłącznie w ramach procesu zameldowania.
Gość może wybrać wyłącznie pokój dostępny w wybranym terminie.
Jeden pokój nie może być przypisany do dwóch gości w nakładających się terminach.
Kod PIN jest generowany dopiero po pomyślnym zakończeniu płatności.
Kod PIN jest przypisany do konkretnego pokoju i okresu pobytu.
Po wymeldowaniu kod PIN zostaje dezaktywowany.
System nie przechowuje historii zakończonych pobytów.

Projekt koncentruje się na automatyzacji procesu zameldowania, tworzeniu rezerwacji na miejscu, obsłudze płatności oraz elektronicznej kontroli dostępu do pokoi za pomocą kodów PIN.
