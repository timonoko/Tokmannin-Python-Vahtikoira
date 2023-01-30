# Tokmannin-Python-Vahtikoira

Nyt pitäisi olla täydellinen. Nappi on nyt vain Vahtikoira päälle/pois. ESPin oma 6 sekunnin vahtikoira
vahtii tätä vahtikoiraa. Sinisellä ledillä on erilaisia vilkutusmoodeja kertomassa mikä on
tilanne. Bootti venaa 20 sekunttia ennenkuin varsinainen koira käynnistyy, jolloin totaalinen
jumiutumistilanne voidaan korjata laitetta avaamatta WebREPLin kautta. Koko systeemin voi myös resetoida
webin kautta. Mikäli pääkone (192.168.1.11) ei pysty pingamaan tätä vahtikoiraa (192.168.1.63), se käynnistää
Wifin uudestaan. Rele pannaan päälle heti bootin alussa, jolloin Vahtikoira voi käynnistyä uudestaan
katkasematta virtaa pääkoneesta. 
