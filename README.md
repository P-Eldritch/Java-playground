#Java-playground :boom: :boom: :boom:#
*Various exercises for Algorithms and Data Structures course at Vilnius University (September 2017 - January 2018).*

##2 Lecture## 
#####13#####

Parašykite statinį metodą masyvas(), kuris priima bet kokio ilgio sveikųjų skaičių masyvą a[], sudarytą iš atsitiktinių skaičių nuo 0 iki 9, ir grąžina masyvą b[], kurio i-tasis elementas lygus pasirodymui skaičiaus i masyve a[]. Išveskite masyvą a[] ir masyvą b[].
Pvz.:
2 4 2 5 9 5 7 4 5 8 9 2 3 4 0 6 2 4 0 2 8 4 7 1 1 3 9 6 5 3 
2 2 5 3 5 4 2 2 2 3 

#####16 exercise#####

Parašykite programą, kuri nuskaito įvestas eilutes, kurių kiekvieną sudaro vardas ir du sveikieji skaičiai. Po to programa turi išvesti panaudojant printf() lentelę, kurioje būtų stulpeliai: vardas, pirmas skaičius, antras skaičius ir dalybos rezultatas dalinant pirmą skaičių iš antro, suapvalintas iki trijų skaičių po kablelio.

#####18 exercise#####

Nupieškite su grafiniais elementais namą, saulę (su keliais spinduliais), žvaigždę.

#####19 exercise#####
Sukurkite failą test1.txt. Parašykite programą, kuri ištrintų skaičių dublikatus ir atsakymą išsaugotų naujame faile. 

test1.txt
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
68

#####20 Exercise#####

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

