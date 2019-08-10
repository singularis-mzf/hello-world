# ASCII

␣ 32 ␣ (zvýrazněná mezera) ␣

! 33 !33! 33 !

" 34 "34" 34 "

\# 35 #35# 35 #

$ 36 $36$ 36 $

% 37 %37% 37 %

&amp; 38 &amp;38&amp; 38 &amp;

' 39 '39' 39 '

( 40 (40( 40 (

) 41 )41) 41 )

\* 42 \*42\* 42 \*

\+ 43 +43+ 43 +

, 44 ,44, 44 ,

\- 45 -45- 45 -

. 46 .46. 46 .

/ 47 /47/ 47 /

\: 58 :58: 58 :

; 59 ;59; 59 ;

&lt; 60 &lt;60&lt; 60 &lt;

= 61 =61= 61 =

&gt; 62 &gt;62&gt; 62 &gt;

? 63 ?63? 63 ?

@ 64 @64@ 64 @

[ 91 [91[ 91 [

\\ 92 \\92\\ 92 \\

] 93 ]93] 93 ]

\^ 94 \^94\^ 94 \^

\_ 95 \_95\_ 95 \_

\` 96 \`96\` 96 \`

{ 123 {123{ 123 {

\| 124 \|124\| 124 \|

} 125 }125} 125 }

~ 126 \~126~ 126 ~

\[test]\(http:⫽neni.odkaz.cz)

# Shrnutí
* Znaky &lt;, &amp; a &gt; vždy nahraďte odpovídajícími entitami *&amp;lt;*, *&amp;amp;* a *&amp;gt;*.
* Znaky \\, \`, \*, \_, \^ a \~ vždy escapujte zpětným lomítkem.
* Znaky #, +, - a : escapujte vložením do zpětných apostrofů jen před prvním alfanumerickým znakem řádku.
* Znak ] escapujte zpětným lomítkem, pokud za ním následuje otevírací kulatá závorka '('.
* Potřebujete-li zapsat URL adresu, která nemá být formátována jako odkaz, nahraďte // v adrese speciálním znakem ⫽.

## Markdown
* ~~přeškrtnutý text~~
* \# Nadpis 1
* \## Nadpis 2
* \### Nadpis 3
* \###### Nadpis 6
* [odkaz](http://www.adresa.cz)
* X
> * Odsazená *položka*.
>> * Dvojitě odsazená *položka*.
* A neosazená položka.

### Číslované položky
1. Číslovaná položka.
1. Další číslovaná položka.


### Horizontální čára
***

### Odsazený kód
    Odsazení 0 (vyžaduje 4 mezery).
    Odsazení 0 (vyžaduje 4 mezery).
     Odsazení 1 (5 mezer).
          Odsazení 6 (Test zalamování: Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum.)
    Odsazený kód nelze zalomit, ale do budoucna se s touto možností počítá.
    Problém: odsazený kód nemůže obsahovat formátování!

### Tabulka

| foo | bar |
| --- | --- |
| baz | bim |

# Testy

*# Uložit image do souboru*<br>
**docker save** [**-o** {*soubor*}] {*image*}

*# Uložit image do souboru*<br>
**docker save** [**-o** {*soubor*}] {*image*}
