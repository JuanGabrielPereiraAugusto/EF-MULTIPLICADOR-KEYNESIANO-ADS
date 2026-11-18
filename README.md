# 💰 Economia e Finanças — Multiplicador Keynesiano aplicado ao setor de ADS

Trabalho da disciplina de **Economia e Finanças** na **Fatec Taquaritinga** que responde à pergunta:

> **Que medidas eu adotaria, se estivesse no governo, para incentivar o setor de Análise e Desenvolvimento de Sistemas na região de Taquaritinga?**

A proposta usa o **multiplicador keynesiano do investimento** para mostrar quanto de renda cada real investido pode gerar na região.

📄 **Trabalho completo:** [`Economia_e_Financas_Multiplicador_Keynesiano.docx`](Economia_e_Financas_Multiplicador_Keynesiano.docx) (9 páginas)

---

## 📐 O multiplicador keynesiano

Segundo Keynes, a renda depende da demanda agregada:

```
Y = C + I + G + (X − M)
```

Cada real gasto vira renda de alguém, que gasta de novo uma parte dele, e assim por diante. Numa **economia regional**, parte da renda "vaza" em **impostos (t)** e em **compras de fora da região (m)**:

```
k = 1 / [1 − c(1 − t) + m]
```

| Parâmetro (hipotético) | Valor |
|---|---|
| Propensão marginal a consumir (c) | 0,8 |
| Alíquota de impostos (t) | 0,2 |
| Propensão a importar (m) | 0,1 |
| **Multiplicador do gasto direto (k)** | **≈ 2,17** |
| **Multiplicador de transferências (c × k)** | **≈ 1,74** |

👉 Cada **R$ 1,00** investido diretamente gera cerca de **R$ 2,17** de renda na região.

---

## 🏛️ As 7 medidas propostas

| # | Medida | O que é | Relação com o multiplicador |
|:---:|---|---|---|
| 1 | 🏢 **Polo tecnológico regional** | Coworking, incubadora e laboratórios junto da Fatec | Investimento público direto (ΔG) |
| 2 | 📶 **Ampliação da conectividade** | Fibra óptica nos bairros e na zona rural, Wi-Fi público | Infraestrutura (ΔG e ΔI) |
| 3 | 🎓 **Formação e retenção de talentos** | Bolsas de estágio, "primeiro emprego em TI" e cursos gratuitos | Transferência (c × k) |
| 4 | 🧾 **Compras públicas de software local** | Prefeituras contratando empresas de tecnologia da região | Gasto do governo; **reduz o vazamento m** |
| 5 | 🚀 **Fundo de capital semente** | Fundo e crédito barato para startups | Estimula o investimento privado (ΔI) |
| 6 | 💸 **Incentivo fiscal com contrapartida** | ISS menor (mínimo de 2%) em troca de contratar na região | Renúncia fiscal (≈ c × k) |
| 7 | 🌾 **Inovação aberta com o agronegócio** | Desafios de cooperativas e usinas resolvidos por startups locais | Induz investimento e reduz o vazamento |

---

## 📊 Simulação do impacto

Programa hipotético de **R$ 10 milhões por ano**:

| Medida | Tipo | Valor (R$ mi) | Multiplicador | Renda gerada (R$ mi) |
|---|---|---:|---:|---:|
| Polo tecnológico | Investimento | 3,00 | 2,17 | 6,52 |
| Conectividade | Investimento | 2,00 | 2,17 | 4,35 |
| Bolsas e primeiro emprego | Transferência | 1,50 | 1,74 | 2,61 |
| Compras públicas locais | Gasto do governo | 1,50 | 2,17 | 3,26 |
| Fundo de capital semente | Investimento | 1,00 | 2,17 | 2,17 |
| Incentivo fiscal de ISS | Renúncia fiscal | 0,50 | 1,74 | 0,87 |
| Inovação com o agronegócio | Gasto do governo | 0,50 | 2,17 | 1,09 |
| **Total** | | **10,00** | **≈ 2,09** | **20,87** |

👉 **R$ 10 milhões** geram cerca de **R$ 20,9 milhões** de renda na região.

### Rodadas do multiplicador (R$ 8 milhões de gasto direto)

```
1ª rodada:  8,00   → acumulado  8,00
2ª rodada:  4,32   → acumulado 12,32   (8,00 × 0,54)
3ª rodada:  2,33   → acumulado 14,65
4ª rodada:  1,26   → acumulado 15,91
5ª rodada:  0,68   → acumulado 16,59
demais:     0,80   → total     17,39   (8,00 × 2,17)
```

### 💡 A lição principal

Se as medidas reduzissem a propensão a importar de **0,10 para 0,05**, o multiplicador subiria de **2,17 para 2,44**, e os mesmos R$ 10 milhões gerariam cerca de **R$ 23,4 milhões**. Ou seja, **R$ 2,5 milhões a mais sem gastar nenhum real a mais**, só mantendo o dinheiro circulando na região.

---

## ⚠️ Cuidados e limitações

- **Capacidade ociosa:** sem profissionais suficientes, o gasto vira aumento de preços, e não de produção.
- **Vazamentos:** comprar fora da região reduz o multiplicador.
- **Financiamento:** o programa precisa caber no orçamento; parcerias ajudam.
- **Tempo:** os efeitos aparecem ao longo de meses e anos.
- **Parâmetros:** os valores de c, t e m são hipotéticos e deveriam ser estimados com dados do IBGE e da Fundação Seade.

**Indicadores propostos:** empresas de tecnologia abertas, empregos formais no setor (Novo Caged), renda média, formados da Fatec que ficam na região e contratos públicos com empresas locais.

---

## 🎓 Informações acadêmicas

| | |
|---|---|
| **Instituição** | Fatec Taquaritinga |
| **Curso** | Análise e Desenvolvimento de Sistemas |
| **Disciplina** | Economia e Finanças |
| **Professor** | Guilherme Augusto Malagoli |
| **Ano** | 2026 |

## 👤 Autor

**Juan Gabriel Pereira Augusto**
GitHub: [@JuanGabrielPereiraAugusto](https://github.com/JuanGabrielPereiraAugusto)
