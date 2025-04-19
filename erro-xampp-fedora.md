Caso ocorra um erro e parte da mensagem contiver: "into server: libnsl.so.1: cannot open shared object file: No such file or directory", é porque falta um biblioteca no Fedora.

Executar comando:

```
sudo dnf install libnsl
```

Após isso, deverá ser possível executar o Xampp na sua máquina.
