---
title: Either.ts
nav_order: 3
parent: Modules
---

# Either overview

Added in v1.6.0

---

<h2 class="text-delta">Table of contents</h2>

- [\_left](#_left)
- [\_right](#_right)

---

# \_left

**Signature**

```ts
export const _left = <L, A>(): Prism<Either<L, A>, L> => ...
```

Added in v1.6.0

# \_right

**Signature**

```ts
export const _right = <L, A>(): Prism<Either<L, A>, A> => ...
```

Added in v1.6.0
