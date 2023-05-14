> ALL MODULE

- 개발할때 도움될만한 기능들이 들어가 있습니다.

계속 업데이트됩니다.

> 영상

<div style="position:relative;width:fit-content;height:fit-content;">
            <a style="position:absolute;top:20px;right:1rem;opacity:0.8;" href="https://clipchamp.com/watch/QLdWDHX5j23?utm_source=embed&utm_medium=embed&utm_campaign=watch">
                <img style="height:22px;" src="https://clipchamp.com/e.svg" alt="Made with Clipchamp" />
            </a>
            <iframe allow="autoplay;" allowfullscreen style="border:none" src="https://clipchamp.com/watch/QLdWDHX5j23/embed" width="640" height="360"></iframe>
        </div>

> 다운로드 방법

```cmd
npm i @keunheekwon/all_module
```

> JAVASCRIPT

- color

```js
const { Color } = require("@keunheekwon/all_module");
const color = new Color();
console.log(color.white());
```

- log

```js
const { Log } = require("@keunheekwon/all_module");
const logger = new Log("테스트");

logger.log("로그 테스트");
logger.error("에러 로그 테스트");
logger.debug("디버그 로그 테스트");
logger.info("인포 로그 테스트");
logger.warning("경고 로그 테스트");
```

- color log

```js
const { LogColor } = require("@keunheekwon/all_module");
const logcolor = new LogColor();
logcolor.white("test");
```

- math

```js
const { Math } = require("@keunheekwon/all_module");
const math = new Math();
console.log(math.pi()); // 파이
console.log(math.divide(6, 3)); // 나누기
console.log(math.minus(6, 3)); // 빼기
console.log(math.multiply(6, 3)); // 곱하기
console.log(math.plus(6, 3)); // 더하기
console.log(math.power(6, 3)); // 제곱
```

- random

```js
const { Random } = require("@keunheekwon/all_module");
const random = new Random();
console.log(random.random(100));
console.log(random.random(50));
```

- timestamp

```js
const { TimeStamp } = require("../index");
const t = new TimeStamp(new Date());

console.log(t.koreaTimeStamp());
console.log(t.discordTimeStamp());
```

> 업데이트 기록

- 2023:05:14 ( ALL MODULE 출시 )
