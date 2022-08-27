# issue

## 安装

要使用 pnpm 安装

```
npm i -g pnpm

pnpm i 
```

## Failed to set up Chromium r901912! Set "PUPPETEER_SKIP_DOWNLOAD" env variable to skip download.

```
ERROR: Failed to set up Chromium r901912! Set "PUPPETEER_SKIP_DOWNLOAD" env variable to skip download.
│ Error: connect ECONNREFUSED 127.0.0.1:443
│     at TCPConnectWrap.afterConnect [as oncomplete] (net.js:1159:16) {
│   errno: -61,
│   code: 'ECONNREFUSED',
│   syscall: 'connect',
│   address: '127.0.0.1',
│   port: 443
│ }
```

```
export PUPPETEER_SKIP_DOWNLOAD='true'

pnpm i 
```