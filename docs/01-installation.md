# ⚡ INSTALLATION - YTM GODAS DEV V2

⚠️ IMPORTANT :  
Suivre les étapes dans l’ordre.

---

## 1. Lancer YouTube Music Desktop

Lancer :

```text
YouTube Music Desktop.exe
```

---

## 2. Activer l’API YouTube Music Desktop

Dans YouTube Music Desktop :

```text
Paramètres → Extensions → Serveur API
```

Mettre :

```text
Activé : Oui
Hôte : 127.0.0.1
Port : 26538
Autorisation : Désactivée / Pas d’autorisation
```

Redémarrer YouTube Music Desktop après modification.

---

## 3. Importer Streamer.bot

Ouvrir Streamer.bot puis importer :

```text
streamerbot/YTM_GODAS_V2.sb
```

---

## 4. Configurer le setup

Dans l’action setup `godasytm`, renseigner :

```text
youtubeApiKey
ytmHost
ytmPort
```

Valeurs recommandées :

```text
ytmHost = 127.0.0.1
ytmPort = 26538
```

---

## 5. Lancer le setup

Dans le chat Twitch :

```text
!godasytm
```

---

## 6. Tester

```text
!sr nom musique artiste
!song
!next
!playlist
!clear
```

---

## ✅ Installation terminée
