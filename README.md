# Lightsaber Duel Loader

Um loader criativo e dinâmico inspirado na franquia Star Wars, desenvolvido inteiramente com **HTML5** e **CSS3**. O componente simula um duelo entre dois sabres de luz (Verde vs Vermelho) com efeitos de colisão e partículas.

## Características

* **Animação Coreografada:** Os sabres realizam movimentos de ataque e defesa sincronizados.
* **Efeitos de Partículas:** Simulação de faíscas que surgem no momento exato do impacto entre as lâminas.
* **Puro CSS:** Utiliza `@keyframes` complexos para gerenciar rotação, brilho (bloom) e translação sem necessidade de JavaScript.
* **Estética Sci-Fi:** Fundo escuro com brilho neon intenso para máxima imersão.

## Estrutura do Projeto

O projeto utiliza uma estrutura simples de elementos `div` que são transformados em sabres de luz através de pseudo-elementos:

* `#loader`: O container principal centralizado.
* `.lightsaber`: Define a base (punho) e a lâmina de cada sabre.
* `.ls-particles`: Elementos responsáveis pelo efeito de faíscas durante o combate.

## Tecnologias Utilizadas

* **HTML5**
* **CSS3** (Transformações 2D, Animações e Box-shadows para o efeito Glow)

## Detalhes das Animações

| Keyframe | Descrição |
| :--- | :--- |
| `showlightgreen/red` | Controla a ativação da lâmina e a intensidade do brilho. |
| `fightleft/right` | Define a trajetória de combate e a rotação dos sabres. |
| `particles1-5` | Gerencia o tempo de vida, cor e direção das faíscas após o impacto. |

## Como Visualizar

1. Clone o repositório ou baixe os arquivos.
2. Certifique-se de que o arquivo `style.css` está na mesma pasta que o `index.html`.
3. Abra o `index.html` em seu navegador preferido.

## Personalização

Você pode trocar as cores dos sabres alterando as variáveis de `box-shadow` nos keyframes:

<img width="962" height="351" alt="image" src="https://github.com/user-attachments/assets/bc9a1e2c-9a92-4aeb-9423-fccf2a1a8f44" />
