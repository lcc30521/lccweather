

<p align="center">高德天气组件</p>


## 安装


$ composer require lcc/weather -vvv
```

## 用法

use Lcc\Weather\Weather;

$key = 'xxxxxxxxxxxxxxxxxxxxxxxxxxx';

$weather = new Weather($key);

$response = $weather->getWeather('深圳');







## License

MIT