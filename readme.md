```
OP_OVER OP_TOALTSTACK OP_SWAP 1 OP_ADD OP_TOALTSTACK
OP_OVER OP_TOALTSTACK OP_SWAP 2 OP_ADD OP_TOALTSTACK
OP_OVER OP_TOALTSTACK OP_SWAP 3 OP_ADD OP_TOALTSTACK
OP_OVER OP_TOALTSTACK OP_SWAP 4 OP_ADD OP_TOALTSTACK
OP_OVER OP_TOALTSTACK OP_SWAP 5 OP_ADD OP_TOALTSTACK
OP_OVER OP_TOALTSTACK OP_SWAP 6 OP_ADD OP_TOALTSTACK
OP_OVER OP_TOALTSTACK OP_SWAP 7 OP_ADD OP_TOALTSTACK
OP_OVER OP_TOALTSTACK OP_SWAP 8 OP_ADD OP_TOALTSTACK
OP_OVER OP_TOALTSTACK OP_SWAP 9 OP_ADD OP_TOALTSTACK

OP_DUP

OP_IF
    OP_FROMALTSTACK
    OP_DROP
OP_ENDIF

OP_FROMALTSTACK OP_FROMALTSTACK OP_DROP
OP_FROMALTSTACK OP_FROMALTSTACK OP_DROP
OP_FROMALTSTACK OP_FROMALTSTACK OP_DROP
OP_FROMALTSTACK OP_FROMALTSTACK OP_DROP
OP_FROMALTSTACK OP_FROMALTSTACK OP_DROP
OP_FROMALTSTACK OP_FROMALTSTACK OP_DROP
OP_FROMALTSTACK OP_FROMALTSTACK OP_DROP
OP_FROMALTSTACK OP_FROMALTSTACK OP_DROP
OP_FROMALTSTACK

9 OP_ROLL

OP_NOTIF
    OP_FROMALTSTACK
    OP_DROP
OP_ENDIF
```
