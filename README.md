# List of software produced for/by Greenpeace

List of software produced specifically for Greenpeace. This repository list includes public and private repositories in Github and other platforms. Please check the repository's license before you use it.

- [List of software produced for/by Greenpeace](#list-of-software-produced-forby-greenpeace)
  - [Wordpress](#wordpress)
    - [Plugins](#plugins)
    - [Themes](#themes)
  - [Sites](#sites)
    - [Large websites](#large-websites)
    - [Microsites](#microsites)
    - [Other web scripts](#other-web-scripts)
    - [Web analytics](#web-analytics)
  - [Microservices](#microservices)
  - [Data visualization](#data-visualization)
    - [Guides, dev and testing tools](#guides-dev-and-testing-tools)
    - [Specific web pieces](#specific-web-pieces)
  - [Processing data](#processing-data)
    - [Command line data processing](#command-line-data-processing)
    - [SQL recipes](#sql-recipes)
    - [Other data related](#other-data-related)
  - [E-learning](#e-learning)
  - [Other](#other)

## Wordpress

### Plugins

Plugins produced to be used either by Planet 4 or/and other Wordpress sites.

- **[gpes-add-to-cal-wp-shortcode](https://github.com/greenpeace/gpes-add-to-cal-wp-shortcode)** - Shortcode to create links that add an event to the user's calendar. Works with iCalendar, Android, Outlook, Gmail, Yahoo and others. Used in es.greenpeace.org and [hazgreenpeace.org](https://hazgreenpeace.org/ourense/personaliza-una-bolsa-reutiliza-tu-bolsa/)
- **[gpes-infographics-wp-shortcode](https://github.com/greenpeace/gpes-infographics-wp-shortcode)** - Shortcode to add responsive SVG infographics. Used in [es.greenpeace.org](https://es.greenpeace.org/es/trabajamos-en/cambio-climatico/pagos-por-capacidad/) and others.
- **[gpes-import-wp-shortcodes](https://github.com/greenpeace/gpes-import-wp-shortcodes)** - Shortcodes to import frontend code into Wordpress. Upload html, css, svg and Javascript files to the media library and insert them in your site. Used in es.greenpeace.org and others.
- **[gpes-socialmedia-buttons-wp-shortcodes](https://github.com/greenpeace/gpes-socialmedia-buttons-wp-shortcodes)** - Wordpress shortcode that creates 3 click to share buttons. Used in [es.greenpeace.org](https://es.greenpeace.org/es/noticias/elecciones28a/).

### Themes

Standalone or child themes with indic. about parent theme.

- **[gpes-magazine](https://github.com/greenpeace/gpes-magazine)** <sup>private</sup> - Wordpress theme for [GPM](https://revista.greenpeace.es/gpm-29/) the new Spanish online magazine.
- **[gpes-haz-wp-theme](https://github.com/greenpeace/gpes-haz-wp-theme)** <sup>private</sup> - Theme for [HAZ microsite](https://hazgreenpeace.org/).
- **[gpes-fabricador](https://bitbucket.org/greenpeace/gpes-fabricador/src/master/)** <sup>private</sup> - Theme to build [Greenpeace's emails](https://correos-dev.greenpeace.es/?p=8693). It adds UTM urls, Google Analytics tracking. It's templates are used both by Engaging Networks (Engagement emails) and Augure (media emails).

## Sites

### Large websites

- **[gp-es](https://bitbucket.org/greenpeace/gp-es/)** <sup>private</sup> - Git mirror of theme, plugins and translations for [es.greenpeace.org](https://bitbucket.org/greenpeace/gp-es/)

### Microsites

- **[gpes-pescadodetemporada](https://bitbucket.org/greenpeace/pescadodetemporada/)** - Source code for [pescadodetemporada.org](https://pescadodetemporada.org/) , a seasonal fish consumer guide.
- **[gpes-ninos-politicos](https://bitbucket.org/greenpeace/ninos-politicos/)** - Source code for [quepoliticoeres.org](https://quepoliticoeres.org/). Analysis of the political parties programs.
- **[gpes-riesgo-incendios](https://bitbucket.org/doersdf/riesgo-incendios/)** <sup>private</sup> - Source code for [riesgodeincendios.org](https://riesgodeincendios.org/), a self diagnosis tool about the risk of forest fires near rural houses.
- **[gpes-melepeconelartico](https://bitbucket.org/greenpeace/melepeconelartico/)** <sup>private, offline</sup> - Source code for [melepeconelartico.org](https://melepeconelartico.org/). An Artcic petition launched by two Youtube celebrities.
- **[gpes-villanos](https://bitbucket.org/greenpeace/villanos/)** <sup>private</sup> - Source code for [villanos.greenpeace.es](https://villanos.greenpeace.es/). Vote for the worse climate vilan and sign a climate petition.
- **[gpes-memoria-de-pez](http://tratamientomemoriadepez.greenpeace.es/)** <sup>private</sup> - Source code for [tratamientomemoriadepez](http://tratamientomemoriadepez.greenpeace.es/), about how politicians forget their promises.

### Other web scripts

- **[gpes-forms-styles-scripts](https://bitbucket.org/greenpeace/gpes-forms-styles-scripts/)** <sup>private</sup> - CSS and JavaScript for Greenpeace's Spain forms (petition, donation and regular giving). Works together with [gp-es](https://bitbucket.org/greenpeace/gp-es/).
- **[gpes-hyperremarketing](https://bitbucket.org/greenpeace/hyperremarketing2)** <sup>private</sup> - Dynamic remarketing and customised content for the Spanish site. Works together with [gp-es](https://bitbucket.org/greenpeace/gp-es/).

### Web analytics

- **[gpes-url-builder-int](https://bitbucket.org/greenpeace/url-builder-int)** - Old translation of gpes current tool to create utm-tagged URLs.
- **[gpes-emailtrack](https://bitbucket.org/greenpeace/emailtrack)** - A class to generate Google Analytics tracking pixels for html email and "view email in the browser" pages.

## Microservices

- **[gpes-old-en-petitions-api-emulator](https://github.com/greenpeace/gpes-old-en-petitions-api-emulator)** - Emulates the deprecated Engaging Networks petition's API. Useful if you have legacy micro-sites with petitions.
- **[gpes-engaging-networks-token](https://github.com/greenpeace/gpes-engaging-networks-token)** - Simple API to get cached tokens that can be used in Engaging Networks petitions when the page is hosted outside EN.

## Data visualization

### Guides, dev and testing tools

- **[gpes-visualisations](https://github.com/greenpeace/gpes-visualisations)** - Proposal for tools and style guide for the visualisations in the Spanish office sites. Used often to produce charts, maps, infographics and other pieces. The **[guide](https://greenpeace.github.io/gpes-visualisations/)** includes near 60 examples and advocates for visualizations that can be shared, translated and adapted by anyone.
- **[gpes-test-visualisations](https://github.com/greenpeace/gpes-test-visualisations)** - **[Tool](https://greenpeace.github.io/gpes-test-visualisations/)** to help developing, testing and translating multilingual responsive interactive media, infographics and graphics that work in many different sites.

### Specific web pieces

- **[gpes-supermarket-ranking](https://github.com/greenpeace/gpes-supermarket-ranking)** - Responsive table with the Spanish office [supermarket ranking](https://es.greenpeace.org/es/trabajamos-en/consumismo/plasticos/ranking-de-supermercados-contra-el-plastico/).
- **[gpes-budget-gov-analisis](https://github.com/greenpeace/gpes-budget-gov-analisis)** - Many charts for the Spain's [budget analisis 2019](https://es.greenpeace.org/es/trabajamos-en/democracia-y-contrapoder/analisis-medioambiental-de-los-presupuestos-generales-2019/).
- **[gpes-yemen-counters](https://github.com/greenpeace/gpes-yemen-counters)** - Counters for the [Yemen War](https://es.greenpeace.org/es/noticias/cuatro-anos-de-verguenza-y-de-horror-en-yemen/). This counter was used in Greenpeace, Oxfam and Amnesty websites.
- **[gpes-weapons-export-spain](https://github.com/greenpeace/gpes-weapons-export-spain)** - Map with [weapons exports](https://es.greenpeace.org/es/trabajamos-en/desarme/armas-marca-espana/) made by Spain between 2014 and 2016.
- **[gpes-wells-map](https://github.com/greenpeace/gpes-wells-map)** - Responsive maps about [illegal wells](https://es.greenpeace.org/es/trabajamos-en/agricultura/pozos-ilegales/).
- **[gpes-mapa-renovales](https://github.com/greenpeace/gpes-mapa-renovales)** <sup>private</sup> - Renewables map that was translated in 3 more languages in Github by the translators. [This project](https://es.greenpeace.org/es/trabajamos-en/cambio-climatico/energias-renovables/alternativas-energeticas/) is going to be redesigned.
- **[gpes-missinformation-published-whatsapp](https://github.com/greenpeace/gpes-missinformation-published-whatsapp)** - Real missinformation messages published in Whatsapp and presented in a simulated WhatsApp interface.

## Processing data

### Command line data processing

- **[gpes-check-my-pages](https://github.com/greenpeace/gpes-check-my-pages)** - Scrapping script used to test the Spanish web archive and redirects system, with more than 10,000 pages. It checks redirections, http responses, analytics, files hosted in soon-to-die servers, canonical urls and more. This script was produced for our migration from Planet 3 to Wordpress.
- **[gpes-ecounter](https://github.com/greenpeace/gpes-ecounter)** - Count unique email addresses, urls, sha256 hashes or Spanish ID numbers in one or multiple files. Works with csv, html and other formats. It also quickly hashes (encrypts) email addresses as sha256 strings that can be uploaded to Adwords and Facebook Ads as audiences.
- **[gpes-ekomp](https://github.com/greenpeace/gpes-ekomp)** - Compares emails or Spanish ID numbers in a text file with an encrypted list. Useful to check a list of emails against an encrypted blacklist. It creates two files with the results: `was-found.txt` and `was-not-found.txt`
- **[gpes-ecompare](https://github.com/greenpeace/gpes-ecompare)** - Compare two files (text, csv, html...) to check which emails, urls or sha256 hashes are in common and are missing in each file. This script is used to debug and to make simple segmenting operations.
- **[gpes-eclean](https://github.com/greenpeace/gpes-eclean)** - Identifies records you should delete or fix on your EN database. It was developed to quickly identify useless/problematic records in your entire EN database.

### SQL recipes

- **[gpes-sql-recipes](https://github.com/greenpeace/gpes-sql-recipes)** - List of MySQL snippets to analyse or fix our database.
- **[gpes-bigquery-recipes](https://github.com/greenpeace/gpes-bigquery-recipes)** - Google Big Query recipes to Analyse our data. Similar to gpes-bigquery-recipes, but uses Google BigQuery instead of MySQL.

### Other data related

- **[gpes-tlmk-validator](https://bitbucket.org/greenpeace/tlmk-validator/)** <sup>private</sup> - CSV validator tool used by telemarketing agencies to validate their calls data before sending it to us. It prevents errors in Salesforce.

## E-learning

- **[gpes-html5-scorm-presentation](https://github.com/greenpeace/gpes-html5-scorm-presentation)** - Create a [GP presentation](ttps://greenpeace.github.io/gpes-html5-scorm-presentation/) using html5. Use it independently or upload it as an elearning SCORM package in Moodle or any other SCORM-compatible LMS.
- **[gpes-activism-school-elearning-template](https://github.com/greenpeace/gpes-activism-school-elearning-template)** - School of Activism e-learning template/example.

## Other

- **[gpes-archive-translations](https://github.com/greenpeace/gpes-archive-translations)** - Translations for [Greenpeace's archive](https://archivo-historico.greenpeace.es/).
- **[gpes-html-document-editor](https://github.com/greenpeace/gpes-html-document-editor)** <sup>private</sup> - Customised html editor based in Tinymce. We have used to produce some campaign documents for the [2018 budget](https://es.greenpeace.org/es/trabajamos-en/democracia-y-contrapoder/presupuestos-generales-2018/).
