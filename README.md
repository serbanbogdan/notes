Vreau sa imi construiesti un program html prin care sa imi organizez echipa, au detaliile in promptul ce urmeaaza.

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
- Bogdan seful echipe (la nevoie - verifica fiecare proiect) [0505]
- Cami (Agnita, Deleni) [2222]
- Adriana (Cristur) [3333]
- Andrea (Filitelnic) [1111]
- Sile (Medias) [4444]
- Cristi (Danes, Roman) [5555]

Nu stiu exact cum sa arate prima pagina deacea vreau sa analizei intregul text si sa faci designul dupa ce ai toate informatiile, dar stiu ca vreau un buton "Calendar" care sa afiseze pe toata interfat bwoserului un calendar cu sarcile echipei, sa se poata selecta fiecare mebru ale ecipei, sa existe posibilitae de afisare pe an luni sapramnai chiar si zile.
Vreau ca la inceput cand deschizi pagina sa ai optiunea sa telogezi alegi userl sunt toate disponibile doar ca daca vrei sa intri terbuie sa introduci si o parola (este notata pentru fiecare user mai sus in paranteze [],) in setati useer poate sa isi schimbe parola din setari. o data ales user browserul menoreza si nu mai ce logar pana la o eventuala delogara a userului. 

Ce am:
- o sa-ti livrez un fisier cu toate sectiile si zacamnitele aferente feicaruia
- date care acopera in mare parte ultimii 2 ani
- cateva fisiere .csv cu avize si acorduri ANRMPSG ca au temene si la unele trebuie intocmie diferite documetaii de prelungire sau conforamare
- fisier cu temene pentru anumite valori estimate si finale pentru care trebuie intocmite "Proiecte tehnice pentru valori finale"
- mai jos este detaliata structura fisierelor enumerat emai sus
- anumie date trebuie introduce manual
- fiecare mebrul al echipe meneregeraza anuminte sonde ale unor zacaminte apartinand geografic anumitoe sectii care sunt: Medias, Deleni, Filitelnic, Danes, Agnita, Cristur si Roman. Mai sus in dreptul fiecruli menbru al echipei in parenteze este trecuta sectia pentru care ei raspund (in fisierul sectie-zacamant.csv ai o structura fiecari sectie si care sunt zacamntele fiecari sectii.
- mai ai un fisier numit: tarife.csv in care ai in fisier ( în conformitate cu prevederile Ordinului A.N.R.M.P.S.G. nr.410)
    - numele sondei, tipul avizului, dacata la carea valoareafa initiala a a fost trimisa catre Serviul Peimtre, daca la care s-a primit aviz sau aocrd (poate sa nu fie daca nu s-a primit), Valaorea estiamta, vaaloarea finala, diferenta dintre acesta, timpul ramas in zile (aici vreau sa calcuelazi 180 zile de la data intrgistrari al serviucl Perimetre), regularizareala valoara finala (doar da e cazul) diferatan intre regalrizare si valoare afianal, si observatii


Ce vreau:
- ca pentru fiecare mbru al echipee meblul sau seflul echipe sa poata trasa termine si sa ii pune tasker cu termen pe care sa le poata respecta
- vreau ca fiecare mebur sa aiba si o rublica ca face a facut saptaman curenta, incluziv seful echipe, acest raport sa fie cumulta pe echip saptamantal, iar seful ecipei sa poarta edita la final raportil, acest raport sa aiba o parte fixa si una fleximabila (la cea felximbial introduce ce a facut extra fat de partea fixa, parte afixa are urmatorul contunut (in rapostul catre sef daca unul lipseste nu pui 0 nu afiseszi total campul:
      - Proiecte ANRMPSG:
      - Date program:
      - Comenzi emise:
      - Studii in lucru:
- pentru tarife ANRMPSG cele din fisierul tarife.csv
  - vreau sa fie pusi intro foram usor de vazu si sa poata fi edita si acualziata acest fisier care sa fie staocat si intro forma .csv si in folserul in care se gaseste fisierul html al progarmului
  - automatat responsabilul de sonda din distrimutia pe colegi sa apara in calendar penttu termenul de 180 de la Data inregistrare(serviciul perimetre) dar si cu o luna iante sa expire cel 180 zile cu mentiu de solicitate cost filan si trimitere doc/
  - costul se cere de la Servicul TEIZ pentru exploatare expermitntala si de restul de la Servoicul Reactivare sonde.

Nu vreau sa oferi inforamtii sensibile despre colegi!




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
 
cand se trece aizuld primit pt sondele convertite in injecti sa fie notificat seful si user aferetne sondei sa trimite si Notificare de "casare partiala" catre serviciul Mecano Energetic
