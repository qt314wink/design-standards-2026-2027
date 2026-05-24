# 📐 Design Standards 2026–2027

> A living cross-system design reference defining visual language, tokens, and principles across all creative projects by Jennipher Troup.

![Version](https://img.shields.io/badge/version-2026.1-blueviolet?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)

---

## 🎯 Purpose

This document unifies design decision-making across a family of related design systems and creative tools. It defines the shared foundation — typography, color philosophy, spacing, motion principles, and accessibility standards — that all sub-systems inherit from.

Think of it as the constitution. Individual design systems (Chromaflora, Woodmorphism, Neumorphism) are the implementations.

---

## 🎨 Design Philosophy

| Principle | Description |
|---|---|
| **Tactile First** | Interfaces should feel touchable, material, and physically grounded |
| **Joy-Centered** | Every surface should invite delight, not just utility |
| **Regenerative** | Systems should be buildable, remixable, and extensible by others |
| **Culturally Responsive** | Visual language should resonate with real communities and lived experience |
| **Accessible by Default** | WCAG AA compliance is the baseline, not the goal |

---

## 📝 Typography System

- **Display**: Expressive, character-rich serif or variable font
- **Body**: Humanist sans-serif, optimized for readability
- **Mono**: Used for code, data, and technical labels
- **Scale**: `12 / 14 / 16 / 20 / 24 / 32 / 48 / 64px`
- **Line Height**: 1.5 body, 1.2 display

---

## 🖌️ Color Philosophy

Color in this system is organized into three tiers:

1. **Material Palettes** — Earth tones, flora hues, mineral pigments (per design system)
2. **Semantic Tokens** — `--color-success`, `--color-warning`, `--color-danger`, etc.
3. **Interactive States** — hover, focus, active, disabled — defined as percentage shifts from base

---

## 📏 Spacing & Layout

- **Base Unit**: `8px`
- **Scale**: `4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96px`
- **Grid**: 12-column fluid with `24px` gutters
- **Breakpoints**: `sm: 640px`, `md: 768px`, `lg: 1024px`, `xl: 1280px`

---

## 🎥 Motion Principles

- **Duration**: Fast interactions `150ms`, Standard `250ms`, Complex entrances `400ms`
- **Easing**: Prefer `ease-out` for entrances, `ease-in` for exits, `spring` for physics-based
- **Reduce Motion**: All animations respect `prefers-reduced-motion`

---

## 🔗 Design System Family

| System | Focus | Status |
|---|---|---|
| [Chromaflora](https://github.com/qt314wink/chromaflora-sitezip) | Color, flora, vibrant UI | Active |
| [Woodmorphism](https://github.com/qt314wink/woodmorphism) | Organic, tactile, earthy | In Development |
| [Neumorphism Soft UI](https://github.com/qt314wink/neumorphism-soft-ui-design-system) | Jewelmorphism, physics animations | Template Ready |

---

## 📄 License

MIT © [Jennipher Troup](https://github.com/qt314wink)
