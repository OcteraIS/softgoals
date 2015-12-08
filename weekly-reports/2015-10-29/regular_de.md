### bCMS_SR_bCMS
```
{	:better gt
 	:binary False
 	:candidates 16
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
Time Taken :  0.763870954514

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,    27.27  ,   9.09 (     ----------|-*     ------ ), 9.09, 27.27, 27.27, 36.36, 45.45
   1 ,     gen20_f1 ,    27.27  ,   9.09 (     ----------|-*     ------ ), 9.09, 27.27, 27.27, 36.36, 45.45
   1 ,     gen40_f1 ,    27.27  ,   9.09 (     ----------|-*     ------ ), 9.09, 27.27, 27.27, 36.36, 45.45
   1 ,     gen60_f1 ,    27.27  ,   9.09 (     ----------|-*     ------ ), 9.09, 27.27, 27.27, 36.36, 45.45
   1 ,     gen80_f1 ,    27.27  ,   9.09 (     ----------|-*     ------ ), 9.09, 27.27, 27.27, 36.36, 45.45
   1 ,    gen100_f1 ,    27.27  ,   9.09 (     ----------|-*     ------ ), 9.09, 27.27, 27.27, 36.36, 45.45

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,    47.62  ,  14.28 (--------    *  | ------------ ),33.33, 42.86, 47.62, 52.38, 66.67
   1 ,     gen20_f2 ,    47.62  ,  14.28 (--------    *  | ------------ ),33.33, 42.86, 47.62, 52.38, 66.67
   1 ,     gen40_f2 ,    47.62  ,  14.28 (--------    *  | ------------ ),33.33, 42.86, 47.62, 52.38, 66.67
   1 ,     gen60_f2 ,    47.62  ,  14.28 (--------    *  | ------------ ),33.33, 42.86, 47.62, 52.38, 66.67
   1 ,     gen80_f2 ,    47.62  ,  14.28 (--------    *  | ------------ ),33.33, 42.86, 47.62, 52.38, 66.67
   1 ,    gen100_f2 ,    47.62  ,  14.28 (--------    *  | ------------ ),33.33, 42.86, 47.62, 52.38, 66.67

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f3 ,     90.0  ,    6.0 (     ------    |       *----- ),84.00, 86.00, 90.00, 90.00, 92.00
   1 ,     gen20_f3 ,     90.0  ,    6.0 (     ------    |       *----- ),84.00, 86.00, 90.00, 90.00, 92.00
   1 ,     gen40_f3 ,     90.0  ,    6.0 (     ------    |       *----- ),84.00, 86.00, 90.00, 90.00, 92.00
   1 ,     gen60_f3 ,     90.0  ,    6.0 (     ------    |       *----- ),84.00, 86.00, 90.00, 90.00, 92.00
   1 ,     gen80_f3 ,     90.0  ,    6.0 (     ------    |       *----- ),84.00, 86.00, 90.00, 90.00, 92.00
   1 ,    gen100_f3 ,     90.0  ,    6.0 (     ------    |       *----- ),84.00, 86.00, 90.00, 90.00, 92.00

```
![1](../../src/img/gen_bCMS_SR_bCMS.png)

### bCMS_SR_bCMS_AuthenticationVariation
```
{	:better gt
 	:binary False
 	:candidates 50
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
Time Taken :  3.51539802551

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,    36.36  ,   9.09 (        ----   | *---         ),18.18, 27.27, 36.36, 36.36, 45.45
   2 ,     gen20_f1 ,    36.36  ,   9.09 (            ---|-    *---     ),27.27, 36.36, 45.45, 45.45, 54.55
   2 ,     gen40_f1 ,    45.45  ,  18.19 (            ---|-    *---     ),27.27, 36.36, 45.45, 45.45, 54.55
   2 ,     gen60_f1 ,    45.45  ,  18.19 (               |     *        ),36.36, 36.36, 45.45, 54.55, 54.55
   2 ,     gen80_f1 ,    45.45  ,  18.19 (               |     *        ),36.36, 36.36, 45.45, 54.55, 54.55
   2 ,    gen100_f1 ,    45.45  ,  18.19 (               | ----*        ),36.36, 45.45, 45.45, 54.55, 54.55

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,    47.62  ,  14.28 (    --    * ---|---           ),33.33, 38.10, 47.62, 52.38, 66.67
   2 ,     gen20_f2 ,     61.9  ,  14.29 (        ----   | * ----       ),42.86, 52.38, 61.90, 66.67, 76.19
   2 ,     gen40_f2 ,     61.9  ,  14.29 (          --   | * ----       ),47.62, 52.38, 61.90, 66.67, 76.19
   2 ,     gen60_f2 ,    66.67  ,  19.05 (          ---- |   * --       ),47.62, 57.14, 66.67, 71.43, 76.19
   2 ,     gen80_f2 ,    66.67  ,  14.29 (          ---- |   * --       ),47.62, 57.14, 66.67, 71.43, 76.19
   2 ,    gen100_f2 ,    66.67  ,  14.29 (          -----|-  * ----     ),47.62, 61.90, 66.67, 71.43, 80.95

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f3 ,    89.66  ,   1.72 (        ----   | *---         ),87.93, 89.66, 91.38, 91.38, 93.10
   2 ,     gen20_f3 ,     93.1  ,   1.72 (            ---|-    *------- ),89.66, 91.38, 93.10, 93.10, 96.55
   2 ,     gen40_f3 ,     93.1  ,   3.45 (               | ----*   ---- ),91.38, 93.10, 93.10, 94.83, 96.55
   2 ,     gen60_f3 ,     93.1  ,   3.45 (               | ----*   ---- ),91.38, 93.10, 93.10, 94.83, 96.55
   2 ,     gen80_f3 ,     93.1  ,   1.73 (               | ----*   ---- ),91.38, 93.10, 93.10, 94.83, 96.55
   2 ,    gen100_f3 ,     93.1  ,   1.73 (               | ----*   ---- ),91.38, 93.10, 93.10, 94.83, 96.55

```
![1](../../src/img/gen_bCMS_SR_bCMS_AuthenticationVariation.png)

### bCMS_SR_bCMS_exceptional
```
{	:better gt
 	:binary False
 	:candidates 4
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
../GMRepo/CMA12/bCMS_SR_bCMS_exceptional.ood
Cannot generate 4 candidates with 10 leaves
```

### bCMS_SR_bCMS_VehicleCommunicationVariant
```
{	:better gt
 	:binary False
 	:candidates 50
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
Time Taken :  3.05808711052

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,    36.36  ,   9.09 (-----      *---|-             ),18.18, 27.27, 36.36, 36.36, 45.45
   2 ,     gen20_f1 ,    45.45  ,   9.09 (     ------    | *------      ),27.27, 36.36, 45.45, 45.45, 54.55
   2 ,     gen40_f1 ,    45.45  ,   9.09 (     ------    | *------      ),27.27, 36.36, 45.45, 45.45, 54.55
   2 ,     gen60_f1 ,    45.45  ,   9.09 (     ------    | *------      ),27.27, 36.36, 45.45, 45.45, 54.55
   2 ,     gen80_f1 ,    45.45  ,   9.09 (     ------    | *------      ),27.27, 36.36, 45.45, 45.45, 54.55
   2 ,    gen100_f1 ,    45.45  ,   9.09 (     ------    | *------      ),27.27, 36.36, 45.45, 45.45, 54.55

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,    45.45  ,  13.64 (      --  *    |-----         ),36.36, 40.91, 45.45, 54.55, 68.18
   2 ,     gen20_f2 ,    63.64  ,  18.18 (          -----|   * --       ),45.45, 54.55, 63.64, 68.18, 72.73
   2 ,     gen40_f2 ,    63.64  ,  18.18 (          -----|   *          ),45.45, 54.55, 63.64, 72.73, 72.73
   2 ,     gen60_f2 ,    68.18  ,  18.18 (          -----|-    * --     ),45.45, 59.09, 68.18, 72.73, 77.27
   2 ,     gen80_f2 ,    68.18  ,  18.18 (            ---|-    * --     ),50.00, 59.09, 68.18, 72.73, 77.27
   2 ,    gen100_f2 ,    68.18  ,  18.18 (               |-    * --     ),54.55, 59.09, 68.18, 72.73, 77.27

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f3 ,    86.44  ,   5.08 (     -----     |*  --         ),81.36, 84.75, 88.14, 89.83, 91.53
   2 ,     gen20_f3 ,    89.83  ,   3.39 (          -----|   *          ),84.75, 88.14, 89.83, 91.53, 91.53
   2 ,     gen40_f3 ,    89.83  ,   3.39 (          -----|---* ---      ),84.75, 89.83, 89.83, 91.53, 93.22
   2 ,     gen60_f3 ,    89.83  ,   3.39 (             --|---* ---      ),86.44, 89.83, 89.83, 91.53, 93.22
   2 ,     gen80_f3 ,    89.83  ,   3.39 (             --|---* ---      ),86.44, 89.83, 89.83, 91.53, 93.22
   2 ,    gen100_f3 ,    89.83  ,   3.39 (             --|---* ---      ),86.44, 89.83, 89.83, 91.53, 93.22

```
![1](../../src/img/gen_bCMS_SR_bCMS_VehicleCommunicationVariant.png)

### bCMS_SR_CommunicationCompromiser
```
{	:better gt
 	:binary False
 	:candidates 16
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
Time Taken :  0.265877962112

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen20_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen40_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen60_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen80_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,    gen100_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,      0.0  ,  33.33 (*              |              ), 0.00,  0.00,  0.00, 33.33, 33.33
   1 ,     gen20_f2 ,      0.0  ,  33.33 (*              |              ), 0.00,  0.00,  0.00, 33.33, 33.33
   1 ,     gen40_f2 ,      0.0  ,  33.33 (*              |              ), 0.00,  0.00,  0.00, 33.33, 33.33
   1 ,     gen60_f2 ,      0.0  ,  33.33 (*              |              ), 0.00,  0.00,  0.00, 33.33, 33.33
   1 ,     gen80_f2 ,      0.0  ,  33.33 (*              |              ), 0.00,  0.00,  0.00, 33.33, 33.33
   1 ,    gen100_f2 ,      0.0  ,  33.33 (*              |              ), 0.00,  0.00,  0.00, 33.33, 33.33

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f3 ,    85.71  ,  14.29 (               |   *          ),78.57, 78.57, 85.71, 92.86, 92.86
   1 ,     gen20_f3 ,    85.71  ,  14.29 (               |   *          ),78.57, 78.57, 85.71, 92.86, 92.86
   1 ,     gen40_f3 ,    85.71  ,  14.29 (               |   *          ),78.57, 78.57, 85.71, 92.86, 92.86
   1 ,     gen60_f3 ,    85.71  ,  14.29 (               |   *          ),78.57, 78.57, 85.71, 92.86, 92.86
   1 ,     gen80_f3 ,    85.71  ,  14.29 (               |   *          ),78.57, 78.57, 85.71, 92.86, 92.86
   1 ,    gen100_f3 ,    85.71  ,  14.29 (               |   *          ),78.57, 78.57, 85.71, 92.86, 92.86

```
![1](../../src/img/gen_bCMS_SR_CommunicationCompromiser.png)

### bCMS_SR_Fireman
```
{	:better gt
 	:binary False
 	:candidates 16
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
Time Taken :  0.758661985397

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,    23.53  ,  11.76 (------      *--|-------       ),11.76, 17.65, 23.53, 23.53, 35.29
   1 ,     gen20_f1 ,    23.53  ,  11.76 (------      *--|-------       ),11.76, 17.65, 23.53, 23.53, 35.29
   1 ,     gen40_f1 ,    23.53  ,  11.76 (------      *--|-------       ),11.76, 17.65, 23.53, 23.53, 35.29
   1 ,     gen60_f1 ,    23.53  ,  11.76 (------      *--|-------       ),11.76, 17.65, 23.53, 23.53, 35.29
   1 ,     gen80_f1 ,    23.53  ,  11.76 (------      *--|-------       ),11.76, 17.65, 23.53, 23.53, 35.29
   1 ,    gen100_f1 ,    23.53  ,  11.76 (------      *--|-------       ),11.76, 17.65, 23.53, 23.53, 35.29

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,     30.0  ,   10.0 (    -----*    -|--------      ),20.00, 30.00, 30.00, 40.00, 60.00
   1 ,     gen20_f2 ,     30.0  ,   10.0 (    -----*    -|--------      ),20.00, 30.00, 30.00, 40.00, 60.00
   1 ,     gen40_f2 ,     30.0  ,   10.0 (    -----*    -|--------      ),20.00, 30.00, 30.00, 40.00, 60.00
   1 ,     gen60_f2 ,     30.0  ,   10.0 (    -----*    -|--------      ),20.00, 30.00, 30.00, 40.00, 60.00
   1 ,     gen80_f2 ,     30.0  ,   10.0 (    -----*    -|--------      ),20.00, 30.00, 30.00, 40.00, 60.00
   1 ,    gen100_f2 ,     30.0  ,   10.0 (    -----*    -|--------      ),20.00, 30.00, 30.00, 40.00, 60.00

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f3 ,    95.12  ,   2.44 (              *|              ),92.68, 92.68, 95.12, 95.12, 95.12
   1 ,     gen20_f3 ,    95.12  ,   2.44 (              *|              ),92.68, 92.68, 95.12, 95.12, 95.12
   1 ,     gen40_f3 ,    95.12  ,   2.44 (              *|              ),92.68, 92.68, 95.12, 95.12, 95.12
   1 ,     gen60_f3 ,    95.12  ,   2.44 (              *|              ),92.68, 92.68, 95.12, 95.12, 95.12
   1 ,     gen80_f3 ,    95.12  ,   2.44 (              *|              ),92.68, 92.68, 95.12, 95.12, 95.12
   1 ,    gen100_f3 ,    95.12  ,   2.44 (              *|              ),92.68, 92.68, 95.12, 95.12, 95.12

```
![1](../../src/img/gen_bCMS_SR_Fireman.png)

### bCMS_SR_FSC
```
{	:better gt
 	:binary False
 	:candidates 8
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
../GMRepo/CMA12/bCMS_SR_FSC.ood
Cannot generate 8 candidates with 5 leaves
```

### bCMS_SR_GovernmentAgency
```
{	:better gt
 	:binary False
 	:candidates 1
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
../GMRepo/CMA12/bCMS_SR_GovernmentAgency.ood
Cannot generate 1 candidates with 7 leaves
```

### bCMS_SR_Policeman
```
{	:better gt
 	:binary False
 	:candidates 16
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
Time Taken :  0.41664481163

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,    11.11  ,  11.11 (              *|------------- ), 0.00,  0.00, 11.11, 11.11, 22.22
   1 ,     gen20_f1 ,    11.11  ,  11.11 (              *|------------- ), 0.00,  0.00, 11.11, 11.11, 22.22
   1 ,     gen40_f1 ,    11.11  ,  11.11 (              *|------------- ), 0.00,  0.00, 11.11, 11.11, 22.22
   1 ,     gen60_f1 ,    11.11  ,  11.11 (              *|------------- ), 0.00,  0.00, 11.11, 11.11, 22.22
   1 ,     gen80_f1 ,    11.11  ,  11.11 (              *|------------- ), 0.00,  0.00, 11.11, 11.11, 22.22
   1 ,    gen100_f1 ,    11.11  ,  11.11 (              *|------------- ), 0.00,  0.00, 11.11, 11.11, 22.22

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,     50.0  ,  16.67 (---------      |   *          ),16.67, 33.33, 50.00, 50.00, 50.00
   1 ,     gen20_f2 ,     50.0  ,  16.67 (---------      |   *          ),16.67, 33.33, 50.00, 50.00, 50.00
   1 ,     gen40_f2 ,     50.0  ,  16.67 (---------      |   *          ),16.67, 33.33, 50.00, 50.00, 50.00
   1 ,     gen60_f2 ,     50.0  ,  16.67 (---------      |   *          ),16.67, 33.33, 50.00, 50.00, 50.00
   1 ,     gen80_f2 ,     50.0  ,  16.67 (---------      |   *          ),16.67, 33.33, 50.00, 50.00, 50.00
   1 ,    gen100_f2 ,     50.0  ,  16.67 (---------      |   *          ),16.67, 33.33, 50.00, 50.00, 50.00

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f3 ,    88.46  ,   7.69 (               |  *---------- ),84.62, 84.62, 88.46, 88.46, 96.15
   1 ,     gen20_f3 ,    88.46  ,   7.69 (               |  *---------- ),84.62, 84.62, 88.46, 88.46, 96.15
   1 ,     gen40_f3 ,    88.46  ,   7.69 (               |  *---------- ),84.62, 84.62, 88.46, 88.46, 96.15
   1 ,     gen60_f3 ,    88.46  ,   7.69 (               |  *---------- ),84.62, 84.62, 88.46, 88.46, 96.15
   1 ,     gen80_f3 ,    88.46  ,   7.69 (               |  *---------- ),84.62, 84.62, 88.46, 88.46, 96.15
   1 ,    gen100_f3 ,    88.46  ,   7.69 (               |  *---------- ),84.62, 84.62, 88.46, 88.46, 96.15

```
![1](../../src/img/gen_bCMS_SR_Policeman.png)

### bCMS_SR_PSC
```
{	:better gt
 	:binary False
 	:candidates 8
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
../GMRepo/CMA12/bCMS_SR_PSC.ood
Cannot generate 8 candidates with 5 leaves
```

### bCMS_SR_Victim
```
{	:better gt
 	:binary False
 	:candidates 50
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
Time Taken :  1.84600400925

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,     7.14  ,   7.14 (--------------*|------------- ), 0.00,  7.14,  7.14,  7.14, 14.29
   2 ,     gen20_f1 ,    14.29  ,   7.15 (               |             *), 7.14,  7.14, 14.29, 14.29, 14.29
   2 ,     gen40_f1 ,    14.29  ,   7.15 (               |             *), 7.14,  7.14, 14.29, 14.29, 14.29
   2 ,     gen60_f1 ,    14.29  ,   7.15 (               |             *), 7.14,  7.14, 14.29, 14.29, 14.29
   2 ,     gen80_f1 ,    14.29  ,   7.15 (              -|-------------*), 7.14, 14.29, 14.29, 14.29, 14.29
   2 ,    gen100_f1 ,    14.29  ,   7.15 (              -|-------------*), 7.14, 14.29, 14.29, 14.29, 14.29

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,    33.33  ,  16.67 (      -----*   |  ------      ),16.67, 33.33, 33.33, 50.00, 66.67
   2 ,     gen20_f2 ,     50.0  ,  33.34 (           ----|--*     ----- ),33.33, 50.00, 50.00, 66.67, 83.33
   2 ,     gen40_f2 ,     50.0  ,  16.67 (           ----|--*     ----- ),33.33, 50.00, 50.00, 66.67, 83.33
   3 ,     gen60_f2 ,    66.67  ,  16.67 (           ----|--      *---- ),33.33, 50.00, 66.67, 66.67, 83.33
   3 ,     gen80_f2 ,    66.67  ,  16.67 (           ----|--      *---- ),33.33, 50.00, 66.67, 66.67, 83.33
   3 ,    gen100_f2 ,    66.67  ,  16.67 (           ----|--      *---- ),33.33, 50.00, 66.67, 66.67, 83.33

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f3 ,    93.94  ,   3.03 (-------       *|------        ),87.88, 90.91, 93.94, 93.94, 96.97
   2 ,     gen20_f3 ,    93.94  ,   3.03 (       ------- |      *       ),90.91, 93.94, 96.97, 96.97, 96.97
   2 ,     gen40_f3 ,    96.97  ,   3.03 (       ------- |      *       ),90.91, 93.94, 96.97, 96.97, 96.97
   2 ,     gen60_f3 ,    96.97  ,   3.03 (       ------- |      *------ ),90.91, 93.94, 96.97, 96.97, 100.00
   2 ,     gen80_f3 ,    96.97  ,   3.03 (               |      *------ ),93.94, 93.94, 96.97, 96.97, 100.00
   2 ,    gen100_f3 ,    96.97  ,   3.03 (              -|------*------ ),93.94, 96.97, 96.97, 96.97, 100.00

```
![1](../../src/img/gen_bCMS_SR_Victim.png)

### bCMS_SR_Witness
```
{	:better gt
 	:binary False
 	:candidates 32
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
Time Taken :  0.870326042175

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,    18.18  ,   9.09 (               |   *--------- ), 9.09,  9.09, 18.18, 18.18, 27.27
   1 ,     gen20_f1 ,    18.18  ,   9.09 (               |   *--------- ), 9.09,  9.09, 18.18, 18.18, 27.27
   1 ,     gen40_f1 ,    18.18  ,   9.09 (               |   *--------- ), 9.09,  9.09, 18.18, 18.18, 27.27
   1 ,     gen60_f1 ,    18.18  ,   9.09 (               |   *--------- ), 9.09,  9.09, 18.18, 18.18, 27.27
   1 ,     gen80_f1 ,    18.18  ,   9.09 (               |   *--------- ), 9.09,  9.09, 18.18, 18.18, 27.27
   1 ,    gen100_f1 ,    18.18  ,   9.09 (               |   *--------- ), 9.09,  9.09, 18.18, 18.18, 27.27

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,     40.0  ,   40.0 (-------       *|      ------- ), 0.00, 20.00, 40.00, 60.00, 80.00
   1 ,     gen20_f2 ,     40.0  ,   40.0 (-------       *|      ------- ), 0.00, 20.00, 40.00, 60.00, 80.00
   1 ,     gen40_f2 ,     40.0  ,   40.0 (-------       *|      ------- ), 0.00, 20.00, 40.00, 60.00, 80.00
   1 ,     gen60_f2 ,     40.0  ,   40.0 (-------       *|      ------- ), 0.00, 20.00, 40.00, 60.00, 80.00
   1 ,     gen80_f2 ,     40.0  ,   40.0 (-------       *|      ------- ), 0.00, 20.00, 40.00, 60.00, 80.00
   1 ,    gen100_f2 ,     40.0  ,   40.0 (-------       *|      ------- ), 0.00, 20.00, 40.00, 60.00, 80.00

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f3 ,    88.89  ,    3.7 (               |    *-------- ),85.19, 85.19, 88.89, 88.89, 92.59
   1 ,     gen20_f3 ,    88.89  ,    3.7 (               |    *-------- ),85.19, 85.19, 88.89, 88.89, 92.59
   1 ,     gen40_f3 ,    88.89  ,    3.7 (               |    *-------- ),85.19, 85.19, 88.89, 88.89, 92.59
   1 ,     gen60_f3 ,    88.89  ,    3.7 (               |    *-------- ),85.19, 85.19, 88.89, 88.89, 92.59
   1 ,     gen80_f3 ,    88.89  ,    3.7 (               |    *-------- ),85.19, 85.19, 88.89, 88.89, 92.59
   1 ,    gen100_f3 ,    88.89  ,    3.7 (               |    *-------- ),85.19, 85.19, 88.89, 88.89, 92.59

```
![1](../../src/img/gen_bCMS_SR_Witness.png)

### bCMS_StrategicDependency_MultiplicityVariant
```
{	:better gt
 	:binary False
 	:candidates 50
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
Time Taken :  1.01119494438

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen20_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen40_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen60_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen80_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,    gen100_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,     50.0  ,  16.67 (-----      *---|--            ),16.67, 33.33, 50.00, 50.00, 66.67
   2 ,     gen20_f2 ,    83.33  ,    0.0 (               |  -----*----- ),66.67, 83.33, 83.33, 83.33, 100.00
   2 ,     gen40_f2 ,    83.33  ,  16.67 (               |       *      ),83.33, 83.33, 83.33, 100.00, 100.00
   3 ,     gen60_f2 ,    100.0  ,  16.67 (               |             *),83.33, 83.33, 100.00, 100.00, 100.00
   3 ,     gen80_f2 ,    100.0  ,  16.67 (               |       ------*),83.33, 100.00, 100.00, 100.00, 100.00
   3 ,    gen100_f2 ,    100.0  ,    0.0 (               |       ------*),83.33, 100.00, 100.00, 100.00, 100.00

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen20_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen40_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen60_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen80_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,    gen100_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00

```
![1](../../src/img/gen_bCMS_StrategicDependency_MultiplicityVariant.png)

### bCMS_StrategicDependency_VehiclesVariant
```
{	:better gt
 	:binary False
 	:candidates 50
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
Time Taken :  0.953500986099

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen20_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen40_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen60_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen80_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,    gen100_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,     50.0  ,   50.0 (              *|      ------- ),25.00, 25.00, 50.00, 75.00, 100.00
   2 ,     gen20_f2 ,    100.0  ,   25.0 (               |      -------*),75.00, 100.00, 100.00, 100.00, 100.00
   2 ,     gen40_f2 ,    100.0  ,    0.0 (               |             *),100.00, 100.00, 100.00, 100.00, 100.00
   2 ,     gen60_f2 ,    100.0  ,    0.0 (               |             *),100.00, 100.00, 100.00, 100.00, 100.00
   2 ,     gen80_f2 ,    100.0  ,    0.0 (               |             *),100.00, 100.00, 100.00, 100.00, 100.00
   2 ,    gen100_f2 ,    100.0  ,    0.0 (               |             *),100.00, 100.00, 100.00, 100.00, 100.00

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen20_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen40_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen60_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen80_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,    gen100_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00

```
![1](../../src/img/gen_bCMS_StrategicDependency_VehiclesVariant.png)

### bCMS_StrategicDependency_withbCMS
```
{	:better gt
 	:binary False
 	:candidates 50
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
Time Taken :  1.00534892082

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen20_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen40_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen60_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen80_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,    gen100_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,     50.0  ,  16.67 (-----      *---|--            ),16.67, 33.33, 50.00, 50.00, 66.67
   2 ,     gen20_f2 ,    83.33  ,    0.0 (               |  -----*----- ),66.67, 83.33, 83.33, 83.33, 100.00
   2 ,     gen40_f2 ,    83.33  ,  16.67 (               |       *      ),83.33, 83.33, 83.33, 100.00, 100.00
   3 ,     gen60_f2 ,    100.0  ,  16.67 (               |             *),83.33, 83.33, 100.00, 100.00, 100.00
   3 ,     gen80_f2 ,    100.0  ,  16.67 (               |       ------*),83.33, 100.00, 100.00, 100.00, 100.00
   3 ,    gen100_f2 ,    100.0  ,    0.0 (               |       ------*),83.33, 100.00, 100.00, 100.00, 100.00

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen20_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen40_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen60_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen80_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,    gen100_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00

```
![1](../../src/img/gen_bCMS_StrategicDependency_withbCMS.png)

### bCMS_StrategicDependency_withoutbCMS
```
{	:better gt
 	:binary False
 	:candidates 50
 	:cr 0.3
 	:evaluation evaluate_random
 	:f 0.75
 	:gens 100
 	:is_percent True
 	:obj_funcs ['eval_softgoals', 'eval_goals', 'eval_coverage']
 	:seed 1
}
Time Taken :  0.830164909363

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen20_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen40_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen60_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,     gen80_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00
   1 ,    gen100_f1 ,      0.0  ,    0.0 (*              |              ), 0.00,  0.00,  0.00,  0.00,  0.00

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f2 ,     50.0  ,   50.0 (              *|              ),25.00, 25.00, 50.00, 75.00, 75.00
   2 ,     gen20_f2 ,    100.0  ,    0.0 (               |      -------*),75.00, 100.00, 100.00, 100.00, 100.00
   2 ,     gen40_f2 ,    100.0  ,    0.0 (               |             *),100.00, 100.00, 100.00, 100.00, 100.00
   2 ,     gen60_f2 ,    100.0  ,    0.0 (               |             *),100.00, 100.00, 100.00, 100.00, 100.00
   2 ,     gen80_f2 ,    100.0  ,    0.0 (               |             *),100.00, 100.00, 100.00, 100.00, 100.00
   2 ,    gen100_f2 ,    100.0  ,    0.0 (               |             *),100.00, 100.00, 100.00, 100.00, 100.00

rank ,         name ,    med   ,   iqr 
----------------------------------------------------
   1 ,      gen0_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen20_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen40_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen60_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,     gen80_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00
   1 ,    gen100_f3 ,    100.0  ,    0.0 (*              |              ),100.00, 100.00, 100.00, 100.00, 100.00

```
![1](../../src/img/gen_bCMS_StrategicDependency_withoutbCMS.png)
