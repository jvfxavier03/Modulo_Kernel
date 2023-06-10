# Módulo de Kernel
https://github.com/jvfxavier03/kernelmodulo/blob/main/Print%20Voc%C3%AA%20Passou/grand%20finale.png
## Descrição

Este repositório contém um exemplo de módulo de kernel para Linux. O módulo de kernel é um programa que pode ser inserido ou removido do núcleo do sistema operacional Linux em tempo de execução. Ele permite estender as funcionalidades do kernel ou adicionar suporte para dispositivos específicos.

Este módulo de kernel de exemplo demonstra as etapas básicas para criar um módulo funcional. Ele inclui uma estrutura de código simples que pode ser usada como ponto de partida para a criação de módulos de kernel personalizados.

## Funcionalidades

- Inicialização e finalização do módulo de kernel.
- Demonstração de manipulação de parâmetros do módulo.
- Exemplo de criação de um dispositivo de caractere no kernel.
- Implementação básica de leitura e escrita no dispositivo de caractere.

## Requisitos

- Sistema operacional Linux.
- Compilador GCC.
- Cabeçalhos do kernel (pacote `linux-headers`).

## Compilação e Uso

1. Clone este repositório em sua máquina local.
2. Acesse o diretório do módulo de kernel.
3. Execute o comando `make` para compilar o módulo.
4. Carregue o módulo no kernel usando o comando `insmod`:
