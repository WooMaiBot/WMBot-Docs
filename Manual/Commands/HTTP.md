# HTTP 请求

发起 HTTP 请求

## Usage

``` 
/curl <URL>
```

## Request Header

``` 
X-Request-At: Telegram Messenger (https://telegram.org)
X-Issue-Command: /curl
X-Request-User: 777000   // 请求者的 User ID
```

## User-Agent

``` 
WooMaiBot/2.9.1 (A Telegram Bot; Linux; curl/7.64.1; OpenSSL/1.0.2r; Powered by WooMai Labs; +https://t.me/s/WooMaiBotChannel)
```

## About robots.txt

抓取网页时会遵守 robots.txt, 如果希望禁止访问，请在 robots.txt 内添加

``` 
User-agent: WooMaiBot
Disallow: /
```
