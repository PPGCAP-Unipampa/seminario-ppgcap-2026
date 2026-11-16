# Seminário de Pesquisa PPGCAP 2026

Página estática (HTML + CSS, sem build e sem backend) do Seminário de Pesquisa do PPGCAP/Unipampa, em 17/12/2026.

## Arquivos

- `index.html`: conteúdo da página
- `style.css`: estilos
- `banner-seminario-2026.png`: banner aprovado

Os cards de divulgação em `assets/` não são usados pela página.

## Visualizar localmente

Abra `index.html` no navegador. No WSL, use `explorer.exe index.html`. Outra opção é rodar `python3 -m http.server` e acessar http://localhost:8000.

## Onde editar

No `index.html`, procure por:

- `BANNER`: troca do banner (ou substitua o PNG mantendo o nome)
- `PROGRAMAÇÃO`: linhas da tabela de horários
- `LINK DA SALA: EDITAR AQUI`: inserir a URL da sala (o texto do link é "Acessar a sala on-line")
- `PRAZO PARA CONFLITOS`: prazo opcional, ainda oculto
- `og:image`: prévia em redes sociais (requer o endereço absoluto, depois de publicar)

## Publicar no GitHub Pages

1. Faça o commit dos arquivos e envie para o GitHub (`git push`).
2. No repositório, abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em alguns minutos, a página estará em `https://<usuario>.github.io/<repositorio>/`.

Como todos os caminhos são relativos, a página funciona nesse endereço de projeto. Se o repositório se chamar `seminario-pesquisa-2026`, por exemplo, o endereço termina em `/seminario-pesquisa-2026/`.
