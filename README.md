# Втора лабораториска вежба по Софтверско инженерство

## Андреј Трајковски, бр. на индекс 183128

### Control Flow Graph
![CFG Image](/CFG.png)
### Цикломатска комплексност
Цикломатската комплексност се пресметува со формулата
``
P+1
``
каде што P е бројот на предикантни јазли. Во овој случај ``P=10`` што следи дека цикломатската комплексност ќе биде ``11``.

### Тест случаи според критериумот Every statement

|  C0 | [] | ["0","#","#"] | ["0", "#", "0", "0", "0", "#", "0", "#", "#"] | ["#","0","#","#","#","#","#","#","#"] |
|:---:|:--:|:-------------:|:---------------------------------------------:|:-------------------------------------:|
|  A  |  * |       *       |                       *                       |                   *                   |
|  B  |  * |               |                                               |                                       |
| CDE |    |       *       |                       *                       |                   *                   |
|  F  |    |       *       |                                               |                                       |
|  G  |    |               |                       *                       |                   *                   |
|  H  |    |               |                       *                       |                   *                   |
|  I  |    |               |                       *                       |                   *                   |
|  JK |    |               |                       *                       |                   *                   |
|  L  |    |               |                       *                       |                   *                   |
|  M  |    |               |                                               |                   *                   |
|  NO |    |               |                       *                       |                                       |
|  P  |    |               |                       *                       |                   *                   |
|  Q  |    |               |                       *                       |                                       |
|  R  |    |               |                       *                       |                   *                   |
|  S  |    |               |                       *                       |                   *                   |
|  T  |    |               |                       *                       |                   *                   |
|  U  |    |               |                       *                       |                   *                   |
|  V  |    |               |                       *                       |                   *                   |
|  W  |    |               |                       *                       |                   *                   |
