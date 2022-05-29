
![logo.infrapatch.com](https://logo.infrapatch.com/1/cover.png)

# [infrapatch.com](https://www.infrapatch.com/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/infra-patch/bash/edit/main/DOCS/MENU.md) 

+ [Strona informacyjna: www.infrapatch.com](https://www.infrapatch.com/)
+ [Dokumentacja - docs.infrapatch.com](https://docs.infrapatch.com/)
+ [Logotyp: logo.infrapatch.com](https://logo.infrapatch.com/)
+ [Pryzkłady - examples.infrapatch.com](http://examples.infrapatch.com)

+ [LICENSE](../LICENSE)



## About [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/infra-patch/bash/edit/main/DOCS/ABOUT.md)

infrapatch służy do naprawiania niedziałających elementów infrastruktury
wedle schematu dopasoanego do typu awarii czy usterki.




często ludki z IT mają problem z ogarnięciem certyfikatu

sam mam tysiące różnych stron i stronek

trudno mi samemu każdą stronę poprawiać, jak się coś sypnie

to są proste rzeczy, typu zmiana nameserwera
rekordu w DNS
Certyfikat SSL
przekierowanie...

ale trzeba się zalogować czasem na kilka platform i poklikać a to kosztuje czas...


braku eksperta w firmie odnośnie bezpieczeństwa i związanym z tym zapotrzebowaniem na dorywcze zlecenia lub stały outsourcing

głównie na bug-ach , chcę oferować możliwość naprawiania jakiś błędów, niezależnie od platformy, wówczas nie muszę nawet z klientem rozmawiać, pojawia się błąd, naprawiam

a już moja głowa, czy będę siedział godzinę, czy skrypt ogarnie to w minutę


Przede wszystkim sprawdź aktywne połączenia:
netstat -utnp
Opcja p wyświetla dodatkowo pid procesu. (zaznaczyłem to strzałeczką na screenie)
Wystarczy teraz polecenie kill+<numer procesu> i intruz wyrzucony.
Następnie odcinamy intruza za pomocą firewalla:
firewall-cmd --permanent --zone=drop --add-source=xx.xx.xx.xx
"Iksy" to naturalnie, adres IP.
Teraz zabezpieczamy logi i sprawdzamy co się działo.
To jest jednak prosty scenariusz.
Gdy szkody są większe i musimy działać natychmiast, użyj polecenia:
firewall-cmd --panic-on
Odcinasz wtedy serwer od sieci. Całkowicie. Również Twoja sesja SSH przedpadnie.
Wyłączenie trybu paniki:
firewall-cmd --panic-off
Ale to dalej nie jest wszystko. Są jeszcze systemy SIEM, które mogą wykonać pracę za nas. Przykładowo, darmowy system WAZUH, sam wykryje atak i usunie intruza.
O tym jednak jutro w moim newsletterze. Zapowiada się interesująco. Będzie sporo o kluczowych narzędziach i systemach do ochrony serwerów Linux. Pokażę Ci, co musisz uruchomić w swojej sieci. Jeżeli jeszcze nie dołączyłeś do ponad 5000 specjalistów IT, śledzących mój newsletter to link do zapisu zostawię Ci w komentarzu.


"Trwa postępowanie wyjaśniające [REGISTERED, ze statusem clientHold/serverHold]"


Typ projektu infrastruktury
dane

DETEKCJA poprzez listę/mapę infrastruktury

infrapatch_website.csv

    TYP,VALUE,STATUS_HTTP
    DOMAIN,www.infrapatch.com


Przetwarzanie za pomocą ApiMacro
[apimacro/examples: Examples of usage the apimacro's](https://github.com/apimacro/examples)
[apimacro/bash: bash macro builder based on CSV data format and Command with bash scripts](https://github.com/apimacro/bash)



## TODO [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/infra-patch/bash/edit/main/DOCS/TODO.md)


echo "UPDATE: infraMonit.com"
echo "UPDATE: grabWhois.com"
echo "UPDATE: ApiPong.com"
echo "UPDATE: AirScanning.com"
echo "UPDATE: MultiSiteMap.com"


install
https://github.com/infra-patch/ultimate-nmap-parser

skanuje hosty
git clone https://github.com/desecsecurity/parsing_html_bash
./parsing_html.sh www.google.com


+ skrypty do detekcji
+ skrypty do naprawy
+ schematy naprawy / template w zalezności od sytuacji





Na początku współpraca z tymi co mają znane panele jak WHMCS
gdzie można przez API uzyskać hasło do panelu i zmieniać:
+ NS,
+ rekordy DNS
+ zawartość strony
+ konfiguracje serwera

+ załadować projekty:
+ WHOISarch
+ letWHOIS
+ WebPageShot:
    + zrzut ekranu
    + text
    + html
    + md
+ MultiSiteMap
    + tworzeniemapy
+ Inframonit.com
    + szukanie stron do naprawy
    + detekcja uszkodzeń
+ infrapatch:
    + naprawianie niedziałających, wedle schematu
+ monit.page
+ alerts.pl

---

+ [edit](https://github.com/infra-patch/bash/edit/main/README.md)
+ [infra-patch/bash](https://github.com/infra-patch/bash)
