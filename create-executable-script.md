1. Crie um novo arquivo de script:

```
sudo vi /usr/local/bin/xampp
```

2. Cole o seguinte conteúdo:

```
#!/bin/bash
sudo /opt/lampp/manager-linux-x64.run
```

Salve e feche 
```
ESC, :x, Enter.
```

Torne o script executável:

```
sudo chmod +x /usr/local/bin/xampp
```

Agora, você pode simplesmente digitar xampp no terminal de qualquer lugar e ele vai abrir o gerenciador do XAMPP.
