# 第三者ライセンス (Third-party notices)

UTAVISTA は、以下に列挙する第三者コンポーネントを同梱して配布します。本書は
`package-lock.json` で固定された本番依存グラフから生成しており、開発・テスト
専用のパッケージは含みません。各コンポーネントには、それぞれのライセンスが
引き続き適用されます。

配布アプリには、対応するライセンス文と通知ファイルの全文を macOS の
`Contents/Resources/legal/licenses/` 配下に同梱しています。UTAVISTA では
**環境設定 → 法的情報 → 第三者ライセンス** からこの一覧を表示し、全文ファイルを
Finder で開けます。

本書は `npm run third-party:notices` で生成します。手動で編集しないでください。

## アプリケーションランタイム

- Electron 44.4.0 — MIT — `licenses/electron/LICENSE`
- Chromium および Electron 同梱コンポーネント — 複数のライセンス — `licenses/electron/LICENSES.chromium.html`
- uv (同梱のインストーラ実行ファイル) — MIT OR Apache-2.0 — `licenses/uv/LICENSE-MIT`, `licenses/uv/LICENSE-APACHE`

## 相互主義ライセンスのコンポーネントのソース入手先

- mediabunny 1.46.0 は MPL-2.0 で配布されています。対応する上流ソースは https://github.com/Vanilagy/mediabunny/tree/v1.46.0 から入手できます。UTAVISTA は mediabunny を改変していません。

## 実行時 npm パッケージ (134)

- @hono/node-server@1.19.14 — MIT — [source](https://github.com/honojs/node-server) — `licenses/npm/hono__node-server@1.19.14/LICENSE`
- @modelcontextprotocol/sdk@1.29.0 — MIT — [source](https://github.com/modelcontextprotocol/typescript-sdk) — `licenses/npm/modelcontextprotocol__sdk@1.29.0/LICENSE`
- @pixi/colord@2.9.6 — MIT — [source](https://github.com/omgovich/colord) — `licenses/npm/pixi__colord@2.9.6/LICENSE.generated`
- @swc/helpers@0.5.23 — Apache-2.0 — [source](https://github.com/swc-project/swc) — `licenses/npm/swc__helpers@0.5.23/LICENSE`
- @types/dom-mediacapture-transform@0.1.11 — MIT — [source](https://github.com/DefinitelyTyped/DefinitelyTyped) — `licenses/npm/types__dom-mediacapture-transform@0.1.11/LICENSE`
- @types/dom-webcodecs@0.1.13 — MIT — [source](https://github.com/DefinitelyTyped/DefinitelyTyped) — `licenses/npm/types__dom-webcodecs@0.1.13/LICENSE`
- @types/earcut@3.0.0 — MIT — [source](https://github.com/DefinitelyTyped/DefinitelyTyped) — `licenses/npm/types__earcut@3.0.0/LICENSE`
- @types/gradient-parser@0.1.5 — MIT — [source](https://github.com/DefinitelyTyped/DefinitelyTyped) — `licenses/npm/types__gradient-parser@0.1.5/LICENSE`
- @types/prop-types@15.7.15 — MIT — [source](https://github.com/DefinitelyTyped/DefinitelyTyped) — `licenses/npm/types__prop-types@15.7.15/LICENSE`
- @types/react@18.3.28 — MIT — [source](https://github.com/DefinitelyTyped/DefinitelyTyped) — `licenses/npm/types__react@18.3.28/LICENSE`
- @webgpu/types@0.1.71 — BSD-3-Clause — [source](https://github.com/gpuweb/types) — `licenses/npm/webgpu__types@0.1.71/LICENSE`
- @xmldom/xmldom@0.8.13 — MIT — [source](https://github.com/xmldom/xmldom) — `licenses/npm/xmldom__xmldom@0.8.13/LICENSE`
- accepts@2.0.0 — MIT — [source](https://registry.npmjs.org/accepts/-/accepts-2.0.0.tgz) — `licenses/npm/accepts@2.0.0/LICENSE`
- ajv-formats@3.0.1 — MIT — [source](https://github.com/ajv-validator/ajv-formats) — `licenses/npm/ajv-formats@3.0.1/LICENSE`
- ajv@8.20.0 — MIT — [source](https://ajv.js.org) — `licenses/npm/ajv@8.20.0/LICENSE`
- base64-js@1.5.1 — MIT — [source](https://github.com/beatgammit/base64-js) — `licenses/npm/base64-js@1.5.1/LICENSE`
- body-parser@2.2.2 — MIT — [source](https://registry.npmjs.org/body-parser/-/body-parser-2.2.2.tgz) — `licenses/npm/body-parser@2.2.2/LICENSE`
- brotli@1.3.3 — MIT — [source](https://github.com/devongovett/brotli.js) — `licenses/npm/brotli@1.3.3/LICENSE.generated`
- bytes@3.1.2 — MIT — [source](https://registry.npmjs.org/bytes/-/bytes-3.1.2.tgz) — `licenses/npm/bytes@3.1.2/LICENSE`
- call-bind-apply-helpers@1.0.2 — MIT — [source](https://github.com/ljharb/call-bind-apply-helpers) — `licenses/npm/call-bind-apply-helpers@1.0.2/LICENSE`
- call-bound@1.0.4 — MIT — [source](https://github.com/ljharb/call-bound) — `licenses/npm/call-bound@1.0.4/LICENSE`
- clone@2.1.2 — MIT — [source](https://github.com/pvorb/node-clone) — `licenses/npm/clone@2.1.2/LICENSE`
- content-disposition@1.1.0 — MIT — [source](https://registry.npmjs.org/content-disposition/-/content-disposition-1.1.0.tgz) — `licenses/npm/content-disposition@1.1.0/LICENSE`
- content-type@1.0.5 — MIT — [source](https://registry.npmjs.org/content-type/-/content-type-1.0.5.tgz) — `licenses/npm/content-type@1.0.5/LICENSE`
- content-type@2.0.0 — MIT — [source](https://registry.npmjs.org/content-type/-/content-type-2.0.0.tgz) — `licenses/npm/content-type@2.0.0/LICENSE`
- cookie-signature@1.2.2 — MIT — [source](https://github.com/visionmedia/node-cookie-signature) — `licenses/npm/cookie-signature@1.2.2/LICENSE`
- cookie@0.7.2 — MIT — [source](https://registry.npmjs.org/cookie/-/cookie-0.7.2.tgz) — `licenses/npm/cookie@0.7.2/LICENSE`
- cors@2.8.6 — MIT — [source](https://registry.npmjs.org/cors/-/cors-2.8.6.tgz) — `licenses/npm/cors@2.8.6/LICENSE`
- cross-spawn@7.0.6 — MIT — [source](https://github.com/moxystudio/node-cross-spawn) — `licenses/npm/cross-spawn@7.0.6/LICENSE`
- csstype@3.2.3 — MIT — [source](https://github.com/frenic/csstype) — `licenses/npm/csstype@3.2.3/LICENSE`
- debug@4.4.3 — MIT — [source](https://github.com/debug-js/debug) — `licenses/npm/debug@4.4.3/LICENSE`
- depd@2.0.0 — MIT — [source](https://registry.npmjs.org/depd/-/depd-2.0.0.tgz) — `licenses/npm/depd@2.0.0/LICENSE`
- dfa@1.2.0 — MIT — [source](https://github.com/devongovett/dfa) — `licenses/npm/dfa@1.2.0/LICENSE.generated`
- dunder-proto@1.0.1 — MIT — [source](https://github.com/es-shims/dunder-proto) — `licenses/npm/dunder-proto@1.0.1/LICENSE`
- earcut@3.0.2 — ISC — [source](https://github.com/mapbox/earcut) — `licenses/npm/earcut@3.0.2/LICENSE`
- ee-first@1.1.1 — MIT — [source](https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz) — `licenses/npm/ee-first@1.1.1/LICENSE`
- encodeurl@2.0.0 — MIT — [source](https://registry.npmjs.org/encodeurl/-/encodeurl-2.0.0.tgz) — `licenses/npm/encodeurl@2.0.0/LICENSE`
- es-define-property@1.0.1 — MIT — [source](https://github.com/ljharb/es-define-property) — `licenses/npm/es-define-property@1.0.1/LICENSE`
- es-errors@1.3.0 — MIT — [source](https://github.com/ljharb/es-errors) — `licenses/npm/es-errors@1.3.0/LICENSE`
- es-object-atoms@1.1.1 — MIT — [source](https://github.com/ljharb/es-object-atoms) — `licenses/npm/es-object-atoms@1.1.1/LICENSE`
- escape-html@1.0.3 — MIT — [source](https://registry.npmjs.org/escape-html/-/escape-html-1.0.3.tgz) — `licenses/npm/escape-html@1.0.3/LICENSE`
- etag@1.8.1 — MIT — [source](https://registry.npmjs.org/etag/-/etag-1.8.1.tgz) — `licenses/npm/etag@1.8.1/LICENSE`
- eventemitter3@5.0.4 — MIT — [source](https://github.com/primus/eventemitter3) — `licenses/npm/eventemitter3@5.0.4/LICENSE`
- eventsource-parser@3.1.0 — MIT — [source](https://github.com/rexxars/eventsource-parser) — `licenses/npm/eventsource-parser@3.1.0/LICENSE`
- eventsource@3.0.7 — MIT — [source](https://github.com/EventSource/eventsource) — `licenses/npm/eventsource@3.0.7/LICENSE`
- express-rate-limit@8.5.2 — MIT — [source](https://github.com/express-rate-limit/express-rate-limit) — `licenses/npm/express-rate-limit@8.5.2/license.md`
- express@5.2.1 — MIT — [source](https://expressjs.com) — `licenses/npm/express@5.2.1/LICENSE`
- fast-deep-equal@3.1.3 — MIT — [source](https://github.com/epoberezkin/fast-deep-equal) — `licenses/npm/fast-deep-equal@3.1.3/LICENSE`
- fast-uri@3.1.2 — BSD-3-Clause — [source](https://github.com/fastify/fast-uri) — `licenses/npm/fast-uri@3.1.2/LICENSE`
- finalhandler@2.1.1 — MIT — [source](https://registry.npmjs.org/finalhandler/-/finalhandler-2.1.1.tgz) — `licenses/npm/finalhandler@2.1.1/LICENSE`
- fontkit@2.0.4 — MIT — [source](https://github.com/foliojs/fontkit) — `licenses/npm/fontkit@2.0.4/LICENSE.generated`
- forwarded@0.2.0 — MIT — [source](https://registry.npmjs.org/forwarded/-/forwarded-0.2.0.tgz) — `licenses/npm/forwarded@0.2.0/LICENSE`
- fresh@2.0.0 — MIT — [source](https://registry.npmjs.org/fresh/-/fresh-2.0.0.tgz) — `licenses/npm/fresh@2.0.0/LICENSE`
- function-bind@1.1.2 — MIT — [source](https://github.com/Raynos/function-bind) — `licenses/npm/function-bind@1.1.2/LICENSE`
- get-intrinsic@1.3.0 — MIT — [source](https://github.com/ljharb/get-intrinsic) — `licenses/npm/get-intrinsic@1.3.0/LICENSE`
- get-proto@1.0.1 — MIT — [source](https://github.com/ljharb/get-proto) — `licenses/npm/get-proto@1.0.1/LICENSE`
- gifuct-js@2.1.2 — MIT — [source](https://github.com/matt-way/gifuct-js) — `licenses/npm/gifuct-js@2.1.2/LICENSE`
- gopd@1.2.0 — MIT — [source](https://github.com/ljharb/gopd) — `licenses/npm/gopd@1.2.0/LICENSE`
- has-symbols@1.1.0 — MIT — [source](https://github.com/inspect-js/has-symbols) — `licenses/npm/has-symbols@1.1.0/LICENSE`
- hasown@2.0.3 — MIT — [source](https://github.com/inspect-js/hasOwn) — `licenses/npm/hasown@2.0.3/LICENSE`
- hono@4.12.25 — MIT — [source](https://github.com/honojs/hono) — `licenses/npm/hono@4.12.25/LICENSE`
- http-errors@2.0.1 — MIT — [source](https://registry.npmjs.org/http-errors/-/http-errors-2.0.1.tgz) — `licenses/npm/http-errors@2.0.1/LICENSE`
- iconv-lite@0.7.2 — MIT — [source](https://github.com/pillarjs/iconv-lite) — `licenses/npm/iconv-lite@0.7.2/LICENSE`
- inherits@2.0.4 — ISC — [source](https://github.com/isaacs/inherits) — `licenses/npm/inherits@2.0.4/LICENSE`
- ip-address@10.2.0 — MIT — [source](https://github.com/beaugunderson/ip-address) — `licenses/npm/ip-address@10.2.0/LICENSE`
- ipaddr.js@1.9.1 — MIT — [source](https://github.com/whitequark/ipaddr.js) — `licenses/npm/ipaddr.js@1.9.1/LICENSE`
- is-promise@4.0.0 — MIT — [source](https://github.com/then/is-promise) — `licenses/npm/is-promise@4.0.0/LICENSE`
- isexe@2.0.0 — ISC — [source](https://github.com/isaacs/isexe) — `licenses/npm/isexe@2.0.0/LICENSE`
- ismobilejs@1.1.1 — MIT — [source](https://github.com/kaimallea/isMobile) — `licenses/npm/ismobilejs@1.1.1/LICENSE`
- jose@6.2.3 — MIT — [source](https://github.com/panva/jose) — `licenses/npm/jose@6.2.3/LICENSE.md`
- js-binary-schema-parser@2.0.3 — MIT — [source](https://github.com/matt-way/jsBinarySchemaParser) — `licenses/npm/js-binary-schema-parser@2.0.3/LICENSE`
- js-tokens@4.0.0 — MIT — [source](https://registry.npmjs.org/js-tokens/-/js-tokens-4.0.0.tgz) — `licenses/npm/js-tokens@4.0.0/LICENSE`
- jsep@1.4.0 — MIT — [source](https://github.com/EricSmekens/jsep) — `licenses/npm/jsep@1.4.0/LICENSE`
- json-schema-traverse@1.0.0 — MIT — [source](https://github.com/epoberezkin/json-schema-traverse) — `licenses/npm/json-schema-traverse@1.0.0/LICENSE`
- json-schema-typed@8.0.2 — BSD-2-Clause — [source](https://github.com/RemyRylan/json-schema-typed) — `licenses/npm/json-schema-typed@8.0.2/LICENSE.md`
- loose-envify@1.4.0 — MIT — [source](https://github.com/zertosh/loose-envify) — `licenses/npm/loose-envify@1.4.0/LICENSE`
- lucide-react@1.34.0 — ISC — [source](https://github.com/lucide-icons/lucide) — `licenses/npm/lucide-react@1.34.0/LICENSE`
- math-intrinsics@1.1.0 — MIT — [source](https://github.com/es-shims/math-intrinsics) — `licenses/npm/math-intrinsics@1.1.0/LICENSE`
- media-typer@1.1.0 — MIT — [source](https://registry.npmjs.org/media-typer/-/media-typer-1.1.0.tgz) — `licenses/npm/media-typer@1.1.0/LICENSE`
- mediabunny@1.46.0 — MPL-2.0 — [source](https://github.com/Vanilagy/mediabunny) — `licenses/npm/mediabunny@1.46.0/LICENSE`
- merge-descriptors@2.0.0 — MIT — [source](https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-2.0.0.tgz) — `licenses/npm/merge-descriptors@2.0.0/license`
- mime-db@1.54.0 — MIT — [source](https://registry.npmjs.org/mime-db/-/mime-db-1.54.0.tgz) — `licenses/npm/mime-db@1.54.0/LICENSE`
- mime-types@3.0.2 — MIT — [source](https://registry.npmjs.org/mime-types/-/mime-types-3.0.2.tgz) — `licenses/npm/mime-types@3.0.2/LICENSE`
- ms@2.1.3 — MIT — [source](https://registry.npmjs.org/ms/-/ms-2.1.3.tgz) — `licenses/npm/ms@2.1.3/license.md`
- negotiator@1.0.0 — MIT — [source](https://registry.npmjs.org/negotiator/-/negotiator-1.0.0.tgz) — `licenses/npm/negotiator@1.0.0/LICENSE`
- object-assign@4.1.1 — MIT — [source](https://registry.npmjs.org/object-assign/-/object-assign-4.1.1.tgz) — `licenses/npm/object-assign@4.1.1/license`
- object-inspect@1.13.4 — MIT — [source](https://github.com/inspect-js/object-inspect) — `licenses/npm/object-inspect@1.13.4/LICENSE`
- on-finished@2.4.1 — MIT — [source](https://registry.npmjs.org/on-finished/-/on-finished-2.4.1.tgz) — `licenses/npm/on-finished@2.4.1/LICENSE`
- once@1.4.0 — ISC — [source](https://github.com/isaacs/once) — `licenses/npm/once@1.4.0/LICENSE`
- pako@0.2.9 — MIT — [source](https://github.com/nodeca/pako) — `licenses/npm/pako@0.2.9/LICENSE`
- parse-svg-path@0.2.0 — MIT — [source](https://github.com/jkroso/parse-svg-path) — `licenses/npm/parse-svg-path@0.2.0/LICENSE`
- parseurl@1.3.3 — MIT — [source](https://registry.npmjs.org/parseurl/-/parseurl-1.3.3.tgz) — `licenses/npm/parseurl@1.3.3/LICENSE`
- path-key@3.1.1 — MIT — [source](https://registry.npmjs.org/path-key/-/path-key-3.1.1.tgz) — `licenses/npm/path-key@3.1.1/license`
- path-to-regexp@8.4.2 — MIT — [source](https://github.com/pillarjs/path-to-regexp) — `licenses/npm/path-to-regexp@8.4.2/LICENSE`
- pixi-filters@6.1.5 — MIT — [source](https://github.com/pixijs/filters) — `licenses/npm/pixi-filters@6.1.5/LICENSE`
- pixi.js@8.19.0 — MIT — [source](https://github.com/pixijs/pixijs) — `licenses/npm/pixi.js@8.19.0/LICENSE`
- pkce-challenge@5.0.1 — MIT — [source](https://github.com/crouchcd/pkce-challenge) — `licenses/npm/pkce-challenge@5.0.1/LICENSE`
- proxy-addr@2.0.7 — MIT — [source](https://registry.npmjs.org/proxy-addr/-/proxy-addr-2.0.7.tgz) — `licenses/npm/proxy-addr@2.0.7/LICENSE`
- qs@6.15.1 — BSD-3-Clause — [source](https://github.com/ljharb/qs) — `licenses/npm/qs@6.15.1/LICENSE.md`
- range-parser@1.2.1 — MIT — [source](https://registry.npmjs.org/range-parser/-/range-parser-1.2.1.tgz) — `licenses/npm/range-parser@1.2.1/LICENSE`
- raw-body@3.0.2 — MIT — [source](https://registry.npmjs.org/raw-body/-/raw-body-3.0.2.tgz) — `licenses/npm/raw-body@3.0.2/LICENSE`
- react-dom@18.3.1 — MIT — [source](https://github.com/facebook/react) — `licenses/npm/react-dom@18.3.1/LICENSE`
- react@18.3.1 — MIT — [source](https://github.com/facebook/react) — `licenses/npm/react@18.3.1/LICENSE`
- require-from-string@2.0.2 — MIT — [source](https://registry.npmjs.org/require-from-string/-/require-from-string-2.0.2.tgz) — `licenses/npm/require-from-string@2.0.2/license`
- restructure@3.0.2 — MIT — [source](https://github.com/devongovett/restructure) — `licenses/npm/restructure@3.0.2/LICENSE`
- router@2.2.0 — MIT — [source](https://registry.npmjs.org/router/-/router-2.2.0.tgz) — `licenses/npm/router@2.2.0/LICENSE`
- safer-buffer@2.1.2 — MIT — [source](https://github.com/ChALkeR/safer-buffer) — `licenses/npm/safer-buffer@2.1.2/LICENSE`
- scheduler@0.23.2 — MIT — [source](https://github.com/facebook/react) — `licenses/npm/scheduler@0.23.2/LICENSE`
- send@1.2.1 — MIT — [source](https://registry.npmjs.org/send/-/send-1.2.1.tgz) — `licenses/npm/send@1.2.1/LICENSE`
- serve-static@2.2.1 — MIT — [source](https://registry.npmjs.org/serve-static/-/serve-static-2.2.1.tgz) — `licenses/npm/serve-static@2.2.1/LICENSE`
- setprototypeof@1.2.0 — ISC — [source](https://github.com/wesleytodd/setprototypeof) — `licenses/npm/setprototypeof@1.2.0/LICENSE`
- shebang-command@2.0.0 — MIT — [source](https://registry.npmjs.org/shebang-command/-/shebang-command-2.0.0.tgz) — `licenses/npm/shebang-command@2.0.0/license`
- shebang-regex@3.0.0 — MIT — [source](https://registry.npmjs.org/shebang-regex/-/shebang-regex-3.0.0.tgz) — `licenses/npm/shebang-regex@3.0.0/license`
- side-channel-list@1.0.1 — MIT — [source](https://github.com/ljharb/side-channel-list) — `licenses/npm/side-channel-list@1.0.1/LICENSE`
- side-channel-map@1.0.1 — MIT — [source](https://github.com/ljharb/side-channel-map) — `licenses/npm/side-channel-map@1.0.1/LICENSE`
- side-channel-weakmap@1.0.2 — MIT — [source](https://github.com/ljharb/side-channel-weakmap) — `licenses/npm/side-channel-weakmap@1.0.2/LICENSE`
- side-channel@1.1.0 — MIT — [source](https://github.com/ljharb/side-channel) — `licenses/npm/side-channel@1.1.0/LICENSE`
- statuses@2.0.2 — MIT — [source](https://registry.npmjs.org/statuses/-/statuses-2.0.2.tgz) — `licenses/npm/statuses@2.0.2/LICENSE`
- tiny-inflate@1.0.3 — MIT — [source](https://github.com/devongovett/tiny-inflate) — `licenses/npm/tiny-inflate@1.0.3/LICENSE`
- tiny-lru@11.4.7 — BSD-3-Clause — [source](https://github.com/avoidwork/tiny-lru) — `licenses/npm/tiny-lru@11.4.7/LICENSE`
- toidentifier@1.0.1 — MIT — [source](https://registry.npmjs.org/toidentifier/-/toidentifier-1.0.1.tgz) — `licenses/npm/toidentifier@1.0.1/LICENSE`
- tslib@2.8.1 — 0BSD — [source](https://github.com/Microsoft/tslib) — `licenses/npm/tslib@2.8.1/LICENSE.txt`
- type-is@2.1.0 — MIT — [source](https://registry.npmjs.org/type-is/-/type-is-2.1.0.tgz) — `licenses/npm/type-is@2.1.0/LICENSE`
- typescript@5.9.3 — Apache-2.0 — [source](https://github.com/microsoft/TypeScript) — `licenses/npm/typescript@5.9.3/LICENSE.txt`
- unicode-properties@1.4.1 — MIT — [source](https://github.com/devongovett/unicode-properties) — `licenses/npm/unicode-properties@1.4.1/LICENSE`
- unicode-trie@2.0.0 — MIT — [source](https://github.com/devongovett/unicode-trie) — `licenses/npm/unicode-trie@2.0.0/LICENSE`
- unpipe@1.0.0 — MIT — [source](https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz) — `licenses/npm/unpipe@1.0.0/LICENSE`
- use-sync-external-store@1.6.0 — MIT — [source](https://github.com/facebook/react) — `licenses/npm/use-sync-external-store@1.6.0/LICENSE`
- vary@1.1.2 — MIT — [source](https://registry.npmjs.org/vary/-/vary-1.1.2.tgz) — `licenses/npm/vary@1.1.2/LICENSE`
- which@2.0.2 — ISC — [source](https://github.com/isaacs/node-which) — `licenses/npm/which@2.0.2/LICENSE`
- wrappy@1.0.2 — ISC — [source](https://github.com/npm/wrappy) — `licenses/npm/wrappy@1.0.2/LICENSE`
- zod-to-json-schema@3.25.2 — ISC — [source](https://github.com/StefanTerdell/zod-to-json-schema) — `licenses/npm/zod-to-json-schema@3.25.2/LICENSE`
- zod@4.4.3 — MIT — [source](https://github.com/colinhacks/zod) — `licenses/npm/zod@4.4.3/LICENSE`
- zustand@4.5.7 — MIT — [source](https://github.com/pmndrs/zustand) — `licenses/npm/zustand@4.5.7/LICENSE`

## パッケージング時の検証

`npm run third-party:notices:check` は、古い一覧、不明なライセンス、および
npm パッケージ内にライセンス文が無く、審査済みの小さな代替一覧でも補えない
実行時パッケージを拒否します。`npm run third-party:bundle` は electron-builder が
使う `build/legal` リソースツリー一式を作成します。
