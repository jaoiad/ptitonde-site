# ptitonde-site

Site officiel du média **Ptitonde**, destiné à `ptitonde.com` : une page d’accueil et les trois pages légales exigées par les revues d’applications TikTok et Meta et par le droit français.

HTML et CSS uniquement : aucun framework, aucune dépendance, aucun script, aucun cookie, aucune ressource chargée depuis un service tiers.

## Pages

| Adresse | Fichier |
|---|---|
| `/` | `index.html` |
| `/mentions-legales` | `mentions-legales.html` |
| `/privacy` | `privacy.html` |
| `/terms` | `terms.html` |

Cloudflare Pages sert chaque fichier `.html` à son adresse sans extension (`privacy.html` → `/privacy`). Les liens internes, les balises canoniques et `sitemap.xml` utilisent ces adresses. Un serveur local sans cette réécriture doit être interrogé avec l’extension.

## Déploiement

Réalisé par le propriétaire sur Cloudflare Pages, branché sur ce dépôt : aucune commande de build, répertoire de sortie à la racine.

Pour que la mention « ce site ne dépose aucun cookie » reste vraie, ne pas activer sur ce domaine Cloudflare Web Analytics (qui injecte un script), Bot Fight Mode ni les défis de sécurité (qui peuvent déposer des cookies).

## Charte

- Bleu nuit `#082549`, orange `#FA5D3E`, crème `#FDF9EE`, relevés sur l’avatar.
- L’orange n’est jamais une couleur de texte sur le crème (contraste 2,98:1) ; il sert de fond, sous du texte bleu nuit (4,89:1), ou de couleur du mot-symbole.
- Police Nunito variable (SIL Open Font License 1.1, voir `assets/fonts/OFL.txt`), sous-ensemble latin, version Fontsource 5.3.0, auto-hébergée.

## Images

Déclinaisons de l’avatar source `avatar_ptitonde.png` (1254 px) : disque détouré, palette réduite à 64 couleurs. `og-ptitonde.png` (1200 × 630) sert d’image Open Graph. L’original porte un manifeste C2PA (génération par un modèle d’image d’OpenAI) que les déclinaisons web ne reprennent pas.

## À confirmer avant la mise en ligne

- Comptes TikTok, YouTube, X et Facebook : affichés « bientôt », sans lien, jusqu’à confirmation des identifiants.
- Compte Instagram `ptit_onde` : lien actif, à confirmer (la fiche de lancement de media-os indique le handle `ptitonde`).
- Numéros de téléphone de l’éditeur et de l’hébergeur, mentionnés par l’article 6 III de la LCEN, absents des mentions légales.
- Politique de confidentialité : l’usage des API y couvre la publication et la consultation des statistiques de nos propres comptes ; retirer la consultation si l’application ne la pratique pas.
