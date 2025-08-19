
# Vérification d'intégrité (SHA‑256)

Pour vérifier une archive téléchargée :

## Windows (PowerShell)
```powershell
Get-FileHash .\AmosProfessionalUnity-*.zip -Algorithm SHA256
```

## macOS / Linux
```bash
shasum -a 256 AmosProfessionalUnity-*.zip
# ou
sha256sum AmosProfessionalUnity-*.zip
```

Comparez la valeur avec la somme publiée dans la *Release* (ou dans `CHECKSUMS.txt` si fourni).
