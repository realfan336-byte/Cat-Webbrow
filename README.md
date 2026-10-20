# Cat-Webbrow
Please report if there is any bugs and try giving us Some ideas to make it better 

PET MY CAT — TWO SETUPS

MOBILE (Android)
1. Extract the ZIP.
2. Open Setup-Mobile.html in a browser.
3. Select the extracted project folder/files and tap “Check files & build Play.html”.
4. Setup checks index.html, css/style.css, and js/app.js. If found and readable, it builds a standalone Play.html.
5. Mobile browser security normally prevents saving directly into the selected folder. The browser downloads Play.html; move it from Downloads into the source folder manually. This is an OS/browser restriction, not something HTML can bypass.

WINDOWS PC
1. Extract the ZIP to a normal folder.
2. Double-click Setup-PC.bat.
3. It checks that the three real source files exist and are non-empty, reads them, embeds CSS and JavaScript, writes Play.html into the SAME folder, then opens it in the default browser.
4. If it reports missing files, keep the folder structure intact and run the BAT again.

Files:
- Setup-Mobile.html: browser-based mobile source checker/builder
- Setup-PC.bat: Windows setup that writes Play.html beside the sources
- Setup-PC.html: short PC setup guide
- index.html, css/style.css, js/app.js: editable source files
- Play.html: prebuilt standalone cat game included as a fallback

No internet is needed to play. This is not a native APK or EXE installer.

Windows setup internals: Setup-PC.bat runs Setup-PC.ps1 to validate sources and create Play.html in the same folder. 


Last thing After setup , your Play.html might download at your Download file please move it to The folder where you installed your game.



