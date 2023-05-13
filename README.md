# IoT-projeti
app.py on ohjelma joka käyttää Flaskia ja Flask-SocketIO:ta luodakseen web-palvelimen. Ohjelma vastaanottaa POST-pyyntöjä '/uusimittaus'-osoitteeseen. 
Kun uusi mittaus vastaanotetaan, se tallennetaan measurements-taulukkoon. 
Mittaustiedot muutetaan sopivaan muotoon, ja taulukko lähetetään takaisin käyttöliittymään Socket.IO:n avulla (semmoiseen muotoon laitetaan että googlecharts osaa lukea sen).
Kun käyttäjä avaa charts.html-sivun, se piirtää kaaviota tallennetuista mittauksista.

***"https://github.com/rikuqt/lammotv4" repositoryn readme sisältää datageneraattorin tiedot***'

**Tekijät:** Joona Säntti, Riku Tomann
