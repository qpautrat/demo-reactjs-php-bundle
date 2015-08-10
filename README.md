# demo-reactjs-php-bundle

Provide a small demo application using [qpautrat/reactjs-php-bundle](https://github.com/qpautrat/reactjs-php-bundle)

## Installation

```bash
docker build -t demo-reactjs-php-bundle .
docker run --name demo-reactjs-php-bundle -p 9000:9000 -v $PWD:/var/www/demo-reactjs-php-bundle demo-reactjs-php-bundle
```

Go to `http://localhost:9000` in your favorite browser