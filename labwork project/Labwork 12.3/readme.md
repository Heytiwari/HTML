# CSS Flexbox Child Properties

This project demonstrates the **CSS Flexbox Child Properties** with practical examples. Each section explains how different child properties affect the layout and behavior of flex items inside a flex container.

---

## 📚 Topics Covered

- Flex Basis
- Flex Grow
- Flex Shrink
- Order
- Align Self
  - flex-start
  - center
  - stretch
  - baseline

---

## 📌 Flex Basis

The `flex-basis` property defines the **initial size** of a flex item before any available space is distributed.

### Examples

- `flex-basis: auto;`
- `flex-basis: 20px;`
- `flex-basis: 30%;`

### Description

- **auto** → Uses the item's default width or content size.
- **20px** → Sets the initial width to **20 pixels**.
- **30%** → Sets the initial width to **30%** of the flex container.

---

## 📌 Flex Grow

The `flex-grow` property determines **how much a flex item can grow** when extra space is available inside the container.

### Examples

- `flex-grow: 0;`
- `flex-grow: 1;`
- `flex-grow: 2;`

### Description

- **0** → Item will not grow.
- **1** → Item takes one share of the available free space.
- **2** → Item takes twice as much free space compared to an item with `flex-grow: 1`.

---

## 📌 Flex Shrink

The `flex-shrink` property determines **how much a flex item will shrink** when the container does not have enough space.

### Examples

- `flex-shrink: 0;`
- `flex-shrink: 1;`
- `flex-shrink: 2;`

### Description

- **0** → Item will not shrink.
- **1** → Default shrinking behavior.
- **2** → Shrinks twice as much as an item with `flex-shrink: 1`.

---

## 📌 Order

The `order` property changes the visual order of flex items without changing the HTML structure.

### Examples

- `order: 0;`
- `order: 1;`
- `order: 2;`

### Description

- Items with lower order values appear first.
- Default value is **0**.
- Items with the same order value follow the HTML source order.

---

## 📌 Align Self

The `align-self` property overrides the `align-items` property for an individual flex item.

---

### 🔹 align-self: flex-start;

Aligns the selected flex item at the **start of the cross axis**.

```css
align-self: flex-start;
```

---

### 🔹 align-self: center;

Centers the selected flex item on the **cross axis**.

```css
align-self: center;
```

---

### 🔹 align-self: stretch;

Stretches the selected flex item to fill the available space on the **cross axis** (when height or width is not fixed).

```css
align-self: stretch;
```

---

### 🔹 align-self: baseline;

Aligns flex items according to the **baseline of their text**.

```css
align-self: baseline;
```

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- Flexbox

---

## 📂 Project Structure

```
Project
│── index.html
│── css/
│   └── style.css
└── README.md
```

---

## 🎯 Learning Objectives

After completing this project, you will understand:

- How `flex-basis` controls the initial size of flex items.
- How `flex-grow` distributes available space.
- How `flex-shrink` behaves when space is limited.
- How `order` changes the display order of flex items.
- How `align-self` overrides alignment for individual items.

---

## 📖 References

- MDN Web Docs – Flexbox
- CSS Flexible Box Layout Module (W3C)

---

## 👨‍💻 Author

**Rajan Kumar Tiwari**

Frontend Developer | Aspiring Full Stack Developer

GitHub: https://github.com/Heytiwari