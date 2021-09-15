# Desafio Maxxsoft

Implemente um sistema que atenda os seguintes itens abaixo:

## back-end
**1 - O sistema deverá ter um serviço back-end restfull utilizando spring-boot:**
 
**1.2 - O sistema deverá ter um end-point para receber dados relacionados ao cadastro de clientes, sendo eles:**

    *Nome;
	*Telefone;
	*E-mail;
	*Endereço;
	*CPF/CNPJ;
	*status(ATIVO/INATIVO);

_Todos os campos precedidos de * são obrigatórios_

**1.2.1 - Validações:**

    O sistema não deverá aceitar ser informado um e-mail inválido;
    Os agendamentos podem ser realizados tanto para pessoa física, como, para pessoa jurídica. Com base nisso garanta que o sistema não aceite CPF ou CNPJ inválido;


###### Sugestão para end-point: "/clientes"

**1.3 - O serviço deverá ter um end-point para receber dados relacionados ao agendamento do cliente, sendo eles:**
    
    *cliente
	*data
	*observação

_Todos os campos precedidos de * são obrigatórios_

**1.3.1 Validações:**

     O sistema não deve permitir realizar um agendamento sem informar um cliente válido;

###### Sugestão para end-point: "/agendamentos"

## front-end     

**2 - O sistema deverá ter uma interface web implementada em Angular que consuma a API do serviço anteriormente descrito:**

**2.1 - Telas necessárias:**
    
    Tela para manutenção de clientes cadastrados (CRUD básico);
	Tela para realizar o agendamento do cliente previamente cadastrado;

## Observações

Sinta-se a vontade para realizar a implementação dos itens acima. Existe uma série de pré-requisitos que podem ser adicionados, porém, não foram especificados e fica a seu critério identificar e implementar, caso julgue necessário.

Por exemplo: Não é obrigatório realizar a persistência desses dados em um base dados (pode trabalhar com tudo em memória). É claro que, caso venha a implementar uma persistência de dados isso será um diferencial;


## ATENÇÃO

**Para a devida avaliação desse exercício, realize o armazenamento da implementação em um repositório público no github;**

**Será avaliado apenas se o repositório for informado até a data e hora previamente informada;**

**Qualquer commit posterior a data e hora limite para entrega será desconsiderado durante a avaliação**
