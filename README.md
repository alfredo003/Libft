# libft

`libft` é uma biblioteca em C que fornece uma coleção de funções úteis, desenvolvidas a partir do zero, para auxiliar na programação. Este projeto é frequentemente utilizado em ambientes acadêmicos, como o bootcamp 42, para ajudar os alunos a entenderem e implementarem funções básicas da biblioteca padrão do C.

## Objetivo

O objetivo principal do `libft` é fornecer implementações próprias para funções comuns da biblioteca padrão do C, permitindo que os desenvolvedores se familiarizem com a programação em baixo nível e a manipulação de memória.

## Funcionalidades

A `libft` inclui funções para:

- Manipulação de strings (`ft_strcpy`, `ft_strlen`, etc.)
- Manipulação de memória (`ft_memcpy`, `ft_memset`, etc.)
- Conversão e formatação (`ft_atoi`, `ft_itoa`, etc.)
- Listas ligadas (`ft_lstnew`, `ft_lstadd_front`, etc.)

## Estrutura do Projeto

O projeto é organizado da seguinte forma:

- `includes/` - Contém arquivos de cabeçalho (.h).
- `srcs/` - Contém a implementação das funções.
- `Makefile` - Para compilar a biblioteca e criar o arquivo `libft.a`.
- `test/` - Scripts e testes para verificar a funcionalidade da biblioteca.

## Compilação

Para compilar a `libft`, use o `Makefile` incluído no repositório. No terminal, navegue até o diretório do projeto e execute:

```sh
make
```

Isso criará a biblioteca estática `libft.a` que pode ser vinculada a outros projetos.

## Testes

Para executar os testes, use:

```sh
make bonus
```

Este comando compilará e executará os testes adicionais.

## Uso

Para utilizar a `libft` em seus próprios projetos, adicione o arquivo `libft.a` ao seu projeto e inclua os arquivos de cabeçalho correspondentes:

```c
#include "libft.h"
```

E vincule a `libft.a` durante a compilação.
