
# Huawei Cloud Comparison

Comparison of Huawei Cloud services vs AWS vs Azure vs GCP

## Compute

| Huawei Cloud          | AWS                   | AZURE               | GCP                 |
| --------------------- | --------------------- | ------------------- | ------------------- |
| ECS                   | EC2                   | VM                  | Compute Engine      |
| Batch                 | Batch                 | Batch               | Batch               |
| IMS                   | AMI                   | VM Images           | Images              |
| Auto Scaling          | EC2 Auto Scaling      | AutoScale           | AutoScaler          |
| CCE                   | ECS                   | Kubernetes Service  | Kubernetes Engines  |
| CCI                   | Fargate               | Container Instances | Cloud Run           |
| Function Graph        | Lambda                | Function Apps       | Cloud Functions     |
| Bare Metal Server     |                       |                     |                     |

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
| Huawei Cloud          | AWS                   | AZURE               | GCP                 |
| --------------------- | --------------------- | ------------------- | ------------------- |
| ECS                   | 3.5.1                 | 3.5.1               | 3.5.1               |
| Batch                 | 2.8.3                 | 3.1.1               | 3.5.1               |
| IMS                   | 1.3.1                 | 2.1.1               | 3.5.1               |
| Auto Scaling          | 2.3.0                 | NA                  | 3.5.1               |
| CCE                   | NA                    | 0.9.1               | 3.5.1               |
| CCI                   | 1.3.0                 | 3.1.0               | 3.5.1               |
| Function Graph        | 1.2.1                 | 1.2.1               | 3.5.1               |
| Dedicated Host        | 2.2.1                 | 2.3.2               | 3.5.1               |
| GPU                   | 1.3.1(Plan to update) | 1.5.1               | 3.5.1               |
| FPGA                  | 0.215                 | 308                 | 3.5.1               |
| Bare Metal Server     | 1.1.0                 | 1.1.0               | 3.5.1               |
### EVS
#### Quick Links:
- [Sample Course](https://education.huaweicloud.com:8443/courses/course-v1:HuaweiX+CBUCNXE006+Self-paced/about?isAuth=0&cfrom=hwc), can get the introductory tutorial of MRS.
- [ECS Homepage](https://www.huaweicloud.com/en-us/product/mrs.html)

## Networking
| Huawei Cloud          | AWS                   | AZURE               | GCP                 |
| --------------------- | --------------------- | ------------------- | ------------------- |
| ECS                   | 3.5.1                 | 3.5.1               | 3.5.1               |
| Batch                 | 2.8.3                 | 3.1.1               | 3.5.1               |
| IMS                   | 1.3.1                 | 2.1.1               | 3.5.1               |
| Auto Scaling          | 2.3.0                 | NA                  | 3.5.1               |
| CCE                   | NA                    | 0.9.1               | 3.5.1               |
| CCI                   | 1.3.0                 | 3.1.0               | 3.5.1               |
| Function Graph        | 1.2.1                 | 1.2.1               | 3.5.1               |
| Dedicated Host        | 2.2.1                 | 2.3.2               | 3.5.1               |
| GPU                   | 1.3.1(Plan to update) | 1.5.1               | 3.5.1               |
| FPGA                  | 0.215                 | 308                 | 3.5.1               |
| Bare Metal Server     | 1.1.0                 | 1.1.0               | 3.5.1               |
### VPC
#### Quick Links:
- [Sample Course](https://education.huaweicloud.com:8443/courses/course-v1:HuaweiX+CBUCNXE006+Self-paced/about?isAuth=0&cfrom=hwc), can get the introductory tutorial of MRS.
- [ECS Homepage](https://www.huaweicloud.com/en-us/product/mrs.html)

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

