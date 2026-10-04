MOUTOU GRAPHIC — Guide d'hébergement
====================================

CONTENU
-------
index.html   -> le site complet (HTML + CSS + JS + SVG dans un seul fichier)

Le site est 100 % statique : pas de base de données, pas de PHP,
pas de Node. Il suffit de le mettre en ligne tel quel.

DÉPENDANCE EXTERNE (seule)
--------------------------
Polices Google Fonts (Poppins, IBM Plex Mono), chargées via internet.
-> Si le visiteur est hors ligne, une police par défaut s'affichera.

HÉBERGER GRATUITEMENT (les plus simples)
----------------------------------------
1) Netlify Drop : https://app.netlify.com/drop
   Glisser-déposer le DOSSIER "moutou-graphic" -> lien en ligne immédiat.

2) Cloudflare Pages : créer un projet > "Upload assets" > déposer le dossier.

3) GitHub Pages : créer un dépôt, envoyer index.html, puis
   Settings > Pages > Branch "main" > Save.

4) Hébergement classique (cPanel / FTP) :
   envoyer index.html dans le dossier public_html/ (ou www/).
   Le fichier DOIT s'appeler index.html.

NOM DE DOMAINE
--------------
Acheter un domaine (ex. moutougraphic.com) puis le relier à l'hébergeur
(Netlify / Cloudflare / cPanel -> section "Domaines" / DNS).

CONTACT
-------
Le bouton contact ouvre le mail : mamoutoutraore981@gmail.com
(lien mailto, aucun serveur nécessaire).
