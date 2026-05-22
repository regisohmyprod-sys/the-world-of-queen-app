# The World of Queen — Site Officiel

> Site public officiel de **The World of Queen — L'Éternelle Légende**
> Show référence en hommage à Queen, produit par [Oh My Prod](https://ohmyprod.com).

🌐 **En ligne sur** : [theworldofqueen.com](https://www.theworldofqueen.com) *(à venir)*

---

## 📦 Stack technique

- **Frontend** : HTML / CSS / JavaScript vanilla (aucun framework)
- **Backend** : [Supabase](https://supabase.com) (project `nhxqcavianozskxgfcbt`)
  - Vue publique `public_dates_twoq` (dates de tournée)
  - Vue publique `public_wall_of_fans` (photos fans validées)
  - Tables `newsletter_subscribers`, `contact_demandes`
- **Hébergement** : GitHub Pages
- **Polices** : Cinzel (titres) + Inter (texte)
- **Charte** : Noir `#0A0A0A` / Or `#D4AF37` / Crème `#F5F1E8`

## 🗂️ Structure du site

| Fichier | Description |
|---|---|
| `index.html` | Page d'accueil — splash, hero, teaser vidéo, pitch, reels, partenaires |
| `dates.html` | Toutes les dates de tournée (Supabase), recherche, filtres, billetterie |
| `artistes.html` | Fred Caramia + le groupe + les sopranos + pianistes + cascadeurs |
| `fanzone.html` | Concours, Wall of Fans, témoignages, backstage, boutique |
| `medias.html` | Reels, vidéos YouTube, galerie photos avec diaporama |
| `moi.html` | Programme de fidélité 4 niveaux (FAN/VIP/OR/PLATINE) |
| `contact-prod.html` | Formulaire contact pro (booking, presse, partenariat, production) |
| `espace-pro.html` | Espace professionnel *(à venir)* |
| `espace-presse.html` | Dossier de presse *(à venir)* |
| `boutique.html` | Boutique merch officiel *(à venir)* |

## 🔗 Écosystème TWOQ

| Repo | Usage | URL |
|---|---|---|
| **`the-world-of-queen-web`** | Site public *(ce repo)* | `theworldofqueen.com` |
| **`twoq-pwa`** | Application PWA membres | `app.theworldofqueen.com` |
| **`ohmyprod`** | Application de gestion interne OMP | `app.ohmyprod.com` |

## 🚀 Mise en production

1. Activer GitHub Pages (Settings → Pages → Source : `main` branch)
2. Ajouter un fichier `CNAME` contenant `www.theworldofqueen.com`
3. Configurer le DNS Wix (record CNAME `www` → `regisohmyprod-sys.github.io`)
4. Configurer le DNS Wix (record A `@` → IPs GitHub Pages)
5. Activer HTTPS

## 📧 Contact

- **Production** : contact@ohmyprod.com
- **Booking** : booking@ohmyprod.com
- **Presse** : presse@ohmyprod.com

---

© 2026 **SAS OH MY PROD** — Tous droits réservés.
