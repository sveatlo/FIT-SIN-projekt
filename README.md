# SINHome
25/30b

# Inštalácia
Je potreba manuálne stiahnuť a nainštalovať:
* Home I/O
* docker

# Spustenie
Pre úspešnú demonštráciu projektu je treba
1. Otvoriť Home I/O a načítať uloženú domácnosť z priloženého XML súboru
2. Otvoriť Connect I/O a spustiť SINHome.CONNECTIO
3. spustit Node-RED (docker `docker run -p 1880:1880 -v ${PWD}/nodered-data:/data --name sin-home-nodered nodered/node-red`)
4. v Node-RED pridať pomocou Pallette modbus a dashboard balíček
5. Importovať `nodered-flow.json`
6. Spustiť deployment
7. ???
8. profit
