build-lists: true

# Styles to add to elements

---

## Flexbox

---

## Header

## `.site-header`

Add:

- `display: flex;`

- `justify-content: space-between;`

---

## Header

## `.siteHeader-section`

Add:

- `display: flex;`

- `align-items: center;`

---

## Navigation menu

## `nav ul`

Add:

- `display: flex;`

---

## Gallery item

## `.gallery`

Add:

- `display: flex;`

- `flex-wrap: wrap;`

---

## Gallery item

## `.gallery-item`

Add:

- `display: flex;`

- `flex-direction: column;`

- `flex-wrap: wrap;`

---

## Gallery item

## `.gallery-item`

Add:

- `flex: 0 0 calc(33.33334% - 2rem);`

- `flex: 1 0 calc(33.33334% - 2rem);`

---

## Gallery text

## `.gallery-text`

Add:

- `display: flex;`

- `flex: 1;`

- `flex-direction: column;`

- `justify-content: space-between;`

---

## Gallery paragraph

## `.gallery-item p`

Add:

- `flex-grow: 1;`

---

## Footer

## `footer`

Add:

- `display: flex;`

- `justify-content: space-between;`

- `align-items: center;`

---

## Grid

---

## First steps

- save `layout-one.html` as `layout-two.html`

- save `css/style.css` as `css/style-two.css`

- link `css/style-two.css` to `layout-two.html`

---

## Main

## `main`

Add:

- `display: grid;`
- `grid-gap: 1rem;`
- `grid-template-columns: 4fr 1fr;`
- `grid-auto-rows: minmax(50px, auto);`

---

## Header

## `.site-header`

Add:

- `grid-column: 1 / -1;`

---

## Header

## `.site-header`

Add:

- `grid-column: 1 / -1;`

---

## Gallery

## `.gallery`

Add:

- `display: grid;`
- `grid-template-columns: repeat(3, 1fr);`
- `grid-column: 1;`
- `grid-row: 2 / 7;`

---

## Gallery item

## `.gallery-item`

Comment out all the `flexbox` properties

---

## Sidebars

## `aside`

Add:

- `grid-column: 2;`
- `grid-row: 2;`

---

## Sidebar two

## `.sidebar-two`

Add:

- `grid-row: 4;`

---

## Footer

## `footer`

Add:

- `grid-column: 1 / -1`

---

## Extras

---

## Gallery item

## `.gallery-item:first-child`

Add:

- `grid-column: 1/4;`


---

## Gallery item

## `.gallery-item:nth-of-type(2)`

Add:

- `rid-column: 1/3;`

