# Monte seu plano — Revenda Mais

Página em etapas para clientes criarem ou trocarem o plano Revenda Mais.
O cliente escolhe módulo a módulo (Gestão, Financeiro/estoque, Assinatura Eletrônica, CRM e Agente de IA,
NF-e com integração Renave e NFS-e) e só no final vê os valores no mensal e no anual, separados entre
**cartão** (sistema e módulos) e **boleto pós-pago** (CRM e Agente de IA), com a mensalidade total.
Sem Sistema de Gestão não há financeiro nem notas fiscais. O botão final abre o WhatsApp do
consultor com o plano já preenchido.

## Link por consultor

```
index.html?wa=5541999990000&consultor=Ana%20Souza&loja=Federal%20Car
```

- `wa` — WhatsApp do consultor (DDI + DDD + número, só dígitos)
- `consultor` — nome exibido no topo e na mensagem
- `loja` — nome da loja (preenche o campo automaticamente)

## Preços e regras

Ficam no objeto `CONFIG`, no início do `<script>` do `index.html` (tabela de readequação de planos).
