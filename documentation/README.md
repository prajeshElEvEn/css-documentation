
# Documentation

## Introduction

### Guidelines

- This CSS is compatible with Bootstrap v5.2
- This CSS is specifically used for the DeepThought's websites.

## Getting Started

## Setup

- Include the DeepThought CSS CDN link in the head tag of your HTML file.

```html
<link rel="stylesheet" href="https://app.deepthought.education/assets/styles.css">
```

- Include the Bootstrap CDN link in the head tag of your HTML file.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css">
```

## Components

### Root Styles

- Typography

```css
--font-family-poppins: "Poppins", sans-serif;
--font-family-open-sans: "Open Sans", sans-serif;
--primary-font-color: #000000;
--secondary-font-color: #ffffff;
--tertiary-font-color: #535353;
```

- Colors

```css
--primary-background-color: #fefeff;
--secondary-background-color: #f6f8fc;
--tertiary-background-color: #0029ff;
--highlighted-background-color: #0029ff;
--primary-foreground-color: #cccccc;
--secondary-foreground-color: #000b47;
--tertiary-foreground-color: #696969;
--quaternary-foreground-color: #ffffff;
```

- Accent Colors

```css
--accent-color-1: #fcfee8;
--accent-color-2: #efffea;
--accent-color-3: #d6f8ff;
--accent-color-4: #fbf4e4;
--accent-color-5: #f2f0ff;
--accent-color-6: #feedf8;
--accent-color-7: #f3f3f3;
```

- Grey Scale Colors

```css
--grey-scale-1: #535353;
--grey-scale-2: #4e4c4c;
--grey-scale-3: #696969;
--grey-scale-4: #a3a3a3;
--grey-scale-5: #bebbbb;
```

- Border Color

```css
--border-color: var(--grey-scale-5);
```

- Hover Color

```css
--list-hover-color: #f1f1f1;
```

- Button Colors

```css
--primary-button-background-color: var(--tertiary-background-color);
--primary-button-text-color: #ffffff;
--secondary-button-background-color: #ffffff;
--secondary-button-text-color: var(--tertiary-background-color);
--tertiary-button-background-color: #0029ff26;
--tertiary-button-text-color: #333333;
--button-disabled-background: #cac9c9;
--secondary-button-disabled-border-color: #333;
--secondary-button-disabled-color: black;
```

- Metrics

```css
--right-container-width: 350px;
--right-sidebar-width: 60px;
--left-sidebar-width: 60px;
--header-height: 75px;
```

- Background Colors

```css
.bg-accent-1 {
  background-color: var(--accent-color-1);
}
```

```css
.bg-accent-2 {
  background-color: var(--accent-color-2);
}
```

```css
.bg-accent-3 {
  background-color: var(--accent-color-3);
}
```

```css
.bg-accent-4 {
  background-color: var(--accent-color-4);
}
```

```css
.bg-accent-5 {
  background-color: var(--accent-color-5);
}
```

```css
.bg-accent-6 {
  background-color: var(--accent-color-6);
}
```

```css
.bg-grey-light {
  background-color: var(--accent-color-7) !important;
}
```

```css
.bg-grey {
  background-color: var(--grey-scale-4);
}
```

- All Root Styles

```css
:root {
  --font-family-poppins: "Poppins", sans-serif;
  --font-family-open-sans: "Open Sans", sans-serif;
  --primary-background-color: #fefeff;
  --secondary-background-color: #f6f8fc;
  --tertiary-background-color: #0029ff;
  --highlighted-background-color: #0029ff;
  --primary-foreground-color: #cccccc;
  --secondary-foreground-color: #000b47;
  --tertiary-foreground-color: #696969;
  --quaternary-foreground-color: #ffffff;
  --accent-color-1: #fcfee8;
  --accent-color-2: #efffea;
  --accent-color-3: #d6f8ff;
  --accent-color-4: #fbf4e4;
  --accent-color-5: #f2f0ff;
  --accent-color-6: #feedf8;
  --accent-color-7: #f3f3f3;
  --grey-scale-1: #535353;
  --grey-scale-2: #4e4c4c;
  --grey-scale-3: #696969;
  --grey-scale-4: #a3a3a3;
  --grey-scale-5: #bebbbb;
  --primary-button-background-color: var(--tertiary-background-color);
  --primary-button-text-color: #ffffff;
  --secondary-button-background-color: #ffffff;
  --secondary-button-text-color: var(--tertiary-background-color);
  --tertiary-button-background-color: #0029ff26;
  --tertiary-button-text-color: #333333;
  --button-disabled-background: #cac9c9;
  --secondary-button-disabled-border-color: #333;
  --secondary-button-disabled-color: black;
  --right-container-width: 350px;
  --right-sidebar-width: 60px;
  --left-sidebar-width: 60px;
  --header-height: 75px;
  --primary-font-color: #000000;
  --secondary-font-color: #ffffff;
  --tertiary-font-color: #535353;
  --border-color: var(--grey-scale-5);
  --list-hover-color: #f1f1f1;
}

```

## Utility Classes

- Utility Class 1: List and explain each custom utility class, detailing its purpose and how to apply it.
- Utility Class 2: Repeat the above for each additional utility class, if applicable.

## Custom Styles and Overrides

- Customization Overview: Explain the modifications made to the default Bootstrap styles.
- Style 1: Document each custom style or override, describing its purpose and how it affects the elements.
- Style 2: Repeat the above for each additional custom style, if applicable.

## Color Palette and Typography

- Color Palette: Specify the colors used in your custom CSS, providing color codes and usage guidelines.
- Typography: Describe the font families, sizes, and styles applied to various elements.

## Usage Guidelines

- Integration: Provide guidelines on how to integrate your custom CSS with Bootstrap v5.
- Best Practices: Offer recommendations and best practices for using your styles effectively.
- Naming Conventions: Explain any naming conventions or patterns used in your CSS.

## Examples and Demos

- Component Examples: Showcase examples of your custom components in use, along with corresponding code snippets.
- Style Demonstrations: Provide visual examples of your custom styles applied to different elements.

## Troubleshooting and FAQs

- Common Issues: Address common problems users might encounter and provide troubleshooting tips.
- Frequently Asked Questions: Include a section with frequently asked questions and their answers.

## Resources and References

- External Libraries: List any external libraries or dependencies used in conjunction with your custom CSS.
- Related Documentation: Include links to relevant Bootstrap v5 documentation and resources.

## Changelog

- Version History: Document the version history of your custom CSS, highlighting changes and updates.

## Support and Contact

- Support Channels: Provide information on how users can seek support or ask questions.
- Contact Details: Share contact details for users to reach out for further assistance.

Remember, this is a suggested structure, and you can modify and adapt it based on your specific requirements. The goal is to provide a well-organized and comprehensive documentation that helps users understand and utilize your custom CSS effectively.
