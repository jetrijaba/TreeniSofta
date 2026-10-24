# Treenipäiväkirja (PWA)

Tiedostot: `index.html`, `manifest.webmanifest`, `sw.js`, `icons/`.

## Julkaisu GitHub Pagesissa
1. Luo GitHubissa uusi repositorio (esim. `treeni`).
2. Lataa kaikki tämän kansion tiedostot repositorion juureen (`icons`-kansio mukaan lukien).
3. Repositorio → **Settings → Pages** → Source: *Deploy from a branch*, Branch: `main`, kansio `/ (root)` → Save.
4. Odota minuutti, sovellus on osoitteessa `https://KÄYTTÄJÄNIMI.github.io/treeni/`.

## Asennus puhelimeen
- **Android / Chrome:** valikko ⋮ → *Asenna sovellus* (tai *Lisää aloitusnäyttöön*).
- **iPhone / Safari:** Jaa-painike → *Lisää Koti-valikkoon*.

## Päivittäminen
Kun muutat tiedostoja, vaihda `sw.js`-tiedoston alussa oleva `VERSION` (esim. `PREFIX + 'v3'`).
Uusi versio latautuu taustalla ja tulee käyttöön, kun sovelluksen sulkee ja avaa uudelleen.

## Huomioita
- Tiedot tallentuvat laitteen selaimeen (localStorage). Tee silloin tällöin varmuuskopio
  Liikkeet-välilehden *Vie tiedostoon* -napilla.
- Iphonella asennettu sovellus ja Safari-selain ovat eri tallennustiloja: aloita kirjaaminen vasta asennuksen jälkeen
  tai tuo varmuuskopio asennettuun sovellukseen.
