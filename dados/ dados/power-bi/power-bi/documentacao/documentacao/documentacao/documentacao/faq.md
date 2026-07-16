# ❓ FAQ - Perguntas Frequentes

## Dados

### P: Como conecto um banco de dados em vez de CSV?
**R:** 
1. No Power BI, clique em "Obter dados"
2. Selecione "SQL Server", "MySQL", etc.
3. Insira credenciais do banco
4. Siga o mesmo processo de mapeamento de colunas

---

### P: Com que frequência devo atualizar os dados?
**R:** 
- Recomendado: **Diariamente** (de manhã)
- Crítico: **A cada 4-6 horas** em análises urgentes
- Mínimo: **Semanalmente**

---

### P: Como adiciono dados históricos?
**R:**
1. Adicione linhas ao CSV existente
2. Clique em "Atualizar" no Power BI
3. Dados históricos aparecerão automáticamente

---

## KPIs

### P: Por que minha taxa de resolução é diferente?
**R:** Verifique:
- Dados atualizados?
- Definição correta de "Concluído"?
- Período selecionado está correto?

---

### P: Como alterar a meta de dias para resolução?
**R:**
1. Clique em "Transformar dados"
2. Encontre a medida DAX "Meta_Prazo"
3. Altere `<= 10` para o valor desejado
4. Salve

---

### P: O que fazer se temos muitas pendências?
**R:**
1. Identifique unidades com mais pendências
2. Verifique responsável por cada uma
3. Agende reunião de follow-up
4. Documente ações tomadas

---

## Dashboards

### P: Como mudar as cores dos gráficos?
**R:**
1. Clique no gráfico
2. Na aba "Formatar visual"
3. Expanda "Cores de dados"
4. Escolha nova paleta

---

### P: Posso criar meu próprio dashboard?
**R:** 
Sim! 
1. Clique em "Nova página"
2. Arraste campos para o canvas
3. Escolha tipo de visualização
4. Configure filtros

---

### P: Como compartilho o BI com meu time?
**R:**
**Opção 1 - Local:**
- Salve `.pbix` em pasta compartilhada

**Opção 2 - Nuvem:**
1. Clique em "Publicar"
2. Selecione workspace
3. Team terá acesso online

---

## Problemas Técnicos

### P: Power BI abre muito lentamente
**R:**
1. Reduz período de dados (ex: últimos 6 meses)
2. Remove visualizações desnecessárias
3. Desativa atualização automática
4. Reinicia Power BI Desktop

---

### P: Erro ao conectar CSV
**R:**
1. Verifique encoding UTF-8
2. Confirma delimitador (vírgula/ponto-e-vírgula)
3. Não deixe arquivo aberto em Excel
4. Salva CSV novamente

---

### P: Gráficos não se atualizam ao filtrar
**R:**
1. Clique em "Atualizar"
2. Verifique se filtro está conectado aos dados
3. Em "Transformar dados", confirme relações

---

## Apresentações

### P: Devo usar tema escuro ou claro?
**R:** 
- **Claro:** Melhor para projetor em sala clara
- **Escuro:** Melhor para sala escura
- Verifique local antes!

---

### P: Como imprimir o BI em papel?
**R:**
1. Clique em "Arquivo" → "Imprimir"
2. Escolha "Colorido" para melhor resultado
3. Formato A3 é ideal para legibilidade
4. Use papel brilhante se possível

---

### P: Preciso fazer backup?
**R:**
**Sim!**
1. Salva `.pbix` em pastas sincronizadas (OneDrive, SharePoint)
2. Exporta dados mensalmente em Excel
3. Arquiva PDFs de relatórios
4. Mantém backup do CSV original

---

## Melhorias

### P: Como adiciono novos KPIs?
**R:**
1. Transformar dados
2. Nova coluna calculada
3. Crie medida DAX
4. Adicione ao dashboard

---

### P: Posso integrar com outras ferramentas?
**R:**
- Excel: Copiar dados
- Power Automate: Automatizar atualizações
- SharePoint: Integrar dashboards em sites
- Outlook: Agendar envios de relatórios

---

### P: Como recebo alertas de anomalias?
**R:**
1. Publicar no Power BI Service
2. Definir alertas de dados
3. Receber notificações por email

---

## Suporte

### P: Onde encontro mais ajuda?
**R:**
- Documentação: `documentacao/`
- Guia Conexão: `power-bi/guia_conexao_csv.md`
- KPIs: `documentacao/kpis.md`
- Design: `documentacao/design_tips.md`

---

### P: Como reporto um problema?
**R:**
1. Descreva o erro
2. Anexe screenshot
3. Indique passo a passo para reproduzir
4. Envie para o time de BI

---
