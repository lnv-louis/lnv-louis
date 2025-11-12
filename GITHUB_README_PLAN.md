# GitHub Profile README Plan

## Overview
Create a unique, personified GitHub profile README for Le Nguyen Vu that showcases your AI/ML expertise, full-stack development skills, and impressive project portfolio.

## Key Elements to Include

### 1. Header Section
- **Animated greeting** with typing effect or wave animation
- **Tagline**: "AI-focused full-stack engineer shipping high-impact MVPs"
- **Location & Contact**: London, UK | UCL BSc CS 2028
- **Quick links**: LinkedIn, Portfolio, Email (with badges)

### 2. About Me (Personified)
- Write in first person, conversational tone
- Highlight unique story: Vietnam → UK, IB 43/45, UCL
- Emphasize hackathon wins (Lovable 1st place, Cursor 6th)
- Passion for AI/ML + practical shipping mentality

### 3. Trophy & Stats Section
- **GitHub Profile Trophy**: Integration from ryo-ma/github-profile-trophy
- **GitHub Stats Card**: Streak stats, contribution graph
- **Language Stats**: Top languages used

### 4. Tech Stack Badges
**Understanding Badge Generation:**
- Most badges use **shields.io** (not camo.githubusercontent.com directly)
- Format: `https://img.shields.io/badge/<LABEL>-<MESSAGE>-<COLOR>?style=<STYLE>&logo=<LOGO>`
- camo.githubusercontent.com is GitHub's image proxy for external images
- When you embed shields.io badges, GitHub caches them through camo

**Categories:**
- **Languages**: Python, TypeScript, JavaScript, R, C, SQL, HTML
- **Frontend**: React, Tailwind CSS, ReactFlow
- **Backend**: Supabase, Convex, Deno, PostgreSQL, Flask, FastAPI
- **ML/AI**: TensorFlow, Keras, Scikit-learn, Pandas, NumPy, Facenet512
- **Tools**: Git, ANSYS Fluent, Google Apps Script

### 5. Featured Projects
**Format as cards with:**
- Project name + trophy/award badge
- One-liner description
- Key tech stack (badges)
- Link to repository

**Projects to feature:**
1. **Grounded** (🏆 1st Place, Lovable Hackathon)
2. **Dex** (🏆 6th Place, Cursor Hack)
3. **Homiq** (AI Property Search)
4. **ML Research** (Cancer Classification, Sentiment Analysis)

### 6. Current Focus
- What you're learning/building now
- Open to opportunities: internships, collaborations
- UCL AI Society - Nexus Labs Officer

### 7. Fun Facts Section (Personification)
- F1 in Schools World Finals 2024 representative
- Silver Scholar - International Logic Olympiad
- Personal interests/hobbies to make it human

### 8. Connect Section
- LinkedIn badge with follower count
- Email button
- Portfolio link
- "Open to collaborations" CTA

## Technical Implementation Steps

### Step 1: Research & Reference Gathering
- Study 3-5 impressive GitHub profile READMEs
- Document badge URLs for all your tech stack
- Test GitHub profile trophy URL format

### Step 2: Structure Design
- Draft markdown structure with sections
- Plan visual hierarchy (what stands out)
- Ensure mobile-friendly (no complex HTML)

### Step 3: Badge Generation
- Create shields.io badges for all technologies
- Format: `![Badge Name](https://img.shields.io/badge/...)`
- Choose consistent style (flat, for-the-badge, plastic, etc.)
- Use official logo colors where possible

### Step 4: Trophy & Stats Integration
- Trophy URL: `https://github-profile-trophy.vercel.app/?username=lnv-louis`
- Stats card: `https://github-readme-stats.vercel.app/api?username=lnv-louis`
- Streak stats: `https://github-readme-streak-stats.herokuapp.com/?user=lnv-louis`

### Step 5: Content Writing
- Write personified "About Me" section (150-200 words)
- Craft project descriptions (1-2 sentences each)
- Add personality: emojis, tone, humor

### Step 6: Create README.md
- Build the actual README.md file in repository root
- Test all image links and badges
- Ensure proper markdown formatting

### Step 7: Repository Setup
- Create special repository: `lnv-louis/lnv-louis`
- Add README.md to root
- Commit and push to GitHub
- Verify rendering on your profile

### Step 8: Polish & Iterate
- Check rendering on GitHub (light/dark mode)
- Adjust spacing, alignment
- Get feedback and refine

## Design Principles

1. **Visual Balance**: Not too cluttered, not too sparse
2. **Scannable**: Key info should jump out in 5 seconds
3. **Authentic**: Sounds like you, not a corporate bio
4. **Updated**: Easy to maintain as you add projects
5. **Professional yet Personal**: Serious skills + human touch

## Example Badge Formats

```markdown
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
```

## Timeline Estimate
- Research & Planning: 15 minutes
- Badge URL generation: 20 minutes
- Content writing: 30 minutes
- README creation & testing: 20 minutes
- Polish & refinement: 15 minutes
**Total: ~90 minutes**

## Notes
- GitHub profile README lives in a repository named `<username>/<username>`
- For you: `lnv-louis/lnv-louis` repository
- README.md in that repo's root becomes your profile README
- Changes are live immediately after pushing
- All images must be publicly accessible URLs
