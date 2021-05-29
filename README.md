# KP
Kriptovanje podataka je realizovano u vise koraka.
Prvi korak predstavlja operaciju sabiranja/oduzimanja. Kljucno je to da se posmatra deljivost broja i da se broj kojim se sabira svaki put menja. Ukoliko je broj deljiv sa dva sabira se prvobitno sa brojem 3, ukoliko se u nekom sledecem kriptovanju javi broj takodje deljiv sa dva on se sabira sa 6, a sledeci put sa 9. Dakle krug sabirackih brojeva predstavljaju brojevi 3, 6 i 9. Slican postupak vazi i za brojeve deljive sa 3, 5 i 7. Ukoliko je broj deljiv sa 3, krug sabiranja je 3, 5, 7 i 9. Ukoliko je deljiv sa 5, krug je oduzimacki i brojevi koji se oduzimaju su  1, 2 i 3. Kod brojeva deljivih sa 7 sabiracki krug je 3, 6 i 9.
Drugi korak takodje predstavlja operaciju oduzimanja. Ukoliko je broj paran smanjuje se za 7, ukoliko je neparan za 6.
Treci korak predstavlja kombinaciju multiplikacije, sabiranja i oduzimanja. Broj se mnozi sa 2, dodaje mu se 10 i oduzima 1.
Cetvrti korak je ponovljeni prvi korak.
Peti korak, ujedno i poslednji korak, predstavlja operaciju siftovanja. Broj se siftuje za 1 bit udesno. 
Dobijeni broj predstavlja kriptovani pocetni broj.

Data encryption is realized in several steps.
The first step is the addition / subtraction operation. The key is to look at the divisibility of the number and to change the number by which it is added each time. If the number is divisible by two, it is initially added to the number 3, if in some subsequent encryption a number also divisible by two appears, it is added to 6, and the next time to 9. So the circle of addition numbers is represented by the numbers 3, 6 and 9. Similar the procedure also applies to numbers divisible by 3, 5 and 7. If the number is divisible by 3, the addition circle is 3, 5, 7 and 9. If it is divisible by 5, the circle is subtractive and the numbers to be subtracted are 1, 2 and 3. For numbers divisible by 7, the addition circle is 3, 6 and 9.
The second step is also a subtraction operation. If the number is even it decreases by 7, if it is odd by 6.
The third step is a combination of multiplication, addition and subtraction. The number is multiplied by 2, 10 is added to it and 1 is subtracted.
The fourth step is a repeated first step.
The fifth step, as well as the last step, is the shifting operation. The number is shifted by 1 bit to the right.
The resulting number represents the encrypted initial number.
