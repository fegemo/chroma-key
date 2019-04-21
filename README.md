# Chroma key

[TP1](docs/tp1_enunciado.pdf) de Processamento Digital de Imagens do
DCC/UFMG em 2019/01 do grupo composto por:

- [Douglas Ludgério](https://github.com/douglaslud)
- [Flávio Coutinho](https://github.com/fegemo)
- [Ricardo de Oliveira](https://github.com/Tsuchiryu)

## Resultado final

...

## Tarefas

- [x] Criar um repositório
- [x] Escolher imagens
- [x] Fazer uma montagem no photoshop para servir de referência
- [x] Definir as operações que serão usadas
    - [x] Operações radiométricas
      - Dessaturação, opacidade
    - [x] Transformações geométricas
      - Escala, translação, rotação e _warping_
    - [x] Filtros
      - Borragem
- [x] Implementar operação de _chroma key_
- [x] Implementar combinação de imagens
- [ ] Implementar transformações geométricas (posicionar/escalar/rotacionar elementos)
  - [x] Translação
  - [x] Escala
  - [ ] Rotação
  - [x] _Warping_ do raio trator
  - [ ] _Warping_ do salnorabo
- [x] Implementar operações radiométricas escolhidas
  - [x] Dessaturação
  - [x] Transparência
- [x] Implementar filtros escolhidos
  - [x] Borragem
- [ ] Gerar documentação explicando o que/como foi feito
- [ ] Publicar documentação

Opcionais:

- [ ] Detecção automática da cor do _chroma key_
  - Ideia: montar um histograma apenas dos pixels da borda e ver qual o(s) bin(s)
    com maior quantidade.
- [ ] Determinação da iluminação das imagens
  - Ideia: usar modelo de iluminação lambertiana para inferir direção da iluminação. Paper [A novel method for detecting light source for digital images forensic](docs/detect-light-sources.pdf).
- [ ] Projeção de sombra dos objetos
    - Ideia: desenhar a imagem sem saturação e com transparência projetada de acordo com posição da luz, depois desenhar o objeto mesmo.
- [ ] Iluminação dinâmica da cena
    - [ ] Gerar um mapa de normais
    - [ ] Representar uma fonte de luz
    - [ ] Sombrear objetos de acordo com fonte de luz e normais
