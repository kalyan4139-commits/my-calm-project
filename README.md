int red = 9;
2int yellow = 8;
3int green = 7;
4
5void setup(){
6  
7  pinMode(red, OUTPUT);
8  pinMode(yellow, OUTPUT);
9  pinMode(green,  OUTPUT);
10  
11}
12void loop(){
13digitalWrite(red, HIGH);
14 delay(15000);
15digitalWrite(red,  LOW);
16  
17  digitalWrite(yellow, HIGH);
18delay(1000);
19  digitalWrite(yellow,  LOW);
20delay(500);
21
22  digitalWrite(yellow, HIGH);
23delay(1000);
24  digitalWrite(yellow,  LOW);
25delay(500);
26
27  digitalWrite(yellow, HIGH);
28delay(1000);
29  digitalWrite(yellow,  LOW);
30delay(500);
31  
32  digitalWrite(yellow, HIGH);
33delay(1000);
34  digitalWrite(yellow, LOW);
35delay(500);
36  
37  digitalWrite(yellow, HIGH);
38delay(1000);
39  digitalWrite(yellow, LOW);
40delay(500);
41  
42digitalWrite(green, HIGH);
43delay(20000);
44digitalWrite(green,  LOW);
45//  
46digitalWrite(yellow, HIGH);
47delay(1000);
48  digitalWrite(yellow,  LOW);
49delay(500);
50
51  digitalWrite(yellow, HIGH);
52delay(1000);
53  digitalWrite(yellow,  LOW);
54delay(500);
55
56  digitalWrite(yellow, HIGH);
57delay(1000);  
58  digitalWrite(yellow, LOW);
59delay(500);
60  
61  digitalWrite(yellow, HIGH);
62delay(1000);
63  digitalWrite(yellow, LOW);
64delay(500);
65  
66  digitalWrite(yellow, HIGH);
67delay(1000);
68  digitalWrite(yellow, LOW);
69delay(500);
70  
71  
72}
