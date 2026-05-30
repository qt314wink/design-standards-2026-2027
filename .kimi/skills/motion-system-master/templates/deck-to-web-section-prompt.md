# Template: Deck-to-Website Section Mapping Prompt

Use to translate a slide deck section into a web-native React/Next editorial module.

## Prompt template

> Task: Translate the following slide into a web-native React/Next section.
> Slide content: [paste title, body, visual description, intent]
> Slide tag: [hero / thesis / comparison / gallery / manifesto / etc]
> Source deck dialect: [Organic — Beautiful Imperfection / Structured — The Death of Perfect]
> Web section requirements:
> - Preserve original thesis and narrative intent
> - Translate visual hierarchy into HTML/CSS/motion equivalents
> - Do not replicate slide layout literally
> - Expand for web-native reading, scrolling, and interaction
> Motion: tag-appropriate role and easing, density rules, reduced-motion fallback,
> keep expressive motion away from dense reading areas
> Output: TypeScript + Tailwind component, motion token references, reduced-motion fallback

## Example

> Translate manifesto slide: Title: The Death of Perfect
> Body: We built systems that prioritized optimization over connection...
> Tag: manifesto. Dialect: Organic.
> Motion: slow fade-rise, no elements near text.
> Output: TypeScript + Tailwind, xl 700ms organic-enter, reduced motion fade only.
