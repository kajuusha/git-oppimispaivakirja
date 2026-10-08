# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Erityisesti etärepositorion, paikallisen repositorion ja eri haarojen välinen ero vaati harjoittelua. Myös git fetch -komennon ja sen tarkoituksen ymmärtäminen oli aluksi haastavaa. Helpointa oli muutosten tekeminen ja commitien tekeminen, kun Gitin perustoiminnot olivat jo tuttuja.

Oli hyödyllistä kokeilla muutoksia sekä komentorivillä että GitHubin käyttöliittymässä. Opin paremmin, mitä push, fetch ja merge tekevät ja miten paikalliset ja etärepositorion haarat liittyvät toisiinsa.

Jos jokin asia ei toiminut, tarkistin ensin git status -komennolla repositorion tilanteen.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| kirjoita tähän komento | tähän lyhyt kuvaus, mitä komento tekee |
| kirjoita tähän komento | tähän lyhyt kuvaus, mitä komento tekee |
| Komento | Kuvaus |
|---|---|
| git remote -v | näyttää repositorion etärepositoriot ja niiden osoitteet |
| git remote add origin URL | lisää uuden etärepositorion nimellä origin |
| git push | lähettää paikalliset commitit etärepositorioon |
| git push -u origin master | lähettää master -haaran GitHubiin ja yhdistää sen etähaaraan|
| git push -u origin new-feat | lähettää uuden haaran GitHubiin |
| git fetch | hakee etärepositorion muutokset yhdistämättä niitä automaattisesti. |
| git switch origin/new-feat | siirtyy tarkastelemaan etärepositorion haaraa |
| git merge origin/new-feat | yhdistää etähaaran muutokset paikalliseen haaraan |
| git pull | hakee etärepositorion muutokset ja yhdistää ne paikalliseen haaraan |

