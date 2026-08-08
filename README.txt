ŠEBELA TOOL, s.r.o. — web (produkčně připravený)
=================================================

OBSAH BALÍKU
  index.html            hlavní stránka (CSS + JS uvnitř, ať se nic nerozbije při uploadu)
  404.html              chybová stránka
  headpage-web.mp4      hero video (optimalizované, 5,3 MB)
  hero-poster.jpg       poster videa (načte se první)
  og-image.jpg          náhledový obrázek pro sdílení (1200×630)
  favicon.svg           favicon
  icon-192/512.png, apple-touch-icon.png   ikony (PWA / iOS)
  site.webmanifest      PWA manifest
  robots.txt            pro vyhledávače
  sitemap.xml           mapa webu
  vercel.json           cache + bezpečnostní hlavičky (pro Vercel)
  img/                  fotky (dílna, obory, výrobky) — samostatné soubory, ne v HTML

PŘED SPUŠTĚNÍM UPRAVIT
  1) DOMÉNA: v index.html, robots.txt, sitemap.xml a site.webmanifest nahradit
     "https://www.sebela-tool.cz/" reálnou doménou.
  2) KONTAKT: ověřit telefon 582 373 843, e-mail sebela@raz-dva.cz a otevírací dobu.
  3) FOTKY: v img/ jsou nasazené fotky. Hero video lze nahradit reálným záběrem;
     ideálně doplnit i konkrétní snímky CNC obrábění / forem / nástrojů.
  4) REFERENCE: nahradit ukázkové recenze reálnými (Google/od klienta).
  5) STROJNÍ PARK / MATERIÁLY: doplnit dle skutečnosti (sekce Obory, FAQ).
  6) FORMULÁŘ: funguje přes mailto. Volitelně Formspree — návod v <script> u handleru.

NASAZENÍ (Vercel)
  A) Drag & drop: přihlas se na vercel.com → New Project → přetáhni celou složku.
  B) GitHub: nahraj složku do repozitáře a v Vercelu ho naimportuj (Framework: Other).
  Po přidání domény nezapomeň na bod 1) výše.

TESTY PO NASAZENÍ (doporučeno)
  - Google Rich Results Test (LocalBusiness + FAQ)
  - PageSpeed Insights (výkon/přístupnost)
  - Sdílení na FB/LinkedIn (kontrola OG obrázku)
