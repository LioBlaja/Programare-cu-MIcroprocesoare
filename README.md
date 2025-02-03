# Programare-cu-Microprocesoare
Microsistem 8086

# Tema Proiectului: Microsistem cu Microprocesor 8086

## Structura Microsistemului:
1. **Unitate centrală**: Microprocesor 8086.
2. **Memorie EPROM**: 128 KB, utilizând circuite 27C512.
3. **Memorie SRAM**: 64 KB, utilizând circuite 62256.
4. **Interfaţă serială**: Circuitul 8251, plasat în zona:
   - 04D0H – 04D2H sau 05D0H – 05D2H, în funcţie de poziţia microcomutatorului S1.
5. **Interfaţă paralelă**: Circuitul 8255, plasat în zona:
   - 0250H – 0256H sau 0A50H – 0A56H, în funcţie de poziţia microcomutatorului S2.
6. **Minitastatură**: Cu 9 contacte.
7. **LED-uri**: 10 LED-uri.
8. **Modul de afişare cu 7 segmente**: 8 ranguri, cu maxim 8 caractere hexa simultan.
9. **Modul LCD**: Cu 2 linii a câte 16 caractere fiecare, cu interfaţă la alegerea studentului.

## Proiectarea cu Microprocesoare
Toate programele vor fi concepute în limbaj de asamblare și vor fi structurate sub formă de subrutine. Programele necesare sunt:

1. **Rutine de programare ale circuitelor 8251 și 8255.**
2. **Rutine de emisie/recepţie caracter pe interfaţa serială.**
3. **Rutina de emisie caracter pe interfaţa paralelă.**
4. **Rutina de scanare a minitastaturii.**
5. **Rutina de aprindere/stingere a unui LED.**
6. **Rutina de afişare a unui caracter hexa pe un rang cu segmente.**

### Structura rutinelor
- Intrări, secvenţe, ieşiri vor fi stabilite de fiecare student în funcție de cerințele specifice ale proiectului.
