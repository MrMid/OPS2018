# Raspberry Pi: Teplotní čidlo
Implementace domácího IoT teploměru s webovým rozhraním na Raspberry Pi

## Cíle projektu:
1) Nastudovat dokumentaci k vybranému teploměru
2) Vytvořit program na pravidelné čtení hodnot
3) Vytvořit výstup z programu, ke bude možno zjistit aktuální teplotu (např. webserver, Twitter API, e-mail, LED)

## Vybrané čidlo:
Původně jsme použili pro projekt jednoduché digitální teplotní čidlo, které jsme však v průběhu vývoje špatně zapojili, čímž jsme jej spálili. Proto jsme pořídili čidlo nové, a vzhledem k tomu, že máme zájem tento IoT teploměr dále používat pro monitorování nejen teploty, ale i vlhkosti, použili jsme nakonec čidlo DHT11.
Technická dokumentace k tomuto čidlu je obsažena v tomto repozitáři [zde](DHT11.pdf).

