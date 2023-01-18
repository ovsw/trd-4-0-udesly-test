---
title: Workflow pentru randarea în arhitectură și design de interior
f_seo-description: >-
  Mulți întreabă:care ar fi un workflow corect? Adică, în ce ordine se fac
  lucrurile. Modelare > Materiale și Texturi > Iluminare > Camere > Randare? Ar
  putea fi
f_excerpt-short-description-of-the-blog-post-content: >-
  Mulți întreabă care ar fi un workflow corect? Adică, în ce ordine se fac
  lucrurile. Modelare > Materiale și Texturi > Iluminare > Camere > Randare? Ar
  putea fi o variantă (sau nu). Haideți să vedem mai jos cum ar trebui să arate
  un workflow pentru randarea în arhitectură și design interior.
f_post-main-image:
  url: >-
    https://uploads-ssl.webflow.com/63b7a4842ba2a509b08261eb/63b7a561aae073d7a8b2f2b9_63999a2ca35a2b5f9d8413a9_cover.jpeg
  alt: null
f_1st-sharable-social-image-from-post:
  url: >-
    https://uploads-ssl.webflow.com/63b7a4842ba2a509b08261eb/63b7a561aae0737cb4b2f2b8_63999a2ca35a2b0fda84139f_photo-1554919700-69c4bb11dde5.jpeg
  alt: null
slug: workflow-pentru-randarea-in-arhitectura-si-design-de-interior
updated-on: '2023-01-07T03:26:19.916Z'
created-on: '2023-01-06T04:36:50.026Z'
published-on: '2023-01-07T04:42:47.017Z'
f_author: cms/echipa/alex-mesesan.md
f_post-date: '2021-07-23T00:00:00.000Z'
f_catgegory: Ghid
layout: '[blog].html'
tags: blog
---

Ce înseamnă wofkflow?
---------------------

Nu știu pe voi la ce vă duce cu gândul termenul ăsta dar, din experiența mea, cei mai mulți se gândesc la un proces liniar, care începe de la punctul A, trece prin B, face un popas la C și se termină la D:

![](https://uploads-ssl.webflow.com/63b7a4842ba2a509b08261eb/63b7a561aae07332f0b2f2be_63999a2ca35a2bfc3f8413a8_workflow-liniar.jpeg)

Simplu, clar și… din păcate, greșit pentru situația noastră. 😅

### De ce nu funcționează un workflow liniar pentru randările 3D?

Pentru că pașii din componența lui depind unii de alții în moduri care ajung în cele din urmă să îl facă orice, doar liniar nu.

Dacă punem în practică modelul de mai sus pentru randarea în 3ds Max, obținem ceva de genul:

![](https://uploads-ssl.webflow.com/63b7a4842ba2a509b08261eb/63b7a561aae073951bb2f2bc_63999a2ca35a2b43798413a5_workflow-liniar-in-3ds-max.jpeg)

![](https://uploads-ssl.webflow.com/63b7a4842ba2a509b08261eb/63b7a561aae0736c21b2f2bd_63999a2ca35a2b847784133a_what.gif)

Soluția: un workflow ciclic, iterativ
-------------------------------------

O abordare iterativă e mult mai potrivită pentru randările 3D: parcurgem toate fazele din workflow, dar nu o singură dată ci de “n” ori, aducând mici îmbunătățiri de fiecare dată, până când ajungem la rezultatul dorit.

![](https://uploads-ssl.webflow.com/63b7a4842ba2a509b08261eb/63b7a561aae073e291b2f2ba_63999a2ca35a2b687a841361_workflow-ciclic-iterativ.jpeg)

> Un **workflow iterativ** e mai degrabă un **proces continuu** de îmbunătățire care depinde mult de cât timp ai la dispoziție și ce încerci sa faci - randare statică sau animație.

De unde începem?
----------------

Un workflow iterativ are două mari faze:

1.  ‍**Schițarea grosieră (iterația nr. 1)**, în care punem bazele fiecărei componente din proiect (modelare, texturare etc.) cu **minimul necesar**, fără sa intrăm în detalii pe care după aceea să trebuiască să le ștergem
2.  ‍**Îmbunătățirile (iterațiile de la 2 la… cât timp și răbdare avem) în care re-vizităm, pe rând, fiecare componentă, și aducem îmbunătățiri fiecăreia.**

Iterația 1
----------

### 1.Modelarea inițială și încadrarea compoziției

Modelul pe care vrei să îl creezi există sau trebuie să îl creezi tu?

*   Dacă nu există, trebuie să îl construim - O schiță în linii mari a modelului e mai mult decât suficientă deocamdată, n-are rost să ne complicăm viața cu detalii în acest stagiu.
*   Dacă există - super, îl importăm și trecem la pasul următor.

Acum că avem modelul schițat în linii mari, e un moment bun să încadrăm compoziția.

> Chiar dacă încă nu avem materiale și lumini, e bine să știm de la bun început ce urmează să randăm, ca să putem să ne concentrăm pe zonele acestea.

Poate vor exista zone din model care nu se văd niciodată, așa că nu are rost să pierdem timpul cu ele.

Aici avem iarăși două opțiuni:

1.  fie vom folosi mai multe camere pentru a genera imagini statice;
2.  sau vom realiza traseul camerei pentru animație. 

În acest moment știm destul de clar ce urmează să randăm și avem modelul construit în linii mari.

### 2\. Materiale și texturi

Urmează să realizam materiale și ne vom concentra atenția pe materialele care ocupă cea mai mare parte din imaginile finale. 

Nu vom intra foarte în detaliu cu materialele și texturile, ci doar vrem să știm ce materiale vor fi folosite pe modelul nostru. 

### 3\. Lumini

După ce am realizat materialele în linii mari vom face același lucru și cu luminile, din nou fără a încerca să le calibrăm prea mult.

### 4\. Randare inițială

Buuun. Avem modelul, materialele, texturile, luminile și camerele setate foarte grosier.

E timpul să setăm motorul de randare la rezoluția finală de randare (o calitate medie acum e suficientă) și să dăm click pe “render”.   

Iterațiile 2, 3, 4… etc.
------------------------

### Îmbunătățiri graduale

Vom analiza în detaliu tot ce am făcut până acum și vom face **o listă cu toate îmbunătățirile** care se pot aduce.

**Revenim la fișierul nostru și continuăm să adăugăm detalii pe model, să îmbunătățim materialele și texturile, luminile, camerele, setările motorului de randare.**

### Clătim din abundență și repetăm...

...în funcție de timpul pe care îl avem la dispoziție. La **fiecare iterație nouă vom crește gradual calitatea tuturor proceselor în paralel**. 

Încercăm pe cât posibil să acordăm tuturor etapelor cam același timp, iar la sfârșit salvăm rezultatul și facem o nouă listă cu îmbunătățiri.

Pentru fanii filmului “Inception“ și amatorii de “meta”, subliniem aici că **modul de funcționare al unui proces iterativ este el însuși un proces iterativ**. Nu credeți? Aruncați o privire mai jos:  

  

![](https://uploads-ssl.webflow.com/63b7a4842ba2a509b08261eb/63b7a561aae0739bb4b2f2bb_63999a2ca35a2bf00d8413a3_workflow-iterativ-meta.jpeg)

V-am convins? 😏  

De ce e bun acest mod de lucru
------------------------------

Un workflow iterativ aduce avantaje greu de ignorat. Câteva exemple:  

*   Chiar dacă am setat corect materialele și luminile s-ar putea ca acestea să nu arate chiar așa de bine din unghiul din care se uită camera. **E mai important ca lucrurile să pară corecte decât să fie corecte**.
*   Același lucru și cu modelul: s-ar putea ca unele dintre modelele pe care le prindeți în compoziție **să arate distorsionat din cauza unghiului camerei** sau a poziției camerei. Ar fi o idee bună să distorsionăm aceste obiecte astfel încât să arate corect.
*   Luminile vor produce **zone speculare** care s-ar putea să nu ne fie favorabile, dar partea bună e că **am observat asta de la prima randare** și voi avea timp să modific.

Concluzia
---------

> _Modul de lucru iterativ ne dă posibilitatea să realizăm compoziții bune pentru că punem accent de la bun început pe compoziție și_ **_evităm să punem efort în ceea ce nu se va vedea niciodată_**_._

_‍_Dacă mă pun să fac etapele pe rând, liniar: 

*   încep cu modelarea și o finalizez;
*   continui cu materiale și texturi - le finalizez;
*   pe urmă lumini, iar și mai pe urmă camere...

**...voi avea o surpriză neplăcută la sfârșit:** chiar dacă am făcut toate etapele corect, am petrecut deja foarte mult timp cu fiecare dintre ele și nu voi avea timp să mă concentrez pe ceea ce chiar contează: rezultatul final.

  

  

---
