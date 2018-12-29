# Konfiguracja

W celu prawidłowej pracy w trakcie warsztatów potrzebujemy skonfigurować w kliencie git nazwę naszego użytkownika oraz jej adres email. Aby skonfigurować nazwę użytkownika wykonujemy polecenie:

```bash
git config --global user.name "MOJA-NAZWA-UŻYTKOWNIKA"
```

Konfiguracji adresu email dokomujemy za pomocą poniższej komendy:

```bash
git config --global user.email "MOJ-ADRES@EMAIL"
```

## Prework (2/3)

Po pomyślnej konfiguracji nazwy użytkownika i adresu email weryfikujemy ją następującymi dwoma poleceniami:

```bash
git config --global user.name
git config --global user.email
```

Wynik poleceń powinien wyglądać podobnie do poniższego:

##### ![](/assets/prework_02_config.png) 