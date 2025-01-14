# SPI Project for STM32F103C8T6

Este projeto é uma implementação básica de comunicação SPI utilizando o microcontrolador STM32F103C8T6. O projeto está sendo desenvolvido com STM32CubeIDE e utiliza a HAL (Hardware Abstraction Layer) da STMicroelectronics.

## Descrição

Este projeto configura e utiliza o módulo SPI do STM32F103C8T6, e está preparado para ser utilizado em aplicações que requerem a comunicação entre o microcontrolador e dispositivos periféricos utilizando o protocolo SPI (Serial Peripheral Interface).

### Funcionalidades
- Inicialização e configuração do periférico SPI.
- Envio e recepção de dados SPI.
- Configuração de interrupções (se necessário).
- Suporte à comunicação SPI Master ou Slave, dependendo das necessidades do projeto.

## Estrutura do Projeto

- `Core/`: Contém o código fonte principal.
  - `Src/`: Arquivos fonte em C, como `main.c` e `stm32f1xx_hal_msp.c`.
  - `Inc/`: Arquivos de cabeçalho, como `main.h`.
  
- `Drivers/`: Contém os drivers da STMicroelectronics, incluindo HAL e CMSIS.
  - `STM32F1xx_HAL_Driver/`: Drivers específicos para o STM32F103.

## Requisitos

- STM32CubeIDE para compilação e depuração.
- Ferramenta de programador/debugger ST-Link ou similar.
- Biblioteca HAL para o STM32F1xx.

## Como compilar e executar

1. Clone este repositório:
    ```bash
    git clone https://github.com/seuusuario/SPI_project.git
    cd SPI_project
    ```

2. Abra o projeto no STM32CubeIDE.

3. Compile o projeto utilizando a opção de build do STM32CubeIDE.

4. Carregue o código no STM32F103C8T6 utilizando um programador ST-Link.

5. Monitore a comunicação SPI através do seu dispositivo periférico conectado.

## Contribuindo

Contribuições são bem-vindas! Se você encontrar bugs ou desejar adicionar novas funcionalidades, fique à vontade para fazer um fork deste repositório e enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

## Autor

Marcos Tullio - [LinkedIn](https://www.linkedin.com/in/marcostullio/) - [GitHub](https://github.com/marcostulliosouza)
