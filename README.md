# Resumo-do-lab

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

*Microsoft Azure* 

Localizando Serviços por Categoria (Aprendizado de como achar ferramentas no Azure e cuidados com as aplicações que estiverem em situação de "versão prévia",já que essas podem ser retiradas pela Microsoft sem avizo prévio.)

----------------------------------------------------------------------------------
* Beneficios da nuvem*
          
  - Alta disponibilidade
      observação:( por contrato, pode se ter quedas, que são prevista em como tempo de queda,e caso ocorra a queda da                   ferramenta a mais  desse prazo e dado um voucher para compensar a parada do sistema;
----------------------------------------------------------------------------------
   - Ecalabilidade e Elasticidade-

*Escalabilidade*

Refere a capacidade de ajustar recursos para atender a demanda ( esté recurso ele ajusta tanto para cima quanto para baixo com base no padrão inicial, ele sobe para atender a demanda e depois reduz;

 *Elasticidade*

E mais ajustavel quando se tem um salto repentino acentuado na demanda, os recursos são expandidos automaticamente ou manualmente, estes valores podem ser pré setados a partir de metas;

*Confiabilidade*

A confiabilidae do sistema ela se baseia em um designe descentralizado, desta forma a nuvem pode ter recursos implantandos em varias partes do mundo,( deve-se olhar as diretrizes de cada região para a aplicação).

----------------------------------------------------------------------------------
*Previsibilidade*

Confianção no desempenho ou no custo , ambas são influenciadas pelo Azure Well Architected Framework

----------------------------------------------------------------------------------     
Benefícios da nuvem

*Governaça*

-  Os dados e informações podem ser auditorados, conforme os padrões corporativos, e fornece estrategias de mitigação

*Gerenciabilidade*

-  um dos principais beneficios são as opções e capacidade de gerenciar a nuvem e escalar automaticamente a inplatação de recursos com base na necessidades.

  Tempo de inatividade (SLA)

![image](https://github.com/user-attachments/assets/ca3d3fe3-d74b-4aaf-b433-f2ce1cc568d2)

----------------------------------------------------------------------------------
*Tipos de serviço de nuvem*

 IaaS
 
Serviço de nuvem mais flexivel  (Mais acesso)

*Infra estrutura como serviço* 

-  Tendem a ser sevições que o cliente faz mais configurações. Exemplo Maquina Virtual;   

PaaS

Focado no desenvolvimento de aplitativos (Intermediario)

*Plataforma como serviço*

-  Fornece um ambiete para criação ,teste e a implatação de aplicativos sem focar no gerenciamento da infraestrutura subjacente      

 SaaS
 
 Modelo de preço de pagamento conforme o uso; (Menos acesso)
 
*Software como serviço*

 - SaAS e Software como serviço, e onde ficam armazenado os softwares,licenças e feito o gerenciamento com as permições;
 - A Aplicação já e existente;
 - O que define o que se vê estão relacionados ao licença;
   
----------------------------------------------------------------------------------




Modelo de Responsabilidade compartilhada

![image](https://github.com/user-attachments/assets/55b2ed85-075f-4a6c-b35a-1d5ca24936c4)

----------------------------------------------------------------------------------

Principais componentes do azure. 

Regiões

Abrangencia Global  em 60 regiões e 160 países.

Pares de regiões

Tem no minimo 300 milhas de separação entre os pares
Replicação automática para Alguns serviços
Recuperação de região priorida em caso de interrupção;

Região soberana

Atende as necessidades de segurança e conformidade das agencias federais,governos estaduais e locais e seus provedores de soluções. Existem poucos e EUA e um deles
esses serviços são operados pela 21vianet na china

----------------------------------------------------------------------------------

Grupo de recursos

São um local para alocar os recursos para que seja possivel acessar e acessar as ferramentas em uma unica unidade.

Uma vez criado o grupo de recursos não e possivel alterar , mais e possivel tirar e colocar recursos 
----------------------------------------------------------------------------------

Assinaturas.

E se criada uma conta Azure que e tida como a principal, essa deve estar com os dados de faturamento e cartão para cobrança dos valores relativo ao consumo das contas.
Após a criação dessa conta e possivel subdividir as assinaturas, aonde e possivel ter uma assinatura para o pessoal de Desenvolvimento,pesso de Teste e para as coisas que vão para produção.Porém será dado o gasto de cada assinatura gastou e elas responderão para a assinatura principal.
