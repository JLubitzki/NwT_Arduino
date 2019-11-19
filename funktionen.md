# Funktionen

Neben den Datentypen sind Funktionen eine grundlegende Programmierstruktur. Die Funktionen sind dazu da mit den Daten zu "rechnen".

Funktionen haben vier Bestandteile.

* den Rückgabewert
* den Funktionsnamen
* die Parameter und
* den Funktionskörper

{% hint style="success" %}
Ordne in der Tabelle zu.
{% endhint %}

| Begriff | Name in der Funktion |
| :--- | :--- |
| Rückgabewert |  |
| Funktionsname |  |
| Parameter |  |
| Funktionskörper |  |

{% tabs %}
{% tab title="Funktion" %}
```text
int meineMultiplikation(int x, int y){
  int ergebnis;
  ergebnis = x * y;
  return ergebnis;
}
```
{% endtab %}

{% tab title="mit Kommentar" %}
```text
int meineMultiplikation(int x, int y){ //Funktion multipliziert 2 ganze Zahlen
  int ergebnis;      // Variable ergebnis angelegt
  ergebnis = x * y;  // multipliziere x und y
  return ergebnis;    // gib das Produkt zurück
}
```
{% endtab %}

{% tab title="ohne \"ergebnis\"" %}
```text
int meineMultiplikation(int x, int y){
  return x * y;
}
```
{% endtab %}
{% endtabs %}

Du kannst auch die Variable "ergebnis" einsparen. Schreibe die Funktion hier ohne diese Variable hin \(Lösung in Tab3\).





Deine Funktiondeklaration muss ausserhalb des Hauptprogramms stehen. Schreibe Sie am besten unter das Hauptprogramm.

Nun kannst du deine Funktion "meineMultiplikation" im Hauptprogramm benutzen und zwar so:

```text
int x;
int y;
int z;

x = 4;
y = 6; 

z = meineMultiplikation( x, y);
Serial.println(z);
```



