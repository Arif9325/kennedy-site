# Kennedy Poulet frit & Pizza

Website and digital menu boards for Kennedy Poulet frit & Pizza, 5904 boul. Gouin Ouest, Montréal.

- **Website:** https://kennedypouletpizza.com
- **TV menu boards:** https://kennedypouletpizza.com/menu/

## TV menu boards

Open one of these links fullscreen on each TV:

| Link | Board |
|---|---|
| `/menu/#1` | Pizzas |
| `/menu/#2` | Poulet frit |
| `/menu/#3` | Super combos |
| `/menu/#4` | Burgers & sous-marins |
| `/menu/#5` | Poutines, pâtes & plus |
| `/menu/` | Rotates through all five (15 s each) |

Keyboard shortcuts: ← / → to change screens, `1`–`5` to pin a screen, `0` to rotate, `F` for fullscreen.

## Changing prices

Prices live in the `const MENU = { ... }` block in **both** files:

- `index.html` (website)
- `menu/index.html` (TV boards)

Edit the number in both, commit, and push. GitHub Pages updates within a minute or two, and the TVs pick it up on their next refresh.

## Hosting (GitHub Pages)

1. Settings → Pages → Source: `main` branch, `/ (root)`.
2. Custom domain: `kennedypouletpizza.com` (the `CNAME` file already sets this).
3. Tick **Enforce HTTPS** once it becomes available.

DNS at the registrar:

| Type | Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | Arif9325.github.io |
