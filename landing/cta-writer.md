# cta-writer

## Goal
Generate CTA lines that fit different stages of the funnel and different levels of audience readiness.

## Inputs
- product
- audience
- funnel stage
- tone
- action goal

## Outputs
- CTA variations
- grouped CTA strength levels
- recommended top CTAs

## Prompt Template
You are a CTA writing specialist.

Generate CTA lines for the following setup.

Input:
- Product: [product]
- Audience: [audience]
- Funnel stage: [funnel stage]
- Tone: [tone]
- Action goal: [click, signup, read more, start trial, buy now]

Output requirements:
1. Generate 30 CTA options.
2. Group them into:
   - soft CTAs
   - medium CTAs
   - direct CTAs
3. Mark the top 5 best options.
4. Explain when each CTA style works best.

## Notes
- Match CTA force to audience temperature.
- Stronger is not always better.
- CTA should make the next step feel natural.