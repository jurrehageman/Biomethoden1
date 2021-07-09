![Hanze](../../hanze/hanze.png)

[Terug naar de hoofdpagina uitwerkingen](../uitwerkingen.md)

# Uitwerkingen les 10

---

## Opgave specifieke acticiteit

Je hebt net een cupje van het enzym invertase gekocht.
Het cupje bevat 5 mg eiwit.
Je lost het cupje op in 1 ml buffer.

Invertase activiteit is te meten met een spectrofotometrische bepaling.

Je leest in een protocol:

Invertase activity can be measured indirectly using 3,5-dinitrosalicylic acid (DNS) reagent. This reagent reacts with reducing sugars to form 3-amino-5-nitrosalicylic acid, which strongly absorbs light at 540 nm.
The absorbance at 540 nm was recorded for a 1 cm cuvet filled with the following solutions:
-	0,9 mL substrate solution in buffer
-	0.1 mL sample solution

Je meetresultaten uit het logboek:

In 10 minutes the absorbance was increased from 0.000 to 0.970 (increase was linear).
The molar absorption coefficient of the product formed is 34000 M-1 * cm-1.

Calculate the specific activity of the enzyme in the protein sample. (U/mg protein sample)

### Uitrekenen $\Delta n$


Wet van Lambert-Beer

$A = \epsilon \cdot c \cdot b$

of:

$c = \frac{A}{\epsilon * b}$

$c = \frac{0,970}{34000 * 1} = 2,85294\cdot10^{-05}\ mol/L$

$c =  2,85294\cdot10^{-08}\ mol/mL$
dus
$\Delta n = 2,85294\cdot10^{-08}\ mol$


### Specifieke activiteit

$specific\ activity = \frac{\frac{\Delta n (product formed)}{\Delta t}}{m(total protein in fraction)}$

$specific\ activity = \frac{\frac{2,85294\cdot10^{-08} mol}{10}}{5} = 5,70588\cdot10^{-10}\ mol/min/mg$

Er is nog een 10 maal verdunningsstap (100 ul in 1 ml)

$specific\ activity = 5,70588\cdot10^{-9}\ mol/min/mg$

1 unit is hoeveelheid enzym dat 1 micromol product omzet in 1 minuut dus:

$specific\ activity = 5,71\cdot10^{-3}\ \mu mol/min/mg$

$specific\ activity = 5,71\cdot10^{-3}\ units/min/mg$

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