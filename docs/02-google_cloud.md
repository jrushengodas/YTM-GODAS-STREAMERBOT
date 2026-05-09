# 🔑 GOOGLE CLOUD - CONFIGURATION V2

La V2 utilise uniquement une **clé API YouTube**.

```text
❌ Plus besoin de Client ID
❌ Plus besoin de Client Secret
❌ Plus besoin de Playlist ID
❌ Plus besoin d’OAuth Google
```

---

## 1. Aller sur Google Cloud

```text
https://console.cloud.google.com/
```

---

## 2. Créer un projet

Créer un nouveau projet Google Cloud.

---

## 3. Activer YouTube Data API v3

Aller dans :

```text
API et services → Bibliothèque
```

Rechercher :

```text
YouTube Data API v3
```

Puis cliquer sur :

```text
Activer
```

---

## 4. Créer une clé API

Aller dans :

```text
API et services → Identifiants
```

Cliquer sur :

```text
Créer des identifiants → Clé API
```

Copier la clé API.

---

## 5. Utilisation dans Streamer.bot

Dans le setup `!godasytm`, coller la clé dans :

```text
youtubeApiKey
```

Le script la sauvegardera automatiquement dans :

```text
youtubeApiKey_godas
```

---

## ✅ Configuration terminée
