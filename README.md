# estrutura

Styli — Seu Guarda-Roupa Inteligente

Styli é um aplicativo desenvolvido em Java com Swing que permite importar imagens de roupas, cadastrar peças com estação e tipo, e visualizar automaticamente todas as combinações possíveis de looks com base nas escolhas feitas. Uma forma prática, visual e divertida de montar seu guarda-roupa digital!

---

Visão Geral

Você já se perguntou quantos looks consegue montar com as roupas que já tem? O Styli resolve isso para você! Ao cadastrar suas peças e informar a estação do ano e o tipo de cada uma, o aplicativo gera combinações de roupas válidas para o clima escolhido, exibindo as imagens dos looks montados.

---

Objetivo

- Tornar a escolha de roupas mais prática e organizada.
- Estimular o aproveitamento inteligente do guarda-roupa.
- Oferecer uma interface amigável e visual para montar looks.

---

Tecnologias Utilizadas

- Java  
- Java Swing (interface gráfica)  
- Programação Orientada a Objetos (POO)  
- Estruturas de Dados (listas para gerar combinações)  
- *(Planejado)* Banco de Dados para persistência de dados  

---

Funcionalidades

- ✅ Importar imagens de peças do guarda-roupa
- ✅ Cadastrar estação do ano e tipo da peça (ex: verão, blusa, calça...)
- ✅ Gerar combinações automáticas com base nas seleções
- ✅ Exibir os looks em miniatura
- ✅ Ampliar looks ao clicar nas imagens

---

Estrutura do Projeto

| Classe/Tela     | Função                                                                   |
| `TelaUm.java`    | Importa imagens de roupas                                               |
| `TelaCadastro.java` | Cadastra tipo da peça e estação do ano                               |
| `TelaDois.java`  | Exibe combinações possíveis e permite visualização dos looks gerados  |
| `Look.java`      | Representa uma peça individual de roupa                                 |
| `LookCombiner.java` | Responsável pela lógica de combinação entre as peças                 |

---

Lógica de Combinação

- O sistema agrupa as roupas por estação e tipo usando listas.
- A combinação dos looks é feita com base em pares ou trios de peças conforme o tipo selecionado.
- Usa laços de repetição para montar todas as combinações válidas.
- Exibe visualmente cada look como uma miniatura composta pelas imagens selecionadas.

---

Demonstração *(em breve)*


---

Próximos Passos

- [ ] Adicionar banco de dados para persistência de dados
- [ ] Melhorar a interface visual (layout, cores, tipografia)
- [ ] Adicionar sistema de favoritos
- [ ] Implementar sugestões automáticas baseadas em eventos ou clima

---

Aprendizados

> Desenvolver o Styli foi uma experiência prática que reforçou meus conhecimentos em:

- Programação Orientada a Objetos (POO)
- Lógica aplicada ao mundo real (moda e combinações)
- Interface gráfica com Swing
- Manipulação de imagens e listas em Java
- Estruturação de múltiplas telas com CardLayout

---

Organização do Código

```bash
src/
│
├── TelaUm.java           # Importação de imagens
├── TelaCadastro.java     # Cadastro das peças
├── TelaDois.java         # Exibição das combinações
├── Look.java             # Classe das peças
└── LookCombiner.java     # Geração dos looks
