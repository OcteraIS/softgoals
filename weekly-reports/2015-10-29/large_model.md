### 2 Objectives - [Hard goals & Soft goals, Coverage] 
```
{       :better gt
        :binary True
        :candidates 50
        :cr 0.3
        :evaluation evaluate_random
        :f 0.75
        :gens 100
        :is_percent True
        :obj_funcs ['eval_all_goals', 'eval_coverage']
        :seed 1
}

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,    32.43  ,   6.31 (       ---  *  |----          ),27.93, 31.53, 33.33, 36.94, 41.44
   2 ,     gen20_f1 ,    41.44  ,    7.2 (             --|-   * ---     ),34.23, 38.74, 41.44, 43.24, 46.85
   3 ,     gen40_f1 ,    43.24  ,    4.5 (              -|----  *---    ),35.14, 41.44, 43.24, 44.14, 47.75
   3 ,     gen60_f1 ,    44.14  ,   5.41 (               |----  *---    ),37.84, 41.44, 44.14, 45.05, 47.75
   3 ,     gen80_f1 ,    44.14  ,   5.41 (               |----  * --    ),37.84, 41.44, 44.14, 45.95, 47.75
   3 ,    gen100_f1 ,    44.14  ,   4.51 (               |----  * --    ),37.84, 41.44, 44.14, 45.95, 47.75

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,    97.76  ,    1.5 (     ----     *|----          ),96.27, 97.01, 97.76, 97.76, 98.51
   2 ,     gen20_f2 ,    98.51  ,   1.49 (         ----- |    *   ----- ),97.01, 97.76, 98.51, 99.25, 100.00
   2 ,     gen40_f2 ,    98.51  ,   1.49 (               |    *   ----- ),97.76, 97.76, 98.51, 99.25, 100.00
   2 ,     gen60_f2 ,    98.51  ,   1.49 (              -|----*   ----- ),97.76, 98.51, 98.51, 99.25, 100.00
   2 ,     gen80_f2 ,    98.51  ,   1.49 (              -|----*   ----- ),97.76, 98.51, 98.51, 99.25, 100.00
   2 ,    gen100_f2 ,    98.51  ,   1.49 (              -|----*   ----- ),97.76, 98.51, 98.51, 99.25, 100.00

Maximums = [51.35, 100.0]
```

### 3 Objectives - [Soft goals, Hard goals, Coverage]
```
{       :better gt
        :binary True
        :candidates 50
        :cr 0.3
        :evaluation evaluate_random
        :f 0.75
        :gens 100
        :is_percent True
        :obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
        :seed 1
}

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,    31.96  ,   6.18 (      ---   * -|----          ),25.77, 28.87, 31.96, 34.02, 39.18
   2 ,     gen20_f1 ,    36.08  ,   5.16 (           ----| *  ----      ),30.93, 35.05, 36.08, 39.18, 43.30
   3 ,     gen40_f1 ,    38.14  ,   6.19 (              -|-  *  --      ),34.02, 36.08, 38.14, 41.24, 43.30
   3 ,     gen60_f1 ,    38.14  ,   7.22 (              -|-  *  --      ),34.02, 36.08, 38.14, 41.24, 43.30
   3 ,     gen80_f1 ,    39.18  ,   6.19 (              -|-   *  --     ),34.02, 36.08, 39.18, 42.27, 44.33
   3 ,    gen100_f1 ,    40.21  ,   6.19 (              -|--   * --     ),34.02, 37.11, 40.21, 42.27, 44.33

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,    42.86  ,  14.28 (    -----*    -|---           ),28.57, 42.86, 42.86, 57.14, 71.43
   2 ,     gen20_f2 ,    71.43  ,  28.57 (         ----- |   *----      ),42.86, 57.14, 71.43, 71.43, 85.71
   2 ,     gen40_f2 ,    71.43  ,  28.57 (         ----- |   *----      ),42.86, 57.14, 71.43, 71.43, 85.71
   2 ,     gen60_f2 ,    71.43  ,  28.57 (         ----- |   *----      ),42.86, 57.14, 71.43, 71.43, 85.71
   2 ,     gen80_f2 ,    71.43  ,  28.57 (         ----- |   *----      ),42.86, 57.14, 71.43, 71.43, 85.71
   2 ,    gen100_f2 ,    71.43  ,  28.57 (         ------|---*          ),42.86, 71.43, 71.43, 85.71, 85.71

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f3 ,    97.76  ,    1.5 (     ----     *|----          ),96.27, 97.01, 97.76, 97.76, 98.51
   2 ,     gen20_f3 ,    97.76  ,   0.75 (         ----- |    *---      ),97.01, 97.76, 98.51, 98.51, 99.25
   2 ,     gen40_f3 ,    98.51  ,   0.75 (         ----- |    *---      ),97.01, 97.76, 98.51, 98.51, 99.25
   2 ,     gen60_f3 ,    98.51  ,   0.75 (         ----- |    *---      ),97.01, 97.76, 98.51, 98.51, 99.25
   2 ,     gen80_f3 ,    98.51  ,   1.49 (         ----- |    *---      ),97.01, 97.76, 98.51, 98.51, 99.25
   2 ,    gen100_f3 ,    98.51  ,   1.49 (         ----- |    *         ),97.01, 97.76, 98.51, 99.25, 99.25

Maximums = [48.45, 100.0, 100.0]
```
