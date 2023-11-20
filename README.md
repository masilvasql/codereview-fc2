1- Inicializado git com o comando: ```git init```

2- Inicializado git flow com o comando : ```git flow init```

3- Inicializado uma branch de feature com o comando: ```git flow feature start welcome```

4- Finalizado a branch de feature com o comando: ```git flow feature finish welcome```


________________________________
GPG

1- gpg --list-secret-keys --keyid-form LONG (verificar se existe a chave)

2- gpg --full-generate-key (gerar chave)

3- gpg --armor --export ```ID DA SUA CHAVE``` (exportar chave)

4- git config --global user.signingkey ```ID DA SUA CHAVE``

5- export GPG_TTY=$(tty) (exportar tty)
6- git config --global commit.gpgsign true (configurar gpgsign)