---
"@biomejs/biome": patch
---

Fixed [#13078](https://github.com/biomejs/biome/issues/13078): [`noUnusedClasses`](https://biomejs.dev/linter/rules/no-unused-classes/) now decodes CSS identifier escapes before comparing class selectors to HTML or JSX class names. `.foo\+bar` is treated as the same class as `foo+bar`.
