# 🌐 Web Projects

Collection de **10 sites vitrines responsive** réalisés en HTML, CSS et JavaScript pur — sans framework, sans dépendance externe.

Chaque site simule un cas client réel avec une attention particulière portée au design, à l'UX et à la **sécurité applicative** (prévention XSS, injections SQL, CSRF).

---

## 📁 Projets

| # | Site | Secteur | Fonctionnalités clés |
|---|------|---------|----------------------|
| 01 | **L'Ardoise** | Restaurant gastronomique | Menu interactif, formulaire de réservation, galerie |
| 02 | **Mora Architectes** | Cabinet d'architecture | Portfolio projets, curseur custom, animations scroll |
| 03 | **Léa Dumont** | Photographe | Galerie masonry, filtres, grille de tarifs |
| 04 | **APEX Coaching** | Coach sportif | Programme en étapes, plans tarifaires, CTA |
| 05 | **Leclerc & Associés** | Cabinet d'avocats | Site institutionnel, formulaire contact, équipe |
| 06 | **CISO Hair Studio** | Salon de coiffure | Réservation en ligne, galerie, prestations & prix |
| 07 | **Élite Immobilier** | Agence immobilière | Listings, filtres de recherche, stats dynamiques |
| 08 | **Garage Torino** | Garage automobile | Formulaire devis, services, marques acceptées |
| 09 | **Lumina Studio** | Yoga & bien-être | Planning interactif, abonnements, cours en ligne |
| 10 | **Saveurs d'Exception** | Traiteur événementiel | Galerie luxe, formulaire événement, prestations |

---

## ⚙️ Technologies

- **HTML5** — structure sémantique, accessibilité
- **CSS3** — Flexbox, Grid, animations, variables CSS, media queries
- **JavaScript vanilla** — DOM, événements, interactions, filtres
- **Google Fonts** — typographies premium (Playfair, Syne, Cormorant...)
- **Aucun framework** — code 100% natif, zéro dépendance

---

## 🔐 Sécurité applicative

En tant qu'étudiant en cybersécurité, chaque site intègre des bonnes pratiques de sécurité front-end :

- Validation des formulaires côté client
- Pas d'injection de HTML brut (`innerHTML` limité)
- Headers de sécurité documentés (CSP, X-Frame-Options...)
- Sensibilisation aux vulnérabilités OWASP Top 10 dans la conception

---

## 📱 Responsive Design

Tous les sites sont testés et adaptés sur :

| Breakpoint | Taille |
|---|---|
| 📱 Mobile | < 480px |
| 📟 Tablette | 480px — 768px |
| 💻 Desktop | > 768px |

---

## 🚀 Lancer un site en local

```bash
# Cloner le repo
git clone https://github.com/Noejimgre/web-projects.git
cd web-projects

# Ouvrir n'importe quel site directement dans le navigateur
open 01-restaurant/index.html

# Ou lancer un serveur local (recommandé)
python3 -m http.server 8080
# puis aller sur http://localhost:8080/01-restaurant/
```

---

## 📌 À venir

- [ ] Versions dark mode pour chaque site
- [ ] Intégration d'une API météo (site tourisme)
- [ ] Version React d'un des sites vitrines
- [ ] Tests de sécurité avec Burp Suite sur les formulaires

---

## 👤 Auteur

**Noé Jimenez-Greverent**
Étudiant BTS CIEL | Développement Web & Cybersécurité

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/noe-jimenez-greverent)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/Noejimgre)
