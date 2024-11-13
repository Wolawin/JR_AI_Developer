# JR_AI_Developer

## Generowanie HTML z Artykułu za pomocą OpenAI

Ten projekt to aplikacja Python, która konwertuje treść artykułu na format HTML przy użyciu API OpenAI. Wygenerowany kod HTML strukturyzuje treść artykułu, a w miejscach, gdzie warto dodać obrazy, umieszcza tagi `<img>` ze wskazówkami dotyczącymi ich generowania.

## Wymagania

- Python 3.7 lub nowszy
- Konto OpenAI z kluczem API
- Biblioteka `openai`

## Instalacja

1. Sklonuj to repozytorium:
   ```bash
   git clone https://github.com/twoje-repozytorium.git
   cd twoje-repozytorium
Zainstaluj zależności:

bash
Skopiuj kod
pip install openai
Wprowadź swój klucz API OpenAI, edytując plik main.py:

python
Skopiuj kod
openai.api_key = 'YOUR_API_KEY'
Struktura projektu
main.py: Główny plik programu, który odczytuje artykuł, generuje HTML i zapisuje wynik w pliku artykul.html.
Zadanie dla JJunior AI Developera - tresc artykulu.txt: Plik tekstowy z przykładowym artykułem, który jest konwertowany na HTML.
artykul.html: Plik wynikowy zawierający wygenerowany kod HTML.
Użycie
Umieść plik tekstowy z treścią artykułu w katalogu głównym projektu i nadaj mu nazwę Zadanie dla JJunior AI Developera - tresc artykulu.txt.

Uruchom skrypt:

bash
Skopiuj kod
python main.py
Po uruchomieniu program odczyta treść artykułu z pliku, wygeneruje HTML i zapisze go do pliku artykul.html.

Otwórz artykul.html w przeglądarce, aby zobaczyć wyniki.

Wytyczne generowania HTML
Generowany kod HTML spełnia następujące wytyczne:

Używa odpowiednich tagów HTML do strukturyzacji treści artykułu.
Wstawia tagi <img src="image_placeholder.jpg" alt="prompt do generowania obrazka"> w miejscach, gdzie warto dodać obrazy.
Umieszcza podpisy pod obrazami za pomocą odpowiednich tagów HTML.
Nie zawiera żadnego kodu CSS ani JavaScript i zawiera tylko kod pomiędzy tagami <body> i </body> (bez <html>, <head>, i <body>).
Przykład wyjściowego kodu HTML
Wygenerowany HTML może wyglądać następująco:

html
Skopiuj kod
<h1>Tytuł artykułu</h1>
<p>Wstęp do artykułu...</p>
<img src="image_placeholder.jpg" alt="Obraz przedstawiający tytuł artykułu">
<figcaption>Opis obrazu</figcaption>
<p>Dalsza część treści...</p>
Uwagi
Przed użyciem projektu upewnij się, że masz dostępny klucz API z OpenAI i że zaktualizowałeś odpowiednio wartość openai.api_key w main.py.
Projekt zapisuje wyniki w pliku artykul.html, który możesz otworzyć w dowolnej przeglądarce, aby zobaczyć wygenerowany HTML.
Licencja
Ten projekt jest objęty licencją MIT. Szczegóły znajdziesz w pliku LICENSE.

markdown
Skopiuj kod

### Wyjaśnienie formatowania:
- **Nagłówki sekcji**: Poprawnie sformatowane, aby były wyraźnie widoczne.
- **Fragmenty kodu**: Umieszczone w blokach `bash`, `python`, lub `html` dla lepszej czytelności.
- **Lista punktowana**: Użyta do opisania struktury projektu oraz wymagań, co poprawia przejrzystość.
