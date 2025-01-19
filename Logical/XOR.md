# 8 bit Logical XOR

| Address | Mnemonics |
| --------|-----------|
3000 | MOV A,#0A
3002 | MOV B,#02
3005| XRL A,B
3007|MOV DPTR,#4500
300A|MOVX @DPTR,A
300B|SJMP 300B

#### OUTPUT

| Address | DATA |
| --------|-----------|
4500 | O8

#### Truth Table

| x | y | xy |
|---|---|----|
0 | 0 | 0
0 | 1 | 1
1 | 0 | 1
1 | 1 | 0