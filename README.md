# Octobre Rose Niger

Site web de sensibilisation au cancer du sein, pensé pour le Niger : comprendre la maladie, savoir s'autopalper, connaître les événements d'Octobre Rose et se faire dépister.

## Fonctionnalités

- Page unique animée (ruban qui se dessine, pétales, apparition au défilement)
- Sections : l'essentiel, comprendre, signes et autopalpation (démonstration animée), que faire, mythes et réalités, hommes et familles, campagnes (galerie d'affiches), calendrier des événements, où se dépister, témoignages
- Langues : français et haoussa
- Audio : lecture à voix haute en français ; emplacements prêts pour des enregistrements haoussa
- Chatbot d'information générale, sans IA externe, qui ne pose jamais de diagnostic
- Mode sombre automatique, adapté au mobile

## Structure

Le site tient dans un seul fichier, `index.html` (CSS, JavaScript et images intégrés). Il suffit de l'ouvrir dans un navigateur.

## Publier avec GitHub Pages

1. Dépôt GitHub > Settings > Pages
2. Source : branche `main`, dossier `/ (root)`
3. Le site sera disponible à l'adresse `https://<votre-compte>.github.io/<nom-du-dépôt>/`

## À faire avant diffusion publique

- [ ] Faire valider les textes médicaux par un médecin ou une structure de santé
- [ ] Faire relire la traduction haoussa par un locuteur natif
- [ ] Ajouter des enregistrements audio haoussa (objet `AUD.ha` dans le JavaScript : clés `ess`, `palp`, `agir`)
- [ ] Remplir le tableau « Où se dépister » avec des structures et numéros vérifiés
- [ ] Vérifier les dates et contacts des événements auprès des organisateurs
- [ ] Obtenir l'autorisation d'utiliser les affiches et photos (logos UNICEF, cliniques, hôtels, sponsors)
- [ ] Ajouter de vrais témoignages, uniquement avec l'accord écrit des personnes

## Droits d'image

Les affiches et photos appartiennent à leurs organisateurs et auteurs. Elles sont présentées ici à titre d'information et ne sont couvertes par aucune licence de ce dépôt.

## Informations médicales

Ce site donne des informations générales de sensibilisation. Il ne remplace pas l'avis d'un professionnel de santé.
