## npm 集成

```shell
npm i tls-sig-api-v2-typescript
```

## yarn 集成

```
yarn add tls-sig-api-v2-typescript
```

## 源码集成

将文件 `TLSSigAPIv2.ts` 放置于需要的路径下即可。

## 接口调用

```typescript
import * as TLSSigAPIv2 from 'tls-sig-api-v2'
const api = new TLSSigAPIv2.Api(1400000000, "5bd2850fff3ecb11d7c805251c51ee463a25727bddc2385f3fa8bfee1bb93b5e");
const sig = api.genSig("xiaojun", 86400*180);
console.log(sig);
```
