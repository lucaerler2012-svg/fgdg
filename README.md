# Bigger Bundles (Fabric, Minecraft 26.3)

- **Large Bundle**: 3 Bundles (beliebige Farbe) im Eimer-Muster (V-Form) craften.
- **Super Large Bundle**: 3 Large Bundles im Eimer-Muster craften.
- Eigene Texturen: Large = gruen, Super Large = lila mit Funkeln.

Wichtig: Bundles vor dem Craften leeren, der Inhalt geht beim Craften sonst verloren.

Hinweis: Die Kapazitaet (3x bzw. 9x) ist noch NICHT eingebaut. Dafuer muss die echte
26.3-Klasse `BundleContents` bekannt sein (siehe Chat).

## Bauen mit GitHub

1. Neues GitHub-Repo anlegen, diesen Ordner hochladen (inkl. `.github/`).
2. Tab **Actions** -> **build** laeuft automatisch.
3. `.jar` unter **Artifacts** -> `bigger-bundles-jar` herunterladen (die Datei ohne `-sources`).
4. Modrinth App -> Fabric-Profil 26.3 -> Fabric API + `.jar` in `mods`.
