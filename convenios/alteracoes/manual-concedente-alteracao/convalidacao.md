# Convalidação

Em regra, apenas convênios vigentes podem ser aditados. Nessa perspectiva, em princípio o SIGCON-SAÍDA não permite a criação de termos aditivos e prorrogações de ofício de convênios vencidos. Contudo, o concedente pode verificar, no caso concreto, a necessidade de prorrogar e/ou alterar o convênio mesmo após o término da vigência, convalidando os atos praticados desde o período de encerramento da vigência do convênio até o momento do ajuste de prorrogação. Para viabilizar esse ato, foi desenvolvida no SIGCON- SAÍDA a ferramenta de convalidação



A convalidação deve ser cadastrada pelo usuário com o perfil de encaminhador, e só estará habilitada se o convênio estiver com a vigência encerrada

![](../../../.gitbook/assets/image%20%28170%29%20%281%29.png)



![](../../../.gitbook/assets/image%20%289%29.png)

#### EXEMPLO PARA AJUDAR A COMPREENSÃO

A título de exemplo, suponhamos que a vigência de um convênio expirou no dia 08/03/2017, que o concedente verificou no dia 05/03/2018 a necessidade de prorrogar sua vigência até o dia 31/12/2018, e que o usuário com o perfil de “Encaminhador” responsável pelo cadastro da convalidação” considerou que o processo de prorrogação de vigência do convênio será concluído em aproximadamente em 25 dias. Um erro comum dos usuários é preencher no campo “N° Dias” o período correspondente entre a data atual \(05/03/2018\) e a data para a qual a vigência será prorrogada \(31/12/2018\) – 301 dias. O que aconteceria, nesse caso, é que a data final para o cadastro da prorrogação de vigência ficaria anterior à data corrente, de modo que as opções de cadastro de alterações e de prorrogações de ofício continuariam desabilitadas

![](../../../.gitbook/assets/image%20%28152%29.png)

O correto seria preencher neste campo o período entre a data em que a vigência expirou \(08/03/2017\) e a data até a qual a opção de cadastro da prorrogação de vigência deverá ficar habilitada, mesmo que convênio esteja vencido \(05/03/2018 + 25 dias = 30/03/2018\) – 387 dias

Após salvas as informações da convalidação, a convalidação é exibida na tabela “Lista de Convalidações Cadastradas”. Além de cadastrar a convalidação, o usuário com o perfil de “Encaminhador” também deverá realizar a assinatura da convalidação e em seguida encaminhá-la para que o ordenador de despesas também a assine

![](../../../.gitbook/assets/image%20%2823%29.png)

Finalmente, após a assinatura do ordenador de despesas, a convalidação assume o status de “Aprovada”, habilitando o cadastro de alterações no convênio



![](../../../.gitbook/assets/image%20%2879%29.png)

*  **Aguardando Convalidação**: o usuário com o perfil de encaminhador deve assinar a convalidação.
* **Convalidação Registrada**: o usuário com o perfil de encaminhador deve enviar a convalidação para o ordenador de despesas
* **Aguardando Aprovação**: o usuário com o perfil de Ordenador de Despesas deve assinar a convalidação
* **Aprovada**: a convalidação foi assinada pelo ordenador de despesas e habilitará o cadastro de alterações no convênio mesmo que ele esteja encerrado, até a data final definida pelo usuário. 
* **Finalizada**: a data final da convalidação é inferior à data corrente, as opções de cadastro de alterações no convênio não serão habilitadas caso este ainda permaneça encerrado
