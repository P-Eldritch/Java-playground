# Java-playground :boom: :boom: :boom:
*Various exercises for Algorithms and Data Structures course at Vilnius University (September 2017 - January 2018).*

## 2 Lecture
### 13

Parašykite statinį metodą masyvas(), kuris priima bet kokio ilgio sveikųjų skaičių masyvą a[], sudarytą iš atsitiktinių skaičių nuo 0 iki 9, ir grąžina masyvą b[], kurio i-tasis elementas lygus pasirodymui skaičiaus i masyve a[]. Išveskite masyvą a[] ir masyvą b[].
Pvz.:
2 4 2 5 9 5 7 4 5 8 9 2 3 4 0 6 2 4 0 2 8 4 7 1 1 3 9 6 5 3 
2 2 5 3 5 4 2 2 2 3 

### 16 exercise

Parašykite programą, kuri nuskaito įvestas eilutes, kurių kiekvieną sudaro vardas ir du sveikieji skaičiai. Po to programa turi išvesti panaudojant printf() lentelę, kurioje būtų stulpeliai: vardas, pirmas skaičius, antras skaičius ir dalybos rezultatas dalinant pirmą skaičių iš antro, suapvalintas iki trijų skaičių po kablelio.

### 18 exercise

Nupieškite su grafiniais elementais namą, saulę (su keliais spinduliais), žvaigždę.

### 19 exercise
Sukurkite failą test1.txt. Parašykite programą, kuri ištrintų skaičių dublikatus ir atsakymą išsaugotų naujame faile. 


*test1.txt
45
78
96
23
21
85
45
68
72
11
13
48
76
45
21
87
68
25
43
68*

### 20 Exercise

Patikrinkite, kaip veikia ši programa:
```
public class Fib {
    public static long F(int N) {
        if (N == 0) return 0;
        if (N == 1) return 1;
        return F(N-1) + F(N-2);
    }
    public static void main(String[] args)
    {
        for (int N = 0; N < 100; N++) {
            System.out.println(N + " " + F(N));
        }
    }

}
```
Parašykite greitesnę programą, kuri užbaigtų darbą per ~1s. 

### 21 Exercise

Sukurkite programą, kuri paprašytų vartotojo įvesti metus ir mėnesį ir kuri išvestų į ekraną to mėnesio didžiausią ir mažiausią Google akcijų kainą bei kokiom dienom tai buvo. Programa turėtų nuskaityti akcijų kainas iš (http://finance.yahoo.com) puslapyje esančio CSV failo.

## 3 Lecture

### 22 Exercise 

Parašykite programą, kuri nupieštų lange stačiakampį ir 500 atsitiktinių taškų. Taškus, kurie pakliuvo į stačiakampį nuspalvinkit raudonai, o likusius – mėlynai. 

### 23 Exercise 

Sukurkite klasę Date, kuri išvestų klaidą, jei vartotojas įvestų ne datą, pvz. 0000-19-57 ir sukurkite metodą dayOfTheWeek(), kuris išvestų kokia savaitės diena (pirmadienis, antradienis ar pan.) yra įvesta data.

### 24 Exercise 

Parašykite programą, kuri išvestų trikampį, sudarytą iš 0. Trikampio aukštis N priklauso nuo to, kokį skaičių įves vartotojas. Tarkim, jei N=6, tai: 
```
     0   
    000
   00000  
  0000000
 000000000
00000000000
```

### 25 Exercise 

Parašykite programą, kuri nuskaito vartotojo įvestus skliaustelius ir panaudoja dėklą tam, kad nuspręsti ar visi skliausteliai yra teisingai atidaryti/uždaryti. *Pvz.:
[()]{}{[()()]()} – grąžina true reikšmę.
[(]) – grąžina false reikšmę.*


### 26 Exercise 

Parašykite programą, kuri priima matematinę išraišką su trūkstamais skliaustais ir išveda teisingą išraišką su skliaustais. Pvz.:
*įvedus 1 + 2) *3-4) *5-6) ) )
programa turi išvesti ( (1 + 2) * ( (3-4) * (5-6) ) )*

### 27 Exercise 

Realizuokite deką, kurio API pateikta 3 paskaitos skaidrėse

## 4 Lecture

### 28 Exercise

Du draugai dirba kepykloje. Lina kepa riestainius, traukia iš krosnies po tris skirtingų formų ir kabina juos ant kartelės iš dešinės: pirmiausia pakabina A riestainį, tada – B, paskiau O. Linas pardavinėja riestainius. Nuo kartelės jis visada ima dešiniausią riestainį. Lina kepa riestainius greičiau, negu Linas juos parduoda.
Parašykite algoritmą, kuris paskaičiuotų, kiek mažiausiai riestainių pardavė Linas, jei kartelė
atrodo taip:
*AAABAABOA*
Paskaičiavimui naudokite dėklą. 

### 29 Exercise

Parašykite programą, kuri konvertuotų temperatūrą iš Celsijaus skalės į Farengeito skalę ir atvirkščiai. Programa galėtų atrodyti taip:

*Paspauskite 1 jeigu norite konvertuoti iš Celsijaus skalės į Farengeito skalę
Paspauskite 2 jeigu norite konvertuoti iš Farengeito skalės į Celsijaus skalę
1
Įveskite temperatūrą pagal Celsijaus skalę: 20
Temperatūra pagal Farengeito skalę: 68*

### 30 Exercise

Parašykite programą, kuri išvestų dvimačio masyvo NxN spiralę. N reikšmę įveda vartotojas. Pvz., jei N=4, tai atsakymas:
```
1   2  3  4
5   6  7  8
9  10 11 12
13 14 15 16

1 2 3 4 8 12 16 15 14 13 9 5 6 7 11 10
```
### 31 Exercise

Parašykite programą, kuri priimtu iš vartotojo kokį nors žodį ir išvestų žodį su simbolių # pagalba. Nekreipkite dėmesio į lietuviškas raides. Raidėms saugoti panaudokite masyvus. Pvz: vartotojas įveda ‘Kevin’, gauna:
```
 #    #  ######  #    #     #    #    #
 #   #   #       #    #     #    ##   #
 ####    #####   #    #     #    # #  #
 #  #    #       #    #     #    #  # #
 #   #   #        #  #      #    #   ##
 #    #  ######    ##       #    #    #

```

### 32 Exercise

Parašykite programą, kuri paprašytų vartotojo įvesti metus ir mėnesį, o programa atspausdintų to mėnesio dienas, pvz:

```
    Vasaris 2009
P   A  T  K  P  S  S
                   1
2   3  4  5  6  7  8
9  10 11 12 13 14 15
16 17 18 19 20 21 22
23 24 25 26 27 28
```

### 33 Exercise

Parašykite programą, kuri išvestų nurodyto katalogo medį su visais failais ir pakatalogiais. Kiekvienas vidinis katalogas patraukiamas į dešinę pusę per vieną poziciją. Panaudokite eilę (queue) ir java.io.File biblioteka. Pvz.:
```
|-Desktop
|--Catalog1
|---Catalog2
|---file1.txt
|---file2.txt
|----file3.txt
|----file4.txt
|--Catalog3
|---file5.txt
ir t.t.
```

### 34 Exercise

Žaidimas „šilta-šalta“. Reikia atspėti kompiuterio sugalvotą skaičių (random) iš intervalo nuo 1 iki N. Po kiekvieno spėjimo kompiuteris turi išvesti „šilčiau“ arba „šalčiau“ priklausomai nuo to, ar spėjamas skaičius palyginus su ankstesniu spėjamu skaičiumi yra arčiau ar toliau sugalvoto skaičiaus. Pvz., kai N=100, sugalvotas skaičius 83. Spėjimas 1 = 10 (neatspėjote). Spėjimas 2 = 50 (šilčiau). Spėjimas 3 = 80 (šilčiau). Spėjimas 4 = 90 (šalčiau). Spėjimas 5 = 83 (atspėjote).

### 35 Exercise

Bitoninė paieška. Masyvas vadinamas bitoniniu, jeigu jis susideda iš didėjančių skaičių, po kurių eina mažėjantys skaičiai. Parašykite programą, kuri uždavus N ilgio bitoninį masyvą nustatytų ar jame yra ieškomas skaičius ar ne. Algoritmo sudėtingumas blogiausiu atveju turi būti 3lgN. Taip pat išveskite maksimalią masyvo reikšmę. Bitoninio masyvo pvz:
3 5 7 10 11 12 23 27 26 18 15 13 9 8 6 2 1 0 -5

