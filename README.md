# System Zarządzania Gastronomią

<img src="https://github.com/patrycja1245/Database-Bistro_Management_System/blob/main/readme.photo.png?raw=true" alt="Image Alt" style="width: 100%; height: auto;">


## Opis Projektu


Projekt "System Zarządzania Gastronomią" ma na celu stworzenie kompleksowego systemu wspomagającego działalność firmy gastronomicznej. System obejmuje różne aspekty zarządzania, takie jak obsługa klientów, rezerwacje stołów, obsługa zamówień, zarządzanie produktami oraz śledzenie płatności. Bazuje na relacyjnej bazie danych, co umożliwia efektywne zarządzanie danymi związanych z obszarem gastronomicznym.

## Cele Projektu

- Umożliwienie efektywnego zarządzania danymi z obszaru gastronomii.
- Zapewnienie intuicyjnego systemu rezerwacji stołów.
- Skuteczna obsługa zamówień, produktów i płatności.
- Ułatwienie śledzenia statusów rezerwacji i zamówień.

1. **Tabela "Clients":**
   - Zarządzanie klientami indywidualnymi i firmowymi.
   - Przechowuje informacje takie jak imię, nazwisko, numer telefonu oraz NIP.

2. **Tabela "Roles"::**
   - Przypisanie ról użytkownikom, np. klient, personel.

3. **Tabela "Users":**
   - Rejestracja użytkowników w systemie, z przypisanymi rolami.

4. **Tabela "Reservations":**
   - Zarządzanie rezerwacjami stołów, z informacjami o stanie rezerwacji.

5. **Tabela "Reservation_Statuses":**
   - Definicje statusów rezerwacji, np. "Potwierdzona", "Anulowana".

6. **Tabela "Reservation_Details":**
   - Szczegóły rezerwacji, takie jak wybrane stoły.

7. **Tabela "Orders":**
   - Obsługa zamówień, ich statusów oraz typów.

8. **Tabela "Categories":**
   - Kategorie produktów dostępnych w menu.

9. **Tabela "Products":**
   - Informacje o produktach, takie jak nazwa, opis i cena.

10. **Tabela "Order_Details":**
    - Szczegóły zamówienia, zawierające informacje o ilości zamówionych produktów.

11. **Tabela "Payment_Statuses":**
    - Rejestracja statusów płatności, np. "Opłacone", "Niezakończone"..

12. **Tabela "Order_Statuses":**
    - Definicje statusów zamówień, np. "W trakcie realizacji", "Zakończone".
