## Puolustuksen syvyys, ja minkälaisista elementeistä se muodostuu


Assets, Vulnerabilities, Threats

Assets - Arvokas asia, omaisuus

• Vulnerabilities - Heikkous tai haavoittuvuus

• Threats - Vaara omaisuudelle

## Vertausket "sipuli" ja "artisokka" 

Security onion eli “turvasipuli” kuvaa perinteistä defense-in-depth-ajattelua.

Ajatus on, että suojattava kohde on keskellä, ja sen ympärillä on monta kerrosta suojausta.

[Ulkoverkko]
    ↓
[Palomuuri]
    ↓
[IDS/IPS]
    ↓
[Verkon segmentointi]
    ↓
[Pääsynhallinta]
    ↓
[Endpoint-suojaus]
    ↓
[Data / kriittinen järjestelmä]

Hyökkääjän pitää ikään kuin “kuoria sipulia” ja läpäistä useita suojauskerroksia ennen kuin hän pääsee tärkeään dataan.

Security Artichoke


Security artichoke eli “turva-artisokka” kuvaa modernimpaa ongelmaa: kaikki kerrokset eivät ole täydellisesti päällekkäin.

Artisokassa on monta “lehteä”, mutta jokainen lehti voi olla oma erillinen suojausalueensa. Hyökkääjän ei välttämättä tarvitse läpäistä kaikkia kerroksia järjestyksessä. Hän voi löytää yhden heikon reitin sisään.


1. Varastettu Microsoft 365 -tunnus
2. Kirjautuminen pilvipalveluun
3. Pääsy SharePointiin tai sähköposteihin
4. Datan varastaminen ilman että sisäverkon palomuuria koskaan läpäistään

Tässä onion-malli ei kuvaa tilannetta kovin hyvin, koska hyökkääjä ei “kuori” kaikkia kerroksia. Hän käyttää yhtä erillistä “artisokan lehteä” reittinä sisään.
