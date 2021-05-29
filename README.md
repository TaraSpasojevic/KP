# broj-1
Kriptovanje podataka je realizovano u vise koraka.
Prvi korak predstavlja operaciju sabiranja/oduzimanja. Kljucno je to da se posmatra deljivost broja i da se broj kojim se sabira svaki put menja. Ukoliko je broj deljiv sa dva sabira se prvobitno sa brojem 3, ukoliko se u nekom sledecem kriptovanju javi broj takodje deljiv sa dva on se sabira sa 6, a sledeci put sa 9. Dakle krug sabirackih brojeva predstavljaju brojevi 3, 6 i 9. Slican postupak vazi i za brojeve deljive sa 3, 5 i 7. Ukoliko je broj deljiv sa 3, krug sabiranja je 3, 5, 7 i 9. Ukoliko je deljiv sa 5, krug je oduzimacki i brojevi koji se oduzimaju su  1, 2 i 3. Kod brojeva deljivih sa 7 sabiracki krug je 3, 6 i 9.
Drugi korak takodje predstavlja operaciju oduzimanja. Ukoliko je broj paran smanjuje se za 7, ukoliko je neparan za 6.
Treci korak predstavlja kombinaciju multiplikacije, sabiranja i oduzimanja. Broj se mnozi sa 2, dodaje mu se 10 i oduzima 1.
Cetvrti korak je ponovljeni prvi korak.
Peti korak, ujedno i poslednji korak, predstavlja operaciju siftovanja. Broj se siftuje za 1 bit udesno. 
Dobijeni broj predstavlja kriptovani pocetni broj.
