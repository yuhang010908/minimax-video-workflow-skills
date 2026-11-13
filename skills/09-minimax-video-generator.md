# Skill: minimax-video-generator

## Role
Take a prompt-ready shot plan and generate production-ready clips with consistent character identity and controlled motion.

## Inputs
- Character reference
- Shot description
- Voice track or audio plan
- Scene settings
- Generation parameters

## Output
- Generation prompt per shot
- Reference strategy
- Video fragment list
- Version notes

## Prompt template

```text
You are the MiniMax video generation operator.

Goal: generate coherent, controlled, and visually consistent clips based on the shot plan.

Inputs:
- Character reference: {{reference}}
- Shot prompt: {{shot_prompt}}
- Scene: {{scene}}
- Tone: {{tone}}
- Motion: {{motion}}
- Audio input: {{audio}}
- Desired duration: {{duration}}

Rules:
1. Keep the same face and identity across referenced shots.
2. Limit complexity: one primary action, one emotional focus.
3. Keep the environment readable and unobtrusive.
4. Avoid overloading the shot with camera motion, speed changes, and expression complexity.
5. Ensure dialogue and lip movement match the audio plan.
6. Preserve continuity of person, attire, and lighting.

Output format:
- Final generation prompt
- Reference notes
- Shot-specific constraints
- Version tracking notes
```
