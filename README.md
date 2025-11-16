SPM Grup – Portofoliu Proiecte
==============================

Prezentul repository conține codul sursă pentru pagina de portofoliu SPM Grup, realizată ca pagină statică HTML/CSS/JS și destinată prezentării unor studii de caz anonimizate și a capabilităților agenției în zona de consulting digital, web development și marketing. 

Descriere generală
------------------

Portofoliul este construit ca o pagină unică (single page) care prezintă un număr limitat de proiecte reprezentative, fiecare proiect fiind structurat cu titlu, industrie, buget estimativ, durată, tip de servicii și rezultate sintetizate. 

Scopul principal al acestei pagini este să ofere un nivel de transparență suficient pentru potențiali parteneri, fără a compromite confidențialitatea clienților și detaliile sensibile de business. 

Structura paginii
-----------------

- Header cu breadcrumb și introducere în portofoliu.  
- Secțiune de credibilitate (ani de experiență, număr de proiecte, satisfacție clienți).  
- Grid de proiecte (case studies) generat dintr-un array JavaScript.  
- Modal de captare email pentru acces la material PDF detaliat (case study complet).  
- Secțiune de call to action pentru accesarea portofoliului extins.  
- Secțiune de contact cu telefon, WhatsApp și formular de contact.  
- Footer cu informații despre SPM Grup și navigație de bază.  

Funcționalități tehnice
-----------------------

- Pagina este statică, fără backend, optimizată pentru deploy pe Vercel, GitHub Pages sau orice alt static hosting.  
- Proiectele sunt definite în JavaScript ca un array de obiecte și sunt randate dinamic în DOM printr-o funcție de render.  
- Există un mecanism de captare email (simulat) pentru butonul de „Descarcă” case study, ce poate fi ulterior conectat la un backend real sau la un serviciu de email marketing.  
- Formularul de contact afișează mesaje de status (success) și poate fi conectat ulterior la un endpoint real (API, CRM, etc.).  

Tehnologii utilizate
--------------------

- HTML5 pentru structură semantică.  
- CSS3 (fără framework) pentru layout responsive și styling, cu focus pe typografie și grilă de carduri.  
- JavaScript vanilla pentru randare dinamică a portofoliului, formulare și interacțiuni (modale, toggle, mesaje).  

Cum rulezi proiectul local
--------------------------

1. Salvează fișierul ca index.html într-un director local.  
2. Deschide fișierul în browser (dublu click sau drag-and-drop în fereastra browserului).  
3. Nu este necesar niciun build step sau server; este suficient un browser modern.  

Deploy recomandat
-----------------

Proiectul este gândit pentru a fi distribuit ca pagină statică, prin:  

- Vercel (import direct din repository sau upload manual).  
- GitHub Pages (setarea branch-ului principal ca sursă pentru site).  
- Orice alt static hosting (Netlify, Cloudflare Pages, etc.).  

Despre confidențialitate
------------------------

Studiile de caz și proiectele prezentate în acest portofoliu sunt anonimizate sau agregate, astfel încât să ilustreze tiparul de lucru, procesele și rezultatele, fără a expune date sensibile sau informații care pot identifica direct clienții finali.  

Detaliile specifice de context, buget, metrici și rezultate punctuale sunt disponibile doar în cadrul discuțiilor directe, pe bază de acord de confidențialitate și interes real de colaborare.  

Contact
-------

Pentru întrebări suplimentare, colaborări sau acces la un portofoliu extins:  

- Email: hello@spmgrup.ro  
- Telefon: +40 756 775 675  
- Website: www.spmgrup.ro  
