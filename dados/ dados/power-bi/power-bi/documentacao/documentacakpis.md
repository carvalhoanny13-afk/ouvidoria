
## 📄 **ARQUIVO 4: documentacao/kpis.md**

```markdown
# 🎯 KPIs - Indicadores Chave de Performance

## 1. Volume Total de Manifestações

**O quê:** Número total de manifestações registradas no período

**Fórmula DAX:**
```dax
Total_Manifestacoes = COUNTA('Ouvidoria'[N_PROCESSO])
