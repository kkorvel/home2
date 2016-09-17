# README #

See on teise kodutöö failide hoidla, mida saab kasutada ainult algseks lugemiseks.
Töötamiseks looge endale isiklik repositoorium, näiteks (privaatne) 'fork' bitbucket serverisse, millest saate luua klooni oma arvutisse.
Ülesande kirjelduse leiate: http://enos.itcollege.ee/~jpoial/algoritmid/aa_prakt2newest.html

## Näidete kasutamine käsurealt ##
#### Kompileerimine: ####

```
#!bash

javac -cp src src/IntSorting.java
```

#### Käivitamine: ####

```
#!bash

java -cp src IntSorting
```


### Testide kasutamine ###
#### Testi kompileerimine: ####

```
#!bash

javac -encoding utf8 -cp 'src:test:test/junit-4.12.jar:test/hamcrest-core-1.3.jar' test/IntSortingTest.java

```
Sama Windows aknas (koolonite asemel peavad olema semikoolonid):

```
#!bash

javac -encoding utf8 -cp 'src;test;test/junit-4.12.jar;test/hamcrest-core-1.3.jar' test/IntSortingTest.java


```

#### Testi käivitamine: ####

```
#!bash

java -cp 'src:test:test/junit-4.12.jar:test/hamcrest-core-1.3.jar' org.junit.runner.JUnitCore IntSortingTest
```

Sama Windows aknas (koolonite asemel semikoolonid):

```
#!bash

java -cp 'src;test;test/junit-4.12.jar;test/hamcrest-core-1.3.jar' org.junit.runner.JUnitCore IntSortingTest
```
"# home2" 
