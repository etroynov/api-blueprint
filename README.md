![logo](assets/logo_apiblueprint.png)

# API Blueprint
### API Дизайн для людей

[![slack](https://apiblueprint-slack.herokuapp.com/badge.svg)](https://apiblueprint-slack.herokuapp.com/)

Мощьный высокоуровневый язык для проектирования веб API.

API Blueprint прост и доступен для всех тех кто занимается проектированием API полного жизненого цикла. Синтаксис данного языка прост но выразителен.

С API Blueprint вы сможете быстро смоделировать прототип APIs to be created or
describe already deployed mission-critical APIs. From a [car][tesla] to the
largest Content Distribution Network (CDN) in the world.

The API Blueprint is built to encourage dialogue and collaboration between
project stakeholders, developers and customers at any point in the API
lifecycle. At the same time, the API Blueprint [tools][] provide the support to
achieve the goals be it API development, governance or delivery.

![API Blueprint Lifecycle](assets/lifecycle.png)

[tesla]: https://github.com/timdorr/model-s-api/blob/master/apiary.apib
[tools]: http://apiblueprint.org/tools.html

## Open Source
API Blueprint is completely open sourced under the MIT license.
Any [contribution][contribute] is highly appreciated.

[contribute]: #contribute

## At home on GitHub
API Blueprint это язык признаный сервисом GitHub. Вы можете
[search for API Blueprint][search] or use the `apib` language identifier for
[syntax highlighting][gfm].

[search]: https://github.com/search?utf8=%E2%9C%93&q=language%3A%22API+Blueprint%22&type=Repositories&ref=advsearch&l=API+Blueprint&l=

[gfm]: https://help.github.com/articles/github-flavored-markdown/#syntax-highlighting

## С чего начать
Для описания нашего первого API, будет достаточно:

```apib
# GET /message
+ Response 200 (text/plain)

        Hello World!
```

в вашем любимом текстовом редкторе.

With this blueprint you can already get a [mock][], [documentation][] and
[test][] for your API before you even start coding.

To learn more about the API Blueprint syntax jump directly to the
[API Blueprint Tutorial][tutorial] or take a look at some [examples][].

[mock]: http://docs.apibstart.apiary.io/#reference/0/message/get?console=1
[documentation]: http://docs.apibstart.apiary.io
[test]: http://dredd.readthedocs.org/en/latest/
[tutorial]: Tutorial.md
[examples]: https://github.com/etroynov/api-blueprint/tree/master/examples

## Media Type
The media type for API Blueprint is `text/vnd.apiblueprint`.

## Информация для самостоятельного изучения
- [Руководстово][tutorial]
- [Advanced Tutorial][advanced_tutorial]
- [Приметы][examples]
- [Вики][wiki]
- [Словарь терминов][glossary]
- [Спецификация][specification]
- [Инструменты][tools]
- [Разработчикам][developers]

[advanced_tutorial]: Advanced%20Tutorial.md
[glossary]: Glossary%20of%20Terms.md
[specification]: API%20Blueprint%20Specification.md
[wiki]: https://github.com/etroynov/api-blueprint/wiki
[developers]: https://apiblueprint.org/developers.html

## Дорожная карта
Планы по дальнейшему развитию API Blueprint подробно описываются на GitHub – подробнее по ссылке
[API Blueprint дорожная карта][roadmap].

[roadmap]: https://github.com/etroynov/api-blueprint/wiki/Roadmap

## Разработчикам
Building tools for API Blueprint is possible thanks to its machine-friendly face
provided by API Blueprint parser.

If you are interested in building tools for API Blueprint check out the
[Developing tools for API Blueprint][developers].

## Сотрудничество
Feel free report problems or propose new ideas using the API Blueprint GitHub
[issues][].

We use an RFC process for proposing any substantial changes to the API
Blueprint language, specification and/or parsers.

Если вы хотите предложить изменение, вы можете проконсультироватся please consult our
[RFC process][rfc].

[issues]: https://github.com/etroynov/api-blueprint/issues
[rfc]: https://github.com/etroynov/api-blueprint-rfcs

## Контакты для связи
- [@apiblueprint](https://twitter.com/apiblueprint)
- [Slack](https://apiblueprint-slack.herokuapp.com/)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/apiblueprint)
- [GitHub Issues][issues]

## Лицензия
Данный язык доступен под MIT лицензией. Подробнее по ссылке [LICENSE](https://github.com/etroynov/api-blueprint/blob/master/LICENSE).
