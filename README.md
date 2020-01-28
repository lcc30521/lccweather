<h1 align="center"> weather </h1>

<p align="center"> test weatger.</p>


## Installing


$ composer require lcc/weather -vvv
```

## Usage

use Lcc\Weather\Weather;

$key = 'xxxxxxxxxxxxxxxxxxxxxxxxxxx';

$weather = new Weather($key);

$response = $weather->getWeather('深圳');



## Contributing



## License

MIT