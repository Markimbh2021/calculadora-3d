# Calculadora 3D — REV.03 (Miguelito)

Aplicativo web estático para estimativa de custos e precificação de impressão 3D.

## Publicação na Vercel
- Framework: Other
- Diretório raiz: `./`
- Comando de build: vazio
- Diretório de saída: `.`
- Comando de instalação: vazio

## Estrutura
- `index.html`: aplicação
- `assets/`: Miguelito e ícones PWA
- `manifest.webmanifest`: instalação como aplicativo
- `sw.js`: cache offline (cache versionado para REV.03)

## Mudanças da REV.03
- Aba Calcular simplificada: dados da peça, impressora, filamento, peso, tempo e quantidade.
- Ajustes recorrentes movidos para Configurações: falhas, desperdício, operacional, embalagem, impostos, marketplace, taxa fixa, markup e anúncios/ROAS.
- Parâmetros são salvos no dispositivo e aplicados automaticamente nos cálculos.
- Botão para restaurar parâmetros iniciais sem apagar cadastros de filamentos/impressoras.
- Mantidos histórico, relatórios, gráfico circular e mascote Miguelito.

## Dados
Configurações e histórico usam `localStorage` do navegador/dispositivo. Não há sincronização entre aparelhos nesta versão.

## Atenção
As fórmulas são as da versão anterior e ainda precisam de validação numérica comparativa com a calculadora original antes de uso comercial.
