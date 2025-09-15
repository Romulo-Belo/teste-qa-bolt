---Teste QA - Bolt.com.br | Menu Institucional---
**Análise Completa de Funcionalidades e Bugs**

Observação: **Limitações Temporais do Teste**
**Período de Análise:** Realizados no dia 12 de Setembro de 2025
**Escopo Temporal:** Snapshot pontual do sistema
**Atualizações Posteriores:** Não monitoradas após a data de execução
**Validade:** Resultados válidos para o estado do sistema em 12/09/2025

**Nota:** Para validação de correções implementadas após 12 de Setembro de 2025, será necessário novo ciclo de testes.
---

 **Informações do Teste**
- **QA Tester:** Rômulo Belo
- **Site Analisado:** https://bolt.com.br/
- **Data:** Setembro 2025
- **Objetivo:** Teste exploratório do Menu Institucional
- **Ambiente:** Chrome, Firefox, Dispositivo Mobile

ARQUIVOS
Relatório_de_bug_CT001.pdf --
Bug report detalhado com passos para reprodução, resultado esperado/obtido e severidade.


Casos Teste Exploratórios_Menu Institucional.xlsx --
Planilha de testes exploratórios feitos no menu institucional, com ações realizadas, observações e bugs encontrados.


Casos de Teste_Menu Institucional.feature.pdf --
Cenários escritos em BDD/Gherkin cobrindo os links do menu institucional.


LEIA-ME.md --
Arquivo de orientação sobre os documentos do repositório.


Registro de bug no Menu Institucional.pdf --
Lista de bugs encontrados no menu institucional, com descrição, passos, severidade e prioridade.


TESTE EXPLORATÓRIO E POSSÍVEIS MELHORIAS - BOLT.pdf --
Relatório de exploração da página Bolt com problemas identificados e sugestões de melhoria.

---

 **Escopo do Teste**
Análise completa dos 7 itens do Menu Institucional:
- ✅ Sobre a Bolt
- ✅ Grupo Adriano Cobuccio  
- ✅ Atendimento Online
- ✅ Ouvidoria
- ✅ Contato
- ✅ Política de Segurança Cibernético
- ✅ Política e Normas Internas de PLD

---

## **PRINCIPAIS DESCOBERTAS CRÍTICAS**

### **Problemas Críticos Encontrados:**
- 🔴 **CT001 - Sobre a Bolt:** Tenta acessar IP interno (192.168.0.33) - Timeout
- 🔴 **CT003 - Atendimento Online:** Apenas recarrega página, não inicia suporte
- 🔴 **CT004 - Ouvidoria:** Página Not Found
- 🔴 **CT005 - Contato:** Página Not Found  
- 🟡 **CT006 - Política Segurança:** Página Not Found
- 🟡 **CT007 - Política PLD:** Página Not Found

### **Funcionalidades OK:**
- ✅ **CT002 - Grupo Adriano Cobuccio:** Funcionando corretamente
- ✅ **Header completo:** Todos os botões do cabeçalho funcionais
- ✅ **Responsividade:** Site adapta bem ao mobile

