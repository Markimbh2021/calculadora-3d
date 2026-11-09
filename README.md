# Calculadora 3D — Rev.01

Protótipo web responsivo, com identidade azul-marinho/amarelo, abas Calcular/Configurações/Histórico/Relatórios, cadastro local de filamentos e impressoras, cálculo em tempo real, gráfico circular e persistência via localStorage.

## Testar
Abra `index.html` em um navegador moderno. Os dados ficam salvos no navegador/dispositivo.

## Publicar na Vercel
Crie um repositório GitHub, envie os arquivos desta pasta e importe o repositório na Vercel. Como é um site estático, não precisa de build command; a pasta raiz é a raiz do projeto.

## Importante — revisão das fórmulas
A fórmula de material aplica falhas + desperdício ao peso; energia usa potência × horas × tarifa; depreciação usa valor da impressora / vida útil × horas; operacional aplica percentual sobre material + energia + depreciação; embalagem e anúncios são adicionados como valores fixos por orçamento. O preço de venda aplica markup e depois desconta imposto, taxa de marketplace e taxa fixa. Essas regras são hipóteses iniciais de protótipo e precisam ser conferidas com a implementação original/resultado esperado antes de uso comercial.

Os dados são locais ao navegador nesta Rev.01; não há login nem sincronização entre dispositivos.
