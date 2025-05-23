# Color Design Tokens

This document contains the color design tokens extracted from the Figma design system.

## Primary Colors

| Color | Name | HEX | RGB |
|-------|------|-----|-----|
| ![#1A1A1A](https://via.placeholder.com/50/1A1A1A/1A1A1A.png) | Primary Black | `#1A1A1A` | `26, 26, 26` |
| ![#333333](https://via.placeholder.com/50/333333/333333.png) | Primary Dark Gray | `#333333` | `51, 51, 51` |
| ![#666666](https://via.placeholder.com/50/666666/666666.png) | Primary Gray | `#666666` | `102, 102, 102` |
| ![#999999](https://via.placeholder.com/50/999999/999999.png) | Primary Light Gray | `#999999` | `153, 153, 153` |
| ![#CCCCCC](https://via.placeholder.com/50/CCCCCC/CCCCCC.png) | Primary Lighter Gray | `#CCCCCC` | `204, 204, 204` |
| ![#F2F2F2](https://via.placeholder.com/50/F2F2F2/F2F2F2.png) | Primary Lightest Gray | `#F2F2F2` | `242, 242, 242` |
| ![#FFFFFF](https://via.placeholder.com/50/FFFFFF/FFFFFF.png) | White | `#FFFFFF` | `255, 255, 255` |

## Accent Colors

| Color | Name | HEX | RGB |
|-------|------|-----|-----|
| ![#FF3B30](https://via.placeholder.com/50/FF3B30/FF3B30.png) | Red | `#FF3B30` | `255, 59, 48` |
| ![#FF9500](https://via.placeholder.com/50/FF9500/FF9500.png) | Orange | `#FF9500` | `255, 149, 0` |
| ![#FFCC00](https://via.placeholder.com/50/FFCC00/FFCC00.png) | Yellow | `#FFCC00` | `255, 204, 0` |
| ![#34C759](https://via.placeholder.com/50/34C759/34C759.png) | Green | `#34C759` | `52, 199, 89` |
| ![#007AFF](https://via.placeholder.com/50/007AFF/007AFF.png) | Blue | `#007AFF` | `0, 122, 255` |
| ![#5856D6](https://via.placeholder.com/50/5856D6/5856D6.png) | Purple | `#5856D6` | `88, 86, 214` |

## Usage in CSS

```css
:root {
  /* Primary Colors */
  --color-primary-black: #1A1A1A;
  --color-primary-dark-gray: #333333;
  --color-primary-gray: #666666;
  --color-primary-light-gray: #999999;
  --color-primary-lighter-gray: #CCCCCC;
  --color-primary-lightest-gray: #F2F2F2;
  --color-white: #FFFFFF;
  
  /* Accent Colors */
  --color-red: #FF3B30;
  --color-orange: #FF9500;
  --color-yellow: #FFCC00;
  --color-green: #34C759;
  --color-blue: #007AFF;
  --color-purple: #5856D6;
}
```

## Usage in JavaScript/TypeScript

```javascript
const colors = {
  // Primary Colors
  primaryBlack: '#1A1A1A',
  primaryDarkGray: '#333333',
  primaryGray: '#666666',
  primaryLightGray: '#999999',
  primaryLighterGray: '#CCCCCC',
  primaryLightestGray: '#F2F2F2',
  white: '#FFFFFF',
  
  // Accent Colors
  red: '#FF3B30',
  orange: '#FF9500',
  yellow: '#FFCC00',
  green: '#34C759',
  blue: '#007AFF',
  purple: '#5856D6',
};
```

## Color Palette

### Primary Colors
<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin-bottom: 2rem;">
  <div style="width: 100px; text-align: center;">
    <div style="background-color: #1A1A1A; height: 100px; width: 100%; border-radius: 8px; margin-bottom: 8px;"></div>
    <div>Primary Black</div>
    <div>#1A1A1A</div>
  </div>
  <div style="width: 100px; text-align: center;">
    <div style="background-color: #333333; height: 100px; width: 100%; border-radius: 8px; margin-bottom: 8px;"></div>
    <div>Primary Dark Gray</div>
    <div>#333333</div>
  </div>
  <div style="width: 100px; text-align: center;">
    <div style="background-color: #666666; height: 100px; width: 100%; border-radius: 8px; margin-bottom: 8px;"></div>
    <div>Primary Gray</div>
    <div>#666666</div>
  </div>
  <div style="width: 100px; text-align: center;">
    <div style="background-color: #999999; height: 100px; width: 100%; border-radius: 8px; margin-bottom: 8px;"></div>
    <div>Primary Light Gray</div>
    <div>#999999</div>
  </div>
  <div style="width: 100px; text-align: center;">
    <div style="background-color: #CCCCCC; height: 100px; width: 100%; border-radius: 8px; margin-bottom: 8px;"></div>
    <div>Primary Lighter Gray</div>
    <div>#CCCCCC</div>
  </div>
  <div style="width: 100px; text-align: center;">
    <div style="background-color: #F2F2F2; height: 100px; width: 100%; border-radius: 8px; margin-bottom: 8px; border: 1px solid #ddd;"></div>
    <div>Primary Lightest Gray</div>
    <div>#F2F2F2</div>
  </div>
  <div style="width: 100px; text-align: center;">
    <div style="background-color: #FFFFFF; height: 100px; width: 100%; border-radius: 8px; margin-bottom: 8px; border: 1px solid #ddd;"></div>
    <div>White</div>
    <div>#FFFFFF</div>
  </div>
</div>

### Accent Colors
<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin-bottom: 2rem;">
  <div style="width: 100px; text-align: center;">
    <div style="background-color: #FF3B30; height: 100px; width: 100%; border-radius: 8px; margin-bottom: 8px;"></div>
    <div>Red</div>
    <div>#FF3B30</div>
  </div>
  <div style="width: 100px; text-align: center;">
    <div style="background-color: #FF9500; height: 100px; width: 100%; border-radius: 8px; margin-bottom: 8px;"></div>
    <div>Orange</div>
    <div>#FF9500</div>
  </div>
  <div style="width: 100px; text-align: center;">
    <div style="background-color: #FFCC00; height: 100px; width: 100%; border-radius: 8px; margin-bottom: 8px;"></div>
    <div>Yellow</div>
    <div>#FFCC00</div>
  </div>
  <div style="width: 100px; text-align: center;">
    <div style="background-color: #34C759; height: 100px; width: 100%; border-radius: 8px; margin-bottom: 8px;"></div>
    <div>Green</div>
    <div>#34C759</div>
  </div>
  <div style="width: 100px; text-align: center;">
    <div style="background-color: #007AFF; height: 100px; width: 100%; border-radius: 8px; margin-bottom: 8px;"></div>
    <div>Blue</div>
    <div>#007AFF</div>
  </div>
  <div style="width: 100px; text-align: center;">
    <div style="background-color: #5856D6; height: 100px; width: 100%; border-radius: 8px; margin-bottom: 8px;"></div>
    <div>Purple</div>
    <div>#5856D6</div>
  </div>
</div>
