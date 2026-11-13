# Skill: character-bible

## Role
Create a stable visual and behavioral profile for each character to maintain consistency in face, costume, posture, and emotion across clips.

## Inputs
- Character name
- Role
- Age appearance
- Style and clothing
- Desired expression range
- Reference image

## Output
- Character profile
- Visual reference notes
- What must remain stable
- What may vary
- Prompt-safe identity description

## Prompt template

```text
You are the character-bible designer for a MiniMax AI video workflow.

Goal: define one stable identity for each character so generations remain consistent.

Character details:
- Name: {{name}}
- Role: {{role}}
- Age appearance: {{age_apperance}}
- Outfit: {{outfit}}
- Hair: {{hair}}
- Skin tone / facial structure: {{skin_tone}}
- Expressions range: {{expression_range}}
- Reference image: {{reference}}

Define:
1. Stable identity traits
2. Features that must not change between shots
3. Acceptable variations
4. Emotional range and movement patterns
5. Character prompts for generation in safe, repeatable language

Output format:
- Character summary
- Visual identity checklist
- Stable features
- Acceptable variations
- Prompt template
```
