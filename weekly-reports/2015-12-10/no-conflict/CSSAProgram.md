## CSSAProgram
```

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,    47.54  ,  22.95 (    ---- *     |---------     ),36.07, 44.26, 47.54, 63.93, 83.61
   2 ,     gen20_f1 ,    73.77  ,  24.59 (          -----|     *  ----  ),49.18, 62.30, 75.41, 81.97, 91.80
   2 ,     gen40_f1 ,    77.05  ,  19.68 (           ----|----   * ---- ),52.46, 72.13, 80.33, 83.61, 95.08
   3 ,     gen60_f1 ,    81.97  ,  13.12 (             --|-----   *---- ),57.38, 75.41, 81.97, 85.25, 95.08
   3 ,     gen80_f1 ,    81.97  ,  11.48 (             --|-----   *---- ),57.38, 75.41, 81.97, 85.25, 95.08
   3 ,    gen100_f1 ,    81.97  ,  11.48 (               |------   *--- ),62.30, 77.05, 83.61, 86.89, 95.08

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen20_f2 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen40_f2 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen60_f2 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen80_f2 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,    gen100_f2 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,     gen60_f3 ,     13.0  ,    9.0 (   ---   *   --|              ), 6.00, 10.00, 13.00, 18.00, 23.00
   1 ,     gen80_f3 ,     13.0  ,    8.0 (   ---   * ----|              ), 6.00,  9.00, 13.00, 16.00, 22.00
   1 ,    gen100_f3 ,     13.0  ,    8.0 (   ---   * ----|              ), 6.00,  9.00, 13.00, 16.00, 21.00
   1 ,     gen40_f3 ,     14.0  ,    9.0 (   ---   *   --|-             ), 6.00, 10.00, 14.00, 18.00, 24.00
   1 ,     gen20_f3 ,     15.0  ,    9.0 (    -----  * --|---           ), 7.00, 13.00, 16.00, 19.00, 27.00
   2 ,      gen0_f3 ,     18.0  ,   10.0 (       ---   * |-------       ),11.00, 15.00, 18.00, 23.00, 31.00
```
### Time Taken : 25.8953390121
![1](../../../src/img/no_conflict/CSSAProgram.png)
```

+------+-------------------------------+----------+-------+------+
| rank |              name             |   type   | value | cost |
+------+-------------------------------+----------+-------+------+
|  1   |          Retrain SA s         |   task   |   1   |  1   |
|  2   |        Provide Speaches       |   task   |   -1  |  3   |
|  3   |           Train SA s          |   task   |   1   |  4   |
|  4   |       Attend CS Meetings      |   task   |   -1  |  2   |
|  5   | School Initiates Presenation1 |   task   |   -1  |  3   |
|  6   |    Help with Presentations    |   task   |   -1  |  5   |
|  7   |  Write Articles for Newspaper |   task   |   1   |  5   |
|  8   |       Attend SA Meetings      |   task   |   -1  |  4   |
|  9   |   Run Fundraiser in Schools1  |   task   |   1   |  3   |
|  10  |      Promotion Resources1     | resource |   -1  |  1   |
|  11  |       Plan Social Events      |   task   |   -1  |  4   |
|  12  |        Send out Emails        |   task   |   -1  |  5   |
+------+-------------------------------+----------+-------+------+
```