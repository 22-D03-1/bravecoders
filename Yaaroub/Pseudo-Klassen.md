# Pseudo-Klassen

Eine **Pseudoklasse** in CSS ist ein Schlüsselbegriff, welcher hinter einen Selektor gestellt wird, um einen besonderen Zustand abzufragen. So steht beispielsweise :hover für Elemente, die gerade mit dem Mauszeiger berührt werden.

Mit Pseudoklassen und Pseudoelementen lässt sich eine Seite nicht nur in Bezug auf die Struktur des Inhalts gestalten, sondern auch im Bezug auf andere Faktoren wie zum Beispiel den Browserverlauf  (:visited), eingegebene Formulardaten (:checked (en-US)) oder die Position des Mauszeigers (:hover).

## SYNTAX:
>selector:pseudo-class {
>
> property: value;
> 
>}

**BEISPIEL :**

<a href="www.facebook.com">Facebook</a>

<style>
    a:hover{
        color:red
    }
</style>
## Andere Pseudo-klassen:
1. **:first-child:** *Wählt das erste Kindelement aus*
2. **:last-child:** *Wählt das letzte Kindelement aus*
3. **:nth-child(n):** *Wählt das zweite Kindelement aus*