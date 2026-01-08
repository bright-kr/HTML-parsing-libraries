# Webスクレイピング을 위한 최고의 HTML 파싱 라이브러리

[![Promo](https://github.com/bright-kr/LinkedIn-Scraper/raw/main/Proxies%20and%20scrapers%20GitHub%20bonus%20banner.png)](https://brightdata.co.kr/) 

[web scraping](https://github.com/bright-kr/Awesome-Web-Scraping) 및 데이터 추출을 위한 최고의 HTML 파서를 살펴보고, `httpx`, `AIOHTTP`, `urllib` 등을 확인해 보십시오.

## HTML 파서란 무엇입니까?

HTML 파서는 HTML 문서를 처리하여, 탐색 및 조작이 쉬운 구조화된 데이터 형식으로 변환합니다. 이들은 HTML 코드를 분석하여 문서의 DOM을 나타내는 트리 형태의 구조를 구축합니다. HTML 파서는 Webスクレイピング에 필수적이며, 웹사이트에서 상품명과 가격 같은 정보를 추출할 수 있게 해줍니다.

## HTML 파서 선택 시 주요 고려 사항

- **장단점**: 라이브러리의 이점과 단점입니다.
- **프로그래밍 언어**: 라이브러리가 작성된 언어입니다.
- **GitHub Stars**: 인기도를 나타내는 지표입니다.
- **CSS Selector 지원**: 내장 CSS Selector 지원 여부입니다.
- **XPath 지원**: 내장 XPath 표현식 지원 여부입니다.

## 상위 7가지 HTML 파서

### 1. [jsoup](https://jsoup.org/)

- **장점**: WHATWG HTML 사양을 구현하고, HTTP 클라이언트를 포함하며, 방대한 API를 제공합니다.
- **단점**: 가장 빠르지는 않습니다.
- **언어**: Java
- **GitHub Stars**: 10.5k
- **CSS Selector 지원**: 예
- **XPath 지원**: 예

> 💡 [**web scraping with jsoup**](https://brightdata.co.kr/blog/how-tos/web-scraping-with-jsoup)에서 더 알아보십시오.

### 2. [Nokogiri](https://nokogiri.org/index.html)

- **장점**: 기본적으로 보안이 적용되어 있고, CSS3 selector를 지원하며, 전체 API 문서를 제공합니다.
- **단점**: 가장 널리 사용되지는 않습니다.
- **언어**: Ruby
- **GitHub Stars**: 6.1k
- **CSS Selector 지원**: 예
- **XPath 지원**: 예

> 💡 [**web scraping with Ruby**](https://brightdata.co.kr/blog/how-tos/web-scraping-with-ruby)에서 더 알아보십시오.

### 3. [Beautiful Soup](https://pypi.org/project/beautifulsoup4/)

- **장점**: 여러 파서를 지원하고, 널리 사용되며, 코드 포맷팅이 가능합니다.
- **단점**: API 문서가 없고, 네이티브 XPath 지원이 없습니다.
- **언어**: Python
- **GitHub Stars**: —
- **CSS Selector 지원**: 예
- **XPath 지원**: `lxml`을 통해 가능

> 💡 [**web scraping with Beautiful Soup**](https://brightdata.co.kr/blog/how-tos/beautiful-soup-web-scraping)에서 더 알아보십시오.

### 4. [Cheerio](https://cheerio.js.org/)

- **장점**: jQuery와 유사한 문법, 높은 성능을 제공합니다.
- **단점**: 아직 베타이며, XPath 지원이 없습니다.
- **언어**: JavaScript (Node.js)
- **GitHub Stars**: 27.6k
- **CSS Selector 지원**: 예
- **XPath 지원**: 아니요

> 💡 [**web scraping with Cheerio**](https://brightdata.co.kr/blog/how-tos/cheerio-npm-web-scraping)에서 더 알아보십시오.

### 5. [Html Agility Pack](https://html-agility-pack.net/)

- **장점**: .NET 언어와 함께 작동하며, XSLT를 지원합니다.
- **단점**: 문서가 적고, 네이티브 CSS Selector 지원이 없습니다.
- **언어**: C#
- **GitHub Stars**: 2.5k
- **CSS Selector 지원**: 확장 기능을 통해 가능
- **XPath 지원**: 예

> 💡 [**web scraping with Html Agility Pack**](https://brightdata.co.kr/blog/how-tos/web-scraping-with-c-sharp)에서 더 알아보십시오.

### 6. [libxml2](https://gitlab.gnome.org/GNOME/libxml2)

- **장점**: 많은 라이브러리에서 사용되며, 매우 뛰어난 성능을 제공합니다.
- **단점**: API가 복잡하고, XPath로 제한됩니다.
- **언어**: C
- **GitHub Stars**: —
- **CSS Selector 지원**: 아니요
- **XPath 지원**: 예

> 💡 [**web scraping with libxml2**](https://brightdata.co.kr/blog/how-tos/web-scraping-in-c-plus-plus)에서 더 알아보십시오.

### 7. [PHPHtmlParser](https://github.com/paquettg/php-html-parser)

- **장점**: 깨진 HTML도 파싱하며, 완전한 API를 제공합니다.
- **단점**: 활발히 유지 관리되지 않으며, 문서가 없습니다.
- **언어**: PHP
- **GitHub Stars**: 2.3k
- **CSS Selector 지원**: 예
- **XPath 지원**: 아니요

> 💡 [**web scraping with PHP**](https://brightdata.co.kr/blog/how-tos/web-scraping-php)에서 더 알아보십시오.

## 요약 표

| HTML Parser       | Language | GitHub Stars | CSS Selector | XPath |
|-------------------|----------|--------------|--------------|-------|
| jsoup             | Java     | 10.5k        | ✅           | ✅    |
| Nokogiri          | Ruby     | 6.1k         | ✅           | ✅    |
| Beautiful Soup    | Python   | —            | ✅           | Possible via `lxml` |
| Cheerio           | JavaScript | 27.6k      | ✅           | ❌    |
| Html Agility Pack | C#       | 2.5k         | Possible via extension | ✅ |
| libxml2           | C        | —            | ❌           | ✅    |
| PHPHtmlParser     | PHP      | 2.3k         | ✅           | ❌    |

## 결론

이 가이드는 최고의 HTML 파싱 라이브러리를 살펴보았습니다. 선택은 사용하시는 프로그래밍 언어와 프로젝트 요구 사항에 따라 달라집니다. 또한 웹사이트는 アンチボット 기술을 사용할 수 있지만, [Bright Data의 プロキシ 서비스](https://brightdata.co.kr/proxy-types) 또는 [Web Scrapers](https://brightdata.co.kr/products/web-scraper) 같은 도구를 활용하면 파싱을 위한 HTML을 가져오는 데 도움이 됩니다.

특정 웹사이트를 스クレイピング하는 방법을 알아보십시오:

- [**Amazon**](https://github.com/bright-kr/LinkedIn-Scraper)
- [**LinkedIn**](https://github.com/bright-kr/LinkedIn-Scraper)
- [**Google Maps**](https://github.com/bright-kr/Google-Maps-Scraper)
- [**Google News**](https://github.com/bright-kr/Google-News-Scraper)