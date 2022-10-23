# Simple Web Server Elixir

## RUN


Run terminal `iex -S mix` 

iex (1)> `{:ok, _pid} = Plug.Cowboy.http(ServerElixir.WebServer,[])`

```elixir
def deps do
  [
    {:server_elixir, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at <https://hexdocs.pm/server_elixir>.

