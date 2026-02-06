# 📱 Modelagem de Sistema de Smartphones com POO

Este projeto foi desenvolvido como parte do desafio prático de **Programação Orientada a Objetos (POO)** da trilha .NET da **DIO (Digital Innovation One)**. O objetivo foi aplicar na prática os pilares da POO utilizando C#, modelando um sistema de smartphones de marcas distintas.

## 🎯 O Desafio
Proposto no bootcamp TIVIT - .Net com GitHub Copilot, o desafio consistiu em abstrair o funcionamento de celulares para que diferentes marcas (Nokia e iPhone) compartilhem uma base comum, mas mantenham comportamentos específicos através de:
1. Uma **Classe Abstrata** base para evitar instanciações indevidas.
2. **Herança** para reutilização de atributos comuns (Número, Modelo, IMEI, Memória).
3. **Sobrescrita de Métodos (Override)** para que cada marca implemente sua própria lógica de instalação de apps.



## 🧠 Pilares de POO Aplicados
* **Abstração:** Criação da classe `Smartphone`, que serve apenas como um "molde" para outras classes.
* **Herança:** As classes `Nokia` e `Iphone` herdam as propriedades e métodos da classe pai.
* **Polimorfismo:** O método `InstalarAplicativo` é abstrato na classe pai e ganha implementações únicas nas classes filhas.
* **Encapsulamento:** Propriedades como `Modelo`, `IMEI` e `Memoria` foram protegidas para garantir a integridade dos dados do objeto.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** C#
* **Paradigma:** Orientação a Objetos (POO)
* **Ambiente:** .NET 6.0 ou superior

## 🚀 Como Executar
1. Clone o repositório.
2. Abra no Visual Studio ou VS Code.
3. Execute o comando `dotnet run`. O console mostrará a simulação de uso de ambos os aparelhos, demonstrando o polimorfismo em ação.

---

A implementação utiliza construtores base (`base`) para passar parâmetros das classes filhas para a classe pai, garantindo uma inicialização limpa e organizada dos objetos.

[Meu GitHub](https://github.com/larissaribeiro-dev)