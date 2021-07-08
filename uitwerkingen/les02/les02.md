![Hanze](../../hanze/hanze.png)

[Terug naar de hoofdpagina uitwerkingen](../uitwerkingen.md)

# Uitwerkingen les 1

---

### Opgave 1

$a_B = 0,2$  
$C_s = 100\ ppm$  
$A_s = 18,4 - 0,2 = 18,2$  
$A_m = 12,7 - 0,2 = 12,5$  
$C_m =\ ?$  
  
$C_m=\frac{A_m}{A_s}\cdot C_s$  
  
$C_m=\frac{12,5}{18,2}\cdot100\ =\ 68,7\ ppm$  
  
---

### Opgave 2
Uit de tekst blijkt:
- Lithium wordt gemeten bij 671 nm
- Natrium wordt gemeten bij 589 nm
- Lithium wordt gebruikt als interne standaard
  
dus:  
$A_{IS,\ std} = 46,7$  
$A_{comp,\ std} = 35,5$  
$A_{IS,\ monster} = 21,3$  
$A_{comp,\ monster} = 54.5$  
$C_{std} = 5\ ppm$  
$C_{monster} =\ ?$  

$C_{monster}= \frac{\frac{A_{comp,\ monster}}{A_{IS,\ monster}}}{\frac{A_{comp,\ std}}{A_{IS,\ std}}}\cdot C_{std}$  

dus:  

$C_{monster}= \frac{A_{comp,\ monster}}{A_{IS,\ monster}}\cdot \frac{A_{IS,\ std}}{A_{comp,\ std}}\cdot C_{std}$  

Dus:
$C_{monster}=\frac{54,5}{21,3}\cdot\frac{46,7}{35,5}\cdot5\ =\ 16,8\ ppm$  

---

### Opgave 3

Zie [Excel File](./files/les2_uitwerkingen.xlsx) voor deel a, b en c.  

d.  
$100\ ppm = 100\ mg/kg = 100\ mg/l$  
Nodig: 250 ml = 0,25 l dus 25 mg  
e.
25 mg < 50 mg dus er is een pre-stock nodig.  

---

### Opgave 4

2 ml urine verdund met water tot 100 ml.  
25 ml monsteroplossing gemeten. A = 0,428  
Daarna aan 25 ml monster 1 ml met 0,05 mg fosfaat toegevoegd. A = 0,517  

Concentratie fosfaat = ?  
Standaard additie met verschillende volumina. Monster is immers 25 ml. Na toevoegen van de standaard 26 ml.  

Opstellen variabelen lijst:  
$C_x =\ ?$  
$C_s = 0,05\ mg/ml$  
$V_s = 1\ ml$  
$V_x = 25\ ml$  
$R_x = 0,428$  
$R_t = 0,517$  

$c_x=c_s\cdot\left(\frac{F_s\cdot R_x}{R_t+R_x\cdot\left(F_s-1\right)}\right)$  

En:  

$F_s=\frac{V_s}{V_s+V_x}$  

Substitutie van $F_s$ geeft:  

$c_x=c_s\cdot\left(\frac{\frac{V_s}{V_s+V_x}\cdot R_x}{R_t+R_x\cdot\left(\frac{V_s}{V_s+V_x}-1\right)}\right)$  

Dus:  
$c_x=0,05\cdot\left(\frac{\frac{1}{1+25}\cdot0,428}{0,517\ +\ 0,428\cdot\left(\frac{1}{1+25}-1\right)}\right)=\ 0,0078\ mg/ml$  


Let op: monster was verdund:  
2 ml naar 100 ml is 50 maal verdund.  
Dus eindantwoord: $0,39\ mg/ml$.  

---

### Opgave 5

Zie de [Excel File](./files/les2_uitwerkingen.xlsx)  

---

### Opgave 6

$y = 0,0854x + 0,1478$  
Stel y op 0:  
$0 = 0,0854x + 0,1478$  
$-0,0854x = 0,1478$  
$x = \frac{0,1478}{-0,0854} = -1,7306792$  
nu nog met -1 vermenigvuldigen:  
$x = 1,7306792\ ml$ equivalent van de standaard  
Komt dus overeen met:  

Methode A: absoluut  
$1,7306792\ ml * 100,6\ ug/ml = 174,106\ \mu g$  
In 25 ml van het monster zit dus $174,106\ \mu g$ mangaan  
Dit komt uit 200 ml totaal dus:  
$174,106 * 8 = 1392,848\  \mu g\ in\ 200\ ml$  

Deze hoeveelheid zat ook in $2\ ml$ dus:  
$1392,848\ \mu g$ in $2\ ml$ oplosmiddel  
In oplossing van $100\ ml$ zit daarom:  
$1392,848\ \mu g * 50 = 69642,4\ \mu g$  
dus:  
$\frac{69,6424\ mg}{100\ ml} = 696,424\ mg/l$  
De $25\ g$ steen is compleet opgelost in $100\ ml$  
dus:  
$69,6424\ mg/100\ ml$ dus $69,6424\ mg/25\ gram steen$  
De steen bevat daarom $0,06964\ g$ ofwel $69,64\ mg$ mangaan.  


Methode B:  
Met concentraties uitrekenen:  
monster komt overeen met $174,106\ \mu g/50\ ml$  
Dit is $3,48212\ \mu g/ml$  
Verdunning:  
$2\ ml$ naar $200\ ml$ -> 100x  
$25\ ml$ naar $50\ ml$ -> 2x  
Totaal: 200x  
Dus concentratie in oplosmiddel is 200 maal hoger:  
$3,48212\ \mu g/ml * 200 = 696,424\ \mu g/ml$  
Er is 100 ml oplosmiddel dus $69642,4\ \mu g$ in 100 ml  
In 100 ml is de volledige steen opgelost.  
De steen bevat $69642,4\ \mu g$ ofwel $69,64\ mg$ mangaan.  

---

### Opgave 7

100% methode  

| Stof          | Oppervlak     | Perc. in %  |
|:------------- |--------------:| -----------:|
| Glucose       | 459570        | 60,0        |
| Lactose       | 238940        | 31,2        |
| Fructose      | 41372         | 5,4         |
| Galactose     | 26102         | 3,4         | 
| Totaal        | 765984        | 100,0       |

---


--- 

[Terug naar de hoofdpagina uitwerkingen](../uitwerkingen.md)

<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [ ['$','$'], ["\\(","\\)"] ],
      processEscapes: true
    }
  });
</script>
    
<script type="text/javascript"
        src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>