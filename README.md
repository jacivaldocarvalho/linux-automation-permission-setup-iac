# **Infraestrutura como Código: Criação de Usuários, Diretórios e Permissões**

## **Objetivo**
Este repositório fornece uma solução prática para a criação de **usuários**, **diretórios** e **permissões** no sistema Linux utilizando **Infraestrutura como Código (IaC)**. Através de scripts em **Shell**, é possível automatizar o processo de configuração de usuários e permissões, aumentando a eficiência e segurança em ambientes de TI.


## **Estrutura do Projeto**

O repositório contém os seguintes arquivos:

- **`README.md`**: Documentação do projeto.
- **`iac-01.sh`**: Script para criar a estrutura de usuários.
- **`iac-02.sh`**: Script para configurar permissões e diretórios associados.
- **`criar_user.sh`**: Script responsável pela criação de novos usuários no sistema.

### **Exemplo de Estrutura de Arquivos:**
```bash
├── README.md
├── criar_user.sh
├── iac-01.sh
└── iac-02.sh
```


## **Como Usar**

### **Requisitos**
- Sistema operacional Linux ou ambiente compatível.
- Permissões de superusuário (root) para execução dos scripts.
  
### **1. Clonando o Repositório**

Clone o repositório em sua máquina:

```bash
git clone https://github.com/jacivaldocarvalho/linux-projeto1-iac.git
cd linux-projeto1-iac
```

### **2. Executando os Scripts**

Após a clonagem, é possível rodar os scripts para configurar os usuários, diretórios e permissões.

Para rodar o script de criação de usuários:

```bash
bash criar_user.sh
```

Para rodar a configuração de permissões e diretórios:

```bash
bash iac-01.sh
bash iac-02.sh
```


## **Evoluções Possíveis para o Projeto**

### 1. **Suporte a Múltiplos Ambientes**
Implemente diferentes configurações para ambientes distintos (desenvolvimento, teste, produção) através de variáveis de ambiente ou múltiplos arquivos de configuração. Isso permitirá que a infraestrutura seja mais flexível.

### 2. **Integração com Ferramentas de CI/CD**
Adicione integração com ferramentas como **Jenkins** ou **GitLab CI** para automatizar a execução desses scripts durante o processo de integração contínua, facilitando a gestão de ambientes em larga escala.

### 3. **Validação de Configurações**
Implemente uma camada de verificação que valide se os usuários, diretórios e permissões foram configurados corretamente, garantindo a integridade da infraestrutura.

### 4. **Criação de Grupos e Roles**
Expanda os scripts para incluir a criação de **grupos de usuários** e a atribuição de **roles** específicas para maior controle de acessos.

## Contribuições

Se você tiver sugestões de melhorias ou encontrar problemas com o script, sinta-se à vontade para abrir um **issue** ou submeter um **pull request**.

## Contatos e Network

- **LinkedIn**: [LinkedIn](https://www.linkedin.com/in/jacivaldocarvalho/) 👔
- **E-mail**: [E-mail](mailto:jacivaldocarvalho@gmail.com) 📧
- **GitHub**: [GitHub](https://github.com/jacivaldocarvalho) 🐙
- **Medium**: [Medium](https://medium.com/@jacivaldocarvalho) ✍️

Sempre aberto a novas conexões e oportunidades de aprendizado!

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## **Referências Bibliográficas**

- [Documentação Oficial do Bash](https://www.gnu.org/software/bash/manual/)
- [Infraestrutura como Código: Conceitos e Práticas](https://www.redhat.com/pt-br/topics/automation/what-is-infrastructure-as-code)
- [Gerenciamento de Usuários no Linux](https://linux.die.net/man/8/useradd)
