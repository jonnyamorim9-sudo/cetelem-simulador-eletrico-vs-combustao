# Simulador Elétrico vs Combustão — proposta de MVP para o Cetelem

Proposta académica (IPAM × Cetelem, Web Design). Compara, para o mesmo crédito automóvel, o custo mensal e a 10 anos de um carro elétrico e de um a combustão.

**Simulação sem valor contratual.** Não é um produto do Cetelem nem substitui o simulador oficial.

## Como correr

É uma página estática, sem dependências nem passo de build. Abre `index.html` no browser ou serve a pasta:

```bash
npx serve .
```

## Estrutura

- `index.html`: HTML, CSS e JavaScript numa só página.
- `assets/`: logótipo oficial (SVG) e mascote do Cetelem, usados apenas como referência visual de marca.

## Modelo de cálculo

- Crédito calibrado com o simulador do Cetelem: 5 000 € a 24 meses dá 226,05 €/mês; a 36 meses dá 156,59 €/mês.
- TAN de 7,65% a 24 e 36 meses (confirmada). As TAN de 48 a 84 meses são estimadas e estão marcadas com asterisco na página.
- Gasolina a 2,001 €/L (média DGEG, 4/11/2026). As tarifas de eletricidade e de carregamento são estimativas e estão identificadas na página.

## Marca

O nome, o logótipo e o mascote Cetelem pertencem à Cetelem / BNP Paribas Personal Finance, Sucursal em Portugal. Estão aqui só para este trabalho académico.
