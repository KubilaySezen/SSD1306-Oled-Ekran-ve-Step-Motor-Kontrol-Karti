# SSD1306-Oled-Ekran-ve-Step-Motor-Kontrol-Karti

Proteus 9.2 versiyonu ile çizilmiştir. Alt versiyon ile açamazsınız.

Atmega328 Mikrodenetleyicisi Kullanıldı.
Osc freq:16MHz





## PIN MAP


Komponet                         ->              Arduino pin map

### Roraty Encoder

 *Button->D4
 
 *Rotary_A->D2(INT0)
 
 *Rotary_B->D3(INT1)

### OLED0.69 inc SSD1306

 *Ekran_Scl->A5
 
 *Ekran_Sda->A4
 
 *Ekran_Reset->D8

### RG led

 *Red->D10
 
 *Green->D11

### Ledler

 *Led1->D0
 
 *Led2->D1

### A4988 Step motor Sürücü

NOT: Step, direction ve adım bölüm oranları iki sürücüdede ortak pinlerden setlenir.

 *Step->D9
 
 *DIR->D7
 
 *En1->D5
 
 *En2->D6

### Buttonlar

 *Button1->A0
 
 *Button2->A1





