# java-uml
```mermaid
classDiagram
  class Iphone {
    <<interface>>
  }


  class ReprodutorMusical {
    +void tocar()
    +void pausar()
    +void selecionarMusica(String musica)
  }

  class AparelhoTelefonico {
    +void ligar(String numero)
    +void atender()
    +void iniciarCorreioVoz()
  }

  class NavegadorNaInternet {
    +void exibirPagina(String url)
    +void adicionarNovaAba()
    +void atualizarPagina()
  }
  Iphone <|-- ReprodutorMusical
  Iphone <|-- AparelhoTelefonico
  Iphone <|-- NavegadorNaInternet
```mermaid
