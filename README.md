# Diagnostika-SuperVAG
Software na komunikaci s řídicími jednotkami v autě

Python project - Diagnostika - Základní komunikace s jednotkou


Python project - Diagnostika - Základní komunikace s jednotkou    1
Popis projektu    1
Části projektu    1


Popis projektu
Tento program slouží k tomu aby začal komunikovat s řídicí jednotkou. Pošle jí správné dotazy (např. pošli mi závady). Jednotka na to odpoví a pošle závady (např. hexadecimálně). Porgram rosparsuje message která mu přijde a uživateli čitelně zobrazí závady (podle dat která pošle jednotka si dohledá v tabulce ke kodu závady význam závady).

Začne se testovat na simulačních datech. Až bude fungovat tento krok začne se komunikovat se živou jednotkou.

Části projektu

GUI
MOCK (něco co bude vracet falešná/simulační data)
Knihovna funkcí pro komunikaci s jednotkou
Unit testy napsané na míru každé funkci s parametry.
tabulka / databáze která odpověď jednotky podle tabulky převede na čitelnou odpověď pro uživatele.

veškeré info o projektu včetně vývojového diagramu je na:

https://docs.google.com/document/d/1DhPxKlqQEMV6DQqfQ1kIARhJL8skA9-xKGnSl5jcpxc/edit#
