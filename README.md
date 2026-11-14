# Missão Alycia: Guerreiras do Pop ✨

Jogo de plataforma 2D para celular e tablet, feito de presente para a Alycia.
É um único arquivo (`index.html`) em HTML, CSS e JavaScript puros, sem dependências, sem imagens e sem arquivos de som: tudo é desenhado e tocado por código.

**Jogar:** https://acordisemfronteiras-create.github.io/Miss-o-Alycia/

## Como jogar

- **Celular/tablet (deitado):** setas ◀ ▶ à esquerda, ⬆ para pular e ✨ para atacar à direita.
- **Teclado:** setas ou WASD para andar, Espaço para pular, Z para atacar, P para pausar.
- **Personagens:** Alycia (pulo duplo), Luna (voa segurando o pulo), Nara (corre mais rápido) e Kira (ataque em área).
- **Sem game over:** ao cair ou ficar sem corações, a heroína volta do último checkpoint.
- O progresso (moedas, roupas, penteados, armas, estrelas e conquistas) fica salvo no próprio aparelho.

Dica: no iPhone/iPad, abra o link no Safari, toque em **Compartilhar → Adicionar à Tela de Início** para jogar em tela cheia, como um app.

## O que tem no jogo

- 6 missões com dificuldade crescente e 3 chefões: Gosma Gigante, Palhaço Desafinado e Rei do Silêncio.
- Mini-jogo de ritmo, corrida contra o tempo e ondas de monstrinhos.
- Missão bônus diferente a cada dia (+50 moedas na primeira vez do dia).
- Loja com roupas, penteados e armas mágicas, 15 conquistas e de 1 a 3 estrelas por missão.
- Cartinha final de parabéns depois do Grande Show Final.

## Publicar no GitHub Pages (passo a passo)

1. **Criar o repositório:** em github.com, clique em **New repository**, dê um nome (ex.: `missao-alycia`), marque **Public** e crie.
2. **Subir o arquivo:** na página do repositório, **Add file → Upload files**, arraste o `index.html` (e este `README.md`) e clique em **Commit changes**.
3. **Ativar o Pages:** vá em **Settings → Pages**. Em **Source**, escolha **Deploy from a branch**; em **Branch**, selecione `main` e a pasta `/ (root)`. Salve.
4. **Pegar o link:** depois de um ou dois minutos, a mesma tela mostra o endereço, no formato `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

Para atualizar o jogo depois, basta enviar um novo `index.html` no lugar do antigo.

## Personalizar

- **Cartinha final:** procure por `function showLetter` no `index.html` e edite o texto.
- **Nome na tela inicial:** procure por `Bem-vinda, Alycia!`.
- **Zerar o progresso:** apague os dados do site no navegador (chave `missaoAlycia_v1` do `localStorage`).
