# Dropdown Component

A customizable dropdown component built with modern web technologies.

## Features

- Customizable dropdown menu
- Easy to integrate
- Responsive design
- Keyboard navigation support
- Accessible

## Installation

```bash
npm install
```

## Usage

```jsx
import Dropdown from "./src/components/Dropdown";

function App() {
  const options = [
    { label: "Option 1", value: "1" },
    { label: "Option 2", value: "2" },
    { label: "Option 3", value: "3" },
  ];

  return (
    <Dropdown
      options={options}
      onChange={(selected) => console.log("Selected:", selected)}
      placeholder="Select an option"
    />
  );
}
```

## Props

| Prop        | Type     | Description                                 |
| ----------- | -------- | ------------------------------------------- |
| options     | Array    | Array of options to display in dropdown     |
| onChange    | Function | Callback function when selection changes    |
| placeholder | String   | Placeholder text when no option is selected |
| value       | String   | Currently selected value                    |
| disabled    | Boolean  | Whether the dropdown is disabled            |

## Development

```bash
# Install dependencies
npm install

# Start development server
npm start

# Build for production
npm run build
```

## License

MIT
