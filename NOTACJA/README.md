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
+ jeśli kamera jest podłączona do netu to `http://www.camera.com/camera1`, a jak do urzadzenia to `usb://camera1`
+ adresowanie klawiatury jest potrzebne, bo trzeba wiedzieć co nacisnąć: `key://enter?press`

```javascript
from('rtmp://youtube.video').data('mimetype://video/mp4').operation('save').to('file://video1.mp4')
# delete
from('ssh://remotesever').data('file://video1.mp4').operation('delete')
# upload
from('localhost').data('file://video1.mp4').operation('save').to('ssh://remotesever')
```

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

Kombinacje
```csv
IN, DATA, OPERATION, OUT, DEVICE
1, 1, 1, 1

```

nazwa urządzenia
```csv
ID, NAZWA
1111,Dyktafon
1112, odtwarzacz audio
1112, odtwarzacz video

```


## Streaming

the content types associated with RTMP streams or related file formats that are served over RTMP, here are some examples:

1. **FLV - Flash Video**: 
   - MIME Type: `video/x-flv`
   - File Extension: `.flv`
   - Example: `SampleVideo.flv`

    Traditional file format used for delivering video streams via RTMP, which used to be played back in the Adobe Flash Player.

2. **F4V - MPEG-4 Video File used in Flash**:
   - MIME Type: `video/mp4`
   - File Extension: `.f4v` or `.mp4`
   - Example: `SampleVideo.f4v`

    An updated version of the FLV file format that was part of the Adobe Flash video workflow, containing H.264/AAC content.

3. **FLA - Adobe Flash Project File**:
   - MIME Type: `application/octet-stream`
   - File Extension: `.fla`
   - Example: `ProjectSource.fla`

    The original project file used by Adobe Flash Professional during the creation of Flash applications or animations.

4. **SWF - ShockWave Flash**:
   - MIME Type: `application/x-shockwave-flash`
   - File Extension: `.swf`
   - Example: `CompiledAnimation.swf`

    The compiled, published version of an FLA file, which was viewed in a web browser with Flash Player plugin.



