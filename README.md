# lerna-intellij-bug-report

1. Open in IntelliJ
1. Run `npx lerna bootstrap`
1. Go to `packages/a/index.ts` and press Alt+Enter (or whatever auto-import is). Should be `import {getB} from 'B'` but becomes `import {getB} from '../b/index';`

NOTE: It works for javascript, but not typescript
