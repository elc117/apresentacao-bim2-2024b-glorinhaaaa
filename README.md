# apresentacao-bim2-2024b-glorinhaaaa
# PolygonBatch Interface 

## Descrição

O código fornecido define a interface PolygonBatch que estende a interface Batch. A interface PolygonBatch é utilizada para fornecer métodos específicos para renderização de polígonos, permitindo desenhar regiões de polígonos com transformações como escala e rotação. Ela é projetada para ser implementada por classes que irão lidar com a renderização de polígonos em um ambiente gráfico.

## Conceitos de Programação: Herança e Polimorfismo

### Herança

A **herança** é um dos pilares da programação orientada a objetos e permite que uma classe ou interface herde características e comportamentos de outra. No código fornecido, a interface PolygonBatch herda da interface Batch:

java
public interface PolygonBatch extends Batch {



# Herança e Polimorfismo na Interface `PolygonBatch`

### Herança

A interface `PolygonBatch` herda de `Batch`, o que significa que `PolygonBatch` adquire todos os métodos definidos em `Batch`. Isso permite que qualquer classe que implemente a interface `PolygonBatch` tenha que implementar os métodos da interface `Batch`, além de adicionar métodos específicos para desenhar polígonos. A **herança** oferece uma estrutura reutilizável e extensível.

### 🌀 Polimorfismo

O **polimorfismo** é um conceito que permite que um único método ou operação se comporte de maneiras diferentes, dependendo do contexto. No código fornecido, o **polimorfismo** é demonstrado através da **sobrecarga de métodos**, onde o método `draw` possui várias versões (ou assinaturas) para desenhar um polígono de diferentes maneiras.

#### Exemplos de polimorfismo no código:
- Desenhar um polígono na posição `(x, y)`.
- Desenhar o polígono redimensionado em uma nova largura e altura.
- Desenhar o polígono com transformações de origem, escala e rotação.
- Desenhar o polígono usando vértices e triângulos customizados.

Isso permite que o mesmo método (`draw`) seja utilizado para diferentes comportamentos, dependendo dos parâmetros passados. O comportamento do método muda, mas o nome permanece o mesmo, caracterizando o **polimorfismo**.

---

## Como **Herança** e **Polimorfismo** se Aplicam no Código

### 🧑‍💻 **Herança**:
- A interface `PolygonBatch` herda de `Batch`, o que significa que qualquer classe que implemente `PolygonBatch` precisa implementar os métodos da interface `Batch`, além de fornecer implementações específicas para os métodos de desenho de polígonos.
- A **herança** permite uma estrutura comum para diferentes tipos de renderização e facilita a reutilização de código.

### 🌀 **Polimorfismo**:
- O **polimorfismo** é demonstrado pela sobrecarga do método `draw`, que pode ser chamado de várias formas, dependendo dos parâmetros fornecidos. Isso oferece flexibilidade no uso da interface e permite que o mesmo método tenha comportamentos distintos, simplificando o código para o desenvolvedor.

---

## Conclusão

A interface `PolygonBatch` é uma extensão da interface `Batch` e oferece métodos especializados para a renderização de polígonos com transformações, como escala e rotação. O uso dos conceitos de **herança** e **polimorfismo** no código permite uma solução flexível, reutilizável e fácil de estender, garantindo que diferentes implementações de renderização de polígonos possam ser criadas de forma eficiente e simples.

---

## Referências

- [Documentação oficial da API LibGDX](https://libgdx.badlogicgames.com/)
  
