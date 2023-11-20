1- Inicializado git com o comando: ```git init```

2- Inicializado git flow com o comando : ```git flow init```

3- Inicializado uma branch de feature com o comando: ```git flow feature start welcome```

4- Finalizado a branch de feature com o comando: ```git flow feature finish welcome```

    
________________________________
GPG

1- gpg --list-secret-keys --keyid-form LONG (verificar se existe a chave)

2- gpg --full-generate-key (gerar chave)

3- gpg --armor --export-secret-keys 3B037003A0818872 | gpg --import (exportar chave)

4- gpgconf --kill gpg-agent

5 - git config --global commit.gpgSign true

6-  git config --global gpg.program "C:\Program Files (x86)\GnuPG\bin\gpg.exe"

7- git config user.signingkey 3B037003A0818872
  
8- git config --global user.signingkey 35F5FFB2
