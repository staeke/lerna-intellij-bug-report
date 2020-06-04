# lerna-intellij-bug-report

1. Open in IntelliJ
1. Run `npx lerna bootstrap`
1. Go to `packages/a/index.ts` and press Alt+Enter (or whatever auto-import is). Should be `import {getB} from 'B'` but becomes `https://github.com/staeke/lerna-intellij-bug-report`

NOTE: It works for javascriptt, but not typescript
