# Sõidutulemuste töötluse skript

See skript võtab sisse sõidutulemiste faili ja töötleb seda, et väljastada sõidutulemuste ülevaade. Skript sorteerib sõidutulemised, arvutab kokku sõiduaegade summad, leidmaks kiireima ringiaja ja sektorite parimad ajad. Lisaks kuvatakse vigased ringid ning erinevused esimese kohaga.

## Kasutamine


1. Lisa sõidutulemiste faili (`Result.txt`) sama kausta, kus see skript asub.
2. Käivita skript käsureal järgmise käsu abil:
3. Skript väljastab sõidutulemuste ülevaate konsooli.

## Sõidutulemiste faili vorming

Sõidutulemiste fail (`Result.txt`) peab olema CSV-vormingus, kus veerud on eraldatud semikoolonitega. Faili esimeses reas peaks olema veergude nimed. Iga järgmine rida esindab ühte sõidutulemust.

Veerud:
1. Ringi number
2. Sõitja nimi
3. Ringi aeg (sekundites)
4. Sektori 1 aeg (sekundites)
5. Sektori 2 aeg (sekundites)
6. Sektori 3 aeg (sekundites)
7. Vigane ring (True/False)



