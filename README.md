# Dlocal payouts

**an unofficial package Dlocal payouts API library for Elixir**

The Dlocal Elixir library provides convenient access to the [Dlocal payouts API](https://docs.dlocal.com/api-documentation/payout-api-reference) from applications written in the Elixir language.

## Installation

the package can be installed by adding `dlocal` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:dlocal, "~> 0.1.6", git: "https://github.com/Zubale/dlocal.git"}
  ]
end
```

## Configuration

```elixir

# config/config.exs
config :dlocal,
  sandbox: System.get_env("DLOCAL_SANDBOX"),
  url: System.get_env("DLOCAL_URL")
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/dlocal](https://hexdocs.pm/dlocal).

