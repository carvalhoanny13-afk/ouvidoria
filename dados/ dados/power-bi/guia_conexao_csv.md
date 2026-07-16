# 🔌 Guia: Conectar CSV ao Power BI

## Passo a Passo

### 1️⃣ Abra Power BI Desktop

- Clique em "Obter dados"
- Selecione "Texto/CSV"

### 2️⃣ Selecione o Arquivo

- Navegue até seu arquivo CSV
- Clique em "Abrir"

### 3️⃣ Visualize Preview

- Power BI mostrará uma prévia
- Clique em "Carregar" para prosseguir
- OU clique em "Transformar dados" para editar

### 4️⃣ Configure Delimitador

Se o arquivo não abrir corretamente:
- Clique em "Transformar dados"
- Na aba "Início", clique em "Dividir Coluna"
- Escolha o delimitador correto (vírgula ou ponto-e-vírgula)

### 5️⃣ Validar Tipos de Dados

- Clique em "Transformar dados"
- Para cada coluna, verifique o tipo:
  - 📅 DATA_REGISTRO → Data
  - 📅 DATA_RESPOSTA → Data
  - 🔢 DIAS_RESOLUCAO → Número Inteiro
  - 📝 Outras → Texto

Para alterar: Clique no ícone de tipo no cabeçalho da coluna

### 6️⃣ Criar Tabela Calendário (Opcional)

Melhora análises por data:

```dax
Calendário = 
CALENDAR(
    MIN('Ouvidoria'[DATA_REGISTRO]),
    MAX('Ouvidoria'[DATA_RESPOSTA])
)
