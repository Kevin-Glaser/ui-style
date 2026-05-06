# UI Styling Toolkit

A comprehensive skill for creating beautiful, accessible user interfaces with shadcn/ui components, Tailwind CSS styling, and canvas-based visual designs.

## Features

- **Component Library**: Pre-built accessible components via shadcn/ui (Radix UI + Tailwind)
- **Utility Styling**: Tailwind CSS utility-first approach for rapid UI development
- **Visual Design**: Canvas-based design system for sophisticated visual compositions
- **Automation Scripts**: Python tools for component installation and configuration generation
- **Rich Font Collection**: 25+ premium fonts for canvas-based designs

## Quick Start

### Install shadcn/ui Components

```bash
# Initialize shadcn/ui in your project
npx shadcn@latest init

# Add components using the automation script
python scripts/shadcn_add.py button card dialog
```

### Generate Tailwind Configuration

```bash
# Generate TypeScript config with custom theme
python scripts/tailwind_config_gen.py --framework nextjs --colors brand:#3b82f6 --fonts display:Inter
```

## Project Structure

```
ui-style/
├── canvas-fonts/          # Premium fonts for visual design
├── references/            # Documentation and guides
│   ├── shadcn-components.md
│   ├── shadcn-theming.md
│   ├── shadcn-accessibility.md
│   ├── tailwind-utilities.md
│   ├── tailwind-responsive.md
│   ├── tailwind-customization.md
│   └── canvas-design-system.md
├── scripts/               # Automation tools
│   ├── shadcn_add.py      # Component installer
│   └── tailwind_config_gen.py  # Config generator
├── SKILL.md              # Skill definition and usage guide
└── LICENSE.txt           # MIT License
```

## Documentation

- **Component Library**: See `references/shadcn-components.md` for complete component catalog
- **Theming**: See `references/shadcn-theming.md` for dark mode and customization
- **Accessibility**: See `references/shadcn-accessibility.md` for ARIA patterns
- **Tailwind Utilities**: See `references/tailwind-utilities.md` for core utility classes
- **Visual Design**: See `references/canvas-design-system.md` for design philosophy

## Resources

- [shadcn/ui Documentation](https://ui.shadcn.com)
- [Tailwind CSS Documentation](https://tailwindcss.com)
- [Radix UI Primitives](https://radix-ui.com)

## License

MIT License - See [LICENSE.txt](LICENSE.txt) for details.
