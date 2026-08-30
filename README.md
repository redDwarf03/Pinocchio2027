# 🤥 Pinocchio2027

> Un outil open-source de fact-checking des débats politiques, à l'approche de la présidentielle 2027.

---

## Le problème

Entre les deepfakes, les éléments de langage et les médias qui privilégient le buzz aux vraies infos, il est devenu difficile de distinguer le vrai du faux dans le discours politique. L'IA est souvent utilisée pour amplifier la désinformation — **Pinocchio2027 propose de l'utiliser pour faire exactement l'inverse**.

---

## L'idée

Un pipeline automatisé, sans biais éditorial, basé uniquement sur de la data froide :

1. **Ingestion** — L'agent aspire les matinales et débats de la veille (transcriptions, sous-titres, articles).
2. **Extraction** — Il isole les affirmations factuelles vérifiables.
3. **Vérification** — Il les croise avec des sources officielles : INSEE, Cour des Comptes, data.gouv.fr, etc.
4. **Dashboard** — Il met à jour un tableau de bord mesurant l'allongement du nez de chaque candidat 📏.
5. **Diffusion** — Il génère des Shorts/Reels sourcés et percutants pour rétablir les faits et les rendre aussi viraux que la désinformation.

---

## Stack envisagée

| Brique | Technologie |
|---|---|
| Ingestion | Python + RSS / scraping |
| Extraction & vérification | LLM (ex. GPT-4o, Mistral) |
| Sources de référence | INSEE, Cour des Comptes, data.gouv.fr |
| Dashboard | JSON → site statique (GitHub Pages) |
| Génération de contenu | LLM + synthèse vidéo/image |

---

## Comment contribuer

Ce projet est communautaire. Voici les briques sur lesquelles on a besoin de monde :

- 🔍 **Ingestion** — scraping de transcriptions, parsing de sous-titres
- 🧠 **Extraction NLP** — isoler les affirmations factuelles d'un discours
- 📊 **Data** — connexion aux APIs officielles (INSEE, etc.)
- 🖥️ **Frontend** — dashboard de visualisation des scores
- 🎬 **Contenu** — génération de Shorts/Reels sourcés
- 🧪 **Tests & qualité** — s'assurer que le pipeline est fiable

Ouvre une issue ou une PR, ou rejoins la discussion !

---

## Objectif

Rendre la vérité factuelle **aussi virale que la désinformation**.

Ce projet n'a aucun but commercial. Il est fait par des citoyens, pour des citoyens.

---

## Licence

[MIT](LICENSE)
