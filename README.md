# php_23

## Primeiro commit 310123
## Passo a Passo 
    1- Verificar se estamos dentro do ubuntu
    2- File : open folder 
    2.1- Apaga conteudo 
    2.2- Informar o caminho: /var/www/html
    2.3- Abre esta pasta com enter ou clicando em html 
    3- Terinal : novo terminal 
    4- Git clone LINK_DO_REPOSITORIO (github)
    5- Informar o caminho /var/www/html/php_23
    5.1- Abre esta pasta com enter ou clicando em html 
    6- Configurar o git (git config --global user.name "" e git user email)
    7- Verificar se i apache esta rodando/executando
    7.1- Acessar navegador com localhost ou 127.0.0.1 (deve aparecer a configuração inicial)
    7.2- Se der erro consultar: sudo service apache2 status (tem que aparecer apache is running)
    7.3- sudo service apache2 start
    7.4- Executar novamente os passos 7.1 e 7.2

## Para salvar no Github
    
    1- git add . (todos os arquivos ou especificar os nomes, ex: git add index.php)
    2- git commit -m "descrever o que foi feito"
    3- git push 
    4- verificar no github se ficou salvo 

## Para alternar  (merge)
        1- git add . (apos as alteraçoes)
        2- git commit -m "" nomear as alterações 
        3- git push 
        4- git checkout NOME_BRANCH
        5- git pull (obter as atualizacoes)
        6- git merge NOME_BRANCH_DA_TRAZER_MUDANCAS
        Ex: 
            Estamos no branch "develop" e queremos levar as mudanças para main
            1- git checkout main 
            2- git pull (main)
            3- git merge "develop"
            4- resolve conflitos se houver
            4.1- com conflito: git add . e git commit -m "...."
            4.2- sem conflito: gir merge e git push
            5- git push

            Estamos no branch "master/main" e queremos levar as mudanças para a develop
            1- git checkout develop
            2- git pull (develop)
            3- git merge "main"
            4- resolve conflitos se houver
            4.1- com conflito: git add . e git commit -m "...."
            4.2- sem conflito: gir merge e git push
            5- git push

    
## Criar Tabelas    
 

    1.id / codigo PK (Primary Key)

    3.user_status
    4.user_fullname
    5.user_name
    6.user_pass
    7.user_mail
    8.user_rank

    9.user_departament FK (chave estrangeira - Foreing Key) = PK de outra tabela

    Dados Tabela de Departamentos:
    1.department_id PK
    2.department_name


    10.alt_who (mod_who)
    11.alt_when - NOK (mod_when)
    12.log_first - NOK
    13.log_last NOK 

   
    Dados Tabela de Produtos:
    1.product_id PK
    2.product_status 0 or 1
    3.product_type
    4.product_cost
    5.product_price
    6.product_profit
    7.product_seekage
    8.product_start


   


   ## Observações Tabelas  

    1.a PK sempre sera tinyint e a unica que sera auto incremento
    2.





        
        

