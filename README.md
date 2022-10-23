# Simple Web Server Elixir

## RUN


Run terminal `iex -S mix` 

iex (1)> `{:ok, _pid} = Plug.Cowboy.http(ServerElixir.WebServer,[])`

Access
http://localhost:4000

```elixir
Hello World
```
Shutdown
iex (2)> `Plug.Cowboy.shutdown(ServerElixir.WebServer.HTTP)`

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at <https://hexdocs.pm/server_elixir>.

