# 8 bit Subtraction

| Address | Mnemonics |
| --------|-----------|
3000 | MOV A,#0C
3002 | MOV B,#02
3005| SUBB A,B
3007|MOV DPTR,#4500
300A|MOVX @DPTR,A
300B|SJMP 300B

#### OUTPUT

| Address | DATA |
| --------|-----------|
4500 | OA
