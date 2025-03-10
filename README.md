# Sistema iPhone - Desafio POO

Este projeto consiste na modelagem e implementação de um sistema para representar um **iPhone**, com funcionalidades de **Reprodutor Musical, Aparelho Telefônico e Navegador na Internet**. O código segue o paradigma da **Programação Orientada a Objetos (POO)** utilizando **interfaces** para modularidade.

## 📌 Funcionalidades Implementadas

1. **Reprodutor Musical** 
   - `tocar()`: Inicia a reprodução da música
   - `pausar()`: Pausa a música
   - `selecionarMusica(String musica)`: Seleciona uma música para reprodução

2. **Aparelho Telefônico** 
   - `ligar(String numero)`: Realiza uma ligação
   - `atender()`: Atende uma chamada
   - `iniciarCorreioVoz()`: Inicia o correio de voz

3. **Navegador na Internet** 
   - `exibirPagina(String url)`: Exibe uma página da web
   - `adicionarNovaAba()`: Adiciona uma nova aba ao navegador
   - `atualizarPagina()`: Atualiza a página atual

##  Estrutura do Código

O código segue a estrutura de **interfaces** para cada funcionalidade do iPhone. A classe `iPhone` implementa todas as interfaces e fornece a funcionalidade completa.

###  Classes e Interfaces

- `SistemaIPhone.java` (Classe principal - Ponto de entrada do programa)
- `ReprodutorMusical.java` (Interface do reprodutor de música)
- `AparelhoTelefonico.java` (Interface do aparelho telefônico)
- `NavegadorInternet.java` (Interface do navegador na internet)
- `iPhone.java` (Classe que implementa todas as interfaces)
 ```

## 📌 Exemplo de Saída no Terminal

```
Música selecionada: Bohemian Rhapsody
Reproduzindo música...
Música pausada.
Ligando para: +5511999999999
Chamada atendida.
Iniciando correio de voz...
Exibindo página: https://www.apple.com
Nova aba adicionada.
Página atualizada.
```

## 📜 Licença

Este projeto é de código aberto e pode ser utilizado para fins educacionais.

---

🚀 **Desenvolvido como parte do desafio de POO da DIO.**

