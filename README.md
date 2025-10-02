# AdoCão – Projeto HTML (SPA)

Este é um projeto **HTML + CSS + JavaScript puro** que replica as telas mostradas: *Landing*, *Welcome*, *Login*, *Criar Conta*, *Esqueci a Senha*, *Loading*, *Home*, *Favoritos* e *Conta*.

## Como executar
1. Baixe o ZIP anexado e extraia a pasta `adocao-spa/`.
2. Abra o arquivo `index.html` no navegador (clique duas vezes).
3. As telas funcionam via hash routing (SPA). Use estes caminhos:
   - `#/landing` – tela inicial (padrão)
   - `#/welcome` – social logins
   - `#/login` – login
   - `#/signup` – criar conta
   - `#/forgot` – esqueci a senha
   - `#/loading` – loading (redireciona para Home)
   - `#/home` – início
   - `#/favorites` – favoritos
   - `#/account` – conta
## aaaaa
Ou apenas navegue pelos botões.

## Estrutura 
```
adocao-spa/
  index.html          # ponto de entrada
  css/styles.css      # estilos
  js/app.js           # lógica e rotas
  assets/             # (vazio – opcional para imagens locais)
```

## Personalização rápida
- **Cores:** edite variáveis em `css/styles.css`.
- **Categorias e pets:** altere os arrays `CATEGORIES` e `PETS` em `js/app.js`.
- **Logo/ícone:** a UI usa `remixicon` (CDN). Você pode trocar por SVG próprio.
