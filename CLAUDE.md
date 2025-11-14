# CLAUDE.md - AI Assistant Guide for devolopereph

## Repository Overview

This is a **GitHub Profile README repository** for Efe (devolopereph), a Turkish-speaking aspiring mobile application developer. This repository displays automatically on the GitHub profile page.

### Repository Purpose
- Personal branding and professional introduction
- Showcase skills, experience, and learning journey
- Display technical stack and career aspirations
- Create an engaging first impression for profile visitors

## Repository Structure

```
devolopereph/
├── README.md              # Main profile page (displayed on GitHub profile)
├── ekler/                 # Assets folder ("ekler" = "attachments" in Turkish)
│   └── eph_hakkinda.gif  # Animated terminal GIF showing profile info
└── CLAUDE.md             # This file - AI assistant guidelines
```

## Language & Tone Guidelines

### Primary Language: Turkish
- **All user-facing content MUST be in Turkish**
- Maintain a friendly, professional, and authentic tone
- Use first-person perspective (Ben = I, Benim = My)
- Keep language casual yet respectful

### Common Turkish Terms Used
- **Amacım**: My goal/purpose
- **Daha önce tecrübe etmiş olduklarım**: What I've experienced before
- **Öğrenme aşamasında olduklarım**: What I'm currently learning
- **Öğrenmeye can attıklarım**: What I'm eager to learn
- **ekler**: Attachments/extras

## Content Structure & Conventions

### 1. Header Section
- Uses capsule-render for wave animation header
- Orange/red color scheme (`color=ff451d`)
- Includes animated GIF terminal display from `./ekler/eph_hakkinda.gif`

### 2. Personal Statement
Located under "### Amacım" - describes:
- Life goals and problem-solving focus
- Career aspiration (mobile app development)
- Collaborative project interests

### 3. Skills & Technology Sections

**Three distinct sections using skillicons.dev:**

a) **Experience** (Daha önce tecrübe etmiş olduklarım)
   - Technologies already worked with
   - Currently includes: Python, C#, VS Code, Android Studio, Linux, Bash, GitHub, WordPress, HTML, CSS, Notion, Flutter, Kotlin

b) **Currently Learning** (Öğrenme aşamasında olduklarım)
   - Technologies actively being learned
   - Currently includes: Flutter, Kotlin

c) **Want to Learn** (Öğrenmeye can attıklarım)
   - Technologies on the learning wishlist
   - Currently includes: React, JavaScript, Swift, Android Studio, Unity, Unreal

### 4. Footer
- Matching wave animation using capsule-render
- Same color scheme for consistency

## Development Workflows

### Updating Skills
When adding/removing technologies from skill sections:

1. **Determine the appropriate section**:
   - Move completed learning items from "Want to Learn" → "Currently Learning" → "Experience"
   - Add new interests to "Want to Learn"
   - Keep sections realistic and honest

2. **Use skillicons.dev syntax**:
   ```markdown
   [![Section Name](https://skillicons.dev/icons?i=tech1,tech2,tech3)](https://skillicons.dev)
   ```

3. **Available technology icons**: Visit https://skillicons.dev for complete list
   - Common: py, js, ts, react, flutter, kotlin, swift, java, cpp, cs, etc.
   - Tools: vscode, git, github, docker, linux, bash, notion, figma, etc.

### Adding/Updating Assets

**Asset Location**: `/ekler/` directory

**Current Assets**:
- `eph_hakkinda.gif` - Terminal animation GIF

**Guidelines for new assets**:
- Keep file sizes reasonable (current GIF is ~1.2MB)
- Use descriptive Turkish names
- Reference with relative paths: `./ekler/filename.ext`
- Optimize images/GIFs before committing

### Git Workflow

**Branch Strategy**:
- Development occurs on feature branches prefixed with `claude/`
- Current branch: `claude/claude-md-mhzcw6artd54zf9u-0153zuvzDE7a7MKRsYoJh7KY`

**Commit Guidelines**:
- Use clear, descriptive commit messages
- Recent pattern shows incremental "Update README.md" commits
- Commit each logical change separately
- Push to origin with: `git push -u origin <branch-name>`

**Important**: Branch names must start with 'claude/' and match session ID

## Key Conventions for AI Assistants

### DO's ✓
1. **Maintain Turkish language** in all user-facing content
2. **Preserve the personal voice** - write as if you are Efe
3. **Keep skill progressions realistic** - only move technologies between sections based on actual learning/usage
4. **Maintain visual consistency** - keep the orange/red color scheme (`#ff451d`)
5. **Test external links** - ensure skillicons.dev and capsule-render URLs work
6. **Respect the casual, friendly tone** while remaining professional
7. **Update sections cohesively** - if adding to "Currently Learning", consider what moved from "Want to Learn"

### DON'Ts ✗
1. **Don't translate to English** - this is a Turkish-language profile
2. **Don't add false claims** - only include technologies actually used/learned
3. **Don't change the color scheme** without explicit request
4. **Don't remove HTML comments** - they contain helpful context notes
5. **Don't add overly technical jargon** - keep it accessible
6. **Don't make the README too long** - profile READMEs should be concise and scannable
7. **Don't add emojis unless explicitly requested** - current style is clean and icon-based

## Common Modification Scenarios

### Scenario 1: Adding a New Technology to Experience
```markdown
1. Identify the technology's skillicons.dev code
2. Add to the appropriate section's icon list
3. If moving from another section, remove from that section
4. Commit with message: "Add [Technology] to experience section"
```

### Scenario 2: Updating Personal Statement
```markdown
1. Edit the "### Amacım" section
2. Maintain Turkish language and personal voice
3. Keep it concise (2-3 sentences)
4. Focus on: goals, aspirations, collaborative spirit
5. Commit with descriptive message
```

### Scenario 3: Adding New Visual Assets
```markdown
1. Add file to /ekler/ directory
2. Use descriptive Turkish filename
3. Optimize file size
4. Reference in README.md with ./ekler/filename
5. Commit both the asset and README update together
```

### Scenario 4: Restructuring Sections
```markdown
1. Preserve all existing content
2. Maintain the header → about → skills → footer flow
3. Keep section headers in Turkish
4. Test that all external URLs still render
5. Commit with clear description of restructuring
```

## Technical Details

### External Dependencies
- **skillicons.dev**: Generates skill badge icons
- **capsule-render.vercel.app**: Generates header/footer wave animations

### File Formats
- **README.md**: GitHub Flavored Markdown
- **Assets**: GIF, PNG, JPG supported in /ekler/

### Image References
- Use relative paths: `./ekler/filename.ext`
- Absolute URLs for external services (skillicons, capsule-render)

## Profile Branding Guidelines

### Current Brand Identity
- **Color**: Orange/Red (`#ff451d`)
- **Style**: Modern, clean, visual-focused
- **Personality**: Friendly, ambitious, collaborative
- **Focus**: Mobile development journey

### Visual Consistency
- Wave animations at top and bottom
- Skill badges in rows
- Animated terminal GIF for personality
- Minimal text, maximum visual impact

## Troubleshooting

### Images Not Displaying
1. Check relative path syntax: `./ekler/filename.ext`
2. Verify file exists in repository
3. Ensure file extension is correct
4. Check if external service (skillicons, capsule-render) is accessible

### skillicons.dev Issues
1. Verify technology codes: https://skillicons.dev
2. Check syntax: `?i=tech1,tech2,tech3` (comma-separated, no spaces)
3. Ensure all codes are valid

### Git Push Issues
1. Verify branch name starts with 'claude/'
2. Use `git push -u origin <branch-name>`
3. Retry with exponential backoff if network errors (2s, 4s, 8s, 16s)

## Quick Reference

### Typical Update Workflow
```bash
# 1. Make changes to README.md or assets
# 2. Stage changes
git add README.md
# or
git add ekler/new-asset.gif README.md

# 3. Commit with clear message
git commit -m "Update skills section with new technologies"

# 4. Push to feature branch
git push -u origin claude/[session-id]
```

### Section Template
```markdown
### [Turkish Section Header]
[Content in Turkish, maintaining personal voice]
```

### Skill Badge Template
```markdown
[![Section Description](https://skillicons.dev/icons?i=tech1,tech2,tech3)](https://skillicons.dev)
```

## Repository Context

**Owner's Background**:
- Aspiring mobile application developer
- Interested in problem-solving and impact
- Values collaboration and friendship in projects
- Currently learning: Flutter & Kotlin
- Goal: Contribute to own life and others' lives through technology

**Repository Activity**:
- Frequent README.md updates
- Iterative improvements to profile presentation
- Recent focus on refining skill section presentation

---

**Last Updated**: 2025-11-14
**Repository**: github.com/devolopereph/devolopereph
**Profile Display**: This README.md displays on github.com/devolopereph

**Note for AI Assistants**: Always maintain the authentic voice and aspirations of Efe. This is a personal profile that represents real skills, real learning, and real career goals. Keep it honest, keep it Turkish, and keep it true to the developer's journey.
