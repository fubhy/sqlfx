---
title: Schema.ts
nav_order: 4
parent: Modules
---

## Schema overview

Added in v1.0.0

---

<h2 class="text-delta">Table of contents</h2>

- [utils](#utils)
  - [decode](#decode)

---

# utils

## decode

**Signature**

```ts
export declare const decode: <I, A>(
  schema: Schema.Schema<I, A>,
  type: any
) => (input: I) => Effect.Effect<never, any, A>
```

Added in v1.0.0