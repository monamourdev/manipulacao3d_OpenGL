# Cepo de Madeira em 3D

Este é um projeto em C++ utilizando OpenGL e OpenAL para simular um martelo batendo em um cepo de madeira em 3D. O programa também inclui efeitos sonoros para a experiência do usuário.

![Martelada no Cepo de Madeira](https://github.com/monamourdev/manipulacao3d_OpenGL/tree/master/imgs/moment1.png)

## Dependências

Para garantir o funcionamento correto do programa, certifique-se de ter as seguintes dependências instaladas:

- [OpenGL](https://www.opengl.org/)
- [OpenAL](https://www.openal.org/)
- [ALUT (OpenAL Utility Toolkit)](https://icculus.org/ALUT/)

Instale as dependências no Ubuntu usando o seguinte comando:

```bash
sudo apt-get update
sudo apt-get install libgl1-mesa-dev libglu1-mesa-dev freeglut3-dev libopenal-dev libalut-dev
```

## Compilação e Execução
Para compilar o programa, utilize o Makefile fornecido:

```
make
```
Após a compilação bem-sucedida, execute o programa:

```
./cepoDeMadeira
```

# Controles

- Use a tecla 'W' para ligar/desligar a luz difusa.
- Use a tecla 'S' para ligar/desligar a luz ambiente.
- Clique com o botão esquerdo do mouse para interagir com a animação do martelo.


