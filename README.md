# -resumo1-lab-Microsoft-Azure
"Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO. Microsoft Azure - Localizando serviços por categoria".

Introdução aos conceitos básicos do Microsoft Azure 

Este é um resumo da aula de Introdução aos conceitos básicos do Microsoft Azure ,ministrada pela proferssora Valéria Baptista, nele contém uma explicação breve do significado de computação em nuvem, os tipos de nuvens e as vantagens e desvantagens de cada um dos tipos, responsabilidade compartilhada e uma comparação entre CapEx e OpEx. 
O que é computação em nuvem
A computação em nuvem é a entrega de serviços de computação pela Internet, como servidores, armazenamento de dados,banco de dados, rede e software. Esses serviços podem ser rapidamente alocados e liberados com mínimo esforço gerencial ou interação com o provedor de serviços.
Modelo de responsabilidade compartilhada
Com o modelo de responsabilidade compartilhada, a responsabilidade com a manutenção e gerenciamento dos serviços são compartilhadas entre o provedor de nuvem e o consumidor. Segurança física, energia, resfriamento e conectividade de rede são responsabilidade do provedor de nuvem já que o consumidor não está na mesma localização física do datacenter.  Ao mesmo tempo, o consumidor é responsável pelos dados e pelas informações armazenados na nuvem e  também é  pela segurança de acesso, o que significa que você só dá acesso àqueles que precisam.
O modelo de responsabilidade compartilhada está fortemente vinculado aos tipos de serviço de nuvem: IaaS (infraestrutura como serviço), PaaS (plataforma como serviço) e SaaS (software como serviço). 

Ao usar um provedor de nuvem, você sempre será responsável por:
⦁	Informações e dados armazenados na nuvem
⦁	Dispositivos que têm permissão para se conectar à nuvem (telefones celulares, computadores e assim por diante)
⦁	Contas e identidades das pessoas, serviços e dispositivos em sua organização
O provedor de nuvem é sempre responsável por:
⦁	Datacenter físico
⦁	Rede física
⦁	Hosts físicos
Seu modelo de serviço determinará a responsabilidade por coisas como:
⦁	Sistemas operacionais
⦁	Controles de rede
⦁	Aplicativos
⦁	Identidade e infraestrutura
Modelos de nuvem
Os modelos de nuvem definem o tipo de implantação de recursos de nuvem. Os três principais modelos de nuvem são: privado, público e híbrido.
⦁	Nuvem privada
Uma nuvem privada é fornece serviços de TI pela Internet usada por uma única entidade. A nuvem privada fornece um controle muito maior para a empresa e o departamento de TI. A nuvem privada pode ser hospedada em seu datacenter local ou em um datacenter dedicado externo, até mesmo por terceiros que tenham dedicado esse datacenter à sua empresa.
Ela tem mais custos e menos benefícios em relação a uma implantação de nuvem pública. 

⦁	Nuvem pública
Uma nuvem pública é criada, controlada e mantida por um provedor de nuvem de terceiros. Com uma nuvem pública, qualquer pessoa que queira comprar serviços de nuvem pode acessar e usar os recursos. A disponibilidade pública geral é uma diferença fundamental entre nuvens públicas e privadas.

⦁	Nuvem híbrida
Uma nuvem híbrida usa nuvens públicas e privadas em um ambiente interconectado. Um ambiente de nuvem híbrida pode ser usado para permitir que uma nuvem privada escale para atender a uma demanda maior temporária implantando recursos de nuvem pública. A nuvem híbrida pode ser usada para fornecer uma camada adicional de segurança. Por exemplo, os usuários podem escolher com flexibilidade quais serviços manter na nuvem pública e quais implantar na infraestrutura de nuvem privada.

⦁	Várias nuvens
Um quarto cenário, é um cenário de várias nuvens. Em um cenário de várias nuvens, você usa vários provedores de nuvem pública. Em um ambiente de várias nuvens, você lida com dois (ou mais) provedores de nuvem pública e gerencia recursos e segurança em ambos os ambientes.

Azure Arc
O Azure Arc é um conjunto de tecnologias que ajuda a gerenciar seu ambiente de nuvem. O Azure Arc pode ajudar a gerenciar o seu ambiente de nuvem, seja uma nuvem pública exclusivamente no Azure, uma nuvem privada em seu datacenter, uma configuração híbrida ou até mesmo um ambiente de várias nuvens em execução em vários provedores de nuvem ao mesmo tempo.
Solução VMware no Azure
Se você já estiver estabelecido com o VMware em um ambiente de nuvem privada, mas quiser migrar para uma nuvem pública ou híbrida a Solução VMware no Azure permite executar suas cargas de trabalho do VMware no Azure com integração e escalabilidade total.
Modelo baseado em consumo
Ao comparar modelos de infraestrutura de TI, há dois tipos de despesas a serem consideradas. CapEx (despesas de capital) e OpEx (despesas operacionais).
⦁	CapEx (despesas de capital) 
É uma despesa inicial única para comprar ou proteger recursos tangíveis. Um prédio novo, a repavimentação do estacionamento, a construção de um datacenter ou a compra de um veículo da empresa são exemplos de CapEx.
⦁	OpEx (despesas operacionais)
É o gasto de capital em serviços ou produtos ao longo do tempo. O aluguel de um centro de convenções, o leasing de um veículo da empresa ou a assinatura de serviços de nuvem são exemplos de OpEx.
A computação em nuvem se enquadra na OpEx porque opera em um modelo baseado em consumo, você não paga pela infraestrutura física, pela eletricidade, pela segurança nem por nada que esteja associado à manutenção de um datacenter. Você paga pelos recursos de TI que usa. Se você não usar nenhum recurso de TI durante o mês, não pagará nada.
Benefícios:
⦁	Sem custos prévios.
⦁	Não há necessidade de comprar nem gerenciar uma infraestrutura cara que os usuários talvez não usem na capacidade máxima.
⦁	A capacidade de pagar para obter mais recursos quando necessário.
⦁	A capacidade de parar de pagar por recursos que não são mais necessários.
⦁	Com um datacenter tradicional, você tenta estimar as necessidades futuras de recursos. Se você superestimar, gastará mais do que o necessário no datacenter, podendo desperdiçar capital. Se você subestimar, o datacenter atingirá a capacidade rapidamente e os aplicativos e serviços poderão sofrer redução de desempenho. A correção de um datacenter subprovisionado pode ser muito demorada. Pode ser necessário solicitar, receber e instalar mais hardware. Você também precisará adicionar energia, resfriamento e rede para o hardware extra.
⦁	Comparar os modelos de preços de nuvem
⦁	Computação em nuvem é a entrega de serviços de computação pela Internet, usando o modelo de preço pago conforme o uso. Normalmente, você paga apenas pelos serviços de nuvem que usa, o que ajuda a:
⦁	Planeje e gerencie os custos operacionais.
⦁	Executar a infraestrutura com mais eficiência.
⦁	Escale as operações de acordo com as necessidades de negócios.
Em outras palavras, a computação em nuvem é uma forma de alugar capacidade computacional e armazenamento do datacenter de terceiros. Você pode tratar os recursos de nuvem como faria com os recursos em seu próprio datacenter. Mas, ao contrário do seu próprio datacenter, ao terminar de usar os recursos de nuvem, basta devolvê-los. Você é cobrado apenas pelo que usa.
Em vez de manter CPUs e armazenamento no seu datacenter, você aluga esses recursos pelo tempo necessário. O provedor em nuvem é responsável por manter a infraestrutura subjacente para você. A nuvem permite que você supere rapidamente os desafios empresariais mais difíceis e ofereça soluções de ponta para seus usuários.

Fonte: https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/2-introduction-cloud-compute
