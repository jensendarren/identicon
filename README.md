# Identicon

## Running the Application

To run, at the terminal do the following:

```
iex -S mix
iex> Identicon.main("banana")
# creates 'banana.png' identicon!
```

## Expected output

In the terminal you will see the atom `:ok` and in your file system you will see a new `.png` file with the same name as the text you provide to the `Identicon.main` function.

For example, running `Identicon.main("banana")` will generate the `banana.png` identicon as shown below:

<img src="./img/banana.png" alt="drawing" width="150"/>

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).

