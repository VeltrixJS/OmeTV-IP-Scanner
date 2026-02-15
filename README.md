# 🔍 Ome.tv IP Scanner

Script pour détecter et géolocaliser les IPs sur [Ome.tv](https://ome.tv/) en temps réel.

> 🔗 **Repository:** [https://github.com/VeltrixJS/Ome.tv-IP-geolocation](https://github.com/VeltrixJS/OmeTV-IP-Scanner)

---

## ✨ Fonctionnalités

- 🎯 Détection automatique d'IP
- 🌍 Géolocalisation (Ville, Pays, ISP)
- 🚨 Détection VPN/Proxy
- 🗺️ Lien Google Maps
- 📺 Mode popup
- 📋 Copie d'IP en 1 clic

---

## 🚀 Installation

### Avec Tampermonkey (Recommandé)

1. **Installer [Tampermonkey](https://www.tampermonkey.net/)**

2. **Créer un nouveau script**
   - Clic sur l'icône Tampermonkey → "Créer un nouveau script"
   - Supprimer le contenu par défaut
   - Coller le code de `ometv-scanner-FINAL.js`
   - Sauvegarder (Ctrl+S)

3. **C'est tout !**
   - Aller sur [ome.tv](https://ome.tv/)
   - Le tracker apparaît automatiquement

---

## 📖 Utilisation

### Interface

```
╔═══════════════════════════════╗
║  DETECTED IP      [📺] [X]   ║
╠═══════════════════════════════╣
║  IP: 162.19.18.158           ║
║  ISP: OVH SAS                ║
║  LOC: Paris, France (75)     ║
║                               ║
║  [Copy]  [Maps]              ║
╚═══════════════════════════════╝
```

### Contrôles

- **📺** - Ouvre une popup détachable
- **X** - Minimise en icône
- **Copy** - Copie l'IP
- **Maps** - Ouvre Google Maps

---

## 🔧 APIs Utilisées

Le script utilise **ipinfo.io** (token déjà configuré, 50k req/mois gratuit) avec 4 APIs de secours :

1. ipinfo.io ⭐ (principale)
2. ip-api.com
3. ipapi.co
4. freeipapi.com
5. ipwhois.io

**Taux de succès : ~98%**

---

## 🎨 Interface

- Design vert néon moderne
- Draggable (déplaçable)
- Mode miniature
- Popup pour multi-écrans

---

## 🔒 Avertissement

⚠️ **Éducation et recherche uniquement**

- Respectez la vie privée
- Ne partagez pas les IPs
- Usage responsable uniquement

---

## 🐛 Problèmes ?

**Le tracker n'apparaît pas ?**
- Vérifiez que Tampermonkey est activé
- Rechargez la page (F5)

**"Unknown" affiché ?**
- Reconnectez-vous à une autre personne
- L'IP détectée est peut-être locale

---

## 📄 Licence

MIT License - Libre d'utilisation

---

<div align="center">

**Made with ❤️ by VeltrixJS**

⭐ [Star ce projet](https://github.com/VeltrixJS/Ome.tv-IP-geolocation) si il vous aide !

</div>
