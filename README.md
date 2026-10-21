# Monte seu plano — Revenda Mais

Página em etapas para readequar clientes de planos antigos à linha de planos atual.
O cliente escolhe módulo a módulo (Gestão, Financeiro/estoque, CRM, Nota Fiscal e complementos)
e só no final vê os valores no mensal e no anual, separados entre **cartão** (sistema e módulos)
e **boleto pós-pago** (CRM e IA SDR), com a mensalidade total. O botão final abre o WhatsApp do
consultor com o plano já preenchido.

## Link por consultor

```
index.html?wa=5541999990000&consultor=Ana%20Souza&loja=Federal%20Car
```

- `wa` — WhatsApp do consultor (DDI + DDD + número, só dígitos)
- `consultor` — nome exibido no topo e na mensagem
- `loja` — nome da loja (preenche o campo automaticamente)

## Preços e regras

Ficam no objeto `CONFIG`, no início do `<script>` do `index.html` (mesma tabela do Gerador de Proposta).
