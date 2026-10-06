Fisier cu prompturi


Vreau ca aplicatia sa o facem sa normalize si logurile SP din gaura libera, dar doar la apasare unui buton

O sa iti explic un flux de lucru pe care il vreau sa il foloseste si sa crezi mai intai un artefact vizul in care sa im iarrtai toti pasii fluzlui

ce sa faci:
- 2 variabile a=10 si b=50 valori presetate dar care sa poate fi moficiate de de user la inceputul procesului
- SP_min (linia nisip) si un SP_max (linie argila) care sa serveasca ca un avelope pentru curba SP initiala

Cum calculezi:
- SP_max sa fie un SP initila pe care aplica urmatoarele formule:
    - similar cu ce face Petrel cu o optiune "Log editor" - actiune: Smoot, Shape: Box, Method: Maximimun, Filter length: varianbila "a"
    - pe noua curba rezultata mai aplici: similar cu ce face Petrel cu o optiune "Log editor" - actiune: Smoot, Shape: Box, Method: Median, Filter length: varianbila "b"
    - iar rezultatul este curba SP_max
 
- SP_min sa fie un SP initila pe care aplica urmatoarele formule:
    - similar cu ce face Petrel cu o optiune "Log editor" - actiune: Smoot, Shape: Box, Method: Manimum, Filter length: varianbila "a"
    - pe noua curba rezultata mai aplici: similar cu ce face Petrel cu o optiune "Log editor" - actiune: Smoot, Shape: Box, Method: Median, Filter length: varianbila "b"
    - iar rezultatul este curba SP_min_temp
    - SP_min_dif vreau sa fie un log cu o valoare unica pe toat lungimea cu valoare vazim optinuela din  (SP_max din care scazi SP_min_temp)
    - si SP_min sa fie SP_max din scare scazi SP_min_dif

  O date ce ai SP_min si SP_max ai avelopa, si considero procetula pt intervalul respectiv SP_min ca 0 iar SP_max ca 100 (ce este su SP_min sa treaca 0 si paote sa aiba calaore negativa dar similar si ce trece de SP_max sa poate tre ce de 100)
