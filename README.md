
# Huawei Cloud Comparison

Comparison of Huawei Cloud services vs AWS vs Azure vs GCP

## Compute 

| Huawei Cloud          | AWS                            | AZURE               | GCP                 |
| --------------------- | ------------------------------ | ------------------- | ------------------- |
| [ECS](#ecs---elastic-cloud-server)                   | EC2                            | VM                  | Compute Engine      |
| [Batch](#batch)                 | Batch                          | Batch               | Batch               |
| [IMS](#ims---image-management-service)                   | AMI                            | VM Images           | Images              |
| [Auto Scaling](#auto-scaling)          | EC2 Auto Scaling               | AutoScale           | AutoScaler          |
| [CCE](#cce---cloud-container-engine)                   | ECS  Elastic Container Service | Kubernetes Service  | Kubernetes Engines  |
| [CCI](#cci---cloud-container-instance)                   | Fargate                        | Container Instances | Cloud Run           |
| [FunctionGraph](#functiongraph)        | Lambda                         | Function Apps       | Cloud Functions     |
| [Bare Metal Server](#bms---bare-metal-server)     |                                |                     |                     |

### ECS - Elastic Cloud Server
Um Elastic Cloud Server (ECS) é um servidor em nuvem que fornece recursos de computação escaláveis e sob demanda para aplicativos seguros, flexíveis e eficientes.
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
| Huawei Cloud                                 | AWS                   | AZURE               | GCP                 |
| ---------------------                        | --------------------- | ------------------- | ------------------- |
| [Elastic Volume Service](#evs---elastic-volume-service)                   | EBS                   | Disk Storage        | Persistent Disk     |
| [Cloud Server Backup Service](#csbs---cloud-server-backup-service)              | Backup                | Backup              | Backup              |
| [Volume Backup Service](#vbs---volume-backup-service)                    | Backup                | Backup              |                     |
| [Object Storage Service](#obs---object-storage-service)                   | S3                    | Blob Storage        | Cloud Storage       |
| [Scalable File Service](#sfs---scalable-file-service)                    | SFS                   | Files               | File Storage        |
| [Data Express Service*](#des---data-express-service)                     | Snowball              | NA                  | NA                    |

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
Maiores informações sobre o Huawei [Teleport] appliance: 
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
| Huawei Cloud                                              | AWS                   | AZURE                     | GCP                 |
| ---------------------                                     | --------------------- | -------------------       | ------------------- |
| [Virtual Private Cloud](#vpc---virtual-private-cloud)     | VPC                   | Virtual Network           | Virtual Network     |
| [Elastic Load Balance](#elb---elastic-load-balance)       | ELB                   | Load Balancer             | Load Balancing      |
| [Virtual Private Network](#vpn---virtual-private-network) | VPN                   | Connections               | VPN                 |
| [Direct Connect](#direct-connect)                         | Direct Connect        | ExpressRoute              | Interconnect        |
| [DNS](#dns)                                               | Route 53              | DNS                       | DNS                 |
| [NAT Gateway](#nat-gateway)                               | NAT Gateway           | Virtual Network Gateway   |                     |
| [CDN](#cdn)                                               | CloudFront            | CDN                       | Cloud CDN           |
| [API Gateway](#api-gateway)                               | API Gateway           |                           |                     |

### VPC - Virtual Private Cloud

#### Quick Links:
- [VPC Homepage]()
- [VPC General FAQs]()
- [VPC Billing Details]()

### ELB - Elastic Load Balance

#### Quick Links:
- [ELB Homepage]()
- [ELB General FAQs]()
- [ELB Billing Details]()

### VPN - Virtual Private Network

#### Quick Links:
- [VPN Homepage]()
- [VPN General FAQs]()
- [VPN Billing Details]()

### Direct Connect

#### Quick Links:
- [Direct Connect Homepage]()
- [Direct Connect General FAQs]()
- [Direct Connect Billing Details]()

### DNS

#### Quick Links:
- [DNS Homepage]()
- [DNS General FAQs]()
- [DNS Billing Details]()

### NAT Gateway

#### Quick Links:
- [NAT Gateway Homepage]()
- [NAT Gateway General FAQs]()
- [NAT Gateway Billing Details]()

### CDN

#### Quick Links:
- [CDN Homepage]()
- [CDN General FAQs]()
- [CDN Billing Details]()

### API Gateway

#### Quick Links:
- [API Gateway Homepage]()
- [API Gateway General FAQs]()
- [API Gateway Billing Details]()



## Management
### IAM

## Database
### RDS

## Security
### Anti-DDoS

## Application & Middleware
### 

## Big Data

## AI & Machine Learning

