## Intel 8080 Emulator

My first emulation project, an intel 8080 emulator written in java.
___

Test used:
* TST8080.COM
* 8080PRE.COM
* 8080EXM.COM
* CPUTEST.COM

---

#### Output:

```
Test: TST8080.COM
START: 10:12:21
______________________________
MICROCOSM ASSOCIATES 8080/8085 CPU DIAGNOSTIC
 VERSION 1.0  (C) 1980

 CPU IS OPERATIONAL
______________________________
END:   10:12:21

***

Test: 8080PRE.COM
START: 10:12:21
______________________________
8080 Preliminary tests complete
______________________________
END:   10:12:21

***

Test: CPUTEST.COM
START: 10:12:21
______________________________

DIAGNOSTICS II V1.2 - CPU TEST
COPYRIGHT (C) 1981 - SUPERSOFT ASSOCIATES

ABCDEFGHIJKLMNOPQRSTUVWXYZ
CPU IS 8080/8085
BEGIN TIMING TEST
END TIMING TEST
CPU TESTS OK

______________________________
END:   10:12:30

***

Test: 8080EXM.COM
START: 10:12:30
______________________________
8080 instruction exerciser

dad <b,d,h,sp>................  PASS! crc is:14474ba6

aluop nn......................  PASS! crc is:9e922f9e

aluop <b,c,d,e,h,l,m,a>.......  PASS! crc is:cf762c86

<daa,cma,stc,cmc>.............  PASS! crc is:bb3f030c

<inr,dcr> a...................  PASS! crc is:adb6460e

<inr,dcr> b...................  PASS! crc is:83ed1345

<inx,dcx> b...................  PASS! crc is:f79287cd

<inr,dcr> c...................  PASS! crc is:e5f6721b

<inr,dcr> d...................  PASS! crc is:15b5579a

<inx,dcx> d...................  PASS! crc is:7f4e2501

<inr,dcr> e...................  PASS! crc is:cf2ab396

<inr,dcr> h...................  PASS! crc is:12b2952c

<inx,dcx> h...................  PASS! crc is:9f2b23c0

<inr,dcr> l...................  PASS! crc is:ff57d356

<inr,dcr> m...................  PASS! crc is:92e963bd

<inx,dcx> sp..................  PASS! crc is:d5702fab

lhld nnnn.....................  PASS! crc is:a9c3d5cb

shld nnnn.....................  PASS! crc is:e8864f26

lxi <b,d,h,sp>,nnnn...........  PASS! crc is:fcf46e12

ldax <b,d>....................  PASS! crc is:2b821d5f

mvi <b,c,d,e,h,l,m,a>,nn......  PASS! crc is:eaa72044

mov <bcdehla>,<bcdehla>.......  PASS! crc is:10b58cee

sta nnnn / lda nnnn...........  PASS! crc is:ed57af72

<rlc,rrc,ral,rar>.............  PASS! crc is:e0d89235

stax <b,d>....................  PASS! crc is:2b0471e9

Tests complete
______________________________
END:   10:22:06

***

```
