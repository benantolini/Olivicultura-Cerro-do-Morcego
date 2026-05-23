# 🫒 Olivicultura — Cerro do Morcego

Dashboard financeiro interativo para planejamento da olivicultura no **Cerro do Morcego**, Missões/RS.

## 🌐 Acesso Online

**👉 [Abrir Dashboard](https://benantolini.github.io/olivicultura-cerro-do-morcego/)**

> O link acima ficará ativo após ativar o **GitHub Pages** nas configurações do repositório (veja instruções abaixo).

---

## 📊 Funcionalidades do Dashboard

| Aba | Conteúdo |
|-----|----------|
| 📈 **Fluxo de Caixa** | Receita vs Custos anuais · Fluxo acumulado · Payback |
| 💰 **Custos Detalhados** | Composição por categoria · Cards com detalhamento R$/ha |
| 🫒 **Produção** | Área plantada vs em produção · Curva de produtividade por lote |
| 🏭 **Comparativo Lagar** | Lagar 3° vs Lagar próprio · Break-even · Delta acumulado |
| 📋 **Tabela Completa** | Todos os anos com todos os valores · Exportável em CSV |

### ⚙️ Premissas Ajustáveis (em tempo real)

- 🌱 **Escala de Plantio** — lote inicial, incremento anual, anos de expansão
- 🏗️ **Implantação** — preparo de solo, mudas, irrigação, infraestrutura, mão de obra
- 🌿 **Manutenção Pré-Produção** — insumos e mão de obra (anos 1–3)
- 🫒 **Operação do Pomar** — insumos, colheita, mão de obra (ano 4+)
- 🚛 **Lagar Terceirizado** — custo por kg de azeitona
- 🏭 **Lagar Próprio** — ano de implantação, investimento, custos fixos e variáveis
- 📊 **Mercado** — preço do azeite extravirgem (R$/L)

---

## 🚀 Como Publicar Online (GitHub Pages)

1. Acesse **Settings** do repositório no GitHub
2. Clique em **Pages** (menu lateral esquerdo)
3. Em **Source**, selecione: **Branch: `main`** · Pasta: **`/ (root)`**
4. Clique em **Save**
5. Aguarde ~2 minutos e acesse: `https://benantolini.github.io/olivicultura-cerro-do-morcego/`

---

## 📁 Estrutura

```
/
├── index.html          ← Dashboard principal (HTML + JS inline, zero dependências locais)
├── .nojekyll           ← Desativa processamento Jekyll do GitHub Pages
└── README.md
```

---

*Modelo financeiro v2025 · Referências Embrapa/SEAPI · Dados estimados para planejamento — consulte técnico habilitado para projeto agronômico oficial*
