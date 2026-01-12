## Version 1

* Ajout des balises meta
```
    <!-- SEO Meta Tags -->
    <meta name="description" content="Sysguard : solutions professionnelles de sécurité informatique, supervision IT et sauvegarde de données pour protéger votre infrastructure entreprise.">
    <meta name="keywords" content="sécurité informatique, infogérance, supervision IT, sauvegarde données, cybersécurité">
    <!-- Open Graph Meta Tags -->
    <meta property="og:title" content="Sysguard - Services IT">
    <meta property="og:description" content="Sysguard : solutions professionnelles de sécurité informatique, supervision IT et sauvegarde de données pour protéger votre infrastructure entreprise.">
    <meta property="og:type" content="website">
```

* Création d'un robots.txt à la racine
```
User-agent: *
Allow: /
Sitemap: https://www.sysguard.fr/sitemap.xml
```

* Création d'un sitemap.xml
```
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  
  <!-- Page d'accueil -->
  <url>
    <loc>https://www.sysguard.fr/index.html</loc>
    <lastmod>2026-01-12</lastmod>
    <changefreq>weekly</changefreq>
    <priority>1.0</priority>
  </url>
  
  <!-- Page Services -->
  <url>
    <loc>https://www.sysguard.fr/services.html</loc>
    <lastmod>2026-01-12</lastmod>
    <changefreq>weekly</changefreq>
    <priority>0.8</priority>
  </url>

</urlset>
```