# Fitxa tècnica: Instal·lació i configuració bàsica de Git

## Objectiu
Instal·lar Git al nostre ordinador i configurar correctament el nom d'usuari i correu electrònic per poder interactuar amb GitHub.

## Materials
- Ordinador amb Windows/Linux/macOS
- Connexió a internet
- Visual Studio Code

## Procediment
1. Descarregar i instal·lar Git per a Windows des de la pàgina oficial.
2. Obrir la terminal integrada de Visual Studio Code.
3. Configurar les dades d'usuari globalment amb les comandes de configuració.

```bash
git config --global user.name "Alex"
git config --global user.email "ukfinds99@gmail.com"
## Comprovacions
- [ ] Git està instal·lat correctament (`git --version`)
- [ ] El nom d'usuari i correu estan guardats (`git config --list`)