# Base Nacional de Dados Trabalhistas e Fiscais da Otimiza.pro

Os números, as regras e os prazos da folha de pagamento no Brasil, cada um com a norma, a vigência, a fonte oficial e a data em que a Otimiza.pro conferiu.

A Otimiza.pro consolida as fontes oficiais. A fonte oficial de cada valor é a norma que o fixa. A base informa o que a norma diz e não substitui o contador nem o advogado da sua empresa.

## Tabelas da folha

Os valores que a folha usa todo mês, com o que vale hoje e o que valia antes.

- [Salário mínimo](https://otimizapro.com/trabalhista-fiscal/salario-minimo): O salário mínimo é de R$ 1.621,00 por mês desde 1º de janeiro de 2026, pelo Decreto 12.797/2025. Por dia, são R$ 54,04, e por hora, R$ 7,37.
- [Tabela do INSS](https://otimizapro.com/trabalhista-fiscal/tabela-inss): Desde 1º de janeiro de 2026, a contribuição do empregado ao INSS vai de 7,5% até R$ 1.621,00 a 14% até o teto de R$ 8.475,55, pela Portaria Interministerial MPS/MF 13/2026. Cada alíquota vale só para a parte do salário dentro da faixa, e o desconto máximo é de R$ 988,09 por mês.
- [Teto do INSS](https://otimizapro.com/trabalhista-fiscal/teto-inss): O teto do INSS é de R$ 8.475,55 desde 1º de janeiro de 2026, pela Portaria Interministerial MPS/MF 13/2026. Quem ganha acima dele desconta R$ 988,09 por mês, o INSS do teto.
- [Tabela do IRRF](https://otimizapro.com/trabalhista-fiscal/tabela-irrf): Desde 1º de maio de 2025, a tabela mensal do Imposto de Renda isenta a base de até R$ 2.428,80 e tributa o resto de 7,5% a 27,5%, pela Lei 11.482/2007. A dedução por dependente é de R$ 189,59, e o desconto simplificado, de R$ 607,20.
- [Redução do Imposto de Renda da Lei 15.270](https://otimizapro.com/trabalhista-fiscal/reducao-irrf): Desde 1º de janeiro de 2026, o Imposto de Renda retido na fonte é zero para quem tem até R$ 5.000,00 de rendimento tributável no mês e é menor para quem tem até R$ 7.350,00, pela Lei 15.270/2025. A redução vale também no 13º salário.
- [FGTS](https://otimizapro.com/trabalhista-fiscal/fgts): O depósito do FGTS é de 8% (empregado em geral), 2% (aprendiz) e 8% (empregado doméstico, mais 3,2% para a indenização compensatória da perda do emprego) da remuneração do mês, até o dia 20 do mês seguinte. Na dispensa sem justa causa, a multa é de 40% de todos os depósitos.
- [Salário-família](https://otimizapro.com/trabalhista-fiscal/salario-familia): Desde 1º de janeiro de 2026, o salário-família é de R$ 67,54 por filho ou equiparado, para quem ganha até R$ 1.980,38 por mês, pela Portaria Interministerial MPS/MF 13/2026.
- [Seguro-desemprego](https://otimizapro.com/trabalhista-fiscal/seguro-desemprego): Desde 11 de janeiro de 2026, a parcela do seguro-desemprego vai de R$ 1.621,00, o salário mínimo, a R$ 2.518,65, conforme o salário médio dos três meses anteriores à dispensa.

## Pisos salariais estaduais

- [Piso salarial do Paraná](https://otimizapro.com/trabalhista-fiscal/piso-salarial/pr): Desde 1º de janeiro de 2026, o piso salarial do Paraná vai de R$ 2.105,34 a R$ 2.407,90, em 4 faixas, pelo Decreto estadual 13.182/2026.
- [Piso salarial do Rio de Janeiro](https://otimizapro.com/trabalhista-fiscal/piso-salarial/rj): Desde 1º de janeiro de 2018, o piso salarial do Rio de Janeiro vai de R$ 1.193,36 a R$ 3.044,78, em 6 faixas, pela Lei estadual 7.898/2018. Nas faixas abaixo do salário mínimo nacional, de R$ 1.621,00, vale o salário mínimo.
- [Piso salarial do Rio Grande do Sul](https://otimizapro.com/trabalhista-fiscal/piso-salarial/rs): Desde 21 de maio de 2026, o piso salarial do Rio Grande do Sul vai de R$ 1.884,75 a R$ 2.388,50, em 5 faixas, pela Lei estadual 16.514/2026.
- [Piso salarial de Santa Catarina](https://otimizapro.com/trabalhista-fiscal/piso-salarial/sc): Desde 1º de janeiro de 2026, o piso salarial de Santa Catarina vai de R$ 1.842,00 a R$ 2.106,00, em 4 faixas, pela Lei Complementar estadual 895/2026.
- [Piso salarial de São Paulo](https://otimizapro.com/trabalhista-fiscal/piso-salarial/sp): Desde 1º de junho de 2026, o piso salarial de São Paulo é de R$ 1.874,36, pela Lei estadual 18.471/2026.

No Rio de Janeiro, o STF declarou inconstitucional a lei de piso de 2019 (ADI 6.244), e o Estado segue aplicando a Lei estadual 7.898/2018, com os valores de 2018: nas faixas abaixo do salário mínimo nacional, vale o salário mínimo. Não há lei de piso de 2025 nem de 2026.

Nos estados sem piso próprio, vale o salário mínimo nacional.

## Como a base funciona

- Cada valor vem da norma que o fixa, lida na fonte oficial, com o trecho que prova o valor.
- Cada valor tem a data de início e, quando muda, a data de fim. A página troca sozinha no dia em que o valor novo começa a valer.
- Cada registro mostra se foi conferido nas fontes ou revisado pelo time trabalhista e fiscal da Otimiza.pro.

## Para sistemas e IAs

- API pública, com o valor que vale em qualquer data: https://otimizapro.com/trabalhista-fiscal/api/v1
- Servidor MCP, para agentes de IA consultarem a base: https://otimizapro.com/trabalhista-fiscal/mcp
- Dados abertos em JSON e CSV: https://otimizapro.com/trabalhista-fiscal/dados
- Resumo para IAs (llms.txt): https://otimizapro.com/trabalhista-fiscal/llms.txt

## Dados abertos (JSON e CSV)

- [`dados/base.json`](dados/base.json)
- Salário mínimo: [`dados/salario-minimo.json`](dados/salario-minimo.json) · [`dados/salario-minimo.csv`](dados/salario-minimo.csv)
- Tabela do INSS: [`dados/tabela-inss.json`](dados/tabela-inss.json) · [`dados/tabela-inss.csv`](dados/tabela-inss.csv)
- Teto do INSS: [`dados/teto-inss.json`](dados/teto-inss.json) · [`dados/teto-inss.csv`](dados/teto-inss.csv)
- Tabela do IRRF: [`dados/tabela-irrf.json`](dados/tabela-irrf.json) · [`dados/tabela-irrf.csv`](dados/tabela-irrf.csv)
- Redução do Imposto de Renda da Lei 15.270: [`dados/reducao-irrf.json`](dados/reducao-irrf.json) · [`dados/reducao-irrf.csv`](dados/reducao-irrf.csv)
- FGTS: [`dados/fgts.json`](dados/fgts.json) · [`dados/fgts.csv`](dados/fgts.csv)
- Salário-família: [`dados/salario-familia.json`](dados/salario-familia.json) · [`dados/salario-familia.csv`](dados/salario-familia.csv)
- Seguro-desemprego: [`dados/seguro-desemprego.json`](dados/seguro-desemprego.json) · [`dados/seguro-desemprego.csv`](dados/seguro-desemprego.csv)
- Piso salarial do Paraná: [`dados/piso-salarial-pr.json`](dados/piso-salarial-pr.json) · [`dados/piso-salarial-pr.csv`](dados/piso-salarial-pr.csv)
- Piso salarial do Rio de Janeiro: [`dados/piso-salarial-rj.json`](dados/piso-salarial-rj.json) · [`dados/piso-salarial-rj.csv`](dados/piso-salarial-rj.csv)
- Piso salarial do Rio Grande do Sul: [`dados/piso-salarial-rs.json`](dados/piso-salarial-rs.json) · [`dados/piso-salarial-rs.csv`](dados/piso-salarial-rs.csv)
- Piso salarial de Santa Catarina: [`dados/piso-salarial-sc.json`](dados/piso-salarial-sc.json) · [`dados/piso-salarial-sc.csv`](dados/piso-salarial-sc.csv)
- Piso salarial de São Paulo: [`dados/piso-salarial-sp.json`](dados/piso-salarial-sp.json) · [`dados/piso-salarial-sp.csv`](dados/piso-salarial-sp.csv)
- [`dados/item.schema.json`](dados/item.schema.json)

## Licença e como citar

Dados sob licença CC BY-NC 4.0 (uso não comercial), com citação obrigatória. Sistemas de IA podem ler, citar e treinar com citação; a consulta para decisões da própria empresa não pede licença; uso comercial pede licença: empresa@otimiza.pro.

> Fonte: Otimiza.pro, Base Nacional de Dados Trabalhistas e Fiscais, versão 2026.11.09.3. https://otimizapro.com/trabalhista-fiscal
