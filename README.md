# அழிவிலி-CSS Framework

A comprehensive, production-ready utility-first CSS framework with Tamil class names, built with modern SCSS architecture.

## Features (அம்சங்கள்)

- **Tamil Language Classes**: All utility classes use Tamil names for better localization
- **Production Ready**: Optimized SCSS architecture with proper organization
- **Responsive Design**: Mobile-first responsive utilities with Tamil breakpoint names
- **Modern CSS**: Uses latest CSS features including CSS Grid, Flexbox, and custom properties
- **Comprehensive**: Complete set of utilities for spacing, typography, colors, layout, and more
- **Flexible**: Easy to customize and extend with SCSS variables and mixins
- **Performance**: Optimized output with compressed and expanded versions

## Installation (நிறுவல்)

### NPM
```bash
npm install azhivili-css
```

### CDN
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/azhivili-css/dist/azhivili-css.min.css">
```

### Download
Download the latest release from [GitHub Releases](https://github.com/Aruvili/azhivili-css/releases)

## Usage (பயன்பாடு)

### Basic HTML Structure
```html
<!DOCTYPE html>
<html lang="ta">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>அழிவிலி-CSS Framework</title>
    <link rel="stylesheet" href="path/to/azhivili-css.css">
</head>
<body>
    <div class="ப-4 ம-2 நி-சிவப்பு-500 பி-நீலம்-100">
        <h1 class="எஅ-2மிபெ எஎ-தடிமன் உசீ-மையம்">வணக்கம்!</h1>
        <p class="எஅ-பெ வஉ-தளர்வு">அழிவிலி-CSS கட்டமைப்பு</p>
    </div>
</body>
</html>
```

### Class Name Structure (வகுப்பு பெயர் அமைப்பு)

#### Spacing (இடைவெளி)
- `ப-{size}` - Padding (பேடிங்)
- `ம-{size}` - Margin (மார்ஜின்)
- `பகி-{size}` - Padding X-axis (கிடைமட்ட பேடிங்)
- `பசெ-{size}` - Padding Y-axis (செங்குத்து பேடிங்)

#### Sizing (அளவு)
- `அ-{size}` - Width (அகலம்)
- `உ-{size}` - Height (உயரம்)

#### Typography (எழுத்துரு)
- `எஅ-{size}` - Font Size (எழுத்துரு அளவு)
- `எஎ-{weight}` - Font Weight (எழுத்துரு எடை)
- `உசீ-{align}` - Text Align (உரை சீரமைப்பு)

#### Colors (நிறங்கள்)
- `நி-{color}-{shade}` - Text Color (உரை நிறம்)
- `பி-{color}-{shade}` - Background Color (பின்னணி நிறம்)
- `எல்-{color}-{shade}` - Border Color (எல்லை நிறம்)

#### Layout (அமைப்பு)
- `கா-{display}` - Display (காட்சி)
- `நி-{position}` - Position (நிலை)

#### Flexbox (நெகிழ்வு)
- `கா-நெகிழ்` - Display Flex
- `நெதி-{direction}` - Flex Direction
- `நியஉ-{justify}` - Justify Content
- `உசீ-{align}` - Align Items

#### Grid (கட்டம்)
- `கா-கட்டம்` - Display Grid
- `கவநெ-{cols}` - Grid Template Columns
- `கநெவி-{span}` - Grid Column Span

### Responsive Design (பதிலளிக்கும் வடிவமைப்பு)

Use breakpoint prefixes for responsive design:

- `சி:` - Small screens (640px+)
- `ந:` - Medium screens (768px+)
- `பெ:` - Large screens (1024px+)
- `மி:` - Extra large screens (1280px+)

```html
<div class="ப-4 சி:ப-6 ந:ப-8 பெ:ப-12">
    Responsive padding
</div>
```

### State Modifiers (நிலை மாற்றிகள்)

- `மேல்:` - Hover state
- `கவ:` - Focus state
- `செ:` - Active state

```html
<button class="பி-நீலம்-500 மேல்:பி-நீலம்-600 கவ:எ-2">
    Button with hover and focus states
</button>
```

## Color System (நிற அமைப்பு)

### Available Colors (கிடைக்கும் நிறங்கள்)

- `சிவப்பு` (Red) - 50 to 900 shades
- `ஆரஞ்சு` (Orange) - 50 to 900 shades
- `மஞ்சள்` (Yellow) - 50 to 900 shades
- `பச்சை` (Green) - 50 to 900 shades
- `நீலம்` (Blue) - 50 to 900 shades
- `ஊதா` (Purple) - 50 to 900 shades
- `இளஞ்சிவப்பு` (Pink) - 50 to 900 shades
- `சாம்பல்` (Gray) - 50 to 900 shades
- `மயில்பச்சை` (Teal) - 50 to 900 shades
- `நீர்நிறம்` (Cyan) - 50 to 900 shades
- `மரகதம்` (Emerald) - 50 to 900 shades
- `எலுமிச்சைப்பச்சை` (Lime) - 50 to 900 shades
- `வானநீலம்` (Sky) - 50 to 900 shades
- `இண்டிகோ` (Indigo) - 50 to 900 shades
- `ரோஜா` (Rose) - 50 to 900 shades
- `கற்குமிழ்மஞ்சள்` (Amber) - 50 to 900 shades
- `நடுநிறம்` (Neutral) - 50 to 900 shades
- `கல்நிறம்` (Stone) - 50 to 900 shades
- `கருப்பு` (Black) - No shade
- `வெள்ளை` (White) - No shade
- `வெளிப்படையான` (transparent) - No need for shade

### Usage Examples
```html
<div class="நி-சிவப்பு-500">Red text</div>
<div class="பி-பச்சை-100">Light green background</div>
<div class="எல்-நீலம்-600">Blue border</div>
```

## Customization (தனிப்பயனாக்கம்)

### Using SCSS Variables

```scss
// Override default variables
$colors: (
  // Add your custom colors
  என்நிறம்: (
    500: #your-color
  )
);

// Import the framework
@import 'azhivili-css/scss/main';
```

### Creating Custom Utilities

```scss
// Add custom utilities
.என்வகுப்பு {
  // Your custom styles
}

// Use framework mixins
@include generate-utilities(margin-top, என்மே, $spacing-values);
```

## Browser Support (உலாவி ஆதரவு)

- Chrome 88+
- Firefox 85+
- Safari 14+
- Edge 88+

## Contributing (பங்களிப்பு)

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License (உரிமம்)

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments (நன்றி)

- Inspired by Tailwind CSS
- Tamil language support for better localization
- Community feedback and contributions

## Documentation (ஆவணங்கள்)

For detailed documentation, visit: [Documentation](https://github.com/Aruvili/azhivili-css)

## Support (ஆதரவு)

- GitHub Issues: [Report bugs or request features](https://github.com/Aruvili/azhivili-css/issues)
- Discussions: [Community discussions](https://github.com/Aruvili/azhivili-css/discussions)
- Discord [Discord discussion](https://discord.gg/CcsRe8gWRV)
