**Tehtävä sarja 2**

Tehtävä 1 ja 2

https://react-f665nzux.stackblitz.io

![alt text](image.png)

Katsoin Reactin dokumentoinnin etusivulta esimerkkejä ja niiden mukaisesti tein koodin. Huomasin vasta toisen tehtävän kohdalla, että ensimmäisestä tehtävästä tuli hieman laajempi ja se kattoi toisenkin tehtävän tavoitteet jos ymmärsin oikein.

Tehtävä 3

https://react-wzyuncd4.stackblitz.io

![alt text](image-1.png)

Katsoin Reactin dokumentoinnista esimerkkejä, mutta en täysin ymmärtänyt ja kysyin Grokilta lisätietoja.

Ymmärsin asian niin, että controlled on parempi reaaliaikaisiin tehtäviin ja uncontrolled sellaisiin, joissa voi olla pieni viive. Koodissa käytetyn controlledin vuoksi Reactin tilanhallinta reagoi jokaiseen painallukseen input-kentässä eli jos lomake on suuri se voi hieman hidastua. Uncontrolledissa DOM hallitsee tilaa ja React lukee vain tarvittaessa arvot eli se on nopeampi koska on vähemmän renderöintiä.

Tehtävä 4

https://vitejsvitejgj2cpwb-kqdj--5173--cf284e50.local-credentialless.webcontainer.io

![alt text](image-2.png)

Luin Reactin dokumentaatiosta useEffectin teoriaosuuden ja esimerkit. Sen jälkeen vielä kysyin Grokilta lisätietoja ja kertomaan yksinkertaisemmin asiasta.

- useEffect hookia käytetään yleensä kun jotain halutaan tehdä renderöinnin jälkeen kuten hakea dataa netistä, tallentaa jotain selaimeen tai käynnistää ajastin. 

- React 19 tekee joistakin useEffectin tapauksista automaattisia eli useEffectiä ei niissä tapauksissa tarvitse käyttää.

- useEffect { ... } sisälle se mitä tehdään kun tila muuttuu, se voi olla console.log tai mitä vaan muuta. Sen jälkeen otetaan [riippuvuudet] sulkujen sisälle kaikki riippuvuudet, eli jos jotain muuttuu tässä kohtaa niin efekti suoritetaan uudelleen

- kun komponentti poistuu suoritetaan siivous, eli jos esimerkiksi katkaistaan yhteys lisätään return, jonka sisällä suoritetaan yhteyden katkaisu:

return () => {
    socket.close();   
  };

Tehtävä 5

Tehtävä 6

Tehtävä 7