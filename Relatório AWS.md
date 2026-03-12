# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 12/03/2026  
**Empresa:** Abstergo Industries  
**Responsável:** Vinicius José  

---

# Introdução

Este relatório apresenta o processo de implementação de serviços em nuvem na empresa **Abstergo Industries**, realizado por **Vinicius José**.

A Abstergo atua como um **hub de integração entre diversas empresas**, sendo responsável pelo processamento, armazenamento e comunicação de dados entre diferentes sistemas.

O objetivo deste projeto foi selecionar e implementar **três serviços da Amazon Web Services (AWS)** com a finalidade de **reduzir custos operacionais imediatos**, além de melhorar a **escalabilidade, disponibilidade e eficiência da infraestrutura tecnológica**.

---

# Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em **três etapas**, cada uma com objetivos específicos voltados à redução de custos e otimização da infraestrutura utilizada pela empresa.

---

# Etapa 1

- **Nome da ferramenta:** Amazon S3  
- **Foco da ferramenta:** Armazenamento escalável e de baixo custo  

### Descrição de caso de uso

O **Amazon S3 (Simple Storage Service)** foi implementado para armazenar arquivos, documentos, logs de integração e dados trocados entre os sistemas das empresas parceiras da Abstergo.

Anteriormente, esses dados eram armazenados em servidores locais, o que gerava custos elevados relacionados à infraestrutura física, manutenção e backup.

Com a implementação do Amazon S3 foi possível:

- Reduzir custos com armazenamento
- Garantir maior durabilidade e segurança dos dados
- Implementar backups automáticos
- Escalar o armazenamento conforme a demanda

O serviço utiliza o modelo **pay-as-you-go**, no qual a empresa paga apenas pelo armazenamento utilizado.

---

# Etapa 2

- **Nome da ferramenta:** Amazon EC2  
- **Foco da ferramenta:** Computação em nuvem sob demanda  

### Descrição de caso de uso

O **Amazon EC2 (Elastic Compute Cloud)** foi utilizado para hospedar as aplicações responsáveis pela comunicação entre os sistemas das empresas integradas ao hub da Abstergo.

A adoção deste serviço permitiu substituir servidores físicos por **instâncias virtuais escaláveis**, reduzindo custos de infraestrutura e manutenção.

Entre os principais benefícios obtidos estão:

- Criação de servidores virtuais sob demanda
- Ajuste da capacidade computacional conforme a necessidade
- Redução de custos com hardware físico
- Maior disponibilidade e confiabilidade da aplicação

Além disso, a utilização de recursos como **Auto Scaling** possibilita aumentar ou diminuir automaticamente a quantidade de servidores conforme o volume de requisições.

---

# Etapa 3

- **Nome da ferramenta:** AWS Lambda  
- **Foco da ferramenta:** Processamento serverless  

### Descrição de caso de uso

O **AWS Lambda** foi implementado para executar rotinas automatizadas responsáveis pelo processamento de eventos e integração entre sistemas parceiros da Abstergo.

Entre as tarefas realizadas estão:

- Processamento de eventos de integração
- Transformação de dados entre sistemas
- Execução de rotinas automatizadas
- Processamento de arquivos enviados para a plataforma

Com a utilização de uma arquitetura **serverless**, não é necessário manter servidores em execução contínua, pois o código é executado apenas quando necessário.

Isso proporciona benefícios como:

- Redução significativa de custos operacionais
- Escalabilidade automática
- Menor necessidade de gerenciamento de infraestrutura
- Execução eficiente de tarefas sob demanda

---

# Conclusão

A implementação dos serviços **Amazon S3, Amazon EC2 e AWS Lambda** na empresa **Abstergo Industries** proporciona uma infraestrutura mais eficiente, escalável e econômica.

A adoção dessas soluções em nuvem permite reduzir custos operacionais relacionados à manutenção de servidores físicos, além de melhorar a disponibilidade e o desempenho das aplicações utilizadas pela empresa.

Recomenda-se a continuidade do uso dessas ferramentas e a avaliação constante de novos serviços da AWS que possam contribuir para a otimização dos processos e melhoria contínua da infraestrutura tecnológica da organização.

---

# Anexos

- Documentação oficial dos serviços AWS utilizados
- Diagramas de arquitetura da solução em nuvem
- Planilha de estimativa de custos da AWS
- Guia de boas práticas para uso dos serviços AWS

---

# Assinatura do Responsável pelo Projeto

**Vinicius José**
