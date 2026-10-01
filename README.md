# GitHub Copilot

Operació NortTec: projecte per desplegar, protegir i monitorar la infraestructura d'una empresa mitjançant tecnologies actuals d'administració de sistemes.

## Treball amb GitHub

### Passos per pujar un canvi

1. Consulta l'estat dels fitxers amb `git status`.
2. Prepara els canvis amb `git add .` (o indica els fitxers concrets).
3. Crea un commit descriptiu amb `git commit -m "Descriu el canvi"`.
4. Puja el commit a GitHub amb `git push`.
5. Comprova a GitHub que el canvi s'ha publicat correctament.

### Tasques

- [x] Instal·lar Visual Studio Code i Git.
- [x] Crear el repositori del projecte.
- [ ] Dissenyar l'arquitectura.
- [ ] Desplegar i documentar la infraestructura.

**Recorda:** revisa els canvis abans de fer el commit. Una descripció *clara i breu* facilita entendre l'historial.

### Comandes d'avui

Enllaç de referència: [documentació oficial de Git](https://git-scm.com/docs).

```bash
git status
git add .
git commit -m "Actualitza la documentació"
git push
```

### Comandes Git

| Comanda | Què fa |
| --- | --- |
| `git status` | Mostra els fitxers modificats i l'estat de l'arbre de treball. |
| `git add <fitxer>` | Prepara un fitxer per incloure'l al pròxim commit. |
| `git commit -m "missatge"` | Desa els canvis preparats amb un missatge. |
| `git push` | Envia els commits locals al repositori remot. |
| `git pull` | Descarrega i integra els canvis del repositori remot. |
| `git log --oneline` | Mostra l'historial de commits en format resumit. |

## Incidències

**Exemple d'incidència d'avui:** en intentar pujar el primer commit, `git push` pot indicar que la branca local no té una branca remota associada. Això passa perquè Git encara no sap a quina branca del repositori remot ha d'enviar els canvis. Es resol associant-les amb `git push -u origin main`; a partir d'aleshores, `git push` ja funciona sense indicar la branca.