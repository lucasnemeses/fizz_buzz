# FizzBuzz

Primeiro projeto em Elixir.

## Explicação do problema

- Múltiplos de 3 substituídos por Fizz
- Múltiplos de 5 substituídos por Buzz
- Múltiplos de 3 e 5 substituídos por FizzBuzz

[1, 2, 3, 4, 5, 15] => [1, 2, Fizz, 4, Buzz, FizzBuzz]

[1, 2, 4, 8, 10] => [1, 2, 4, 8, Buzz]

## Executando o projeto

```bash
mix compile
iex -S mix
```

```elixir
FizzBuzz.build("numbers.txt")
```

## Executando os testes

```bash
mix test
```
