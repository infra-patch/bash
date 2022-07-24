
![logo.infrapatch.com](https://logo.infrapatch.com/1/cover.png)

# [Dokumentacja - docs.infrapatch.com](https://docs.infrapatch.com/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/infra-patch/docs/edit/main/DOCS/MENU.md) 

+ [Strona informacyjna: www.infrapatch.com](https://www.infrapatch.com/)
+ [Logotyp: logo.infrapatch.com](https://logo.infrapatch.com/)
+ [Przykłady - examples.infrapatch.com](http://examples.infrapatch.com)

+ [LICENSE](../LICENSE)



## About [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/infra-patch/docs/edit/main/ABOUT/ABOUT.md)

infrapatch służy do naprawiania niedziałających elementów infrastruktury
wedle schematu dopasowanego do typu awarii czy usterki.

### Jakie problemy można rozwiązać dzięki rozwiązaniu infrapatch?

#### Certyfikaty SSL
Częstym problemem dla firm utrzymujących własną domenę jest aktualizowanie certyfikatu SSL
Jest to tym trudniejsze im więcej stron www i subdomen musimy monitorować.

#### Rekordy NS domeny 
Problemy dotyczące ustawień rekordów domen, to często proste rzeczy, typu:
+ zmiana nameserwera
+ rekordu w DNS
+ przekierowanie...

Wszystko jest łatwiejsze, gdy posiada się jeden serwer i domenę u tego samego providera, gdzie
można uzyskać fachową pomoc supportu.

Wraz ze wzrostem organizacji i rozbudową infrastruktury, trudno wszystko ustawić w jednym panelu i u jednego usługodawcy.
Trzeba się zalogować na kilka platform i wiedzieć co jak ustawić a to kosztuje czas...

#### Outsourcing DevOps

Zapewniamy równiez specjalistę d/s bezpieczeństwa i związanym z tym zapotrzebowaniem na dorywcze zlecenia lub stały outsourcing
głównie na błedach infrastryuktury



## Korzyści
Możliwość naprawiania błędów, niezależnie od platformy, w sposób pół automatyczny
nie potrzebny jest kontakt z klientem,
wystarczy wykrycie i akceptacja, wyrażenie chęci naprawy.
pojawia się błąd, naprawiamy.





## Contribution [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/flatedit/examples/edit/main/DOCS/CONTRIBUTION.md)

### Update

apifork
```bash
curl https://raw.githubusercontent.com/apifork/bash/main/apifork.sh -o apifork
./apifork update
```

apipackage
```bash
curl https://raw.githubusercontent.com/apipackage/bash/main/apipackage.sh -o apipackage
./apipackage update
```

### Remove


apifork
```bash
./apifork remove
```

### Install

Install dependencies after created project
```bash
curl https://raw.githubusercontent.com/apifork/bash/main/apifork.sh -o apifork
echo "https://github.com/flatedit/bash.git flatedit" > "apifork.dev.txt"
./apifork install apifork.dev.txt
```


Install package list after created project
```bash
curl https://raw.githubusercontent.com/apipackage/bash/main/apipackage.sh -o apipackage
echo "https://github.com/letwhois/bash apidsl/apidsl/bash letwhois" >> "apipackage.txt"
./apipackage install
```

Edit documentation with flatedit
```bash
echo '#!/bin/bash' > 'readme'
echo './flatedit/readme.sh readme.txt' >> 'readme'
echo "./DOCS/MENU.md" >> "readme.txt"
echo "./DOCS/ABOUT.md" >> "readme.txt"
echo "./DOCS/FOOT.md" >> "readme.txt"
```

### Update documentation

```bash
 ./readme
```

### Config project file

The config file: **.apifork** can be another, e.g. **apifork.txt**

Just change the first line in  **.apifork** on **apifork.txt**
```bash
apifork.txt
```


### install

[minsungson/GitHub-cURL: A guide to installing files from GitHub repos in terminal using cURL](https://github.com/minsungson/GitHub-cURL)

```bash
./apifork install
```
OR

```bash
./apifork
```

### update

```bash
./apifork update
```


### remove

```bash
./apifork remove
```


## TODO [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/infra-patch/docs/edit/main/DOCS/TODO.md)


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



---

+ [infra-patch/docs](https://github.com/infra-patch/docs)
