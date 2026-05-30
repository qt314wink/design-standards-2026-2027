# Template: React/Next Motion Component Prompt

Use when asking Kimi CLI to generate a React/Next.js component with motion from the motion-system-master skill.

## Prompt template

> Task: Generate a [COMPONENT_TYPE] React component with motion from the motion-system-master skill.
> Component: [NAME]
> Tag: [TAG — e.g. hero / card-grid / modal / cta]
> Primary motion role: [Informational / Expressive / Focus]
> Brand dialect: [Organic / Structured / Hybrid]
> Required behavior:
> - [enter/exit/hover/active states]
> - [stagger requirements]
> - [scroll or interaction trigger]
> Token references:
> - Duration: [e.g. motion-duration-lg]
> - Easing: [e.g. motion-ease-organic-enter]
> Accessibility: support prefers-reduced-motion, keyboard nav, visible focus
> Performance: prefer transform and opacity only
> Output: TypeScript + Tailwind, inline animation comments, reduced-motion block

## Example

> Generate a HeroSection React component. Tag: hero. Role: Expressive. Dialect: Organic.
> Headline fades and rises on page load, subheadline staggers 120ms after,
> background texture drifts at ambient opacity.
> Tokens: duration-xl 700ms, ease-organic-enter.
> Reduced motion: fade only, no drift. TypeScript + Tailwind.
