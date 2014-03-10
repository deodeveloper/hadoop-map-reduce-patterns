## BasicJobChaining
### Description
Given a data set of StackOverflow posts, bin users based on if they are below
or above the number of average posts per user. Also to enrich each user with his or her
reputation from a separate data set when generating the output.


### Input
```
<row Id="1" 
PostId="7" 
Score="2" 
Text="Just ask this @Robert how annoying this can be..." 
CreationDate="2010-06-30T19:29:03.500" 
UserId="17" />
```
### Output
```
//hour  count    average   
0	771.0	143.84306
1	671.0	146.65276
2	665.0	137.0752
3	710.0	137.87042
4	691.0	145.37192
5	658.0	136.94681
6	736.0	137.86142
7	811.0	135.46117
8	895.0	128.91173
9	977.0	138.41556
10	884.0	129.6233
11	1032.0	135.2219
12	1312.0	134.72638
13	1478.0	135.6042
14	1573.0	142.11888
15	1628.0	143.65295
16	1472.0	143.72758
17	1436.0	137.7688
18	1384.0	142.86995
19	1304.0	142.43558
20	1399.0	138.73839
21	1200.0	143.34
22	1098.0	142.72313
23	822.0	145.39052

```
