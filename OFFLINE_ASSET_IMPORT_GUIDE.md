# Offline Asset Import Guide

This project is configured to run fully offline from:
- [genizymath.github.io/iframe/90-fix2.html](genizymath.github.io/iframe/90-fix2.html)

## Current status (checked against your workspace)

Already present:
- [genizymath.github.io/iframe/Build/GrannyPortButBetter.json](genizymath.github.io/iframe/Build/GrannyPortButBetter.json)
- [genizymath.github.io/iframe/Build/GrannyPortButBetter.data.unityweb.part1](genizymath.github.io/iframe/Build/GrannyPortButBetter.data.unityweb.part1) through [genizymath.github.io/iframe/Build/GrannyPortButBetter.data.unityweb.part29](genizymath.github.io/iframe/Build/GrannyPortButBetter.data.unityweb.part29)
- [cdn.jsdelivr.net/gh/web-ports/granny@main/TemplateData/UnityProgress.js](cdn.jsdelivr.net/gh/web-ports/granny@main/TemplateData/UnityProgress.js)
- [cdn.jsdelivr.net/gh/web-ports/granny@main/Build/UnityLoader.js](cdn.jsdelivr.net/gh/web-ports/granny@main/Build/UnityLoader.js)

## Still needed (required)

These 2 files are required by [genizymath.github.io/iframe/Build/GrannyPortButBetter.json](genizymath.github.io/iframe/Build/GrannyPortButBetter.json) and are currently missing:

1. Source URL:
- `https://cdn.jsdelivr.net/gh/web-ports/granny@main/Build/GrannyPortButBetter.wasm.code.unityweb`
Destination path:
- [genizymath.github.io/iframe/Build/GrannyPortButBetter.wasm.code.unityweb](genizymath.github.io/iframe/Build/GrannyPortButBetter.wasm.code.unityweb)

2. Source URL:
- `https://cdn.jsdelivr.net/gh/web-ports/granny@main/Build/GrannyPortButBetter.wasm.framework.unityweb`
Destination path:
- [genizymath.github.io/iframe/Build/GrannyPortButBetter.wasm.framework.unityweb](genizymath.github.io/iframe/Build/GrannyPortButBetter.wasm.framework.unityweb)

## Optional

Optional local favicon:
- Source URL: `https://cdn.jsdelivr.net/gh/web-ports/granny@main/TemplateData/favicon.ico`
- Destination path: [cdn.jsdelivr.net/gh/web-ports/granny@main/TemplateData/favicon.ico](cdn.jsdelivr.net/gh/web-ports/granny@main/TemplateData/favicon.ico)

## Final offline check

1. Confirm both missing wasm files exist in [genizymath.github.io/iframe/Build](genizymath.github.io/iframe/Build)
2. Open [genizymath.github.io/iframe/90-fix2.html](genizymath.github.io/iframe/90-fix2.html)
3. Test while internet is disconnected
