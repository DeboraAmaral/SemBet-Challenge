# SemBet-Challenge - Plugin de Combate ao Vício em Apostas

> **📌 ENTREGA OFICIAL - BRANCH DEVELOP**
> *Esta branch contém a versão de entrega do projeto para correção.*

## 📋 Sobre o Projeto
O **SemBet-Challenge** é um plugin de navegador desenvolvido para combater o vício em apostas online, bloqueando proativamente o acesso a sites de apostas e fornecendo ferramentas de monitoramento para o usuário.

## 🧪 Testes e Qualidade

### PARTE A - Testes Manuais (Azure Boards)
**Plano de Testes de Validação no Nível de Sistema**

**Funcionalidades Principais Testadas:**
- ✅ Detecção e Bloqueio de Sites de Apostas
- ✅ Exibição de Página de Bloqueio
- ✅ Registro no Histórico de Bloqueios
- ✅ Navegação em Sites Permitidos

**Link de Acesso:** [Azure Boards - SemBet Project](https://dev.azure.com/RM97819/SemBet-Challenge/_backlogs/backlog/SemBet-Challenge%20Team/Backlog%20items)

### PARTE B - Testes de Automação
**Ferramenta Utilizada:** Selenium IDE

**Casos de Teste Automatizados:**
1. **ATA-01_Validar_Popup_Plugin** - Validação da interface principal
2. **ATA-02_Verificar_Historico_Bloqueios** - Verificação do histórico
3. **ATA-03_Validar_Pagina_Bloqueio** - Validação da página de bloqueio
4. **ATA-04_Navegacao_Site_Seguro** - Teste de navegação segura

**Vídeo de Demonstração:** [Clique aqui para ver o vídeo](https://drive.google.com/file/d/1rny6RQalQ7IoLsPbCxu3DBrk7PeT0Tgf/view?usp=sharing)

## 🚀 Como Executar os Testes

### Pré-requisitos
- Selenium IDE instalado no navegador
- Arquivo `.side` do projeto de automação

### Executando Testes Automatizados
1. Abra o Selenium IDE
2. Importe o arquivo `SemBet_Automation_Tests.side`
3. Execute os testes individualmente ou em suite

## 👥 Desenvolvido por
[Debora da Silva Amaral] - [RM550412]
[Eduardo Pielich Sanchez] - [RM99767]
[Livia Namba Seraphim] - [RM97819]

*Projeto acadêmico para disciplina de Testing, Compliance and Quality.*
