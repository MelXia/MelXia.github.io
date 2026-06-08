# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is Mel's personal homepage (个人主页), featuring a collection of interactive HTML pages including articles, stories, photo galleries, and educational psychology demos. All files are self-contained single-file HTML applications with embedded CSS and JavaScript. No build system or package manager is used.

## Main Files

- `index.html` - Main homepage with personal introduction, navigation to all sections
- `article-1.html` to `article-5.html` - Article pages
- `story-1.html` to `story-4.html` - Story pages
- `photo-gallery.html` - Photo gallery page
- `flower-gallery.html` - Flower-themed gallery
- `AI性格透视.html` - AI personality insight interactive page
- `中断的记忆.html` - Memory interruption interactive story
- `找茬挑战.html` - Spot the difference game
- `颜色快判.html` - Color judgment game (Stroop effect demo)
- `阿希从众实验.html` - Asch conformity experiment simulation
- `师恩难忘挂画生成器.html` - Photo collage generator for A3 posters
- `生日引力场.html` - Birthday gravity field visualization
- `照片素材/` - Photo assets directory

## Technical Notes

- All HTML files are self-contained with inline styles and scripts
- Uses CSS custom properties (variables) for theming with dark purple color scheme
- No external dependencies or build process required
- Files can be opened directly in a browser
- When modifying HTML files, maintain the self-contained structure
- Keep consistent styling with the existing design system (--primary, --accent, --bg, --card, --text CSS variables)
