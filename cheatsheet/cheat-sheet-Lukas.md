# Cheat sheets en checklists

> Student: Lukas Jacobs

## Basiscommando's

| Taak                                                   | Commando                         |
| :----------------------------------------------------- | :------------------------------- |
| Bekijk IP-adressen van alle netwerkadapters            | `ip a`                           |
| Bekijk de status van een service                       | `systemctl status SERVICE`       |
| Start een service                                      | `sudo systemctl start SERVICE`   |
| Stop een service                                       | `sudo systemctl stop SERVICE`    |
| Herstart een service                                   | `sudo systemctl restart SERVICE` |
| Update de package repositories (Ubuntu & Debian based) | `sudo apt update`                |
| Installeer een package (Ubuntu & Debian based)         | `sudo apt install PACKAGE`       |

## Git Commando's

Simpele git workflow voor projecten met een enkele branch en zonder contributors.

| Task                                                               | Command                   |
| :----------------------------------------------------------------- | :------------------------ |
| Status van het huidige project                                     | `git status`              |
| Selecteer te committen bestanden                                   | `git add FILE...`         |
| Selecteerd de hele repository                                      | `git add -A    `          |  
| Commit alle wijzigingen naar de lokale repository                  | `git commit -m 'MESSAGE'` |
| Push lokale wijzigingen naar de remote repository                  | `git push`                |
| Haal alle wijzigingen van de remote repository binnen in de lokale | `git pull`                |
| Defineert expliciet de bron bij het pullen en pushen               | `git pull/push origin`    |
| Maakt een folder aan in de branch/folder                           | `mkdir NAME`              |
| Print tekst op een gegeven output                                  | `echo "...."`             |

## Checklist netwerkconfiguratie

1. Is het IP-adres correct? `ip a`
2. Is de router/default gateway correct? `ip r -n`
3. Is een DNS-server ingesteld? `cat /etc/resolv.conf`


## Opdracht 1: gebruikte commands 

|Task                                                                 |Command                     |
|:--------------------------------------------------------------------|:---------------------------|
|Digitale handtekeningen uitzetten voor scripts te kunnen uitvoeren   |`Set-ExecutionPolicyBypass -Scope rocess`                                                                                     |
|change directory                                                     |`cd`                        |
|Een lijst tonen van de software die nu geïnstalleerd is via WinGet   |`winget list`               |
|zoekt pakketten via de console                                       |`winget search`             |
|installeerd een pakket                                               |`winget install (-e --id)`  |
|geinstalleerd pakket verwijderen                                     |`winget uninstall`          |
|pin aanmaken en verwijderen                                          |`winget pin add/remove`     |



