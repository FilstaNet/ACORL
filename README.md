# ACORL
API Controlled Overlay Rocket League
SHA256: 
Languages: Polish / english

NOTE: Be aware the app might malfunction as ACORL is in early production stage.


English:
ACORL is used to create dynamic overlays for Rocket League. It uses the API recently released by the game developers (https://www.rocketleague.com/en/developer/stats-api) to capture data.
User Guide:
1. Download the latest release of the application.
2. After launching the application, select your monitor resolution.
3. Enter the appropriate Rocket League API port (default: 49123) and click Connect.
4. Launch OBS Studio and create a new scene. First, set the image source as Game Capture -> Capture a specific window -> select the RocketLeague.exe process (while it's running).
5. Add the image source in the browser and enter the URL visible in the ACORL menu (default: http://127.0.0.1:5147/overlay) and adjust the height and width. Set it to display over the game. 
6. Import the overlay file (use the default one or create your own using overlay_template).
7. Create elements you need or download template and load it.
8. Once you're finished, you can save the overlay to a file and then load it whenever needed.

Set the same resolution in both OBS Studio and ACORL.
To start using ACORL, simply download the default .png overlay image and import it into the app.
If you have any problems with the app, contact me on Discord: filip.223w

Default overlay PNG file is available for download. Overlay template is available for download.


Polish:
ACORL służy do tworzenia dynamicznych overlayów dla Rocket League. Używa niedawno udostępnionego przez twórców gry API (https://www.rocketleague.com/en/developer/stats-api) do przechwytywania danych. 
Instrukcja obsługi:
1. pobierz najnowsze wydanie (release) aplikacji,
2. Po uruchomieniu aplikacji Wybierz swoją rozdzielczość monitora,
3. Wpisz odpowiedni port API rocket league (domyślnie: 49123) i Połącz,
4. Uruchom OBS studio i stwórz nową scenę. Pierwsze źródło obrazu sutaw jako przechwytywanie gry -> przechwytuj konkretne okno -> wybierz proces RocketLeague.exe (musi być uruchomiony)
5. Dodaj źródło obrazu Przeglądarka i wprowadź adres URL widoczny w aplikacji (domyślnie: http://127.0.0.1:5147/overlay) i dopasuj wysokość oraz szerokość. Ustaw go aby wyświetlał się ponad grą.
6. Importuj plik overlay (użyj domyślnego, lub stwórz własny z pomocą overlay_template)
7. Utwórz potrzebne elementy lub pobierz szablon i załaduj go.
8. Po zakończonej pracy możesz zapisać overlay do pliku i potem ponownie go wczytać. 

W OBS studio jak i w ACORL ustaw tą samą rozdzielczość. 
Aby rozpocząć korzystanie z ACORL wystarczy pobrać domyślny obraz overlay .png i go importować do aplikacji.
W razie problemów z aplikacją napisz do mnie na discordzie: filip.223w


2026 FilstaNet. All rights reserved©.

# Known issues

Unexpected resolution behaviour. As for now, while editing the Overlay Profile, pick Full HD option for best editing expierience. choosing else (even if your monitor is different) will cause text appear different than it actually is.
Another issue related to this one is display changes while changing screens you operate on. Please, edit in Fullscreen mode on the monitor your game will be running to be sure no issues occure.

Issues with inputs. Sometimes you will be unable to input text anywhere in the app. In order to fix it open another window (for example google) and tab back to the app. Sometimes apps' reset will be necessary. In this case rememebr to save your overlay profile.

