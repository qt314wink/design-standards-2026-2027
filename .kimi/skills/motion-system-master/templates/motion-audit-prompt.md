# Template: Motion Audit Prompt

Use to audit an existing component or page section for motion compliance.

## Prompt template

> Task: Audit the following [component/section/file] for motion compliance.
> Subject: [paste component or describe UI]
> Audit criteria:
> 1. Is motion role correctly assigned? (Informational / Expressive / Focus)
> 2. Is the tag correct?
> 3. Is the brand dialect appropriate?
> 4. Are semantic tokens used or are values hardcoded?
> 5. Is prefers-reduced-motion handled?
> 6. Are performance-safe properties used (transform / opacity)?
> 7. Is motion density appropriate for content type?
> 8. Is text readable during and after animation?
> 9. Are interactive states keyboard-accessible?
> 10. Is there a reduced-motion fallback that preserves function?
> Output: summary, per-criterion pass/fail/partial, token replacements, code changes, accessibility risk flags

## Example

> Audit the following NavBar component for motion compliance.
> [paste code]
> Flag hardcoded durations, missing reduced-motion support, or overly expressive behavior on structural nav.
