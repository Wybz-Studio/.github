# Checklist UX
Excellent réflexe. Voici des **sections supplémentaires à intégrer à ta checklist de livrable web**, centrées sur le **copywriting**, la **clarté des messages**, et l'**expérience utilisateur complète (parcours client, onboarding, conversions, etc.)**.

---

## ✍️ Copywriting et ton de marque

> *Vérifier que les textes sont impactants, clairs et cohérents avec l’identité du projet.*

* [ ] Les **titres captent l’attention** (ex. : bénéfice client clair, promesse forte)
* [ ] Les **CTA (Call-to-Action)** sont clairs, visibles et incitent à l’action
* [ ] Les paragraphes sont **courts, sans fautes et clairs** et contiennent des mots clés pour le SEO (1§ / idée)
* [ ] Les titres ont une **hiérarchie logique (H1 > H2 > H3)** bien structurée
* [ ] Les bénéfices clients sont **clairement exprimés** (pas seulement des features)
* [ ] Le **ton** est cohérent avec la cible (sérieux, fun, décalé, professionnel…)

---

## 👣 Parcours client (UX flow)

> *S’assurer que l’expérience utilisateur est fluide, logique et engageante.*

* [ ] L'**onboarding est fluide** (explication simple ou guided tour si nécessaire)
* [ ] Les **étapes complexes sont simplifiées** (ex. : inscriptions, filtres, formulaires…)
* [ ] Un utilisateur comprend **directement** ce que propose le site
* [ ] Présence de **preuves sociales** (témoignages, logos clients, avis, chiffres clés…)
* [ ] Le **parcours mobile** est aussi fluide que desktop
* [ ] Des CTA bien placés tout au long du parcours (pas uniquement en bas)

---

## 💸 Conversion & marketing

> *Optimiser pour l’action : vente, inscription, contact…*

* [ ] Présence d’un **lead magnet**, tunnel d’inscription ou capture email (si besoin)
* [ ] CTA présent sur toutes les pages stratégiques
* [ ] **Landing pages optimisées** pour le SEO et la conversion
* [ ] Les formulaires sont courts, efficaces, et rassurants
* [ ] Présence de **mécanismes de réassurance** :
  * [ ] Labels de confiance, sécurité, retours faciles, support client, etc.
* [ ] Les actions principales sont **accessibles en 1 à 2 clics max**

# Checklist technique

### 🔧 **Fonctionnalités & Comportements**

* [ ] Toutes les fonctionnalités listées dans le cahier des charges sont présentes et testées
* [ ] Aucune action utilisateur ne mène à une erreur non gérée (404, 500, etc.)
* [ ] Aucune console error / warning dans le navigateur
* [ ] La navigation fonctionne (liens internes, back, redirections...)
* [ ] Les erreurs sont affichées proprement à l'utilisateur
* [ ] Les messages de succès / confirmation sont visibles et clairs

---

### 🎨 **Design & Responsiveness**

* [ ] Design responsive, sur toutes les plateformes
* [ ] Utilisation cohérente des composants (boutons, inputs, cards…)

---

### 🖱️ **Accessibilité (a11y)**

* [ ] Balises **sémantiques** HTML correctement utilisées (`<header>`, `<nav>`, etc.)
* [ ] Contrastes conformes (test via [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/))
* [ ] Le site est navigable entièrement au clavier
* [ ] Les images ont tous un **attribut `alt` significatif**
* [ ] Tous les boutons et liens ont un `aria-label` ou un texte visible
* [ ] Utilisation raisonnable des animations (pas de clignotements, pas too much)
* [ ] Le site obtient une bonne note sur [EcoIndex](https://www.ecoindex.fr/)

---

### 🚀 **Performance et éco-responsabilité**

* [ ] Score Lighthouse > 90 sur **Mobile et Desktop** (Performance, a11y, Best practices, SEO)
* [ ] Images optimisées (WebP/SVG, tailles adaptées, lazy-loading)
* [ ] CSS / JS minifiés en prod
* [ ] Aucun appel réseau inutile ou redondant
* [ ] Temps de chargement inférieur à 2s en 4G simulée

---

### 🛡️ **Sécurité**

* [ ] Pas de données sensibles dans le front (clés API, tokens…)
* [ ] Les entrées utilisateurs sont correctement échappées / filtrées (XSS)
* [ ] Les appels API sont protégés par auth/token si nécessaire

---

### 📦 **Code & Structure**

* [ ] Code commenté si nécessaire, clair, sans console.log résiduels
* [ ] Fichiers inutilisés supprimés (CSS morts, images jamais appelées, etc.)
* [ ] Convention de nommage respectée (CamelCase, kebab-case, etc.)

---

### 🧪 **Tests**

* [ ] Tests manuels faits sur tous les parcours utilisateurs
* [ ] Pages d'erreurs testées : 404, 500, accès refusé

---

### 📈 **SEO & Analytics (si site public)**

* [ ] Titres de pages (`<title>`) et méta-descriptions personnalisés
* [ ] Balises `meta` sociales (OG, Twitter cards) présentes
* [ ] Sitemap.xml généré
* [ ] robots.txt présent et correct

---

### 🧾 **Documentation / Passation**

* [ ] Documentation technique de l'API le cas échéant
