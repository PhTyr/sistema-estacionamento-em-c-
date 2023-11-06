# DIO - Trilha .NET - Fundamentos
[www.dio.me](https://www.dio.me)

## Desafio de Projeto
Este desafio envolve a aplicação dos conhecimentos adquiridos no módulo de fundamentos da trilha .NET da DIO.

## Contexto
Fomos contratados para desenvolver um sistema de gerenciamento de estacionamento. Este sistema tem como finalidade gerenciar os veículos estacionados e realizar operações como adicionar veículos, remover veículos (calculando o valor cobrado durante o período) e listar os veículos estacionados.

## Proposta
Para atender aos requisitos do projeto, é necessário construir uma classe chamada "Estacionamento". A classe é composta por três variáveis:

**precoInicial**: do tipo decimal, representa o preço cobrado para deixar um veículo estacionado.

**precoPorHora**: do tipo decimal, representa o preço por hora que o veículo permanece estacionado.

**veiculos**: uma lista de strings que representa uma coleção de veículos estacionados, contendo apenas a placa do veículo.

A classe "Estacionamento" possui três métodos:

**AdicionarVeiculo**: Método responsável por receber a placa de um veículo digitada pelo usuário e armazená-la na variável **veiculos**.

**RemoverVeiculo**: Método responsável por verificar se um veículo específico está estacionado. Caso positivo, o método solicitará ao usuário a quantidade de horas que o veículo permaneceu estacionado e, em seguida, calculará o valor a ser cobrado usando a fórmula: **precoInicial** * **precoPorHora**. O valor calculado é então exibido ao usuário.

**ListarVeiculos**: Lista todos os veículos atualmente estacionados. Caso não haja veículos estacionados, a mensagem "Não há veículos estacionados" é exibida.

Além disso, um menu interativo foi implementado com as seguintes ações:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar

## Solução
O código fornecido está pela metade, e você deve continuar implementando de acordo com as regras mencionadas acima. Procure pelos comentários "TODO" no código e implemente as funcionalidades restantes para que o programa final funcione corretamente.