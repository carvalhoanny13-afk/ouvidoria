# 📖 Como Usar o BI de Ouvidoria

## 1️⃣ Primeira Inicialização

### Passo 1: Abra o Arquivo Power BI
- Abra `ouvidoria_hotelaria.pbix`

### Passo 2: Conecte os Dados
- Siga `power-bi/guia_conexao_csv.md`

### Passo 3: Atualize os Dados
- Clique em "Atualizar" (ou Ctrl+Shift+R)

### Passo 4: Explore os Dashboards
- Abra a aba "Relatório"
- Explore cada página

---

## 2️⃣ Navegação pelos Dashboards

### Dashboard Executivo
**Para quem:** Superintendência, Diretoria
**Contém:** KPIs principais, gráficos resumidos
**Ação:** Apresentar mensalmente

### Dashboard Operacional
**Para quem:** Gerentes de unidades
**Contém:** Detalhes por unidade, análise de resolução
**Ação:** Consultar semanalmente

### Dashboard Detalhado
**Para quem:** Analistas, Supervisores
**Contém:** Filtros avançados, dados granulares
**Ação:** Usar para investigações específicas

---

## 3️⃣ Usando Slicers (Filtros)

### Filtro por Período
- Selecione data inicial e final
- Todos os gráficos se atualizam

### Filtro por Unidade
- Clique na unidade desejada
- Pressione Ctrl para múltipla seleção
- Clique em "Limpar filtro" para resetar

### Filtro por Tipo
- Selecione: Elogio, Reclamação, Sugestão
- Análise se atualiza automaticamente

### Filtro por Status
- Concluído, Pendente, Em Análise
- Mostra apenas manifestações selecionadas

---

## 4️⃣ Interpretando os Gráficos

### Gráfico de Distribuição (Pizza)
- Fatia maior = categoria dominante
- Útil para ver proporção de tipos

### Gráfico de Barras
- Barra mais longa = unidade com mais manifestações
- Use para identificar hotspots

### Gráfico de Linhas
- Linha para cima = mais manifestações
- Identifica períodos críticos

### Cards de KPI
- Número grande = valor principal
- Seta para cima (↑) = crescimento
- Seta para baixo (↓) = redução

---

## 5️⃣ Drill-Down (Aprofundamento)

### Como Funciona
1. Clique em um gráfico
2. Clique na categoria desejada (ex: "UPA Planaltina")
3. Gráficos se detalham para aquela categoria
4. Clique em "Voltar" para retornar

### Exemplo
- Clique na barra "UPA Planaltina"
- Dashboard mostra apenas dados dessa unidade
- Veja manifestions, tempo, etc específicos

---

## 6️⃣ Análises Comuns

### "Qual unidade tem mais problemas?"
1. Vá ao Dashboard Operacional
2. Observe o gráfico "Manifestações por Unidade"
3. Top 5 aparecerá destacado

### "Estamos cumprindo prazos?"
1. Dashboard Executivo
2. Verifique card "Meta de Prazo"
3. Verde (✅) = Meta atingida
4. Vermelho (❌) = Necessário ação

### "Qual é a satisfação dos usuários?"
1. Dashboard Executivo
2. Veja "Distribuição por Tipo"
3. Elogios altos = satisfação boa

### "Qual departamento está com problemas?"
1. Dashboard Operacional
2. Filtro por Unidade
3. Verifique tempo médio e volume

---

## 7️⃣ Exportar Dados

### Exportar Visualização como Imagem
1. Clique com botão direito no gráfico
2. Selecione "Exportar"
3. Escolha formato (PNG, JPG)

### Exportar Página como PDF
1. Clique em "Arquivo"
2. Selecione "Exportar para PDF"
3. Nomeie e salve

### Exportar Dados para Excel
1. Clique no gráfico
2. Clique em "Mais opções (...)"
3. Selecione "Exportar dados"

---

## 8️⃣ Atualizar Dados

### Atualização Manual
- Clique em "Atualizar"
- Power BI buscará novos dados do CSV

### Atualização Automática (Agendada)
1. Publique o BI na nuvem (Power BI Service)
2. Configure agendamento de atualização
3. Dados atualizarão automaticamente

---

## 9️⃣ Troubleshooting

### Problema: Gráfico em branco
- **Solução:** Clique em "Atualizar"
- Verifique se CSV foi carregado corretamente

### Problema: Filtros não funcionam
- **Solução:** Clique em "Limpar filtro"
- Reapplique manualmente

### Problema: Dados não aparecem
- **Solução:** Verifique se o CSV está conectado
- Confirme que colunas têm os nomes corretos

### Problema: Datas estão erradas
- **Solução:** Transformar dados → Alterar tipo para Data
- Selecione formato DD/MM/YYYY

---

## 🔟 Dicas Profissionais

✅ **Atualize dados diariamente**
- Mantenha informações sempre atualizadas

✅ **Crie snapshots mensais**
- Salve PDF com dados de cada mês
- Facilita comparações

✅ **Configure alertas**
- Se taxa de resolução cair abaixo de 90%
- Se tempo médio ultrapassar 12 dias

✅ **Compartilhe com time**
- Publique no Power BI Service
- Equipe acessa em qualquer dispositivo

✅ **Documente ações**
- Quando taxa sobe, documente causa
- Melhoria contínua

---
