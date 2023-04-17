
```mermaid

classDiagram
  direction RL

  class Produto{
    -id : int
    -nome : String
    -descricao : String
    -preco : Float
    -tipo : String
  }
  class Usuario{
    -id : int
    -usermane : String
    -senha : String
    -cargo : String
    -tipo_permissao : Bool
  }
  class Cliente{
    -id : int
    -nome : String
    -telefone : String
    -endereco : String
    -email : String
  }
  class Estoque{
    -id : int 
    -id_prod : int
    -desc_prod : String
    -qtde : int
  }
  class Pagamento{
    -id : int
    -id_cli : int
    -id_vend : int
    -status : Bool
    -data : date
    -valor_total : Float
    -tipo : String
  }
  class Venda{
    -id : int
    -id_cli : int
    -data_time : date
    -tipo_prod : String
    -preco_prod : Float
    -qtde_prod : int
    -valor_total : Float
  }
  class Relatorio{
    -id : int
    -desc_relat : String
    -id_vend : int
  }

  Produto "1..n" -- "1..n" Usuario : vende
  Produto "1..n" -- "0..n" Cliente : compra
  Produto "1..n" -- "1..n" Estoque : tem
  Cliente "1..1" -- "1..1" Pagamento : realiza
  Cliente "1..1" -- "1..n" Venda : possiu
  Pagamento "1..1" -- "1..1" Venda : gera
  Produto "1..n" -- "1..n" Venda : tem
  Venda "1..n" -- "1..n" Relatorio : possui


```