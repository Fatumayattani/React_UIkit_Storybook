# UI Kit Library

A reusable component library built with React and Storybook, providing essential UI elements for modern web applications. Each component is designed to be flexible, customizable, and easy to integrate into any project.

## Table of Contents

- [About](#about)
- [Components](#components)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)
- [Storybook](#storybook)
- [Contributing](#contributing)
- [License](#license)

## About

This UI Kit Library offers a collection of pre-built and customizable components to help accelerate front-end development. Each component is built with accessibility, responsiveness, and flexibility in mind. Documented in Storybook, these components come with interactive demos to showcase different states, variants, and configurations.

## Components

The following components are included in this library:

1. **Button** - Variants: Primary, Secondary, Outline, Icon; Sizes: Small, Medium, Large.
2. **Input Field** - Types: Text, Password, Email, Number; Supports validation feedback.
3. **Dropdown Menu** - Variants: Single-select, Multi-select; Optional search functionality.
4. **Modal** - Types: Centered, Full-screen, Side-drawer; Supports customizable content.
5. **Card** - Variants: Basic, Image Card, Info Card; Layout options: Vertical, Horizontal.
6. **Avatar** - Variants: User image, initials-only, icon-based; Includes status indicators.
7. **Badge/Tag** - Types: Status-based (success, warning), category tags, counters.
8. **Progress Bar** - Types: Linear, Circular; Shows loading states, percentage indicators.
9. **Tooltip** - Positions: Top, Bottom, Left, Right; Supports hover and click triggers.
10. **Toast/Notification** - Types: Success, Warning, Error, Info; Position options included.

## Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.

### Installation

To install the library and its dependencies, run:

```bash
git clone https://github.com/your-username/ui-kit-library.git
cd ui-kit-library
npm install
```

## Usage

Import the components you need into your project:

```javascript
import { Button, InputField, DropdownMenu } from 'your-ui-kit-library';

function App() {
  return (
    <div>
      <Button variant="primary" size="large">Click Me</Button>
      <InputField type="text" placeholder="Enter text" />
      <DropdownMenu options={['Option 1', 'Option 2']} />
    </div>
  );
}
```

## Development

To develop or modify components, use Storybook for a development environment that lets you visualize components in isolation.

### Running Storybook

To start Storybook locally:

```bash
npm run storybook
```

This will start the Storybook server, and you can access it at `http://localhost:6006`.

### Storybook Structure

Each component has its own stories showcasing:
- **Variants**: Different configurations, such as `primary`, `secondary`, or `outline` for buttons.
- **States**: Active, disabled, loading, etc.
- **Sizes**: Small, medium, large, as appropriate.

### Component Directory Structure

The project follows a modular structure where each component is isolated in its own directory.

```
src/
 ├── components/
 │   ├── Button/
 │   ├── InputField/
 │   ├── DropdownMenu/
 │   └── ... (other components)
 └── stories/
     ├── Button.stories.js
     ├── InputField.stories.js
     └── ... (other story files)
```

## Contributing

Contributions are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add new feature"`.
4. Push to the branch: `git push origin feature-name`.
5. Open a Pull Request.

Please make sure all new components and features are documented with Storybook stories.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

This `README.md` provides an overview of the project, installation instructions, usage examples, and development guidelines. It also emphasizes Storybook usage and how each component is structured for easy navigation and contribution.