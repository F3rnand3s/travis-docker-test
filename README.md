# Travis: Docker test

O propósito deste teste é perceber como utilizar docker juntamente com Travis.
Travis vai ser configurado de maneira a: 

- Construir e testar uma imagem docker a partir de um dockerfile;
- Devolver se a imagem passou ou não por todas as fases que foram configuradas;
Com o resultado destes testes é pretendido proteger a master branch de modo que não seja possível fazer alterações a não ser que essas sejam aprovadas por Travis;
