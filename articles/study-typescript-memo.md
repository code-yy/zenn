---
title: "[TypeScript]ๅบๆฌใฎๅ"
emoji: "๐"
type: "tech" # tech: ๆ่ก่จไบ / idea: ใขใคใใข
topics: [TypeScript]
published: false
---

ๆ่ฟ TypeScript ใฎใคใณใใใใๅคใใชใฃใฆใใใฎใงใๆด็ใฎใใใซใพใจใใพใใใ

:::message alert

#### ใใฎ่จไบใงใใใชใใใจ

- TypeScript ใจใฏใฟใใใชๆฆๅฟต็่งฃ
- ๅฎ่ทต็ใช TypeScript ใฎไฝฟใๆน

ใใใใฏใพใๅฅใง่จไบใซใใใใจๆใฃใฆใใพใ
:::
ใใฎ่จไบใฎๆๅพใซใๅ่ใซใใ่จไบใ่ผใใฆใใใพใใ

## TypeScript ใฎๅ๏ผๅบๆฌ๏ผ

### ใใชใใใฃใๅ

TypeScript ไปฅไธใฎๅ 7 ใคใใใชใใใฃใๅใจๅผใณใพใใ

#### ๆๅญๅๅ(string)

ๆๅญๅใฎใฟใๅใๅใๅ

```tsx
const str: string = "Hello, TypeScript!";
const str: string = 111; // error
```

#### ๆฐๅคๅ(number)

ๆฐๅญใฎใฟใๅใๅใๅ

```tsx
const num: number = 0;
const num: number = "Hello, TypeScript!"; // error
```

#### ่ซ็ๅ(boolean)

็ๅฝๅค(true/false)ใฎใฟใๅใๅใๅ

```tsx
const bool: boolean = true;
const bool: boolean = false;
const bool: boolean = "Hello, TypeScript!"; // error
```

#### undefined ๅ

undefined ใฎใฟใๅใๅใๅ

```tsx
const undef: undefined = undefined;
const undef: undefined = null; // error
```

#### null ๅ

null ใฎใฟใๅใๅใๅ

```tsx
const null: null = null;
const null: null = undefined; // error
```

#### symbol ๅใจ bigint ๅ

ๅพใฏไปใซใ symbol ๅใจ bigint ๅใใใใพใใใใใพใ่ฆใใใจใใชใใๅ่ใซใใ่จไบใงใใใใพใงๆทฑใๆธใใใฆใใชใใฃใใฎใงใไปๅใฏๅฒๆใใใฆใใใ ใใพใใ

### ใชใใธใงใฏใๅ

TypeScript ใงใฏใใใชใใใฃใๅไปฅๅคใฎๅใใชใใธใงใฏใๅใจๅผใณใพใใ

#### any ๅ

#### void ๅ

#### object ๅ

#### ้ๅๅ
