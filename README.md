# ULA de 8 bits — Circuitos Digitais | 8-bit ALU — Digital Circuits

> 🇧🇷 **Projeto acadêmico em desenvolvimento.** Este repositório contém versões de trabalho dos circuitos e **não representa uma ULA completa, finalizada ou totalmente validada**.
>
> 🇺🇸 **Academic work in progress.** This repository contains working versions of the circuits and **does not represent a complete, finalized, or fully validated ALU**.

## 🇧🇷 Português (Brasil)

### Sobre o projeto

Este repositório reúne circuitos desenvolvidos durante os estudos de **Circuitos Digitais**, no curso de **Ciência da Computação**. O objetivo é aplicar conceitos de lógica digital, sinais de controle e manipulação de bits na construção gradual de uma **Unidade Lógica e Aritmética (ULA) de 8 bits**.

Os esquemas foram elaborados no **CircuitMaker** e estão disponibilizados para fins acadêmicos, estudo e acompanhamento da evolução do projeto.

### 🚧 Situação do projeto

**Status: NÃO CONCLUÍDO — EM DESENVOLVIMENTO.** A ULA de 8 bits ainda não está finalizada. Os circuitos publicados documentam etapas do desenvolvimento e poderão passar por correções, testes e integrações adicionais. Portanto, este repositório não deve ser interpretado como uma ULA pronta ou integralmente validada.

### 🆕 Última atualização — quatro circuitos desenvolvidos

Na versão mais recente disponibilizada no repositório, foram desenvolvidos e adicionados estes **quatro componentes**:

1. **Decodificador de 1 bit (`Decode.1b`)** — gera sinais de seleção a partir de uma entrada de controle.
2. **Multiplexador 2×1 (`Mux2x1`)** — seleciona uma entre duas entradas com base no sinal de controle.
3. **AMUX de 8 bits (`Amux.8b`)** — aplica a seleção de dados a um barramento de 8 bits.
4. **Shifter de 8 bits (`Shifter.8b`)** — implementa o deslocamento de bits em um barramento de 8 bits.

Esses componentes **não significam a conclusão da ULA**: são mais uma etapa de sua construção modular.

### Circuitos disponíveis

| Componente | Descrição |
| --- | --- |
| Somador de 1 bit (`Add.1b`) | Bloco de soma binária de 1 bit. |
| Somador de 8 bits (`Add.8b`) | Soma binária em um barramento de 8 bits. |
| Subtrator de 1 bit (`Sub.1b`) | Bloco de subtração binária de 1 bit. |
| Subtrator de 8 bits (`Sub.8b`) | Subtração binária em um barramento de 8 bits. |
| Buffer de 8 bits (`Buffer.8b`) | Encaminhamento de sinais de 8 bits. |
| NOR de 8 bits (`Nor.8b`) | Operação lógica NOR em 8 bits. |
| Decodificador de 1 bit (`Decode.1b`) | Decodificação de um sinal de seleção. |
| Decodificador de 2 bits (`Decode.2b`) | Decodificação de sinais de seleção. |
| Multiplexador 2×1 (`Mux2x1`) | Seleção entre duas entradas. |
| Multiplexador 4×1 (`Mux4x1`) | Seleção entre quatro entradas. |
| AMUX de 8 bits (`Amux.8b`) | Seleção de dados em um barramento de 8 bits. |
| Shifter de 8 bits (`Shifter.8b`) | Circuito para deslocamento de bits. |
| ULA de 8 bits (`ULA.8b`) | Esquema de integração da unidade lógica e aritmética, ainda em desenvolvimento. |

### Estado atual e limitações

- **Em desenvolvimento:** os arquivos representam o progresso atual do trabalho acadêmico.
- A presença de um arquivo da ULA **não significa** que todas as operações estejam integradas, concluídas ou verificadas.
- Não há garantia de cobertura completa de testes, tratamento de todos os casos-limite ou funcionamento pronto para produção.
- A organização e documentação poderão ser ampliadas conforme o projeto evoluir.

### Como abrir

1. Utilize o **CircuitMaker** compatível com os arquivos legados presentes neste repositório (cabeçalho dos arquivos: `CircuitMaker Text 5.6`).
2. Abra os arquivos `.CKT` para examinar os esquemas.
3. Os arquivos com `MACRO` no nome representam versões de componentes usadas na organização modular dos circuitos.
4. Os arquivos `USER.LIB` e `Treedb.dat` foram preservados do projeto original para auxiliar na compatibilidade. Faça cópias de segurança antes de substituir bibliotecas locais.

> **Observação:** dependendo da versão e da configuração do CircuitMaker, pode ser necessário ajustar bibliotecas ou caminhos de componentes.

---

## 🇺🇸 English

### About this project

This repository contains circuits created while studying **Digital Circuits** as part of a **Computer Science** degree. Its purpose is to put digital logic, control signals, and bit manipulation into practice through the gradual development of an **8-bit Arithmetic Logic Unit (ALU)**.

The schematics were created with **CircuitMaker** and are shared for academic purposes, learning, and tracking project progress.

### 🚧 Project status

**Status: INCOMPLETE — WORK IN PROGRESS.** The 8-bit ALU has not been finalized. The published circuits document development stages and may require further corrections, testing, and integration. This repository should not be considered a finished or fully validated ALU.

### 🆕 Latest update — four newly developed circuits

The latest version published in this repository includes the development and addition of these **four components**:

1. **1-bit decoder (`Decode.1b`)** — generates selection signals from a control input.
2. **2-to-1 multiplexer (`Mux2x1`)** — chooses between two inputs using a control signal.
3. **8-bit AMUX (`Amux.8b`)** — performs data selection across an 8-bit bus.
4. **8-bit shifter (`Shifter.8b`)** — implements bit shifting across an 8-bit bus.

These components **do not mark the completion of the ALU**; they represent another step in its modular development.

### Available circuits

| Component | Description |
| --- | --- |
| 1-bit adder (`Add.1b`) | 1-bit binary addition block. |
| 8-bit adder (`Add.8b`) | Binary addition across an 8-bit bus. |
| 1-bit subtractor (`Sub.1b`) | 1-bit binary subtraction block. |
| 8-bit subtractor (`Sub.8b`) | Binary subtraction across an 8-bit bus. |
| 8-bit buffer (`Buffer.8b`) | 8-bit signal forwarding. |
| 8-bit NOR (`Nor.8b`) | Bitwise NOR operation. |
| 1-bit decoder (`Decode.1b`) | Decoding of a selection signal. |
| 2-bit decoder (`Decode.2b`) | Decoding of selection signals. |
| 2-to-1 multiplexer (`Mux2x1`) | Selects one of two inputs. |
| 4-to-1 multiplexer (`Mux4x1`) | Selects one of four inputs. |
| 8-bit AMUX (`Amux.8b`) | Data selection across an 8-bit bus. |
| 8-bit shifter (`Shifter.8b`) | Bit-shifting circuit. |
| 8-bit ALU (`ULA.8b`) | Work-in-progress arithmetic logic unit integration schematic. |

### Project status and limitations

- **Work in progress:** these files reflect the current stage of an academic project.
- Having an ALU schematic **does not mean** every operation has been integrated, completed, or verified.
- Full test coverage, edge-case handling, and production readiness are **not guaranteed**.
- The project structure and documentation may be expanded as development continues.

### Opening the files

1. Use a **CircuitMaker** version compatible with these legacy files (file header: `CircuitMaker Text 5.6`).
2. Open the `.CKT` files to inspect the schematics.
3. Filenames containing `MACRO` denote component versions used for modular circuit organization.
4. The original `USER.LIB` and `Treedb.dat` files have been preserved to help with compatibility. Back up your local libraries before replacing anything.

> **Note:** Some versions or configurations of CircuitMaker may require library or component-path adjustments.

---

**Tecnologias / Tools:** CircuitMaker · Lógica digital / Digital logic · Circuitos combinacionais / Combinational circuits · ULA / ALU
