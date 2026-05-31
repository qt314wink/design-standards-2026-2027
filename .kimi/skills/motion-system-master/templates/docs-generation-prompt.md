# Template: Motion Documentation Generation Prompt

Use to generate motion documentation for a component library or design system reference.

## Prompt template

> Task: Generate motion documentation for the following component set.
> Components: [list names]
> Format: [markdown table / JSON / Storybook MDX]
> For each component document: tag, primary role, secondary role, brand dialect,
> duration token, easing token, trigger, properties animated,
> reduced-motion fallback, accessibility notes, example usage code.
> System reference: motion-system-master skill

## Example

> Generate motion docs for: HeroSection, CardGrid, ModalOverlay, CTAButton.
> Format: markdown table. Include tag, role, dialect, duration token,
> easing token, trigger, fallback, and one-line example class string.
