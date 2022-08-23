# Korea Bok-Nal (Three Dog Days) Calculator

[![Build Badge](https://img.shields.io/cirrus/github/Jennas-Lee/korea-bok-nal-calculator/main)](https://app.travis-ci.com/Jennas-Lee/korea-bok-nal-calculator)


## Overview

Calculate Korea's _Three Dog Days (Bok-Nal)_. [What is Bok-Nal?](https://folkency.nfm.go.kr/en/topic/detail/4130)

대한민국의 잡절인 복날(삼복) 날짜를 계산합니다.

초복 : 하지 후 세 번째 오는 경일

중복 : 하지 후 네 번째 오는 경일

말복 : 입추 후 첫 번재 경일

## How to use

### Install using `pip`

``` shell
pip install boknal
```

### Quickstart

Get this year's bok-nal:

``` python
from boknal import Boknal

this_year_boknal = Boknal()

print('chobok', this_year_boknal.chobok)

print('jungbok', this_year_boknal.jungbok)

print('malbok', this_year_boknal.malbok)
```

Output:

```
chobok 2022-07-16
jungbok 2022-07-26
malbok 2022-08-15
```

Get specific year's bok-nal:

``` python
from boknal import Boknal

this_year_boknal = Boknal(2012)

print('chobok', this_year_boknal.chobok)

print('jungbok', this_year_boknal.jungbok)

print('malbok', this_year_boknal.malbok)
```

Output:

```
chobok 2012-07-18
jungbok 2012-07-28
malbok 2012-08-07
```