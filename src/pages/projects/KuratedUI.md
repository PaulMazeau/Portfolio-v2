---
layout: ../../layouts/MarkdownProjectLayout.astro
title: 'Kurated UI'
pubDate: '2024-02-21'
priority: 2
wip: true
description: "Kurated UI est une librairie de composants qui ont pour vocations d'être copier coller simplement dans vos projets. Les composants sont accessibles, personalisables et open source. "
author: 'Paul Mazeau'
image:
    url: '/images/projects/KuratedUI/KuratedUIThumbmail.webp'
    alt: 'Charte Graphique Disrupt Sound'
tags: ["Design", "Développement"]
thumbnail: "/images/projects/KuratedUI/KuratedUIThumbmail.webp"
---

Kurated UI est une librairie de composants qui ont pour vocations d'être copier coller simplement dans vos projets. Les composants sont **accessibles**, **personalisables** et **open source**. 

## La vision 

Kurated UI défend une vison peu intrusive, inclusive et durable du web. Par durable j'entend un web propre, optimisé et développer avec passion ce qui permet une longévité et ainsi une durabilité pour chaque projet utilisant kurated UI. Cela passe par une réduction des dépendances externe, un design qui transforme la complexité en simplicité tout en conservant une volonté d'innover. Ce procédé prend du temps mais, je pense, est nécessaire pour l'avenir du web.

## Comment y parvenir ?

Pour réussir à créer Kurated UI je me suis beaucoup appuyé sur le travail de [shadcn](https://shadcn.com) et de [nextUI](http://nextui.org). J'ai choisis d'utiliser des outils qui permettent une grande liberté dans la création de composant et de leur personalisation tout en gardant cette obsession pour l'inclusivité et la durabilité du web. Voici mes choix concernant les outils que je vais utiliser pour la réalisation de ce projet

<img src="/images/projects/KuratedUI/KuratedUIStack.webp" alt="Showcase Project Image" class="blog-content-image"/>

Pour faciliter l'intégration et la mise en place de kurated ui au sein d'un projet, j'ai créer un [script npx](https://www.npmjs.com/package/kurated-ui) qui permet une mise en place automatique direct depuis le CLI à travers 5 questions : 
- Do you have tailwind? › no / yes
- Where is your global CSS file? › ./src/globals.css
- Do you have a tailwind.config.js located? › no / yes 
- Do you want animated components? › no / yes
- Do you want to set up an alias for your paths? › no / yes
- Where is your tsconfig.json located? › ./tsconfig


Actuellement je suis en train de finaliser la création du design system associé à Kurated UI et de concevoir les premiers composants qui seront disponible. 
