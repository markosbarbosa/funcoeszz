## Funções ZZ

Funções ZZ é uma coletânea com mais de 170 miniaplicativos de utilidades diversas, prontos para serem usados na linha de comando de sistemas tipo UNIX (Linux, BSD, Cygwin, Mac OS X, entre outros).

- Website: http://funcoeszz.net
- GitHub: https://github.com/funcoeszz/funcoeszz
- Grupo: http://br.groups.yahoo.com/group/zztabtab/
- Twitter: https://twitter.com/Funcoes_ZZ


## Lista de colaboradores

https://github.com/funcoeszz/funcoeszz/contributors


## Como contribuir

Forka nóis e pulla! :)

https://github.com/funcoeszz/funcoeszz/blob/master/CONTRIBUTING.md


## Instalação das Funções ZZ (versão de desenvolvimento)

Baixe o repositório para sua máquina:

    $ git clone git://github.com/funcoeszz/funcoeszz.git ~/funcoeszz
    $ cd ~/funcoeszz

Rode o comando seguinte para adicionar o carregamento das Funções ZZ no final de seu `~/.bashrc`:

    $ ./funcoeszz zzzz --bashrc
    Feito!
    As Funções ZZ foram instaladas no /Users/aurelio/.bashrc

Confira que as linhas foram adicionadas, e perceba que o PATH atual do script fica na variável `$ZZPATH`.

    $ tail -4 ~/.bashrc
    # Instalacao das Funcoes ZZ (www.funcoeszz.net)
    export ZZOFF=""  # desligue funcoes indesejadas
    export ZZPATH="/Users/aurelio/funcoeszz/funcoeszz"  # script
    source "$ZZPATH"

Você precisa adicionar "na mão" mais uma linha lá no `~/.bashrc`, antes do comando `source`, para indicar onde está a pasta com as funções:

    export ZZDIR="/Users/aurelio/funcoeszz/zz"

Agora sim, você pode usar as Funções ZZ em toda a sua glória. Abra um novo terminal e divirta-se!

    $ zzcalcula 10+5
    15
    
    $ zzbissexto
    2012 é bissexto
    
    $ zzmaiusculas tá funcionando
    TÁ FUNCIONANDO

Quando quiser atualizar os arquivos para a versão mais recente, basta um `git pull`.
