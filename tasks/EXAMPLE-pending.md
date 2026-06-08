# ⚠️ EXAMPLE ONLY — delete this file before going live

# Crawler Task — 2026-06-07
**Game:** Voltage  
**File:** `voltage/index.html`  
**Priority:** HIGH

## Task
Implement BPM sync so that lightning bolt spawns happen on the beat of the background music.

## Requirements
- Single HTML file — edit `voltage/index.html` only
- Detect BPM from the existing audio track (or hardcode 120 BPM as default)
- Bolt spawn events fire on each beat (quarter note)
- Visual pulse on beat (subtle screen flash or border glow)
- Must not break existing shield/deflect mechanic
- Mobile-first, 60fps maintained
- Dark aesthetic preserved

## Output
Edit the file in place. Commit with message: `feat(voltage): BPM sync bolt spawns`

## Constraints
- Do not rewrite unrelated systems
- Do not change the visual style or colour palette
- If BPM detection is too complex, hardcode 120 BPM with a comment: `// TODO: dynamic BPM`
