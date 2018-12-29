# GitHub

Jednym z celi warsztatu jest pokazanie uczestnikom w jaki sposób publikować dokonane w projekcie zmiany aby były dostępne one dla innych członków zespołu. Do tego celu wykorzystamy darmowy portal [GitHub](https://github.com).

Na potrzeby warsztatu uczestnik musi założyć i zweryfikować swoje konto w portalu GitHub (instrukcja dostępna jest [tutaj](https://help.github.com/articles/signing-up-for-a-new-github-account/)).

## SSH

Po pomyślnym zweryfikowaniu konta w portalu GitHub należy skonfigurawać dostęp do portalu za pomocą [protokołu SSH](https://en.wikipedia.org/wiki/Secure_Shell). Pełna instrukcja jak tego dokonać dostępna jest w [dokumentacji GitHub](https://help.github.com/articles/connecting-to-github-with-ssh/).

## Prework (3/3)

Aby zweryfikować czy nasze połączenie za pomocą protokołu SSH zostało skonfigurowane poprawnie należy w wierszu poleceń wykonać następujące polecenie:

```bash
ssh -T git@github.com
```

Wynik polecenia powinien wyglądać podobnie do poniższego:

##### ![](/assets/prework_03_ssh.png) 