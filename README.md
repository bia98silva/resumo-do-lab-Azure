# Resumo do Lab - Azure (DIO)

Este repositório contém um resumo das lições aprendidas durante o desenvolvimento do laboratório sobre computação em nuvem oferecido pela **DIO (Digital Innovation One)**.

## Tipos de Nuvem

Durante o laboratório, foram apresentados os principais tipos de nuvem:

- **Nuvem Privada:**  
  A nuvem privada é acessada apenas por pessoas de uma organização específica. A própria organização é responsável por operar e manter os serviços hospedados.

- **Nuvem Pública:**  
  Utiliza datacenters distribuídos ao redor do mundo. Os recursos são compartilhados entre diversas organizações e usuários, com gestão e infraestrutura fornecidas por provedores como Microsoft Azure, AWS, entre outros.

- **Nuvem Híbrida:**  
  Combina os dois modelos anteriores. A organização possui uma nuvem privada que se comunica com a nuvem pública, possibilitando maior flexibilidade e escalabilidade. É considerada uma solução que reúne o melhor dos dois mundos.

## Diferença entre CAPEX e OPEX

- **CAPEX (Capital Expenditure):**  
  Refere-se aos gastos iniciais com infraestrutura física. São investimentos que se depreciam com o tempo, como a compra de servidores e equipamentos.

- **OPEX (Operational Expenditure):**  
  Refere-se às despesas operacionais com produtos e serviços. Um exemplo é o uso de recursos na nuvem, como o Azure, onde a cobrança é feita conforme o tempo de uso. Quanto mais tempo o recurso for utilizado, maior será o custo.

---

📌 *Esse conteúdo faz parte do programa de capacitação em tecnologia da DIO, com foco em computação em nuvem e serviços Azure.*

# 💻 Guia Rápido: Criando uma Máquina Virtual no Microsoft Azure

Este guia descreve os passos para criar uma máquina virtual (VM) no portal do Microsoft Azure.

---

## 🧭 Passos para criar uma VM no Azure

### 1. Acesse o portal do Azure
- Vá para: [https://portal.azure.com](https://portal.azure.com)
- Faça login com sua conta Microsoft.

---

### 2. Inicie a criação da VM
- No menu lateral, clique em **Máquinas virtuais**.
- Clique em **Criar > Máquina virtual**.

---

### 3. Configurações básicas
- **Assinatura**: Selecione sua assinatura ativa.
- **Grupo de Recursos**: Escolha um grupo existente ou clique em *Criar novo*.
- **Nome da VM**: Dê um nome à sua máquina virtual.
- **Região**: Escolha a região onde deseja hospedar a VM (ex: *Brasil Sul*).
- **Imagem**: Selecione o sistema operacional (ex: *Ubuntu 22.04 LTS*, *Windows Server 2022*, etc.).
- **Tamanho da VM**: Selecione um tamanho compatível com seu uso (ex: *B1s* para testes).
- **Usuário administrador**:
  - Nome de usuário
  - Autenticação por senha ou chave SSH

---

### 4. Configurar discos
- **Tipo de disco do SO**: SSD padrão, SSD premium ou HDD.
- Pode adicionar discos adicionais, se necessário.

---

### 5. Rede
- Uma interface de rede virtual será criada automaticamente.
- Pode manter as configurações padrão para testes.

---

### 6. Revisar + criar
- Revise todas as configurações.
- Clique em **Criar** para iniciar a criação da VM.

---

## ✅ Dicas
- **Para acesso remoto**: Certifique-se de permitir portas como:
  - **22** para SSH (Linux)
  - **3389** para RDP (Windows)
- **Recursos gratuitos**: Se você estiver usando uma conta gratuita, verifique os limites antes de criar.

---

> 🔒 Não se esqueça de encerrar a VM quando não estiver usando para evitar cobranças desnecessárias!

