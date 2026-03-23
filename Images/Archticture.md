# 📘 CSS File Structure Explanation

This document explains the purpose of each CSS file in your fitness website project, what it controls, and why it is separated this way.

---

# 1. base.css

## 🔹 Purpose

This file contains the **global foundation styles** for the entire website.

## 🔹 Responsible For

* Resetting default browser styles
* Setting global fonts and colors
* Basic element styling (body, links, images)

## 🔹 Why It Exists

Every browser applies its own default styles. This file ensures:

* Consistency across all pages
* Clean starting point

## 🔹 Example Responsibilities

* Remove margins and padding
* Define main font family
* Set default text color

---

# 2. layout.css

## 🔹 Purpose

Controls the **structure and spacing** of the page.

## 🔹 Responsible For

* Page width (container)
* Section spacing
* Grid layouts (columns)
* General alignment

## 🔹 Why It Exists

Separates structure from design so you can:

* Change layout without affecting styling
* Reuse layout across all pages

## 🔹 Example Responsibilities

* Centering content
* Creating 2-column layouts
* Adding spacing between sections

---

# 3. navbar.css

## 🔹 Purpose

Handles everything related to the **header and navigation bar**.

## 🔹 Responsible For

* Logo styling
* Navigation links
* Hover effects
* Sticky header behavior

## 🔹 Why It Exists

The navbar is used on every page, so it needs:

* Isolation for easy updates
* Consistent behavior everywhere

## 🔹 Example Responsibilities

* Making navbar fixed (sticky)
* Adding hover underline animation
* Styling active page link

---

# 4. hero.css

## 🔹 Purpose

Styles the **hero section** (top section of the homepage).

## 🔹 Responsible For

* Main headline styling
* Background color or image
* Intro text layout

## 🔹 Why It Exists

The hero is a special section that:

* Has unique styling
* Should not mix with other sections

## 🔹 Example Responsibilities

* Large title (H1)
* Centered text
* Highlighted words (span color)

---

# 5. components.css

## 🔹 Purpose

Contains **reusable UI components** used across the site.

## 🔹 Responsible For

* Buttons
* Cards
* Forms
* Badges
* Login box

## 🔹 Why It Exists

Components are reused many times, so this file allows:

* Reusability
* Consistency
* Faster development

## 🔹 Example Responsibilities

* Button styles (primary / outline)
* Card layout for plans
* Input fields styling

---

# 6. pages.css

## 🔹 Purpose

Handles **page-specific elements**.

## 🔹 Responsible For

* Blog layout
* Tables (workout plans)
* Stats sections

## 🔹 Why It Exists

Some styles are only used in specific pages, so we isolate them to:

* Avoid clutter
* Keep components clean

## 🔹 Example Responsibilities

* Blog post design
* Workout tables
* Statistics grid

---

# 7. footer.css

## 🔹 Purpose

Styles the **footer section** of the website.

## 🔹 Responsible For

* Footer layout
* Footer links
* Bottom copyright section

## 🔹 Why It Exists

Footer appears on all pages and should be:

* Consistent
* Easy to update

## 🔹 Example Responsibilities

* Grid layout for footer columns
* Link styling
* Bottom text alignment

---

# 🧠 Big Picture (Very Important)

## Why split CSS like this?

Instead of one large file, you now have:

* Organized structure
* Easier debugging
* Scalable project
* Cleaner codebase

---

# 🏗️ How Everything Works Together

* base.css → foundation
* layout.css → structure
* navbar.css → top navigation
* hero.css → homepage highlight
* components.css → reusable UI
* pages.css → special sections
* footer.css → bottom section

👉 Together, they form a complete styling system.

---

# 🚀 Final Insight

You just moved from:
👉 Beginner (single CSS file)

To:
👉 Intermediate (modular CSS architecture)

This is how real-world frontend projects are built.

---

If you want next step:
👉 We can refactor this into a **design system (colors, spacing, typography scale)** like professionals use.
