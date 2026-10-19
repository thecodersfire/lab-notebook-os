# Built-in features for lab-notebook-os

Purpose: scientific computing

1. **prepare study and research files** — run lab-notebook-os-workspace. It creates ~/Documents/lab-notebook-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run lab-notebook-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/lab-notebook-os-session-plans/.
3. **check study and source readiness** — run lab-notebook-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/lab-notebook-os-workspace features/lab-notebook-os-plan features/lab-notebook-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for scientific computing:

1. **Zotero** — org.zotero.Zotero
2. **Anki** — net.ankiweb.Anki
3. **Foliate** — com.github.johnfactotum.Foliate

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for scientific computing:

1. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
2. **Thonny** — write and debug Python code (org.thonny.Thonny)
3. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
4. **QGIS** — analyze geographic data and make maps (org.qgis.qgis)
5. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
6. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
7. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
8. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
9. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
10. **GNOME Weather** — check local weather conditions (org.gnome.Weather)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
2. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
3. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
4. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
5. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
6. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
7. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
8. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
9. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
10. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
11. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
12. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
13. **GNOME Text Editor** (org.gnome.TextEditor) — edit plain-text notes and configuration files.
14. **Document Scanner** (org.gnome.SimpleScan) — digitize paper notes and forms.
15. **GNOME Contacts** (org.gnome.Contacts) — organize partner and team contacts.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
2. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
3. **Marknote** (org.kde.marknote) — keep structured Markdown notes and project notebooks.
4. **KleverNotes** (org.kde.klevernotes) — capture and manage Markdown notes for projects and research.
5. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
6. **Clock** (org.kde.kclock) — set study, work, and routine timers with alarms and a stopwatch.
7. **KBibTeX** (org.kde.kbibtex) — maintain BibTeX citations for research and technical writing.
8. **Kontact** (org.kde.kontact) — organize email, calendars, contacts, and schedules in one workspace.
9. **KAlarm** (org.kde.kalarm) — schedule reminders and recurring task alerts.
10. **KMyMoney** (org.kde.kmymoney) — track household or small-business accounts, categories, and budgets.
11. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
12. **Ark** (org.kde.ark) — open and create common project archive files.
13. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
14. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
15. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.

## Fifteen additional purpose-specific applications

The setup adds these Flathub applications for scientific computing. Applications are fetched from Flathub by the setup script; each app keeps its own licensing and terms.

1. **Marble** (org.kde.marble) — Explore maps and a virtual globe for route and place context.
2. **KGeography** (org.kde.kgeography) — Practice place and map recognition.
3. **KGeoTag** (org.kde.kgeotag) — Review and edit photo location metadata.
4. **Kst** (org.kde.kst) — Display and inspect scientific measurement and time-series data.
5. **LabPlot** (org.kde.labplot) — Plot and analyze data imported from spreadsheets or research files.
6. **KStars** (org.kde.kstars) — Explore astronomy data and sky observations.
7. **KPhotoAlbum** (org.kde.kphotoalbum) — Tag and organize large photo collections.
8. **Tellico** (org.kde.tellico) — Catalog books, media, games, and other collections.
9. **PDF Arranger** (com.github.jeromerobert.pdfarranger) — Reorder, rotate, split, and merge PDF pages.
10. **LocalSend** (org.localsend.localsend_app) — Transfer files directly between nearby devices on your local network.
11. **Joplin** (net.cozic.joplin_desktop) — Organize notes and checklists in notebooks.
12. **KBackup** (org.kde.kbackup) — Create user-selected backup archives of files and folders.
13. **Déjà Dup** (org.gnome.DejaDup) — Create user-configured file backups to a chosen destination.
14. **KRename** (org.kde.krename) — Batch rename photo, document, and project files.
15. **Skanpage** (org.kde.skanpage) — Scan and arrange multipage documents from a connected scanner.
