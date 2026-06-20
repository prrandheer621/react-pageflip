# @prrandheer621/react-pageflip

A modern, 3D page flip effect for React. This is a fork of the original `react-pageflip` package, enhanced with smooth peeling effects for hard cover pages in mobile portrait mode!

## Installation

```bash
npm install @prrandheer621/react-pageflip
```

## Usage

```tsx
import HTMLFlipBook from "@prrandheer621/react-pageflip";

function MyBook() {
  return (
    <HTMLFlipBook width={300} height={500}>
      <div className="demoPage">Page 1</div>
      <div className="demoPage">Page 2</div>
      <div className="demoPage">Page 3</div>
      <div className="demoPage">Page 4</div>
    </HTMLFlipBook>
  );
}
```

## Enhancements
- Perfectly smooth 3D peeling for back covers in Mobile (Portrait) View.
- Graceful error handling for bounds checking on `.showNext()`.

## License
MIT License.
