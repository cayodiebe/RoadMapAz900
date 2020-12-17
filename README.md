# Primeiras Anotações - Certificação AZ-900 #
    Oriundos WhizLabs 
  
  - Azure DataLake é mais worth it perante a utilização de muitos dados referentes a Power Bi e consultas.
  - Microsoft garante 99.9% de estabilidade do usuário mais básico ao usuário mais avançado.
  - Usuários Microsoft acessando a estrutura de Painel de Acesso, poderão resetar a sua senha.
  - IT Administradores, são responsáveis em deletar, criar, escrever e ler os diretorios dentro do directory
  - Para reduzir a administração/esforço requerido para ativar essas maquinas, é utilizado o Azure ScaleSets.
  - Caso, seja necessário realizar um deploy muito grande de usuários, será necessário utilizar o privilégio de identity managment do Azure.
  - Sempre que, for pausada uma máquina virtual, junto, o seu custo é stopped.
  - Para realizar deployment do código, é necessário utilizar os Azure Pipelines.
  - A Licença Public Preview, a Microsoft não consegue garantir o ambiente, para o ambiente de produção 100% estável.
  - Storage Account:
  	-- Número de SA por região é de 250.
	-- Capacidade máxima de 5 PiB¹.
	-- Não há limite para blobs, messages, tables, file shares.
	-- Request Rate: 20,000 requests por segundo.
	-- Máximo de Ingresso por Storage Account: 25GBPS.
	-- Máximo de regras de acesso virtual: 200.
	-- Máximo de números de IP: 200
  - Na criação de Máquinas Virtuais, o que mais pesa para o preço é:
  	-- O Tamanho do servidor (Normal).
	-- O Local onde ele está é um peso grande também.
  - Configurações de Blob Storaged:
  	-- Transmissão de vídeo e aúdio.
	-- Abrindo imagens ou documentos diretamente pelo navegador.
	-- Inscrito em logs.
	-- Arquivos distribuídos em ações remotas.
  - Azure SQL Database é possível visualizar através do Power BI.
  - Elastic Pools são responsáveis por gerenciar muitas bases de dados.
  - OS DISK suporta somente 2TB
  - Data Disk suporta +32TB
  - Temporary Disk é somente em um escopo temporário.
  - O que é PaaS?
  	-> SQL SERVER é um exemplo.
	-> Web App.
	-> IaaS.
	-> Entrega uma plataforma.

  - O que é IaaS?
  	-> Categoria Básica, NÓS gerenciamos a camada de storage, nós gerenciamos o sistema operacional.  (Alugar um carro, mas, a responsabilidade de gasolina, estacionamento, atividades é sua).
  - O que é SaaS?
  	-> Exemplo, do transporte público, onde você somente CONSOME o serviço que lá já está planejado e arquiteturado.
	-> Office 365.
	
  - Nuvem é facil para elasticidade(Black Friday).
  
High Availability
	-> Com falhas, 99.9%
	
Fault Tolerance
	-> Nunca Falha, se manter online TODOS os tempos, com a tratavia mais planejada.

Escalabilidaed
	-> Escala, porém, não é elastica. (Aumentar o poder computacional de uma máquina), não é em horizontal, elasticy é em vertical).

Elasticy
	-> Black friday, por exemplo, Scale Set (por exemplo 50), ativa outra máquina virtual.

Global Reach 
	-> Disponível em várias regiões, por exemplo, 100% dos serviços, não estão em todas as regiões.
	
Segurança e Compliance
	-> Legislação de Banco com Auditoria, cuidado com os dados no storage fora do PAIS.
	
Agilidade
	-> Montar um datacenter, muito mais rápido do que físico.

Disaster Recovery
	-> Catastrofe, (por exemplos, torres gêmeas), o tempo para subir (dual time), é mais rápido.
	
Nuvem, é para economia de escala, por exemplo, no on-primesses (Escala).

Capex
	-> Capex é gasto que é feito em uma paulada só, usando ou não. (Dentro da núvem, é mais para licenças).

Opex
	-> Opex,  é o gasto após o uso, a despesa operacional, por exemplo horas de consultorias. (Dentro da nuvem, é quase tudo).

Consumption-based model.
	-> Sem custos iniciais, por exemplo, os recursos são exponenciais, é o consumo por produtos abertos, você é cobrado após shutdown de uma VM pelo disco.
	
Public Cloud (Maiores provedores)
	-> Qualquer pessoa no Azure, pode criar uma conta, Pas you Go.
	-> Alocando recurso conforme necessidade.

Private Cloud
	-> ???????????????
	-> Nuvem privada, gerenciamento geral da sua infraestrutura.

Hybrid Cloud
	-> Maior Flexibilidade
	-> Maioria das empresas, combina o on-premises juntamente com a nuvem, (Exemplo: Através do Azure Express Houte (VPN)).

Muito Importante -> https://prnt.sc/w4c3ix

Subscrição
	-> Tem serviços grátis de 12 meses
	-> 200$ ~ 750R$
	-> Free
	-> Pay-as-you-go
		- Seu cartão de crédito.
	-> Enterprise Agreement
	-> Estudante
	-> Uma Conta pode ter várias assinaturas.

A primeira coisa a ser desenvolvida, é o RESOURCE GROUP.

Tag é imporatante, para NOMEAR os recursos utilizados.

Azure Virtual Network (Infraestrutura de Rede) - Os Switchs
	-> fornece uma comunicação segura entre os recursos do Azure.

Azure Load Balancer 
	-> faz redirecionamentos de IP
	
Azure Application Gateway
	-> /images, por exemplo, redireciona para outro servidor, para não sobrecarregar somente o servidor.
	-> Proxy reverso.
	
-> Content Delivery Network (CDN)
	-> Por exemplo, se o usuário estiver na europa, redireciona para os servidores na europa, se for no Brasil, redireciona para o brasil.

https://prnt.sc/w4ch93

https://www.youtube.com/watch?v=ijyA2wtEH0s
1:13:00
