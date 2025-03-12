# sed_projet
# Controle de Robôs Autônomos em um Armazém

Este repositório contém a implementação do projeto **Controle de Robôs Autônomos em um Armazém**, desenvolvido como parte da disciplina **Sistemas a Eventos Discretos** na **Universidade Federal de Campina Grande (UFCG)**.

## Integrantes do Projeto
- Gabrielle Pereira Barbosa
- Sarah Stella Borba Miguel
- Victor Gomes de Freitas Borge

## Professor Orientador
- Prof. Kyller Costa Gorgônio

## Descrição
O projeto tem como objetivo desenvolver um sistema de controle supervisionado para robôs móveis em um armazém automatizado. O sistema é baseado em **Autômatos Finitos** e **Controle Supervisório**, garantindo que os robôs realizem suas tarefas sem colisões e seguindo as regras operacionais predefinidas.

### Componentes do Sistema
- **3 Robôs (R1, R2, R3):** Transportam caixas do Buffer de Entrada (BE) para as máquinas de processamento.
- **4 Máquinas (M1, M2, M3, M4):** Recebem os insumos e processam as cargas.
- **Buffer de Entrada (BE):** Local onde os robôs coletam os insumos antes da entrega.

### Funcionamento
1. Uma máquina solicita um insumo.
2. O sistema aloca um robô disponível para transportar a carga.
3. O robô coleta o insumo no BE e o leva à máquina solicitante.
4. Em caso de falha de R1 ou R2, o robô R3 assume a tarefa.

## Implementação
A implementação do sistema foi realizada utilizando **autômatos finitos** para modelagem do comportamento dos robôs e das máquinas, além de um **supervisor** para gerenciar as transições de estado e as falhas eventuais.

## Requisitos
- Python 3+
- Ferramentas para modelagem de autômatos

## Execução
1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/controle-robos-armazem.git
   ```
2. Navegue até o diretório do projeto:
   ```sh
   cd controle-robos-armazem
   ```
3. Execute os arquivos conforme documentado na seção de implementação.

## Apresentação do Projeto
Assista à apresentação do projeto no YouTube: [Link para o vídeo]

## Relatório
O relatório completo do projeto está disponível neste repositório como **Relatório_SED.pdf**.



