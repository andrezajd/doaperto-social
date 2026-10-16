# Diagrama de Classes - DoaPerto Social

```mermaid
classDiagram
    class Usuario {
        <<abstract>>
        -int id
        -String nome
        -String email
        -String senha
        +login() boolean
        +logout() void
    }

    class Doador {
        -String cidade
        -boolean anonimo
        +agendarDoacao() void
        +visualizarCampanhas() List
    }

    class Instituicao {
        -String cnpj
        -String endereco
        -String telefone
        -boolean validada
        +criarCampanha() void
        +gerenciarAgendamentos() void
    }

    class Campanha {
        -int id
        -String titulo
        -String descricao
        -Date dataFim
        -boolean statusAtiva
        +adicionarItem() void
        +encerrarCampanha() void
    }

    class Agendamento {
        -int id
        -DateTime dataEntrega
        -String status
        +confirmarRecebimento() void
        +cancelar() void
    }

    %% Relacionamentos Corrigidos (Sem setas de navegabilidade)
    Usuario <|-- Doador : Herança
    Usuario <|-- Instituicao : Herança
    
    Instituicao "1" -- "*" Campanha : cria
    Doador "1" -- "*" Agendamento : realiza
    Agendamento "*" -- "1" Campanha : referente a

```

**O que mudou na prática?**
Trocamos os `-->` e `<--` por `--`. Isso cria uma linha reta padrão no Mermaid. Além disso, invertemos a ordem do último relacionamento para `Agendamento "*" -- "1" Campanha : referente a`, o que facilita a leitura de cima para baixo no desenho final: *"Um Doador realiza Agendamentos, e esses Agendamentos são referentes a uma Campanha"*.
