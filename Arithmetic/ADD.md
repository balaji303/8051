# 8 bit addition

| Address | Mnemonics |
| --------|-----------|
3000 | MOV A,#0A
3002 | MOV B,#02
3005| ADDC A,B
3007|MOV DPTR,#4500
300A|MOVX @DPTR,A
300B|SJMP 300B

#### OUTPUT

| Address | DATA |
| --------|-----------|
4500 | OC
