# Explore a Base de Dados Azure para PostgreSQL

Neste exercício, você provisionará um recurso do Banco de Dados do Azure para PostgreSQL na sua assinatura do Azure.

Este laboratório levará aproximadamente **5** minutos para ser concluído.

## Antes que você comece

Você precisará de uma [assinatura do Azure](https://azure.microsoft.com/free) na qual tenha acesso de nível administrativo.

## Provisionar um recurso do Banco de Dados do Azure para servidores flexíveis do PostgreSQL

Neste exercício, você provisionará um recurso do Banco de Dados do Azure para PostgreSQL.

1.  No portal do Azure, selecione **＋ Criar um recurso** no canto superior esquerdo e procure _Banco de Dados do Azure para PostgreSQL_ . Em seguida, na página resultante **do Banco de Dados do Azure para PostgreSQL** , selecione **Criar** .
    
2.  Revise as opções do Banco de Dados do Azure para PostgreSQL disponíveis e, em seguida, no bloco **Banco de Dados do Azure para PostgreSQL** , selecione **Servidor flexível (recomendado)** e, em seguida , **Crie** .
    
    [![Captura de tela do Banco de Dados do Azure para opções de implantação do PostgreSQL](https://microsoftlearning.github.io/DP-900T00A-Azure-Data-Fundamentals/Instructions/Labs/images/postgresql-options.png)](https://microsoftlearning.github.io/DP-900T00A-Azure-Data-Fundamentals/Instructions/Labs/images/postgresql-options.png)
    
3.  Insira os seguintes valores na página **Criar Banco de Dados SQL** :
    -   **Assinatura** : selecione sua assinatura do Azure.
    -   **Grupo de recursos** : crie um novo grupo de recursos com um nome de sua escolha.
    -   **Nome do servidor** : insira um nome exclusivo.
    -   **Região** : Selecione uma região perto de você.
    -   **Versão PostgreSQL** : deixe inalterado.
    -   **Tipo de carga de trabalho** : Selecione **Desenvolvimento** .
    -   **Computação + armazenamento** : deixe inalterado.
    -   **Zona de disponibilidade** : Deixe inalterado.
    -   **Habilitar alta disponibilidade** : deixe inalterado.
    -   **Nome de usuário do administrador** : seu nome.
    -   **Senha** e **Confirmar senha** : Uma senha adequadamente complexa.
4.  Selecione **Próximo: Rede** .
    
5.  Em **Regras de firewall** , selecione **+ Adicionar endereço IP do cliente atual** .
    
6.  Selecione **Review + Create** e selecione **Criar** para criar seu banco de dados Azure PostgreSQL.
    
7.  Aguarde a conclusão da implantação. Em seguida, acesse o recurso que foi implantado, que deverá ficar assim:
    
    [![Captura de tela do portal do Azure mostrando a página do Banco de Dados do Azure para PostgreSQL.](https://microsoftlearning.github.io/DP-900T00A-Azure-Data-Fundamentals/Instructions/Labs/images/postgresql-portal.png)](https://microsoftlearning.github.io/DP-900T00A-Azure-Data-Fundamentals/Instructions/Labs/images/postgresql-portal.png)
    
8.  Revise as opções para gerenciar seu recurso do Banco de Dados do Azure para PostgreSQL.

> **Dica** : Se tiver terminado de explorar o Banco de Dados do Azure para PostgreSQL, você poderá excluir o grupo de recursos criado neste exercício.
