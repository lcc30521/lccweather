

<p align="center">高德天气组件</p>


## Installing


$ composer require lcc/weather -vvv
```

## Usage

use Lcc\Weather\Weather;

$key = 'xxxxxxxxxxxxxxxxxxxxxxxxxxx';

$weather = new Weather($key);

$response = $weather->getWeather('深圳');







## License

MIT