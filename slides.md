---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: 'text-center'
highlighter: shiki
lineNumbers: false
info: |
  ## Bitcoin: The Solution to a Broken System
  A deep dive into why Bitcoin matters and how it fixes the problems of fractional reserve banking.
drawings:
  persist: false
css: unocss
---

# Bitcoin: The Solution
## Breaking Free from the Fractional Reserve Prison

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: image-right
image: https://images.unsplash.com/photo-1633158829585-23ba8f7c8caf?ixlib=rb-4.0.3
---

# The Problem

Your money isn't really yours.

<v-clicks>

- Banks only keep a fraction of your deposits
- They create money out of thin air
- Your savings lose value through inflation
- You have no control over your wealth
- The system is designed to benefit the few

</v-clicks>

---
layout: two-cols
---

# Fractional Reserve Banking

How banks multiply your money without your permission

<v-clicks>

- You deposit $1,000
- Bank keeps only $100 (10%)
- Lends out $900
- That $900 gets redeposited
- Process repeats...
- Your $1,000 becomes $10,000 in the system

</v-clicks>

::right::

```mermaid {scale: 0.7}
graph TD
    A[Your $1,000 Deposit] --> B[Bank Reserve $100]
    A --> C[Loan $900]
    C --> D[New Deposit $900]
    D --> E[Bank Reserve $90]
    D --> F[Loan $810]
    F --> G[New Deposit $810]
    G --> H[...]
    style A fill:#f96
    style C fill:#9cf
    style F fill:#9cf
```

---
layout: center
class: text-center
---

# The Real Cost

<div grid="~ cols-2 gap-4">
<div>

## Inflation
Your money loses value every year

<div v-click class="mt-4">
<Counter :count="100" />
<p class="text-sm opacity-75">Your $100 purchasing power over time</p>
</div>

</div>
<div>

## Bank Profits
While they play with your money

```mermaid {scale: 0.7}
pie
    "Your Return" : 2
    "Bank Profits" : 15
    "Hidden Fees" : 8
```

</div>
</div>

---
layout: image-left
image: https://images.unsplash.com/photo-1621761191319-c6fb62004040?ixlib=rb-4.0.3
---

# Enter Bitcoin

The first truly sound money

<v-clicks>

- Fixed supply: Only 21 million ever
- No central authority
- Can't be inflated away
- You hold your own keys
- Transparent and verifiable
- Borderless and permissionless

</v-clicks>

<!--
- How many Millionaires are there?
- What happens if there is one server with all your data in it and it goes down?
- calculator analogy and on changing 1+1 = 2.
-
-->

---

# How Bitcoin Fixes This

<div class="grid grid-cols-2 gap-4">

<div v-click>

## Traditional Banking
- Centralized control
- Infinite money printing
- Your money, their rules
- Hidden fees and restrictions
- Requires trust in institutions

</div>

<div v-click>

## Bitcoin
- Decentralized network
- Fixed supply
- Your keys, your coins
- Transparent fees
- Trust in math, not humans

</div>

</div>

<div v-click class="mt-8">

```mermaid {scale: 0.7}
graph LR
    A[Your Money] --> B{Choice}
    B -->|Traditional| C[Bank Control]
    B -->|Bitcoin| D[Your Control]
    C --> E[Inflation & Fees]
    D --> F[Value Preservation]
```

</div>

---
layout: center
---

# The Path Forward

<div class="grid grid-cols-3 gap-4">

<div v-click>

## Learn
- Understand money
- Study Bitcoin
- Join communities
- Stay informed

</div>

<div v-click>

## Start Small
- Get a wallet
- Buy some Bitcoin
- Make a transaction
- Experience freedom

</div>

<div v-click>

## Take Control
- Be your own bank
- Protect your wealth
- Support the network
- Shape the future

</div>

</div>

---
layout: center
class: text-center
---

# Questions?

Let's discuss how we can break free from the traditional banking system

<div class="pt-12">
  <span class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Your financial freedom starts here
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://bitcoin.org" target="_blank" alt="Bitcoin"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:currency-dollar />
  </a>
</div>
