Fisier cu prompturi

Esti un inginer software si vreau sa imi construiesti un program html prin care sa imi organizez echipa, au detaliile in promptul ce urmeaaza.

Inginerul alege sa construiasca  aplciatii tinad cosnt de urmatoarele conditii:
- vreau sa cosntruiesti 2 echipe multidisciplinare formaete din cel putin urmatorii menbri (daca crezi ca trebuie mai multi poti sa adaugi):
  geolog, 
  analist de legislație, 
  analist de management, 
  designer de interfață, 
  arhitect și dezvoltator software,
  specialist in managementul echipelor (specialist HR)
  tester.
- ambele echipe fac un plan dezvolaat cum sa cosntuiasca totul pe baza promptului vin cu o solutie completa
- cele 2 echipe cauta in instrustia de oil and gas solutii, deasemana solutii de cum sa eficietizeis o echipa
- adica sa faca o cercetare avansate pe toate domeniile conexe 
- Un arhitect software senior cu experiență de Technical Lead de talie mondiala coordoneaza proiectul si fa final alege solutia final de implementaree
- proiectul final poate sa contina elemente din ambele proiecte nu numai unul
  

Echipa:
- Bogdan seful echipe (la nevoie - verifica fiecare proiect)
- Cami (Agnita, Deleni)
- Adriana (Cristur)
- Andrea (Filitelnic)
- Sile (Medias)
- Cristi (Danes, Roman)

Nu stiu exact cum sa arate prima pagina deacea vreau sa analizei intregul text si sa faci designul dupa ce ai toate informatiile, dar stiu ca vreau un buton "Calendar" care sa afiseze pe toata interfat bwoserului un calendar cu sarcile echipei, sa se poata selecta fiecare mebru ale ecipei, sa existe posibilitae de afisare pe an luni sapramnai chiar si zile.

Ce am:
- cateva fisiere .csv cu avize si acorduri ANRMPSG ca au temene si la unele trebuie intocmie diferite documetaii de prelungire sau conforamare
- fisier cu temene pentru anumite valori estimate si finale pentru care trebuie intocmite "Proiecte tehnice pentru valori finale"
- mai jos este detaliata structura fisierelor enumerat emai sus
- anumie date trebuie introduce manual
- fiecare mebrul al echipe meneregeraza anuminte sonde ale unor zacaminte apartinand geografic anumitoe sectii care sunt: Medias, Deleni, Filitelnic, Danes, Agnita, Cristur si Roman. Mai sus in dreptul fiecruli menbru al echipei in parenteze este trecuta sectia pentru care ei raspund (in fisierul XXXXXXXXXXXXXXXXXX.csv ai o structura fiecari sectie si care sunt zacamntele fiecari sectii.

Pe parcusrs aplicatia doresc sa se maturizes si sa fei mul mai complexa, dar in faza actuala o sa o testam si sa o folosim pentru trasnmiter la timp a documentaiiloe catre ANRMPSG.
Ce trebuie trimis:
- documetatii care trebue trimise cand situatia o cere si care nu o data stiuda prealabil, ele apra cand dupa o intervetie la sonda situati o cere (In paranteza mai ai si prescurate pentru operatia respectiva cu care o mai poti gasi in fisierele csv):
    - Documentatie pentru saparea unei sonde (SAP)
    - Documentatie pentru conservarea unie sonde (CON)
    - Documentatie pentru ridicarea conservarii  unie sonde (RCON)
    - Documentatie pentru trecerea unei sonde in exploatare experimentala (EE)
    - Documentatie pentru obtinera avizului de abandoanre (ABN)
    - Documentatie pentru ridicarea abandonarii unei sonde (RABN)
    - Informare pentru situatii exceptionale (INF)
    - Documentatie tehnico econimica pentru valoare estimata (VEST)
    - Documentatie tehnico econimica pentru valoare finala (VFIN)
    - *daca una din documentatii este omisa in lista de mai sus sa poata fi introdusa manual iar sistemul sa o memoreze pe viitor
- documentatii care au o o limita stabilita la care trebuie trimis, fata de temenul limita inter in cadrul comanie iexista si un termeni internpana la care trebuie trimis, aceste sunt:
    - Documentatie pentru prelungirea conservarii unei sonde (PCON) fata de data expiraraii trebuie trimisa cu 4 saptamani inainte
    - Documentatie pentru exploatere definitiva (ED) fata de data expiraraii trebuie trimisa cu 4 saptamani inainte, dar cu 6 saptamani inaite se solicita si "Program de cercetare" de la Serviciul TEIZ
    - Informare pentru situatii cunosculte cum sunt unele conservari pe care ANRMPSG le care  (INF)
    - Documentatie pentru 
