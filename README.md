# Script de Análise e Relatório do Servidor Linux

Este repositório contém um script para Linux que gera um relatório detalhado sobre diversos aspectos do servidor. O script foi projetado para fornecer uma visão abrangente do estado e das configurações do servidor, abordando as seguintes áreas:

## Funcionalidades

1. **Relatório Consolidado do Servidor**
   - Gera um relatório geral sobre o servidor, consolidando as principais informações.

2. **Informações do Servidor (Hardware)**
   - Coleta dados detalhados sobre o hardware do servidor, incluindo CPU, memória e discos.

3. **Informações dos Usuários (Acessos e Permissões)**
   - Exibe informações sobre os usuários do sistema, incluindo acessos e permissões concedidas.

4. **Informações sobre Permissões (Arquivos e Diretórios Diversos)**
   - Relata as permissões configuradas para arquivos e diretórios importantes.

5. **Informações dos Serviços/Produtos Web**
   - Fornece detalhes sobre os serviços e produtos web em execução no servidor.

6. **Informações sobre Portas de Conexão Abertas (Server/Client)**
   - Lista as portas de conexão abertas e os serviços que as utilizam.

7. **Informações sobre Serviço de Horário (NTP)**
   - Mostra o status e a configuração do serviço de sincronização de horário (NTP).

8. **Informações sobre Serviço de Autenticação (SSH)**
   - Apresenta detalhes sobre a configuração e status do serviço SSH.

9. **Informações sobre Aplicações/Pacotes Instalados (Inclusive PHP)**
   - Relata as aplicações e pacotes instalados no servidor, com destaque para o PHP.

10. **Informações sobre Rotinas de Recuperação de Arquivos (Backup)**
    - Fornece informações sobre as rotinas de backup configuradas no servidor.

11. **Informações sobre Camadas de Segurança Aplicadas**
    - Exibe as camadas de segurança aplicadas, incluindo firewalls e outras medidas.

12. **Informações sobre o Serviço de Agendamentos (CRON)**
    - Mostra as tarefas agendadas no sistema através do CRON.

13. **Informações sobre o SGBD do Servidor**
    - Apresenta detalhes sobre o Sistema de Gerenciamento de Banco de Dados (SGBD) em uso.

14. **Análise dos Arquivos de Log das Aplicações e Serviços Não Web**
    - Analisa os arquivos de log das aplicações e serviços não relacionados à web.

15. **Informações da Quantidade de Acessos a Páginas Web (Incluso por Status HTTP)**
    - Fornece estatísticas sobre o acesso às páginas web, incluindo informações por status HTTP.

16. **Análise dos Arquivos de Log dos Serviços Web (Identificar Tentativas de Acesso Não Autorizado)**
    - Analisa os arquivos de log dos serviços web para identificar tentativas de acesso não autorizado.

## Como Usar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seurepositorio/script-relatorio-linux.git
    cd script-relatorio-linux
    ```

2. Torne o script executável:
    ```bash
    chmod +x script.sh
    ```

3. Execute o script:
    ```bash
    ./script.sh
    ```

## Requisitos

- Bash
- Ferramentas padrão do Linux (ex.: `ps`, `df`, `netstat`, `grep`, `awk`)

## Contribuição

Sinta-se à vontade para contribuir com melhorias ou correções. Para isso, por favor, siga o fluxo de trabalho de pull request padrão do GitHub.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Se você tiver dúvidas ou sugestões, abra uma [issue](https://github.com/seurepositorio/script-relatorio-linux/issues).
