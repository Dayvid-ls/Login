# Formulário de Cadastro 📝

Formulário de cadastro moderno com campos para nome, e-mail e senha, desenvolvido com HTML, CSS e ícones do Font Awesome. Apresenta animação de entrada suave ao carregar a página.

## Tecnologias usadas
- HTML5
- CSS3 (gradientes, flexbox, animações, keyframes)
- Font Awesome (biblioteca de ícones)
- Google Fonts (Poppins)

## Funcionalidades
- Campo para Nome (Username)
- Campo para E-mail
- Campo para Senha (tipo password)
- Ícones decorativos dentro de cada campo
- Botão "Cadastrar" com efeito hover
- Fundo com gradiente diagonal (azul para amarelo)
- Container do formulário centralizado na tela
- Animação de entrada (`iniciar`) deslizando de cima para baixo
- Layout responsivo (largura mínima dos campos de 280px)

## Como executar
1. Baixe todos os arquivos na mesma pasta:
2. Abra o arquivo `form.html` em qualquer navegador moderno.

## Funcionalidades em detalhe

| Elemento | Descrição |
|----------|-----------|
| `#form` | Container centralizado com `position: relative`, `top/left: 50%` e `transform: translate(-50%, -50%)`; fundo transparente, borda arredondada, sombra e animação de entrada |
| `.input` | Caixa de entrada com borda cinza arredondada, padding interno, ícone à esquerda e campo de texto sem borda |
| Ícones | Font Awesome: `fa-circle-user` (usuário), `fa-envelope` (email), `fa-lock` (senha) |
| `#btn button` | Botão de enviar com borda arredondada, fundo transparente, sombra e efeito hover que aplica gradiente (azul para amarelo) |
| Animação `iniciar` | Keyframe que move o formulário de `top: -20%` até `top: 50%`, aumentando opacidade de 0% para 100%; duração de 1.6s |
| Fundo `body` | Gradiente linear de `#52adff` (azul) para `#fedb40` (amarelo) |

## Observações
- O formulário **não envia dados** para nenhum backend. É apenas um estudo de interface.
- O campo de e-mail está como `type="text"` em vez de `type="email"` – pode ser alterado para melhor validação HTML5.
- O botão tem `tipe="submit"` (erro de digitação – deveria ser `type="submit"`). Isso não impede a exibição, mas pode ser corrigido.
- O `placeholder` do campo senha está em inglês ("Password") enquanto os outros estão em português ("Username", "Email") – ajuste opcional para consistência.

## Possíveis melhorias futuras
- Corrigir o atributo `tipe` para `type` no botão
- Adicionar validação JavaScript nos campos (e-mail válido, senha com mínimo de caracteres)
- Implementar máscara de entrada para os campos
- Adicionar link "Esqueci minha senha" e "Já tenho cadastro"
- Incluir checkbox de "Lembrar-me" ou "Aceito os termos"
- Conectar o formulário a um backend real (Firebase, API própria, etc.)
- Adicionar mensagens de erro amigáveis em tempo real

---
