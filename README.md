
# Huawei Cloud Comparison

Comparação dos serviços da Huawei Cloud vs AWS vs Azure vs GCP vs Oracle

## Compute 
| Huawei Cloud                                      | AWS                            | AZURE               | GCP                 | Oracle                          |
| ---------------------                             | ------------------------------ | ------------------- | ------------------- | -------------------             |
| [ECS](#ecs---elastic-cloud-server)                | EC2                            | VM                  | Compute Engine      | Virtual Machines                |
| [Batch](#batch)                 | Batch           | Batch                          | Batch               |                     |                                 |
| [IMS](#ims---image-management-service)            | AMI                            | VM Images           | Images              | Images                          |
| [Auto Scaling](#auto-scaling)                     | EC2 Auto Scaling               | AutoScale           | AutoScaler          | Auto Scaling                    |
| [CCE](#cce---cloud-container-engine)              | ECS  Elastic Container Service | Kubernetes Service  | Kubernetes Engines  | Container Engine for Kubernetes |
| [CCI](#cci---cloud-container-instance)            | Fargate                        | Container Instances | Cloud Run           |                                 |
| [FunctionGraph](#functiongraph)                   | Lambda                         | Function Apps       | Cloud Functions     | Functions                       |
| [Bare Metal Server](#bms---bare-metal-server)     |                                |                     |                     | Bare Metal                      |

### ECS - Elastic Cloud Server
Um Elastic Cloud Server (ECS) é um servidor em nuvem que fornece recursos de computação escaláveis e sob demanda para aplicativos seguros, flexíveis e eficientes. Consiste basicamente de vCPUs (Processador virtual), memória e disco, podendo ser usado exatamente como um computador local ou servidor físico.
O ECS está disponível em vários tipos para os mais variados cenários, com aplicações que exigem alto poder de processamento, alta quantidade memória RAM, GPU integrada ou alta quantidade de IOPS para armazenamento utilizando NVMe acoplado físicamente ao servidor.
#### Links:
- [ECS Homepage](https://support.huaweicloud.com/intl/en-us/ecs/index.html)
- [ECS General FAQs](https://support.huaweicloud.com/en-us/ecs_faq/ecs_faq_0001.html)
- [ECS Billing Details](https://support.huaweicloud.com/intl/en-us/price-ecs/en-us_topic_0088450533.html)

### Batch
Batch Service (Batch) é um serviço de computação em nuvem distribuído usado para executar tarefas de computação em lote em larga escala. Ele suporta gerenciamento de recursos automático e flexível, agendamento personalizado de tarefas, carregamento conveniente de dados e visualização em tempo real de logs de tarefas. O Batch simplifica a utilização dos recursos da nuvem e cobra com base nos recursos realmente usados, reduzindo os custos de O&M.
#### Links:
- [Batch Homepage](https://support.huaweicloud.com/intl/en-us/batch/index.html)

### IMS - Image Management Service
O Serviço de Gerenciamento de Imagens (IMS) permite criar e gerenciar imagens com facilidade. Você pode criar uma imagem de disco do sistema ou imagem de disco de dados a partir de um disco ou de um arquivo de imagem externo. Você também pode criar uma imagem de ECS completa a partir de um ECS com discos de dados ou um backup de um ECS.
A criação da imagem é gratuita. Somente o espaço de armazenamento do OBS ou os backups do CSBS que você usou incorrem em taxas.
#### Links:
- [IMS Homepage](https://www.huaweicloud.com/intl/en-us/product/ims.html)
- [IMS General FAQs](https://support.huaweicloud.com/en-us/ims_faq/ims_faq_0104.html)

### Auto Scaling
O Auto Scaling (AS) é um serviço que ajusta automaticamente os recursos com base nos requisitos de serviço e nas políticas configuradas. Você pode especificar políticas com base nos requisitos de serviço. O AS pode ajustar automaticamente os recursos de ECS e largura de banda (EIP).
#### Links:
- [Auto Scaling Homepage](https://support.huaweicloud.com/intl/en-us/as/index.html)
- [AS General FAQs](https://support.huaweicloud.com/intl/en-us/as_faq/as_faq_1101.html)
- [AS Billing Details](https://support.huaweicloud.com/intl/en-us/productdesc-as/en-us_topic_0042398002.html)

### CCE - Cloud Container Engine
O CCE é uma plataforma completa de contêineres que fornece serviços de contêineres completos, desde o gerenciamento de cluster Kubernetes, gerenciamento do ciclo de vida de aplicativos em contêineres, application service mesh e Helm charts para gerenciamento de complemento, agendamento de aplicativos e O&M.
O CCE está profundamente integrado aos serviços HUAWEI CLOUD, incluindo serviços de computação de alto desempenho (ECS / BMS), rede (VPC / EIP / ELB) e armazenamento (EVS / OBS / SFS).
HUAWEI CLOUD é um dos primeiros provedores de serviços Kubernetes certificados do mundo  (KCSPs) e o primeiro participante da China na comunidade Kubernetes. Há muito tempo contribui para as comunidades de contêineres de código aberto e assume a liderança no ecossistema de contêineres. A HUAWEI CLOUD também é fundadora e membro de platina da Cloud Native Computing Foundation (CNCF)
Você pode usar o CCE por meio do console, kubectl ou APIs.
#### Links:
- [CCE Homepage](https://support.huaweicloud.com/intl/en-us/cce/index.html)
- [CCE General FAQs](https://support.huaweicloud.com/intl/en-us/cce_faq/cce_faq_00001.html) 
- [CCE Billing Details](https://support.huaweicloud.com/intl/en-us/cce_faq/cce_faq_00101.html)

### CCI - Cloud Container Instance
O Cloud Container Instance (CCI) é um mecanismo de contêiner serverless que permite executar contêineres sem criar ou gerenciar clusters de servidores.
Com a arquitetura serverless, você pode se concentrar na criação e operação de aplicativos sem ter que criar ou gerenciar servidores ou se preocupar com a integridade do servidor. Tudo o que você precisa fazer é especificar os requisitos de recursos (como os núcleos da CPU e o espaço em memória necessários). Isso fornece uma abordagem mais focada às necessidades da empresa e ajuda a reduzir os custos de gerenciamento e manutenção. Tradicionalmente, para executar cargas de trabalho em contêineres usando o Kubernetes, você precisa primeiro criar um cluster de servidores Kubernetes. Esse não é o caso da CCI. Sob a arquitetura serverless, o CCI permite criar e usar diretamente cargas de trabalho em contêiner usando as APIs e console, kubectl e outras e pagar apenas pelos recursos consumidos por essas cargas de trabalho.
#### Links:
- [CCI Homepage](https://support.huaweicloud.com/intl/en-us/ecs/index.html)
- [CCI General FAQs](https://support.huaweicloud.com/en-us/cci_faq/cci_faq_0038.html)

### FunctionGraph
O FunctionGraph hospeda e calcula funções em um contexto serverless. Ele é dimensionado automaticamente para se adequar às flutuações nas demandas de recursos durante picos de utilização, sem exigir reserva de servidores ou capacidades dedicados. Você será cobrado com base no uso real. O FunctionGraph consiste nos módulos de função e fluxo de trabalho que implementam respectivamente a computação e a orquestração de funções.

#### Links:
- [FunctionGraph Homepage](https://support.huaweicloud.com/en-us/productdesc-functiongraph/functiongraph_01_0100.html)
- [FunctionGraph General FAQs](https://support.huaweicloud.com/en-us/functiongraph_faq/index.html)
- [FunctionGraph Billing Details](https://support.huaweicloud.com/en-us/price-functiongraph/en-us_topic_0118926116.html)

### BMS - Bare Metal Server
O Bare Metal Server (BMS) apresenta a escalabilidade de VMs e o alto desempenho de servidores físicos. Ele fornece servidores dedicados na nuvem que oferecem o desempenho da computação e a segurança dos dados exigidos pelos bancos de dados, principais sistemas de aplicativos, computação de alto desempenho (HPC) e Big Data. Você pode solicitar e usar BMSs sob demanda.
O recurso de autoprovisionamento do BMS permite que você solicite um BMS sem a burocracia de se contratar um servidor fisico. Para solicitar um BMS, você só precisa especificar o tipo de servidor, imagem, rede e outras configurações. Em seguida, você obterá o BMS solicitado em até 30 minutos. Você pode se concentrar em seus serviços sem se preocupar com o fornecimento do servidor ou O&M.
#### Links:
- [BMS Homepage](https://support.huaweicloud.com/en-us/productdesc-bms/bms_01_0001.html)
- [BMS General FAQs](https://support.huaweicloud.com/en-us/bms_faq/en-us_topic_0053536927.html)
- [BMS Billing Details](https://support.huaweicloud.com/en-us/price-bms/en-us_topic_0088467849.html)


## Storage
| Huawei Cloud                                                          | AWS                   | AZURE               | GCP                 | Oracle              |
| ---------------------                                                 | --------------------- | ------------------- | ------------------- | ------------------- |
| [Elastic Volume Service](#evs---elastic-volume-service)               | EBS                   | Disk Storage        | Persistent Disk     | Block Volumes       |
| [Cloud Server Backup Service](#csbs---cloud-server-backup-service)    | Backup                | Backup              | Backup              | Backup              |
| [Volume Backup Service](#vbs---volume-backup-service)                 | Backup                | Backup              |                     | Snapshot            |
| [Object Storage Service](#obs---object-storage-service)               | S3                    | Blob Storage        | Cloud Storage       | Object Storage      |
| [Scalable File Service](#sfs---scalable-file-service)                 | SFS                   | Files               | File Storage        | File Storage        |
| [Data Express Service*](#des---data-express-service)                  | Snowball              | NA                  | NA                  | NA                  |

### EVS - Elastic Volume Service
O Elastic Volume Service (EVS) oferece armazenamento em bloco escalável para servidores em nuvem. Com alta confiabilidade, alto desempenho e especificações ricas, os discos EVS podem ser usados para sistemas de arquivos distribuídos, ambientes de desenvolvimento e teste, aplicativos de DW e cenários de computação de alto desempenho (HPC) para atender a diversos requisitos de serviço. Servidores que o EVS suporta incluem Elastic Cloud Servers ([ECSs](#ecs---elastic-cloud-server)) e Bare Metal Servers ([BMSs](#bms---bare-metal-server)).
 
![Figure 1](img/en-us_image_0205523160.png?raw=true "EVS architecture")
#### Quick Links:
- [EVS Homepage](https://support.huaweicloud.com/intl/en-us/evs/index.html)
- [EVS General FAQs](https://support.huaweicloud.com/en-us/evs_faq/evs_01_0096.html)
- [EVS Billing Details](https://support.huaweicloud.com/intl/en-us/price-evs/en-us_topic_0088763748.html)

### CSBS - Cloud Server Backup Service
O CSBS (Cloud Server Backup Service) oferece o serviço de proteção de backup para os Elastic Cloud Servers ([ECS](#ecs---elastic-cloud-server)). Ele funciona com base na consistente tecnologia de captura instantânea (Snapshot) de discos do Elastic Volume Service ([EVS](#evs---elastic-volume-service)), o que significa que você pode usar perfeitamente os dados de backup para restaurar os dados do ECS. O CSBS aprimora a integridade dos dados e a continuidade do serviço.
#### Quick Links:
- [CSBS Homepage](https://support.huaweicloud.com/intl/en-us/csbs/index.html)
- [CSBS General FAQs](https://support.huaweicloud.com/intl/en-us/csbs_faq/index.html)
- [CSBS Billing Details - How it is charged](https://support.huaweicloud.com/intl/en-us/csbs_faq/en-us_topic_0089772263.html)

### VBS - Volume Backup Service
O Volume Backup Service (VBS) fornece proteção de dados baseada em snapshot para discos do Elastic Volume Service (EVS).
O VBS protege seus dados, mesmo se um disco do EVS estiver com defeito ou encontrar um erro lógico (por exemplo, exclusão incorreta, ataques de hackers e infecção por vírus). Ele permite que você crie backups de seus dados sem esforço, e esses backups de dados podem ser usados para restaurar dados rapidamente.
O VBS suporta os modos de backup completo e incremental. Por padrão, o sistema executa um backup completo inicialmente e, em seguida, executa backups incrementais. Você pode usar um backup de dados gerado no modo de backup para restaurar o disco EVS de origem para o estado em que estava o disco EVS quando o backup foi criado.
O VBS permite backup e restauração com um clique dos discos EVS nos servidores, por meio de sua plataforma fácil de usar.
#### Quick Links:
- [VBS Homepage](https://support.huaweicloud.com/intl/en-us/vbs/index.html)
- [VBS General FAQs](https://support.huaweicloud.com/intl/en-us/vbs_faq/index.html)
- [VBS Billing Details](https://support.huaweicloud.com/intl/en-us/price-vbs/en-us_topic_0088543838.html)

### OBS - Object Storage Service
O Object Storage Service (OBS) é um serviço de armazenamento em nuvem otimizado para armazenar grandes quantidades de dados. Ele fornece recursos de armazenamento ilimitados, seguros e altamente confiáveis ​​a um custo relativamente baixo.
O OBS fornece aos usuários capacidade ilimitada de armazenamento, armazena arquivos em qualquer formato e atende às necessidades de usuários, sites, empresas e desenvolvedores comuns. Nem todo o sistema OBS nem nenhum único bucket têm limitações na capacidade de armazenamento ou no número de objetos / arquivos que podem ser armazenados. Como serviço da Web, o OBS oferece suporte a APIs através de HTTP (Hypertext Transfer Protocol) e HTTPS (Hypertext Transfer Protocol Secure). Você pode usar o OBS Console ou as ferramentas do OBS para acessar e gerenciar dados armazenados no OBS a qualquer momento, em qualquer lugar. Com SDKs e APIs fornecidos pelo OBS, você pode gerenciar facilmente os dados armazenados no OBS e desenvolver aplicativos de serviço. O HUAWEI CLOUD implementa infra-estruturas OBS em várias regiões e oferece expansão flexível e confiabilidade aprimorada. 
#### Quick Links:
- [OBS Homepage](https://support.huaweicloud.com/intl/en-us/obs/index.html)
- [OBS General FAQs](https://support.huaweicloud.com/intl/en-us/obs/index.html#section1)
- [OBS Billing Details](https://support.huaweicloud.com/intl/en-us/price-obs/en-us_topic_0088219452.html)

### SFS - Scalable File Service
O Scalable File Service (SFS) é um serviço NAS (Network Attached Storage) que fornece armazenamento escalável de arquivos de alto desempenho. Com o serviço, é possível obter acesso compartilhado entre vários Elastic Cloud Servers (ECSs), Bare Metal Servers (BMSs) e contêineres criados no Cloud Container Engine (CCE).
![Figure 1](img/en-us_image_sfs.png?raw=true "SFS example")

#### Quick Links:
- [SFS Homepage](https://support.huaweicloud.com/intl/en-us/sfs/index.html)
- [SFS General FAQs](https://support.huaweicloud.com/intl/en-us/sfs_faq/en-us_topic_0188610599.html)
- [SFS Billing Details](https://support.huaweicloud.com/intl/en-us/price-sfs/en-us_topic_0088406036.html)

### DES - Data Express Service
O Data Express Service (DES) é um serviço de transmissão de dados em escala TB ou PB. Ele usa mídia de armazenamento físico (como [Teleport(Ainda não disponivel no Brasil)](https://support.huaweicloud.com/en-us/des_faq/des_faq_0053.html), unidades flash USB externas, discos SATA e discos SAS) para transmitir uma grande quantidade de dados ao HUAWEI CLOUD. O DES fornece uma velocidade de transmissão de dados de 1000 Mbit / s, 10 vezes mais rápida que a transmissão de alta velocidade pela Internet, mas com apenas um quinto do custo. Ajuda a resolver problemas enfrentados pela transmissão massiva de dados, como altos custos de rede e longo tempo de transmissão. O DES não ocupa a largura de banda da sua rede pública ou compete com os principais serviços por recursos de largura de banda.
Atualmente, o DES suporta dois modos de transmissão de dados: por teletransporte e por disco. O teleporte se adapta à migração de dados nas escalas TB e PB, enquanto os discos são preferidos para a migração de dados no nível da TB. Selecione um modo de transmissão com base na quantidade de dados a serem transmitidos. Para obter detalhes, consulte a Tabela 1. Para o DES baseado em teleporte, você receberá um teleporte enviado por um data center (DC) da Huawei. Para o DES baseado em disco, você precisa preparar os discos sozinho.

Maiores informações sobre o Huawei *Teleport appliance*: 
 Teleport é um dispositivo de armazenamento personalizado de alto desempenho usado para transmissão de dados. É o meio de migração para o DES baseado em applicance. O data center da Huawei envia o Teleports para os usuários, os usuários copiam seus dados para o sistema de armazenamento de Teleport e enviam o de volta para a Huawei para migrar dados para o HUAWEI CLOUD OBS. Através do Teleport, os dados podem ser carregados no HUAWEI CLOUD dentro de poucos dias. 
 O Teleport possui os seguintes recursos:
* É à prova de poeira e água e resistente à vibração e compressão. Com uma trava de segurança e gravação de alarme, além das funções de criptografia AES-256, os dados são protegidos durante a entrega.
* Ele suporta uma taxa de compactação de dados de 30: 1.
* Suporte para protocolos NFS / CIFS / FTP para o OBS.
* Ele suporta mesclagem automática de arquivos pequenos para melhorar a eficiência de leitura e gravação.
* Com gabinete de classe militar, rastreamento por GPS, desbloqueio de área restrita, e aplicável a cenários de logística para qualquer clima para garantir uma transmissão segura.
* As opções de capacidade são 60 TB e 120 TB.
* Ele fornece duas portas de alta velocidade 10GE.
#### Quick Links:
- [DES Homepage](https://support.huaweicloud.com/intl/en-us/des/index.html)
- [DES General FAQs](https://support.huaweicloud.com/intl/en-us/des_faq/des_faq_0100.html)
- [DES Billing Details](https://support.huaweicloud.com/intl/en-us/price-des/en_000002.html)


## Network
| Huawei Cloud                                              | AWS                   | AZURE                     | GCP                 | Oracle                |
| ---------------------                                     | --------------------- | -------------------       | ------------------- |-------------------    |
| [Virtual Private Cloud](#vpc---virtual-private-cloud)     | VPC                   | Virtual Network           | Virtual Network     | Virtual Cloud Network |
| [Elastic Load Balance](#elb---elastic-load-balance)       | ELB                   | Load Balancer             | Load Balancing      | Load Balancing        |
| [Virtual Private Network](#vpn---virtual-private-network) | VPN                   | Connections               | VPN                 | VPN                   |
| [Direct Connect](#direct-connect)                         | Direct Connect        | ExpressRoute              | Interconnect        | FastConnect           |
| [DNS](#dns)                                               | Route 53              | DNS                       | DNS                 | DNS                   |
| [NAT Gateway](#nat-gateway)                               | NAT Gateway           | Virtual Network Gateway   |                     | NAT Gateway           |
| [CDN](#cdn)                                               | CloudFront            | CDN                       | Cloud CDN           |                       |
| [API Gateway](#api-gateway)                               | API Gateway           |                           |                     | API Gateway           |

### VPC - Virtual Private Cloud
O Virtual Private Cloud (VPC) é um serviço que possibilita o provisionamento de redes virtuais configuráveis, administráveis e isoladas lógicamente para servidores na nuvem, simplificando a implantação da rede e melhorando a segurança dos recursos no sistema. Os Servidores na nuvem podem ser Elastic Cloud Server (ECS) ou Bare Metal Servers(BMS).
É possível selecionar a abrangência do endereço de IP, criar múltiplas sub-redes, configurar tabela de rotas e gateways, e customizar os grupos de segurança na sua VPC. Com isso, você administra, altera redes internas e ainda modifica as configurações de maneira flexível e segura. Também é permitido customizar as regras de acesso e firewalls para controlar o acesso aos servidores na nuvem em um grupo de segurança e entre vários outros grupos para otimizar a segurança dos servidores na sub-rede.

![Figure 1](img/vpc.png?raw=true "VPC example")

#### Quick Links:
- [VPC Homepage](https://support.huaweicloud.com/intl/en-us/vpc/index.html)
- [VPC General FAQs](https://support.huaweicloud.com/intl/en-us/vpc_faq/faq_vpc.html)
- [VPC Billing Details](https://support.huaweicloud.com/intl/en-us/productdesc-vpc/vpc_price_0001.html)

### ELB - Elastic Load Balance
Elastic Load Balance (ELB) é um serviço que distribui automaticamente o tráfego de fora para dentro da rede entre múltiplos servidores internos baseado em políticas de encaminhamento pré-definidas. O ELB vai expandir a capacidade de gerenciamento de acesso às aplicações e sistemas por meio da distribuição de tráfego e alcançar um nível mais alto de desempenho e tolerância a falhas, eliminando o ponto único de falha (SPOFs).

![Figure 1](img/elb.png?raw=true "ELB example")

#### Quick Links:
- [ELB Homepage](https://support.huaweicloud.com/intl/en-us/elb/index.html)
- [ELB General FAQs](https://support.huaweicloud.com/intl/en-us/elb_faq/elb_faq_0200.html)
- [ELB Billing Details](https://support.huaweicloud.com/intl/en-us/productdesc-elb/elb_pro_0014.html)

### VPN - Virtual Private Network
Um Virtual Private Network é um túnel de comunicação encriptado e seguro estabelecido entre uma rede privada remota e a Virtual Private Cloud (VPC) na nuvem. Esse túnel cumpre com todos os requisitos padranizados pela indústria e extende, por exemplo, um data center privado para a VPC na nuvem.

![Figure 1](img/vpn2.png?raw=true "VPN example")

#### Quick Links:
- [VPN Homepage](https://support.huaweicloud.com/intl/en-us/vpn/index.html)
- [VPN General FAQs](https://support.huaweicloud.com/intl/en-us/vpn_faq/vpn_08_0100.html)
- [VPN Billing Details](https://support.huaweicloud.com/intl/en-us/productdesc-vpn/vpn_01_0004.html)

### Direct Connect
É um serviço de conexão de rede dedicada entre o Data Center e a rede virtual privada (VPC) na Huawei Cloud. Com a largura de banda suportando até 10 Gbit/s de conexão, garante um alto nível de segurança com um canal isolado de outras conexões, baixa latência para uma excelente experiência do cliente, possibilitando a construção de um cenário híbrido, escalável e flexível.

![Figure 1](img/dc.png?raw=true "Direct Connect example")

#### Quick Links:
- [Direct Connect Homepage](https://support.huaweicloud.com/intl/en-us/dc/index.html)
- [Direct Connect General FAQs](https://support.huaweicloud.com/intl/en-us/dc_faq/dc_07_0100.html)
- [Direct Connect Billing Details](https://support.huaweicloud.com/intl/en-us/productdesc-dc/dc_01_0006.html)

### DNS
O Domain Name Service (DNS) é um serviço de DNS autoritativo gerenciado que traduz nomes de domínio (www.example.com) em endereços de IP (192.168.X.X), direcionando o tráfego da Internet para aplicações em seus respectivos servidores.

![Figure 1](img/dns.png?raw=true "DNS example")

#### Quick Links:
- [DNS Homepage](https://support.huaweicloud.com/intl/en-us/dns/index.html)
- [DNS General FAQs](https://support.huaweicloud.com/intl/en-us/dns_faq/dns_faq_1402.html)
- [DNS Billing Details](https://support.huaweicloud.com/intl/en-us/dns_faq/dns_faq_006.html)

### NAT Gateway
O Network Address Translation Gateway (NAT Gateway) é um serviço que possibilita a conexão entre a VPC e a Internet para múltiplus servidores, podendo ser distribuido entre várias sub-redes e zonas de disponibilidades. Tanto os dados de saída quanto os de entrada podem ser devidamente configurados através de regras SNAT (saída da rede) e DNAT (entrada na rede).

![Figure 1](img/natgw.png?raw=true "NAT Gateway example")

#### Quick Links:
- [NAT Gateway Homepage](https://support.huaweicloud.com/intl/en-us/natgateway/index.html)
- [NAT Gateway General FAQs](https://support.huaweicloud.com/intl/en-us/natgateway_faq/nat_faq_0003.html)
- [NAT Gateway Billing Details](https://support.huaweicloud.com/intl/en-us/productdesc-natgateway/nat_price_0001.html)

### CDN
O Content Delivery Network DN é um serviço de redirecionamento de conteúdo para reduzir congestionamento de rede, que acelera a distribuição de conteúdo para servidores de borda, trazendo mais performance na abertura de websites.

![Figure 1](img/cdn.png?raw=true "CDN example")

#### Quick Links:
- [CDN Homepage](https://support.huaweicloud.com/intl/en-us/cdn/index.html)
- [CDN General FAQs](https://support.huaweicloud.com/intl/en-us/cdn_faq/cdn_faq_1.html)
- [CDN Billing Details](https://support.huaweicloud.com/intl/en-us/productdesc-cdn/cdn_01_0104.html)

### API Gateway

O API Gateway é um serviço de hospedagem de API de alta performance, alta disponibilidade e segurança que ajuda empresas a construir, administrar e implantar APIs em qualquer escala. Com alguns cliques, é possível implementar integrações de sistemas internos com o mínimo de custo e risco.

![Figure 1](img/api.png?raw=true "API Gateway example")

#### Quick Links:
- [API Gateway Homepage](https://support.huaweicloud.com/intl/en-us/apig/index.html)
- [API Gateway General FAQs](https://support.huaweicloud.com/intl/en-us/apig_faq/index.html)
- [API Gateway Billing Details](https://support.huaweicloud.com/intl/en-us/price-apig/en-us_topic_0112975574.html)

## Management
| Huawei Cloud                        | AWS                   | AZURE              | GCP                 |
| ---------------------               | --------------------- | -------------------| ------------------- |
| [Cloud Eye](#cloud-eye)             | CloudWatch            | Monitor            | Monitoring          |
| [Log Tank](#log-tank)               | CloudTrail            | Monitor            | Logging             |
| [IAM](#iam)                         | IAM                   | Managed Identities | IAM                 |
| [Cloud Trace Service](#cloud-trace) | CloudTrail            | Monitor            | Trace               |

### Cloud Eye

#### Quick Links:
- [Cloud Eye Homepage]()
- [Cloud Eye General FAQs]()
- [Cloud Eye Billing Details]()

### Log Tank

#### Quick Links:
- [Log Tank Homepage]()
- [Log Tank General FAQs]()
- [Log Tank Billing Details]()

### IAM

#### Quick Links:
- [IAM Homepage]()
- [IAM General FAQs]()
- [IAM Billing Details]()

### Cloud Trace

#### Quick Links:
- [Cloud Trace Homepage]()
- [Cloud Trace General FAQs]()
- [Cloud Trace Billing Details]()

## Database
| Huawei Cloud                                                                  | AWS                           | AZURE                         | GCP                 |
| ---------------------                                                         | ---------------------         | -------------------           | ------------------- |
| [RDS MySQL](#rds-mysql)                                                       | RDS MySQL                     | RDS MySQL                     | Cloud SQL           |
| [RDS Postgre SQL](#rds-postgre-sql)                                           | RDS Postgre SQL               | RDS Postgre SQL               | Cloud SQL           |
| [RDS SQL Server](#rds-sql-server)                                             | RDS SQL Server                | SQL Azure                     | Cloud SQL           |
| [DDS](#dds---document-database-service)                                       | DynamoDB                      | Cosmos DB                     | Datastore           |
| [Redis](#distributed-cache-service-for-redis)                                 | ElastiCache for Redis         | Cache for Redis               | Firestore           |
| [Memcache](#distributed-cache-service-for-memcache)                           | ElastiCache for Memcached     |                               | Firestore           |
| [DRS - Data Replication Service](#drs---data-replication-service)             | Database Migration Service    | Database Migration Service    | Transfer Applicance |
| [DAS - Data Admin Service](#das---data-admin-service)                         |                               |                               |                     | 

### RDS MySQL

#### Quick Links:
- [RDS MySQL Homepage]()
- [RDS MySQL General FAQs]()
- [RDS MySQL Billing Details]()

### RDS Postgre SQL

#### Quick Links:
- [RDS Postgre SQL Homepage]()
- [RDS Postgre SQL FAQs]()
- [RDS Postgre SQL Details]()

### RDS SQL Server

#### Quick Links:
- [RDS SQL Server Homepage]()
- [RDS SQL Server General FAQs]()
- [RDS SQL Server Billing Details]()

### DDS - Document Database Service

#### Quick Links:
- [DDS Homepage]()
- [DDS General FAQs]()
- [DDS Billing Details]()

### Distributed Cache Service for Redis

#### Quick Links:
- [DCS - Redis Homepage]()
- [DCS - Redis General FAQs]()
- [DCS - Redis Billing Details]()

### Distributed Cache Service for Memcache

#### Quick Links:
- [DCS - Memcache Homepage]()
- [DCS - Memcache General FAQs]()
- [DCS - Memcache Billing Details]()

### DRS - Data Replication Service

#### Quick Links:
- [DRS Homepage]()
- [DRS General FAQs]()
- [DRS Billing Details]()

### DAS - Data Admin Service

#### Quick Links:
- [DAS Homepage]()
- [DAS General FAQs]()
- [DAS Billing Details]()

## Security
| Huawei Cloud                                                              | AWS                           | AZURE                         | GCP                  |
| ---------------------                                                     | ---------------------         | -------------------           | -------------------  |
| [Anti-DDoS](#anti-ddos)                                                   | Shield                        | DDoS Protection               | Cloud Armor          |
| [Advanced Anti-DDoS](#anti-ddos)                                          | Shield                        | DDoS Protection               | Cloud Armor          |
| [WAF - Web Application Firewall](#waf)                                    | WAF                           | Web App Firewall              | Security Platform    |
| [VSS - Vulnerability Scan Service](#rds-sql-server)                       | Inspector                     | Security Center               | Web Security Scanner |
| [HSS - Host Security Service](#dds---document-database-service)           | Inspector                     | Security Center               | Security Platform    |
| [DEW - Data Encryption Workshop](#distributed-cache-service-for-redis)    | CloudHSM                      | Key Vault                     | KMS API              |
| [SSL Certificate Manager](#distributed-cache-service-for-memcache)        | Certification Manager         | Key Vault                     | SSL Policies         |
| [DBSS - Database Security Service](#drs---data-replication-service)       |                               |                               |                      |
| [Situation Awareness](#das---data-admin-service)                          | GuardDuty                     | Security Center               | Threat Detection     |  

### Anti-DDoS

#### Quick Links:
- [Anti-DDoS Homepage]()
- [Anti-DDoS General FAQs]()
- [Anti-DDoS Billing Details]()

### Advanced Anti-DDoS

#### Quick Links:
- [Advanced Anti-DDoS Homepage]()
- [Advanced Anti-DDoS General FAQs]()
- [Advanced Anti-DDoS Billing Details]()

### WAF - Web Application Firewall

#### Quick Links:
- [WAF - Web Application Firewall Homepage]()
- [WAF - Web Application Firewall General FAQs]()
- [WAF - Web Application Firewall Billing Details]()

### VSS - Vulnerability Scan Service

#### Quick Links:
- [VSS - Vulnerability Scan Service Homepage]()
- [VSS - Vulnerability Scan Service General FAQs]()
- [VSS - Vulnerability Scan Service Billing Details]()

### HSS - Host Security Service

#### Quick Links:
- [HSS - Host Security Service Homepage]()
- [HSS - Host Security Service General FAQs]()
- [HSS - Host Security Service Billing Details]()

### DEW - Data Encryption Workshop

#### Quick Links:
- [DEW - Data Encryption Workshop Homepage]()
- [DEW - Data Encryption Workshop General FAQs]()
- [DEW - Data Encryption Workshop Billing Details]()

### SSL Certificate Manager

#### Quick Links:
- [SSL Certificate Manager Homepage]()
- [SSL Certificate Manager General FAQs]()
- [SSL Certificate Manager Billing Details]()

### DBSS - Database Security Service

#### Quick Links:
- [DBSS - Database Security Service Homepage]()
- [DBSS - Database Security Service General FAQs]()
- [DBSS - Database Security Service Billing Details]()

### Situation Awareness

#### Quick Links:
- [Situation Awareness Homepage]()
- [Situation Awareness General FAQs]()
- [Situation Awareness Billing Details]()



## Application & Middleware
| Huawei Cloud                                                                              | AWS                           | AZURE                         | GCP                 |
| ---------------------                                                                     | ---------------------         | -------------------           | ------------------- |
| [ServiceStage](#ServiceStage)                                                             | Elastic Beanstalk             | Service Fabric                | App Engine          |
| [Software Repository for Container (SWR)](#swr---software-repository-for-container)       | Elastic Container Registry    | Container Registry            | Container Registry  |
| [SMN - Simple Message Notification](#smn---simple-message-notification)                   | SNS                           | Notification Hub              | Pub/Sub             |
| [DMS - Distributed Message Service](#dms---distributed-message-service)                   | SQS                           | Queue Storage                 | Pub/Sub             |
| [APM - Application Performance Management](#apm---application-performance-management)     | X-Ray                         | Monitor                       | Management Tools    |
| [BCS - Blockchain Service](#bcs---blockchain-service)         | ElastiCache for Redis     | Blockchain                    | Blockchain                    |                     |
| [AOM - Application Operations Management](#aom---application-operations-management)       |                               |                               |                     |
| [CTPS - Cloud Performance Test Service](#ctps---cloud-performance-test-service)           |                               |                               |                     |

### ServiceStage

#### Quick Links:
- [ServiceStage Homepage]()
- [ServiceStage General FAQs]()
- [ServiceStage Billing Details]()

### SWR - Software Repository for Container

#### Quick Links:
- [SWR Homepage]()
- [SWR General FAQs]()
- [SWR Billing Details]()

### SMN - Simple Message Notification

#### Quick Links:
- [SMN Homepage]()
- [SMN General FAQs]()
- [SMN Billing Details]()

###  DMS - Distributed Message Service

#### Quick Links:
- [DMS Homepage]()
- [DMS General FAQs]()
- [DMS Billing Details]()

###  APM - Application Performance Management

#### Quick Links:
- [APM Homepage]()
- [APM General FAQs]()
- [APM Billing Details]()

###  BCS - Blockchain Service

#### Quick Links:
- [BCS Homepage]()
- [BCS General FAQs]()
- [BCS Billing Details]()

###  AOM - Application Operations Management

#### Quick Links:
- [AOM Homepage]()
- [AOM General FAQs]()
- [AOM Billing Details]()

###  CTPS - Cloud Performance Test Service

#### Quick Links:
- [CTPS Homepage]()
- [CTPS General FAQs]()
- [CTPS Billing Details]()

## Big Data
| Huawei Cloud                                                      | AWS                   | AZURE              | GCP                 |
| ---------------------                                             | --------------------- | -------------------| ------------------- |
| [DIS - Data Ingestion Service](#dis---data-ingestion-service)     | Kinesis               | Event Hubs         | DataFlow            |
| [CDM - Cloud Data Migration](#cdm---cloud-data-migration)         | DMS                   | DMS                | DataFlow            |
| [DLF - Data Lake Factory](#dlf---data-lake-factory)               | Data Pipeline         | Data Factory       | Composer            |
| [MRS - MapReduce Service](#mrs---mapreduce-service)               | EMR                   | HDInsight          | Dataproc            |
| [DWS - Data Warehouse Service](#dws---data-warehouse-service)     | Redshift              | Synapse Analytics  | Bigquery            |
| [DLI - Data Lake Insight](#dli---data-lake-insight)               | Athena                | Stream Analytics   | Bigquery            |
| [CloudTable Service](#cloudtable-service)                         | DynamoDB              | Cosmos DB          | Bigtable            |
| [CSS - Cloud Search Service](#css---cloud-search-service)         | CloudSearch           | Cognitive Search   | Cloud Search        |
| [DLV - Data Lake Visualization](#dlv---data-lake-visualization)   | QuickSight            | Power BI           | Data Studio         |


### DIS - Data Ingestion Service

#### Quick Links:
- [DIS Homepage]()
- [DIS General FAQs]()
- [DIS Billing Details]()

### CDM - Cloud Data Migration

#### Quick Links:
- [CDM Homepage]()
- [CDM General FAQs]()
- [CDM Billing Details]()

### DLF - Data Lake Factory

#### Quick Links:
- [DLF Homepage]()
- [DLF General FAQs]()
- [DLF Billing Details]()

### MRS - MapReduce Service

#### Quick Links:
- [MRS Homepage]()
- [MRS General FAQs]()
- [MRS Billing Details]()

### DWS - Data Warehouse Service

#### Quick Links:
- [DWS Homepage]()
- [DWS General FAQs]()
- [DWS Billing Details]()

### DLI - Data Lake Insight

#### Quick Links:
- [DLI Homepage]()
- [DLI General FAQs]()
- [DLI Billing Details]()

### CloudTable Service

#### Quick Links:
- [CloudTable Homepage]()
- [CloudTable General FAQs]()
- [CloudTable Billing Details]()

### CSS - Cloud Search Service

#### Quick Links:
- [CSS Homepage]()
- [CSS General FAQs]()
- [CSS Billing Details]()

### DLV - Data Lake Visualization

#### Quick Links:
- [DLV Homepage]()
- [DLV General FAQs]()
- [DLV Billing Details]()




## AI & Machine Learning (Enterprise Intelligence) 
| Huawei Cloud                                                                      | AWS                   | AZURE              | GCP                 |
| ---------------------                                                             | --------------------- | -------------------| ------------------- |
| [ModelArts](#modelarts)                                                           | SageMaker             | Machine Learning   | Machine Learning    |
| [OCR - Optical Character Recognition](#ocr---optical-character-recognition)       | Textract              | Cognitive          | Vision API          |
| [Image Recognition](#image-recognition)                                           | Rekognition           | Cognitive          | Vision API          |
| [FRS - Face Recognition Service](#frs---face-recognition-service)                 | Rekognition           | Cognitive          | Vision API          |
| [SIS - Speech Interaction Service](#sis---speech-interaction-service)             | Transcribe            | Cognitive          | Speech API          |
| [NLP - Natural Language Processing](#nlp---natural-language-processing)           | Comprehend            | Cognitive          | Natual Language API |
| [SIS - Speech Interaction Service - Translate](#sis---speech-interaction-service) | Translate             | Cognitive          | Translation API     |
| [SIS - Speech Interaction Service - TTS](#sis---speech-interaction-service)       | Polly                 | Cognitive          | Speech API          |
| [CBS - Conversational Bot Service](#cbs---conversational-bot-service)             | Lex                   | Bot                | Dialog Flow         |

* [EI Experience Center](https://www.huaweicloud.com/en-us/ei/experiencespace.html)

### ModelArts

#### Quick Links:
- [ModelArts Homepage]()
- [ModelArts General FAQs]()
- [ModelArts Billing Details]()

### OCR - Optical Character Recognition

#### Quick Links:
- [OCR Homepage]()
- [OCR General FAQs]()
- [OCR Billing Details]()

### Image Recognition

#### Quick Links:
- [Image Homepage]()
- [Image General FAQs]()
- [Image Billing Details]()

### FRS - Face Recognition Service

#### Quick Links:
- [FRS Homepage]()
- [FRS General FAQs]()
- [FRS Billing Details]()


### SIS - Speech Interaction Service

O Serviço Speech Interaction Service (SIS) fornece um modo de interação homem-máquina por APIs (Application Programming Interfaces). Você pode obter o resultado da interação da fala acessando em tempo real e chamando a API. O SIS consiste nos seguintes sub-serviços:

* Reconhecimento Automático de Fala (ASR): converte gravações de áudio em texto.

* ASR Customization (ASRC) aproveita a tecnologia de "deep learning" para otimizar o reconhecimento de fala em campos específicos e permite definir modelos de idioma. O ASRC fornece as funções de transcrição de sentenças e transcrição de áudio.

* Real-Time ASR (RASR): converte fluxos de áudio contínuos em texto em tempo real, permitindo um reconhecimento de fala mais rápido.

* Text To Speech (TTS): converte texto em vozes realistas.

* A personalização de texto em fala (TTSC) utiliza tecnologias avançadas de fala da Huawei, em combinação com algoritmos de depp learning, para converter texto em fala natural e suave.

#### Quick Links:
- [SIS Homepage]()
- [SIS General FAQs]()
- [SIS Billing Details]()

### NLP - Natural Language Processing

#### Quick Links:
- [NLP Homepage]()
- [NLP General FAQs]()
- [NLP Billing Details]()

### CBS - Conversational Bot Service

#### Quick Links:
- [CBS Homepage]()
- [CBS General FAQs]()
- [CBS Billing Details]()