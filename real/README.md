# Настоящие 3D-модели

Положи сюда файлы `.glb` и впиши их в `config.json` — игра сама заменит свои самолёты на них.

| Файл | Какой самолёт |
|---|---|
| `f16.glb` | F-16C |
| `fa18.glb` | F/A-18E |
| `su33.glb` | Су-33 |
| `mig29.glb` | МиГ-29 |
| `f35c.glb` | F-35C |
| `rafale.glb` | Рафаль |
| `f4e.glb`, `a4.glb`, `av8b.glb`, `j7.glb`, `mir.glb` | остальные |
| `b2.glb` | B-2 Спирит |
| `cockpit.glb` | кабина |

Пример `config.json`:
```json
{"models":["f16","su33"],"cockpit":true,
 "f16":{"flip":true},
 "cockpit":{"scale":1,"y":-0.9,"z":-0.2}}
```
- `flip: true` — если самолёт летит хвостом вперёд.
- `scale` — подправить размер, `rotY` — повернуть (в радианах).

## Установленные модели (Sketchfab)
| Файл | Модель | Автор | Лицензия |
|---|---|---|---|
| f16.glb | F16 with streamline and afterburner | MrrrBoB | CC BY 4.0 |
| rafale.glb | Dassault Rafale | andertan | CC BY 4.0 |
| fa18.glb | Boeing F/A-18E/F Super Hornet | andertan | CC BY 4.0 |
| su33.glb | Sukhoi Su-33 | andertan | CC BY 4.0 |
| av8b.glb | AV-8B Harrier II | 42manako | CC BY 4.0 |
| mir.glb | Dassault Mirage 2000 | bohmerang | CC BY-NC-SA 4.0 |
| f35c.glb | F-35 Lightning II | bohmerang | CC BY-NC-SA 4.0 |
| mig29.glb | MiG-29 | bohmerang | CC BY-NC-SA 4.0 |
| f4e.glb | F-4 Phantom II | bohmerang | CC BY-NC-SA 4.0 |
| b2.glb | Northrop Grumman B-2 Spirit (текстуры уменьшены до 2048) | bohmerang | CC BY-NC-SA 4.0 |
| j7.glb | MIG-21 Fishbed (один самолёт из трёх, текстуры 1024) | NETRUNNER_pl | CC BY 4.0 |
| a4.glb | Douglas A-4 Skyhawk (упрощён 590k → 63k треугольников) | johnnokomis | CC BY 4.0 |
| cockpit.glb | F-16 Block 50/52 Cockpit | rukh | CC BY 4.0 |

Модели CC BY-NC-SA нельзя использовать в коммерческих целях (продажа игры, реклама).
