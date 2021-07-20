### Images Approximation

<table border="1" width="100%">
    <tr>
        <td><img src="images/022-naruto.gif" width="250"></td>
        <td><img src="images/030-steve.gif" width="250"></td>
        <td><img src="images/032-raupy.gif" width="250"></td>
    </tr>
</table>

<table border="1" width="100%">
    <tr>
        <td><img src="images/028-banksy.gif" width="250"></td>
        <td><img src="images/024-racoon.gif" width="250"></td>
        <td><img src="images/026-saitama.gif" width="250"></td>
    </tr>
</table>

---

### Traveling Salesman

Solution on 10 cities:

```
0 58 94 91 77 99 75 84 59 67 
58 0 85 52 55 85 88 74 84 82 
94 85 0 52 76 53 56 99 95 53 
91 52 52 0 70 84 50 66 87 53 
77 55 76 70 0 99 77 76 59 66 
99 85 53 84 99 0 67 89 94 84 
75 88 56 50 77 67 0 79 87 69 
84 74 99 66 76 89 79 0 99 84 
59 84 95 87 59 94 87 99 0 77 
67 82 53 53 66 84 69 84 77 0 

Genetic algorithm's solution after 2 seconds: Shortest path 313.0 - Longest path 842.0
```

Solution on 20 cities:
```
0 97 88 92 71 61 61 65 53 54 90 79 59 59 80 56 89 76 59 56 
97 0 78 67 50 96 73 60 98 86 55 70 83 67 93 94 87 52 64 57 
88 78 0 70 61 62 65 92 98 56 89 68 68 93 58 76 69 63 62 94 
92 67 70 0 58 67 64 60 56 83 97 94 60 65 79 72 52 55 60 57 
71 50 61 58 0 50 90 72 76 65 51 71 82 86 89 97 61 85 71 55 
61 96 62 67 50 0 65 65 58 60 51 65 66 55 56 64 62 55 82 85 
61 73 65 64 90 65 0 87 53 72 63 74 94 61 82 68 67 59 88 74 
65 60 92 60 72 65 87 0 64 96 59 94 88 66 92 70 84 94 55 76 
53 98 98 56 76 58 53 64 0 88 58 55 67 64 61 64 63 59 76 77 
54 86 56 83 65 60 72 96 88 0 65 57 63 66 90 72 75 73 91 50 
90 55 89 97 51 51 63 59 58 65 0 78 93 79 74 55 78 75 83 66 
79 70 68 94 71 65 74 94 55 57 78 0 57 65 53 83 67 55 94 62 
59 83 68 60 82 66 94 88 67 63 93 57 0 51 55 95 76 96 58 79 
59 67 93 65 86 55 61 66 64 66 79 65 51 0 91 99 99 80 96 75 
80 93 58 79 89 56 82 92 61 90 74 53 55 91 0 81 63 57 54 95 
56 94 76 72 97 64 68 70 64 72 55 83 95 99 81 0 50 74 58 65 
89 87 69 52 61 62 67 84 63 75 78 67 76 99 63 50 0 87 87 83 
76 52 63 55 85 55 59 94 59 73 75 55 96 80 57 74 87 0 53 54 
59 64 62 60 71 82 88 55 76 91 83 94 58 96 54 58 87 53 0 64 
56 57 94 57 55 85 74 76 77 50 66 62 79 75 95 65 83 54 64 0 

Genetic algorithm's solution after 3 seconds: Shortest path 942.0 - Longest path 1574.0
```

Solution on 30 cities:
```
0 51 51 91 50 76 86 77 86 84 64 54 95 74 60 65 57 84 61 71 98 68 98 83 62 71 99 62 97 89 
51 0 75 51 77 53 85 67 55 55 92 51 76 74 82 76 71 81 93 95 53 54 75 93 53 59 52 98 86 61 
51 75 0 96 90 72 71 75 91 75 99 71 78 59 64 73 83 60 67 58 99 81 72 66 61 94 94 95 56 78 
91 51 96 0 84 87 65 90 64 95 68 84 60 65 94 90 91 60 99 83 93 89 77 89 71 50 85 85 97 61 
50 77 90 84 0 61 74 79 65 63 68 65 54 84 84 89 82 67 73 69 79 57 83 90 68 99 83 83 87 78 
76 53 72 87 61 0 90 62 61 52 60 96 55 94 73 99 87 88 85 67 68 66 91 98 74 90 93 59 59 80 
86 85 71 65 74 90 0 55 78 88 69 55 89 97 71 82 54 75 79 93 68 76 74 62 69 55 81 95 60 55 
77 67 75 90 79 62 55 0 88 92 96 90 77 62 79 85 78 57 50 99 57 56 55 54 67 94 79 71 93 74 
86 55 91 64 65 61 78 88 0 72 95 94 52 72 87 85 84 52 70 67 51 77 74 93 54 83 66 87 63 53 
84 55 75 95 63 52 88 92 72 0 57 53 91 74 70 58 65 95 74 55 91 89 55 85 52 52 98 62 50 65 
64 92 99 68 68 60 69 96 95 57 0 68 93 60 61 73 56 50 64 51 64 75 52 63 79 75 51 58 74 82 
54 51 71 84 65 96 55 90 94 53 68 0 82 70 67 52 90 50 58 68 95 57 82 60 92 75 74 69 51 61 
95 76 78 60 54 55 89 77 52 91 93 82 0 84 87 80 99 94 99 52 79 75 64 90 86 87 83 55 95 67 
74 74 59 65 84 94 97 62 72 74 60 70 84 0 73 56 75 52 97 65 62 71 92 57 69 76 50 83 84 83 
60 82 64 94 84 73 71 79 87 70 61 67 87 73 0 83 73 95 60 54 93 71 82 71 97 70 89 80 74 51 
65 76 73 90 89 99 82 85 85 58 73 52 80 56 83 0 72 68 57 92 69 72 96 91 54 64 81 77 53 62 
57 71 83 91 82 87 54 78 84 65 56 90 99 75 73 72 0 75 57 64 63 92 86 60 84 93 52 72 65 87 
84 81 60 60 67 88 75 57 52 95 50 50 94 52 95 68 75 0 97 79 55 76 97 62 50 63 71 94 79 80 
61 93 67 99 73 85 79 50 70 74 64 58 99 97 60 57 57 97 0 57 81 73 90 82 84 79 69 54 86 61 
71 95 58 83 69 67 93 99 67 55 51 68 52 65 54 92 64 79 57 0 87 55 55 68 88 77 80 53 56 69 
98 53 99 93 79 68 68 57 51 91 64 95 79 62 93 69 63 55 81 87 0 77 59 59 93 82 80 80 61 68 
68 54 81 89 57 66 76 56 77 89 75 57 75 71 71 72 92 76 73 55 77 0 92 87 64 98 99 56 92 56 
98 75 72 77 83 91 74 55 74 55 52 82 64 92 82 96 86 97 90 55 59 92 0 57 73 60 73 62 77 69 
83 93 66 89 90 98 62 54 93 85 63 60 90 57 71 91 60 62 82 68 59 87 57 0 57 64 90 80 84 97 
62 53 61 71 68 74 69 67 54 52 79 92 86 69 97 54 84 50 84 88 93 64 73 57 0 80 85 52 93 51 
71 59 94 50 99 90 55 94 83 52 75 75 87 76 70 64 93 63 79 77 82 98 60 64 80 0 59 51 91 67 
99 52 94 85 83 93 81 79 66 98 51 74 83 50 89 81 52 71 69 80 80 99 73 90 85 59 0 92 70 64 
62 98 95 85 83 59 95 71 87 62 58 69 55 83 80 77 72 94 54 53 80 56 62 80 52 51 92 0 65 91 
97 86 56 97 87 59 60 93 63 50 74 51 95 84 74 53 65 79 86 56 61 92 77 84 93 91 70 65 0 76 
89 61 78 61 78 80 55 74 53 65 82 61 67 83 51 62 87 80 61 69 68 56 69 97 51 67 64 91 76 0 

Genetic algorithm's solution after 4 seconds: Shortest path 1658.0 - Longest path 2395.0
```

---

### N-Queen problem

```
Genetic algorithm's fittest solution (48.0) after 0 seconds: 

0 0 0 0 0 0 1 0 
0 0 0 0 1 0 0 0 
0 0 0 0 0 0 0 1 
0 1 0 0 0 0 0 0 
0 0 0 1 0 0 0 0 
0 0 0 0 0 1 0 0 
1 0 0 0 0 0 0 0 
0 0 1 0 0 0 0 0 
```

---

### Shakespeare Monkeys

<table border="1" width="100%">
    <tr>
        <td><img src="images/033-jfk.png" width="1000"></td>
    </tr>
</table>

---

### Knapsack

<table border="1" width="100%">
    <tr>
        <td><img src="images/034-knapsack.png" width="1000"></td>
    </tr>
</table>

---

