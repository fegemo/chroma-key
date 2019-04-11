# Chroma key

[TP1](docs/tp1_enunciado.pdf) de Processamento Digital de Imagens do 
DCC/UFMG em 2019/01 do grupo composto por:

- [Douglas Ludgério](github.com/douglaslud)
- [Flávio Coutinho](github.com/fegemo)
- [Ricardo de Oliveira](github.com/Tsuchiryu)

## Resultado final

...

## Tarefas

- [x] Criar um repositório
- [ ] Escolher imagens
- [ ] Fazer uma montagem no photoshop para servir de referência
- [ ] Definir as operações que serão usadas
    - [ ] Operações radiométricas
    - [ ] Transformações geométricas
    - [ ] Filtros
- [ ] Implementar operação de _chroma key_
- [ ] Implementar transformações geométricas (posicionar/escalar/rotacionar elementos)
- [ ] Implementar operações radiométricas escolhidas
- [ ] Implementar filtros escolhidos
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

