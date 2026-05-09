# 🎮 COMMANDES DISPONIBLES

## Setup

```text
!godasytm
```

Configure la clé API YouTube, le host et le port YouTube Music Desktop.

---

## Song Request

```text
!sr nom musique artiste
```

Ajoute une musique dans la queue locale prioritaire.

Exemples :

```text
!sr Eminem Lose Yourself
!sr Bouss Ma Vida
!sr https://music.youtube.com/watch?v=VIDEOID
```

---

## Musique actuelle

```text
!song
```

Affiche la musique actuellement détectée.

---

## Prochaine SR

```text
!next
```

Affiche la prochaine musique en attente dans la queue SR.

---

## Playlist / Queue

```text
!playlist
```

Affiche la file d’attente des SR.

---

## Clear

```text
!clear
```

Vide la queue locale des SR.

---

## Fonctionnement

```text
Viewer → !sr
↓
Ajout dans la queue locale
↓
Auto Watcher
↓
Ajout prioritaire dans YouTube Music Desktop
↓
Retour à la lecture normale quand la queue est vide
```
