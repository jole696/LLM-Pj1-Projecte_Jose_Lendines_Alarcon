<img width="651" height="424" alt="image" src="https://github.com/user-attachments/assets/5ee851b1-4e5e-4c4e-8f90-b498d13a2bc6" /># PROJECTE WEB: Disseny i Implementació d’una Pàgina Web Personalitzada: Tarraco Boards

# Fase 1. Definir la Marca i el Client Fictici
## 1. Justificació i objectius

El projecte sorgeix arran de la inauguració del nou skatepark de Salou, aprofitant l'oportunitat per crear un referent local en aquest esport.

- **Objectius:**
    - Digitalitzar l'oferta de la botiga i l'escola de skate.
    - Facilitar la reserva de classes i la compra de material especialitzat.
    - Crear comunitat al voltant del nou espai urbà.

## 2. Públic objectiu

- **Joves i adolescents (12-25 anys):** Usuaris actius del skatepark interessats en la cultura urbana i material tècnic.
- **Pares i famílies:** Busquen activitats extraescolars i classes guiades per als seus fills.
- **Fingerboarders:** Aficionats a aquest nínxol específic.

# Fase 2. (Fases 2, 3, 4, 5, 6, 7, 8 i 9)

## 1. Metadades i Schema.org

S'ha implementat un marcatge de dades estructurades (JSON-LD) complet per millorar la comprensió del lloc per part dels cercadors.

- **Pàgina Principal (
    
    index.html)**: Defineix l'entitat `LocalBusiness`, incloent nom, logo, descripció i adreça física.
- **Subpàgines (
    
    productes.html, 
    
    serveis.html, etc.)**: Defineixen l'entitat `WebPage` o `AboutPage` amb `BreadcrumbList` per indicar la jerarquia de navegació.

**Justificació**: Això permet que Google mostri rich snippets (fragments enriquits) amb informació del negoci local i la ruta de navegació (breadcrumbs).

## 2. SEO i Accessibilitat

- **Meta Etiquetes**: Totes les pàgines inclouen `description` i `keywords` úniques i rellevants per al contingut.
- **Open Graph (OG)**: S'han configurat etiquetes `og:title`, `og:description` i `og:image` per assegurar que el contingut es visualitzi correctament en compartir-lo a xarxes socials.
- **Semàntica HTML5**: Ús correcte d'etiquetes semàntiques (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) per millorar l'accessibilitat i l'estructura del document.
- **Atributs ARIA**: S'han utilitzat atributs com `aria-label`, `aria-expanded` i `aria-labelledby` per millorar la navegació amb lectors de pantalla.

## 3. LOPD i RGPD (Compliment Legal)

El lloc web compleix amb les normatives de protecció de dades vigents:

- **Pàgina de Privacitat**: Existeix una pàgina dedicada (
    
    politica_privacitat.html) accessible des de tot el lloc.
- **Avís de Galetes (Cookies)**: S'ha implementat un banner de consentiment que bloqueja les cookies (simulat via localStorage) fins que l'usuari les accepta explícitament.
- **Formularis**: El formulari de contacte a 
    
    sobre_nosaltres.html inclou una casella de verificació (`checkbox`) obligatòria (`required`) per acceptar la política de privacitat abans d'enviar les dades. Això garanteix el **consentiment explícit**.

## 4. Implementació CSS

- **Arquitectura**: Ús de variables CSS (`:root`) per a colors i mesures, facilitant el manteniment i la coherència visual.
- **Layout**: Ús de `Flexbox` per a l'estructura principal i `Grid` per a la disposició de targetes, assegurant la responsivitat.
- **Comentaris**: El codi CSS està documentat en castellà/català, explicant seccions clau com "Disseny Flex", "Barra de scroll", etc.

## 5. Validació del Codi

- **HTML**: L'estructura segueix l'estàndard HTML5. S'han tancat correctament les etiquetes i s'han utilitzat els atributs obligatoris com `alt` en les imatges.
- **CSS**: S'han utilitzat propietats estàndard i prefixes (`-webkit-`) on era necessari per a la compatibilitat (barra de desplaçament).
Validacion styles.css
<img width="651" height="424" alt="image" src="https://github.com/user-attachments/assets/432cd9d3-44d0-4452-a615-19382ed38e53" />
Validacion index.html
<img width="651" height="424" alt="image" src="https://github.com/user-attachments/assets/a8a7f67f-282f-4e98-918c-b34b2c1383bf" />
Validacion productes.html
<img width="651" height="424" alt="image" src="https://github.com/user-attachments/assets/a03834e2-3da2-44b3-b23e-30066499304e" />
Validacion serveis.html
<img width="651" height="424" alt="image" src="https://github.com/user-attachments/assets/4768e5fc-0438-408c-86d0-3bc059fdb63f" />
Validacion privacitat.html
<img width="651" height="424" alt="image" src="https://github.com/user-attachments/assets/e51b35aa-236e-428d-931f-5cf277c0b141" />
Validacion sobre_nosaltres.html
<img width="651" height="453" alt="image" src="https://github.com/user-attachments/assets/58965571-a8db-442e-af1e-10800d16bb3f" />

## 6. Conclusions i Reflexió

El desenvolupament d'aquest projecte ha permès integrar bones pràctiques tècniques amb requisits legals i de negoci.

- Hem après que el **SEO** no és només posar paraules clau, sinó estructurar la informació perquè les màquines la puguin entendre (Schema.org).
- La **Privacitat (RGPD)** s'ha de dissenyar des del principi (Privacy by Design), assegurant que cap dada es recull sense consentiment.
- L'ús de **CSS modern** (sense frameworks pesats) permet crear interfícies netes, ràpides i totalment personalitzades amb menys codi.

## Fase 3: Presentació i Vídeo Final
