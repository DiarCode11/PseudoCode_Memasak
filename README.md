## TUTORIAL MEMASAK MIE SEDAAP GORENG

Berikut adalah pseudocode untuk memasak mie sedaap goreng ala Gede Sudiartika :v

```bash
# Algoritma Memasak Mie Sedaap Goreng

Declare:
GET mie_sedaap_goreng
GET air
GET panci
GET kompor
GET mangkok
GET sendok
GET pisau
GET penyaringan

Algorithm:
- mie, bumbu = SEPARATE(mie_sedaap_goreng)
- PUT mie, bumbu INTO mangkok
- PUT panci INTO kompor
- PUT air INTO panci
- TURN_ON kompor
- IF air = panas:
    - INSERT mie INTO panci
    - IF mie = matang:
        - MOVE mie TO penyaringan
        - MOVE mie TO mangkok
- ELSE :
    - WAIT UNTIL air = panas
- ENDIF
- OPEN bumbu WITH pisau
- PUT bumbu INTO mangkok
- MIX(mie, bumbu) 
- SERVE
End Algorithm



```


