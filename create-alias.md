# Criar um alias

1. Abra seu terminal.
2. Edite seu arquivo de configuração do shell (geralmente .bashrc ou .zshrc):

```
vi ~/.bashrc
```

3. Adicione a seguinte linha no final do arquivo:
 
 ```
 alias xampp='sudo /opt/lampp/manager-linux-x64.run'
 ```

4. Salve e feche.
 
 ```
ESC, :x, Enter
 ```

6. Recarregue o shell:
```
source ~/.bashrc
```

Agora, sempre que você digitar xampp, o gerenciador do XAMPP vai abrir.
