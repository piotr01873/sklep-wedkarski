# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


# NURT Sklep Wędkarski — opis funkcji sklepu

1. **Strona główna**
   Prezentuje ofertę sklepu, bestsellery i metody łowienia. Użytkownik może wybrać interesującą go metodę, przejść do sprzętu spinningowego lub skorzystać z odnośnika do poradnika.

2. **Menu kategorii**
   Pozwala wybrać rodzaj sprzętu, np. wędki, kołowrotki, przynęty lub akcesoria. Zawiera również odnośniki do poradnika i promocji.

3. **Wyszukiwarka**
   Służy do wpisania nazwy szukanego sprzętu, np. wędki lub przynęty. Na makietach pokazano pole wyszukiwania, ale nie pokazano ekranu wyników.

4. **Lista produktów**
   Pozwala przeglądać i porównywać produkty na podstawie nazwy, ilustracji, parametrów, ceny i oceny. Oznaczenia „Bestseller” i „Nowość” wyróżniają wybrane produkty.

5. **Filtrowanie produktów**
   Pozwala zawęzić ofertę według ceny, producenta, długości wędki i ciężaru wyrzutowego. Przycisk „Pokaż produkty” służy do zastosowania filtrów, „Wyczyść” do ich wyzerowania, a symbol × przy aktywnym filtrze do jego usunięcia.

6. **Sortowanie i zmiana strony**
   Pole sortowania służy do wyboru kolejności produktów; na makiecie widoczna jest opcja „Polecane”. Numery stron i strzałka pozwalają przechodzić do kolejnych części listy produktów.

7. **Karta produktu**
   Pozwala zapoznać się z produktem przed zakupem. Pokazuje ilustracje, nazwę, cenę, ocenę, dostępność, opis i parametry. Zawiera też zakładki dotyczące parametrów, opinii oraz dostawy i zwrotów.

8. **Wybór wariantu i ilości**
   Użytkownik może wybrać długość wędki spośród pokazanych wariantów. Przyciski minus i plus służą do ustalenia liczby sztuk przed dodaniem produktu do koszyka.

9. **Dodawanie do koszyka**
   Przycisk „Dodaj do koszyka” służy do dodania wybranego wariantu i liczby sztuk. Ikony koszyka znajdują się również na kartach produktów. Na makietach nie pokazano potwierdzenia dodania.

10. **Dobieranie zestawu**
    Sekcja „Dobierz do zestawu” proponuje kołowrotek, wobler i plecionkę do wędki. Akcja „Dodaj do zestawu” umożliwia wybranie dodatkowego wyposażenia.

11. **Ulubione**
    Ikona serca służy do oznaczenia produktu jako ulubionego. Na makietach pokazano ikony przy produktach i w nagłówku, ale nie pokazano osobnej listy ulubionych.

12. **Zarządzanie koszykiem**
    Koszyk pozwala sprawdzić wybrane produkty, ich ceny i dostępność. Przyciski minus i plus służą do zmiany liczby sztuk, a ikona kosza do usunięcia pozycji. Odnośnik „Kontynuuj zakupy” umożliwia powrót do przeglądania oferty.

13. **Podsumowanie zamówienia**
    Pokazuje wartość produktów, koszt dostawy i łączną kwotę zakupu. W przedstawionym koszyku suma wynosi 388,90 zł, a dostawa jest darmowa. Komunikat wyjaśnia, że zamówienie przekracza próg darmowej dostawy 199 zł.

14. **Kod rabatowy**
    Pole pozwala wpisać kod rabatowy, a przycisk „Zastosuj” służy do jego użycia. Makieta nie pokazuje wysokości rabatu ani komunikatów po wpisaniu kodu.

15. **Przejście do dostawy**
    Przycisk „Przejdź do dostawy” prowadzi do następnego kroku zamówienia. Wskaźnik pokazuje kolejność: koszyk, dostawa i płatność. Ekrany dostawy i płatności nie zostały przedstawione.

16. **Kontakt i pomoc**
    Odnośniki do doradcy służą do uzyskania pomocy przy wyborze sprzętu. Stopka zawiera odnośniki do kontaktu oraz informacji o dostawie, płatnościach, zwrotach i reklamacji. Makiety nie pokazują treści tych podstron.

17. **Wersja mobilna**
    Strona główna i karta produktu mają układ dostosowany do telefonu. Mobilna karta pozwala zapoznać się z produktem, wybrać długość i liczbę sztuk oraz skorzystać z przycisku dodania do koszyka. Nagłówek zawiera ikony menu, wyszukiwania i koszyka.
