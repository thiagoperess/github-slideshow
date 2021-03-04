1 Entendo o sistema de permissões

No Linux, as permissões são definidas em três atributos: leitura, gravação e execução (no caso de arquivos) ou listagem do conteúdo (no caso das pastas). São representados, respectivamente pelas letras r (read), w (write), x (execute).

Acesso aos arquivos - "Beautiful is better than ugly."

Neste sistema, o acesso aos arquivos se dá por donos, grupos e usuários. Se usarmos o comando ls -l veremos as permissões de acesso:

drwxr-xr– root root teste

O primeiro root indica o nome do dono do arquivo.

O segundo root indica o nome do grupo que o arquivo pertence.

A palavra teste indica o nome da pasta.

A primeira letra diz qual é o tipo do arquivo. Da segunda a quarta letra (rwx) dizem qual é a permissão de acesso ao dono do arquivo. Da quinta a sétima letra (r-x) diz qual é a permissão de acesso ao grupo do arquivo. Da oitava a décima letra (r–) diz qual é a permissão de acesso para os outros usuários. 


