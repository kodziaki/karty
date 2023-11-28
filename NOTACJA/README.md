# NOTACJA 


## URI
+ URL
+ QRCODE

forma reprezentacji tych kart w formie adresu URI i QRcode

dzięki temu bedzie można robić converter z URI na kod

apache camel ma taką URI notację + dsl

![image](https://github.com/kodziaki/karty/assets/5669657/24c7fef5-bbb8-4784-abe1-841e46df9e2c)
Działający mikroserwis: [REST :: Apache Camel](https://camel.apache.org/components/4.0.x/rest-component.html)


## URI
Wykorzystanie URI do adresowania wejścia i wyjścia, czyli np. 
+ jeśli kamera jest podłączona do netu to `http://`, a jak do urzadzenia to `usb://`
+ adresowanie klawiatury jest potrzebne, bo trzeba wiedzieć co nacisnąć: key://enter

w ten sposób budowanie z klocków będzie odnosiło się do zasobów istniejących i opartych w jakimś wycinku infrastruktury niezależnie czy to smartfon czy internet

jak dziecko przejdzie etap zgadywanek i kombinacji to potem może przejść do poziomu tworzenia  aplikacji w smartfonie

skanując wybrane kwadraciki



Każdy objekt, zassób czy komenda ma swój numer, który można sprawdzić w tabeli

Interfejs wejścia

```csv
NO,NAME
1,Mikrofon
2,Kamera
3,Klawiatura
4,przycisk

```

Interfejs wyjścia
```csv
NO,NAME
1,Głośnik
2,Wyświetlacz
3,Dioda LED
4,
```

Dane
```csv
NO,
1,
```

Operacja
```csv
NO,NAME
1,wyślij
2,odbierz
3,włącz
4,wyłącz
```


```csv
IN, DATA, OPERATION, OUT
1, 1, 1, 1

```
