# Scalenie ofert – podsumowanie

Plik wynikowy: **PRACTIC_PRODUCT_OFFER_2026_MERGED.xlsx** (arkusz `OFERTOWNIK`)

Bazą jest `PRACTIC_PRODUCT_OFFER_2026.xlsx` (pełna oferta 2026 wraz ze zdjęciami
produktów), do której scalono dane z `Practic_offer_Rajanis.xlsx`.

## Zasady scalenia
- **Klucz dopasowania:** kod EAN (kolumna `CODE EAN`).
- **Brak duplikatów:** produkty występujące w obu plikach pojawiają się tylko raz.
- **Tylko lepsze (niższe) ceny:** dla produktów obecnych w obu plikach cena z
  oferty Rajanis została użyta **wyłącznie wtedy, gdy była niższa** niż w ofercie
  2026. Ceny droższe lub równe pozostawiono bez zmian.
- **Produkty wyłącznie z Rajanis** zostały dopisane na końcu listy.

## Statystyki
- Wspólne produkty (po EAN): 34
  - Cena zaktualizowana na tańszą z Rajanis: **23**
  - Cena z Rajanis droższa/równa – pozostawiono ofertę 2026: 11
- Produkty dopisane (tylko w Rajanis): **11** (LP 471–481, wiersze 323–333)
- Łączna liczba pozycji produktowych: 331 (330 unikalnych EAN)

## Uwaga
EAN `5903456110499` występuje dwukrotnie – jest to duplikat istniejący już w
źródłowym pliku oferty 2026 (niezwiązany ze scaleniem z Rajanis).
