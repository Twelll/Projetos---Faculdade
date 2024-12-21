# 🚦Projeto Semáforo

## 📃Objetivo Geral
O objetivo deste projeto foi criar um semáforo conforme as restrições e informações fornecidas pelos professores.

## 🗡Desafio

### 1. Ciclo de Passagem de Carros
- **Condições**:
  - O semáforo da via deve estar sempre verde.
  - O semáforo do pedestre deve estar sempre vermelho.

### 2. Modo de Passagem de Pedestre (quando o botão é pressionado)
- **Etapas**:
  1. **Semáforo da via**:
     - Fica amarelo por 3 segundos.
     - Fica vermelho por 2 segundos.
  2. **Semáforo do pedestre**:
     - Fica verde por 5 segundos.
     - Pisca o verde 3 vezes durante 6 segundos.
  3. **Modo Latência**:
     - Duração: 5 segundos.
     - Durante esse período, os semáforos operam no modo de passagem de veículos.
     - Se o botão for pressionado durante a latência:
       - O ciclo de pedestre não começa imediatamente.
       - O ciclo só inicia após os 5 segundos de latência.
     - Se o botão não for pressionado, o semáforo retorna ao modo "passagem de veículos".

### 3. Restrição Importante
- O semáforo não pode reiniciar o modo "passagem de pedestre" se o botão for pressionado novamente durante o ciclo.

## 📄 Licença
Você pode usar, modificar e distribuir este projeto. [MIT License](./LICENSE)
