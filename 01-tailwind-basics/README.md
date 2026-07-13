# Tailwind CSS Basics

A small React project demonstrating some of the core concepts of Tailwind CSS.

## Concepts Covered

- Utility-first styling
- Responsive design using breakpoints (`sm`, `md`)
- Flexbox
- CSS Grid
- Responsive navigation
- Conditional rendering in React
- Dark mode using a custom variant
- Custom theme colors
- Hover states
- Transitions and animations
- Spacing, typography, and rounded corners

## Features

- Responsive navbar with desktop and mobile layouts
- Collapsible mobile navigation menu
- Light and dark theme toggle
- Responsive feature grid
- Hover effects with color and scale transitions
- Custom colors defined using Tailwind's `@theme`

## Tech Stack

- React
- Vite
- Tailwind CSS v4

## Running Locally

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

## Tailwind Utility Classes Used

| Utility | Simple Description | Related Variations |
|---|---|---|
| `p-4`, `p-6` | Adds space inside the element on all sides. | `px-4` left & right, `py-4` top & bottom, `pt-4` top, `pb-4` bottom, `pl-4` left, `pr-4` right |
| `gap-2`, `gap-6` | Adds space between items inside a flex or grid layout. | `gap-x-4` horizontal gap, `gap-y-4` vertical gap |
| `flex` | Places items in a flexible row by default. | `inline-flex` creates an inline flex layout |
| `flex-col` | Places items vertically, one below another. | `flex-row` places them horizontally |
| `items-center` | Aligns items in the center. | `items-start`, `items-end`, `items-stretch` |
| `justify-between` | Pushes items apart with space between them. | `justify-start`, `justify-center`, `justify-end`, `justify-around` |
| `grid` | Arranges items in a grid layout. | Used with `grid-cols-*` |
| `grid-cols-2`, `grid-cols-3` | Creates a grid with 2 or 3 columns. | `grid-cols-1` through `grid-cols-12` |
| `hidden` | Hides the element. | Can be combined with `sm:flex`, `sm:block`, etc. |
| `sm:flex` | Makes the element a flex layout on small screens (`640px`) and bigger. | `md:flex`, `lg:flex`, `xl:flex` |
| `sm:hidden` | Hides the element on small screens (`640px`) and bigger. | `md:hidden`, `lg:hidden`, `xl:hidden` |
| `sm:grid-cols-2` | Shows 2 grid columns on screens `640px` and bigger. | `md:grid-cols-*`, `lg:grid-cols-*` |
| `md:grid-cols-3` | Shows 3 grid columns on screens `768px` and bigger. | `lg:grid-cols-*`, `xl:grid-cols-*` |
| `text-sm`, `text-xl`, `text-2xl` | Changes the text size. | `text-xs`, `text-base`, `text-lg`, `text-3xl`, etc. |
| `text-center` | Centers the text. | `text-left`, `text-right`, `text-justify` |
| `font-bold`, `font-semibold` | Makes the text bold or semi-bold. | `font-normal`, `font-medium`, `font-extrabold` |
| `text-white`, `text-slate-900` | Changes the text color. | `text-red-500`, `text-blue-500`, etc. |
| `bg-slate-500` | Changes the background color. | `bg-red-500`, `bg-blue-500`, etc. |
| `bg-background` | Uses the custom `background` color. | Defined using `--color-background` |
| `text-primary` | Uses the custom `primary` text color. | Defined using `--color-primary` |
| `min-h-screen` | Makes the element at least as tall as the whole screen. | `h-screen`, `h-full`, `min-h-full` |
| `rounded` | Rounds the corners of an element. | `rounded-md`, `rounded-lg`, `rounded-xl`, `rounded-full` |
| `cursor-pointer` | Shows the hand/pointer cursor when hovering. | `cursor-default`, `cursor-not-allowed`, `cursor-wait` |
| `hover:bg-slate-600` | Changes the background color when hovered. | `hover:text-*`, `hover:bg-*` |
| `hover:scale-105` | Makes the element slightly bigger when hovered. | `scale-100`, `scale-110`, etc. |
| `transition-all` | Makes style changes happen smoothly. | `transition-colors`, `transition-transform` |
| `duration-500` | Makes the transition take `500ms`. | `duration-200`, `duration-300`, `duration-700`, etc. |
| `dark:bg-background` | Uses the custom background color when dark mode is active. | `dark:bg-*` |
| `dark:text-primary` | Uses the custom primary text color when dark mode is active. | `dark:text-white`, `dark:text-slate-300`, etc. |

---

[Tailwind Colors](https://tailscan.com/colors)