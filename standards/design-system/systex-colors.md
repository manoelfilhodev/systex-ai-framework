# Paleta oficial Systex

## Diretriz

O tema dark e o padrao visual oficial da Systex. A interface deve transmitir sobriedade, precisao, seguranca e maturidade empresarial.

## Cores base

- Preto: base principal de fundos e superficies escuras.
- Cinza: textos secundarios, bordas, divisores e hierarquia visual.
- Vermelho: cor de acento da Systex para destaque, acao primaria e identidade.
- Branco: texto principal, contraste e informacao critica.

## Estados

- success: operacao concluida, confirmacao ou status positivo.
- warning: atencao, pendencia ou risco controlado.
- danger: erro, falha, bloqueio ou risco critico.
- info: informacao contextual, status neutro ou orientacao.

## CSS variables oficiais

```css
:root {
  --bg-primary: #0B0B0B;
  --bg-secondary: #121214;
  --bg-card: #18181B;

  --text-primary: #FFFFFF;
  --text-secondary: #A1A1AA;
  --text-muted: #71717A;

  --accent-primary: #FF2A2A;
  --accent-hover: #E11D1D;
  --accent-soft: rgba(255, 42, 42, 0.08);

  --border-primary: rgba(255,255,255,0.06);
  --border-secondary: rgba(255,255,255,0.10);

  --success: #22C55E;
  --warning: #F59E0B;
  --danger: #EF4444;
  --info: #3B82F6;
}
```

## Regras de uso

- O vermelho Systex deve ser usado com criterio, como acento e chamada de acao.
- Fundos principais devem preservar contraste e leitura prolongada.
- Estados nao devem competir com a cor de marca.
- White Label pode alterar identidade visual apenas quando contratado como escopo premium.
