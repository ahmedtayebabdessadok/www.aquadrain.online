AQUADRAIN — PACK GITHUB + VERCEL

Fichiers à mettre à la RACINE du dépôt GitHub :
- index.html
- package.json
- vercel.json
- CNAME

Sur Vercel :
- Framework Preset : Other
- Build Command : npm run build
- Output Directory : public
- Install Command : npm install
- Root Directory : vide

Ensuite : Redeploy.

Le formulaire reste configuré en 2 étapes :
Préparer ma demande -> Vérifier/Modifier -> Envoyer ma demande.

IMPORTANT DNS :
Si Vercel est l'hébergeur final de www.aquadrain.online, le DNS du domaine doit pointer vers Vercel,
pas vers GitHub Pages. Le fichier CNAME dans ce pack est uniquement utile côté GitHub Pages et peut
être supprimé si vous utilisez exclusivement Vercel.
