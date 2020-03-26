## Fork of https://github.com/mohuk/ts-jsonapi
Changes:
  1. deserializer returns `{ data, meta }` object where `meta` -> top level meta object, `data` -> a regular deserialized resource.
  2. Each resource object includes meta object 
  3. For meta object applied same letter casing options.
  4. Fixed tests

### NPM - https://www.npmjs.com/package/@vvitto/ts-jsonapi
