---
layout: ../../layouts/MarkdownProjectLayout.astro
title: 'Pigly'
pubDate: '2024-02-21'
priority: 1
wip: true
description: "Pigly, l'application qui résout le dilemme où allons-nous manger ? en 1 minute et 37 secondes, en fonction de votre humeur actuelle. Conçue pour les décisions spontanées, Pigly est votre guide ultime vers la découverte culinaire."
author: 'Paul Mazeau'
image:
    url: '/images/projects/Pigly/Pigly.webp'
    alt: 'Application Pigly'
tags: ["Tech", "Application"]
thumbnail: "/images/projects/Pigly/PiglyThumbmail.webp"
---
Pigly est une application qui vous donne un restaurant, un bar ou un club à visiter en 1 minute et 37 secondes basé sur votre mood actuel. L'application se concentre sur l'instant pour mettre fin au dilemme "où devrions-nous manger ?". Ce projet a été entièrement conçu par moi-même, et la partie business de l'application a été pensée par Mathis Laubier. Je suis actuellement en train de développer l'application, qui devrait être lancée d'ici la rentrée 2025.

## Le problème

Avec Pigly, nous nous sommes concentrés sur la complexité de trouver rapidement un restaurant qui correspond à vos envies et à votre humeur du moment.

## Solution

Une application qui vous donne un restaurant, un bar ou un club à visiter en 1 minute et 37 secondes basé sur votre humeur actuelle. L'application se concentre sur l'instant pour mettre fin au dilemme "où devrions-nous manger ?".

<img src="/images/projects/Pigly/Pigly.webp" alt="Pigly Project Image" class="blog-content-image"/>

## Mon approche pour atteindre l'interface utilisateur actuelle

### 1. Recherche et découverte

Notre première étape a été d'identifier les problèmes que les utilisateurs rencontrent lorsqu'ils cherchent un restaurant qui correspond à leur humeur ou à leurs envies du moment. Nous avons mené une série d'enquêtes et d'entretiens avec des personnes qui mangent fréquemment à l'extérieur ou utilisent des applications de recherche de restaurant. En outre, nous avons effectué une analyse concurrentielle des applications existantes dans ce domaine. Je pense que ce qui nous a le plus aidé c'est le sondage que nous avons lancé pendant que nous concevons l'application.

<img src="/images/projects/Pigly/Data.webp" alt="Pigly Project Image" class="blog-content-image-details"/>

### 2. Personas

Sur la base de notre recherche utilisateur, nous avons créé deux personas clés représentant nos utilisateurs cibles :

**1. Sasha l'étudiant(e) :**

- Occupation : Étudiant(e) au lycée ou à l'université
- Âge : 15-25 ans
- Aisance avec la technologie : Très à l'aise avec la technologie. Utilise fréquemment son smartphone pour diverses tâches.
- Objectif : Trouver rapidement des restaurants qui correspondent à ses envies spécifiques, à son budget et à ses préférences de localisation.

**2. Thomas le Jeune Professionnel :**

- Occupation : Professionnel(le) actif(ve) jeune
- Âge : 25-30 ans
- Aisance avec la technologie : À l'aise avec la technologie. Utilise principalement son smartphone pour des tâches utilitaires.
- Objectif : Localiser rapidement un restaurant capable de répondre à ses exigences diététiques, à sa localisation et à ses contraintes de temps.

### 3. UserStory & UserFlow

À partir des personas définis, nous avons développé des histoires d'utilisateurs pour illustrer leurs besoins. Nous avons ensuite défini les parcours utilisateurs basés sur ces histoires, décrivant le chemin que nos utilisateurs suivraient dans l'application pour atteindre leurs objectifs.

<img src="/images/projects/Pigly/UserFlow.webp" alt="Pigly Project Image" class="blog-content-image-details"/>

### 4. Wireframes

J'ai conçu des low-fidelity wireframe pour la disposition de base et les fonctions de l'application. Ces esquisses ont fourni une structure de base de l'application et nous ont permis de recueillir les premiers retours des utilisateurs potentiels. Notre volonté était, dès la conception, de faire de nombreux aller retours entre les users et nous pour créer l'application qui fit au mieux le besoin.

<img src="/images/projects/Pigly/LowFi.webp" alt="Pigly Project Image" class="blog-content-image-details"/>

### 5. Itération

Les commentaires issus des premiers tests utilisateurs ont été pris en compte pour affiner et améliorer la conception. Le cycle de test et d'itération s'est poursuivi jusqu'à obtenir un design satisfaisant qui répond aux besoins des utilisateurs.

<img src="/images/projects/Pigly/Iteration.webp" alt="Pigly Project Image" class="blog-content-image-details"/>

### 6. Prototypage et tests

J'ai créé des high-fidelity wireframe qui incorporaient des éléments d'interface utilisateur et des interactions réalistes basées sur nos low fi wireframe. Ces prototypes ont été utilisés pour des tests d'utilisabilité, où nous avons recueilli des retours précieux des utilisateurs pour créer la version finale du MVP de l'application.

### 7. Documentation

Dès le début, nous avons maintenu une documentation détaillée de nos découvertes de recherche, personas, parcours utilisateurs, maquettes, prototypes et retours des utilisateurs. Ce sont des ressources très précieuse qu'il ne faut pas perdre car on en aura besoin tout au long du cycle de conception et de vie de l'application.

### 8. Développement

Une fois les prototypes validés j'ai commencé le développement. J'ai choisis un stack technique que je connaisais déjà via [MyColoc](https://www.paulmazeau.com/projects/MyColoc) : react native avec expo et firebase. Vous pouvez trouver le code source de l'application juste [ici](https://github.com/PaulMazeau/Pigly).

Cette approche nous garantit que Pigly est centré sur l'utilisateur et résout un problème réel pour ses utilisateurs en fournissant un moyen rapide et pratique de trouver un restaurant qui correspond à leur humeur et à leurs préférences.


