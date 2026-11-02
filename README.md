# Atlas — carnet de voyage

Application de bureau (Linux) et Android pour préparer, vivre et garder ses voyages : itinéraires, agenda, carte mentale, réservations, valise & météo, pass de parcs, souvenirs et **livres photo par voyage**.

## Téléchargement

Les binaires sont dans l'onglet **Releases** de ce dépôt :

| Fichier | Plateforme | Installation |
| --- | --- | --- |
| `Atlas-1.0.0-x86_64.AppImage` | Linux x86_64 | `chmod +x` puis lancer le fichier |
| `Atlas-1.0.0.apk` | Android | autoriser l'installation hors Play Store, puis ouvrir le fichier |
| `SHA256SUMS.txt` | — | empreintes de vérification |

```bash
sha256sum -c SHA256SUMS.txt
```

## Vie privée

Vos voyages, photos et réservations restent sur l'appareil (stockage local / IndexedDB). Aucun compte n'est nécessaire et rien n'est envoyé à un serveur, hormis les recherches de lieux (OpenStreetMap), la météo (Open-Meteo) et l'IA si vous la configurez.

## Notes

- Android : l'application embarque la même interface ; les photos ne sont pas synchronisées entre le PC et le téléphone.
- L'AppImage n'est pas signée : au premier lancement, autorisez l'exécution si votre distribution le demande.
