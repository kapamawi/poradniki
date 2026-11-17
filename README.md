# ChatGPT krok po kroku — strona e-booka

Statyczna strona gotowa do publikacji np. na Netlify: katalog publikacji to katalog główny repozytorium, bez kroku budowania. Lokalny podgląd: `python3 -m http.server 8000`.

Przyciski prowadzą do wskazanej strony Naffy. Przed publikacją sprzedawca powinien sprawdzić dostępność produktu, cenę, sposób dostarczenia i warunki zakupu oraz uzupełnić w stopce dane kontaktowe, regulamin, politykę prywatności i informacje o prawach konsumenta. Pełny e-book nie znajduje się w repozytorium; ilustracja zawiera wyłącznie jego okładkę.

## Publikacja i wyszukiwarki

Strona główna zawiera opis, metadane udostępniania oraz dane strukturalne książki i oferty. `robots.txt` dopuszcza indeksowanie; dokumenty prawne mają `noindex`, ponieważ są wersją testową. Przed rzeczywistą sprzedażą sprawdź kompletność dokumentów, proces płatności i dostarczenie produktu.

Po ustaleniu ostatecznego publicznego adresu HTTPS dodaj pełny adres kanoniczny, `og:url`, absolutny `og:image` oraz mapę witryny `sitemap.xml` z pełnymi adresami i jej adres w `robots.txt`. Zarejestruj witrynę w Google Search Console, zgłoś mapę i sprawdź indeksowanie oraz dostępność strony bez logowania. W przypadku publikacji w podkatalogu dopasuj adresy. Google może zaindeksować i wyświetlać strony według własnych zasad; metadane ani dane strukturalne nie gwarantują pozycji ani specjalnego wyglądu wyników.
