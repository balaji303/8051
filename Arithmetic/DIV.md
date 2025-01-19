# 8 bit Division

| Address | Mnemonics |
| --------|-----------|
3000 | MOV A,#0B
3002 | MOV B,#03
3005| DIV A,B
3007|MOV DPTR,#4500
300A|MOVX @DPTR,A
300B|SJMP 300B

#### OUTPUT

| Address | DATA |
| --------|-----------|
4500 | O2