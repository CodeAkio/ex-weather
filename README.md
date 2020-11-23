### Elixir - Parallel Weather App

#### How to use it

Open lib/app/weather.ex and add your app ID into fuction get_appid.

- $ mix test
- $ mix deps.get
- $ iex -S mix

``` ruby
iex> cities = ["Rio de Janeiro", "Niteroi", "Sao Paulo", "Porto Alegre"]
["Rio de Janeiro", "Niteroi", "Sao Paulo", "Porto Alegre"]

iex> App.SimpleWeather.start cities
["Rio de Janeiro: 30.3 °C", "Niteroi: 30.3 °C", "Sao Paulo: 28.0 °C",
 "Porto Alegre: 25.8 °C"]
```

``` ruby
Compiling 1 file (.ex)
....

Finished in 0.9 seconds
4 tests, 0 failures

Randomized with seed 217833
```

#### Enjoy!
