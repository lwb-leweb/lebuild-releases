# Live-Editor – Releases

Update-Kanal der Kunden-Installationen. Wird ausschließlich vom Release-Workflow des Quell-Repos beschrieben, nicht von Hand.

- `latest.json` – aktuelle Version, Release-Notes, ZIP-URL und Ed25519-Signatur
- `releases/vX.Y.Z.zip` – Installationspaket; auch für Neuinstallationen geeignet

Der Updater installiert ein ZIP nur, wenn die Signatur zum öffentlichen Schlüssel in `core/updater.php` passt.
