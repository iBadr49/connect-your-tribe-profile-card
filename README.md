> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Visitekaartje Met Api
<!-- Geef je project een titel en schrijf in één zin wat het is -->
<img width="100%" alt="Scherm­afbeelding 2023-03-07 om 19 28 39" src="https://user-images.githubusercontent.com/112857932/223527748-d96e3a06-7eba-4cf9-8c53-5e779a7ffc4d.png">

## 📚 Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->

- Ik heb een eerder gemaakte visitekaartje die ik in week 1 heb gemaakt opnieuw ontworpen en gebouwd. Ik heb deze opdracht voor het eerst met Node gewerkt en het visitekaartje met een REST API en JSON herontworpen, gebouwd en gepubliceerd via "cyclic", ik heb mijn visitekaartje simpel gehouden de bedoeling was om data uit de Api uithalen. 

- 🌐 > https://good-jade-perch-gown.cyclic.app

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->
- Hieronder ``` EJS ``` code die ik gebruikte om mijn data uit de Api kon halen:

```ejs
        <div id="gradient"></div>
  <div id="card">
    <!-- Hier haal ik mijn Avatar uit de Api -->
  <img src= "<%= member.avatar %>" alt="avatar van <%= member.name %>" />
  
  <div class="text">
    <!-- Hier haal ik mijn prefix & mijn naam uit de Api -->
  <h2> <%= member.prefix %>. <%= member.name %> </h2> 
  <!-- Hier haal ik mijn Bio uit -->
  <p> <%- member.bio.html %> </p>
  </div>

```

## Bronnen
- 'Justus' Workshop
-  https://github.com/iBadr49/your-tribe-profile-card (VK uit sprint 1)


## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
