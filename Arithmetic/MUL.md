# 8 bit Multiplication

| Address | Mnemonics |
| --------|-----------|
3000 | MOV A,#04
3002 | MOV B,#02
3005| MUL A,B
3007|MOV DPTR,#4500
300A|MOVX @DPTR,A
300B|SJMP 300B

#### OUTPUT

| Address | DATA |
| --------|-----------|
4500 | O8
