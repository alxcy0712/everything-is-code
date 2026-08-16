# Prototype Instructions

Run the local server yourself and open the preview in the browser available to this environment. Do not give the user server-start instructions when you can run it.

Before making substantial visual changes, use the Product Design plugin's `get-context` skill when the visual source is unclear or no longer matches the current goal. When the user gives durable prototype-specific design feedback, preferences, or decisions, record them in `AGENTS.md`.

When implementing from a selected generated mock, treat that image as the source of truth for layout, component anatomy, density, spacing, color, typography, visible content, and hierarchy.

## Project Design Decisions

- The core statement is “万物皆为代码 / Everything is code.” Code is a philosophical metaphor for rules, state, inputs, feedback, causality, and evolution.
- The site is a personal thought publication covering technology, human nature, society, value investing, and the self. Career history remains brief context.
- The publication uses a four-slide vertical presentation model: cover, thought index, essays, and about/contact. The header stays fixed; wheel, swipe, and keyboard input advance one viewport page per transition through a discrete PPT-style animation. Continuous wheel or trackpad input keeps advancing sequentially as each transition finishes, without requiring pointer movement or an idle pause. A Mac trackpad wheel transaction retains its original slide as an event target until the gesture goes idle, so a stationary pointer never loses the scroll path when that slide moves offscreen.
- The cover is a typography-led editorial composition. The title, bilingual statement, explanatory copy, primary CTA, and social links form the complete hero content.
- The project contains no 3D scene, machine component, Three.js dependency, or reserved machine column.
- Visual constraints: premium editorial whitespace, restrained brass/glass/aluminum materials, no portraits, no neon AI palette, and no resume-style information density.
