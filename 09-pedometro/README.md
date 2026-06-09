# Projeto 09: Pedómetro (Contador de Passos e Distância)

Este projeto foi desenvolvido no âmbito do projeto de extensão **Elas Programando**. O aplicativo utiliza os sensores internos do smartphone para detetar o movimento do utilizador, calculando a quantidade exata de passos dados e estimando a distância percorrida em metros, promovendo a monitorização de atividades físicas de forma simples e intuitiva.

## Demonstração do App
Veja abaixo o sensor em funcionamento, alterando as imagens de estado e contando os passos em tempo real:

![Demonstração do Pedómetro](pedometro%(1).gif)

---

## Funcionalidades
* **Contagem de Passos e Metros:** Atualização instantânea na tela assim que o sensor deteta o deslocamento físico.
* **Interface Responsiva por Estados:** Mudança dinâmica das imagens de exibição baseada na atividade do utilizador ("Comece a andar" ou "Descanse um pouco").
* **Painel de Controle Completo:** Botões para `INICIAR` a monitorização, `PARAR` o sensor temporariamente e `REINICIAR` para zerar as métricas coletadas.

---

## Conceitos de Programação Aprendidos
* **Uso de Sensores Nativos (`Pedometer`):** Exploração do sensor de pedómetro/acelerómetro do dispositivo para capturar vibrações e passos mecânicos reais.
* **Estruturas Condicionais Dinâmicas:** Uso de blocos de lógica (`if/then`) para verificar o progresso dos passos e alterar as imagens e textos da interface dependendo do comportamento do utilizador.
* **Conversão de Dados Matemáticos:** Aplicação de fórmulas simples internas para converter a passada detetada em distância estimada em metros.
