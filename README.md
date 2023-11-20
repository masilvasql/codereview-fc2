1- Inicializado git com o comando: ```git init```

2- Inicializado git flow com o comando : ```git flow init```

3- Inicializado uma branch de feature com o comando: ```git flow feature start welcome```

4- Finalizado a branch de feature com o comando: ```git flow feature finish welcome```

    
________________________________
GPG

1- gpg --list-secret-keys --keyid-form LONG (verificar se existe a chave)

2- gpg --full-generate-key (gerar chave)

3- gpg --armor --export 99C0DC47340E574C ```ID DA SUA CHAVE``` (exportar chave)

4- git config --global user.signingkey 99C0DC47340E574C ```ID DA SUA CHAVE``

5- export GPG_TTY=$(tty) (exportar tty)

6- git config --global commit.gpgsign true (configurar gpgsign)

7- git log --show-signature (verificar se a assinatura está funcionando)
  

  