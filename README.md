# Smoketest

Det här är ett test för att kolla så virtualbox och vagrant fungerar, kod exemplet är taget från [vagrant getting started](https://www.vagrantup.com/intro/getting-started/provisioning.html)

Börja med att clona(*ladda ner*) det här projektet till er dator

Öppna en terminal, gitbash, och gå till er *projektmapp*, `cd <your_path>`
Sedan hämtar ni projeket med
```
$ git clone https://github.com/bojohan/smoketest.git
```
Filerna laddades ner till en katalog *smoketest*, förflytta er till den katalogen
```
$ cd smoketest
```

Nu startar vi maskinen

```
$ vagrant up
```

När maskinen har laddat klart, förhoppningsvis fungerar det. Så öppna den här sidan i en webläsare [192.168.33.10](http://192.168.33.10)

Den innehåller ett väldigt kort meddelande, vill ni ändra på sidan, ändra i *index.html* som finns i den här katalogen och refresha sidan.

## Mera vagrant

Ni kan behöva lära er några fler vagrant kommandon exempelvis halt och destroy, hjälp hittar ni [här](https://www.vagrantup.com/intro/getting-started/teardown.html)

Ni har också en inbyggd hjälp om ni bara skriver vagant i terminalen

```
$ vagrant

```

Innan ni slutar kan ni stänga ner och ta bort servern.
