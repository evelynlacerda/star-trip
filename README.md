# 🌌 StarTrip React Lib

StarTrip is a lightweight and easy-to-use React component that renders a starfield animation background using `canvas`. It simulates a smooth interstellar journey, similar to Star Wars hyperspace effects — ideal for futuristic and immersive UIs.

### 🌠 [Click here to preview StarTrip Demo](#)

---

### 🚀 Installation

```bash
npm install star-trip
# or
yarn add star-trip
```

---

### 💡 Usage

```tsx
import { StarTrip } from 'star-trip';

function App() {
	return (
		<>
			<StarTrip />
			<header>
				<h1>StarTrip React Lib</h1>
			</header>****
		</>
	);
}

export default App;

```

The component renders a full-screen `canvas` with stars moving toward the user.

---

### ⚙️ Available Props (optional)

| Prop              | Type     | Default   | Description                                                 |
|-------------------|----------|-----------|-------------------------------------------------------------|
| `numStars`        | `number` | `300`     | Total number of animated stars                             |
| `speed`           | `number` | `2`       | Speed of star movement                                     |
| `starSize`        | `number` | `1.5`     | Base size of the stars                                     |
| `maxOpacity`      | `number` | `0.8`     | Maximum opacity a star can reach                           |
| `maxDepth`        | `number` | `500`     | Maximum depth — how far stars can travel                   |
| `zIndex`          | `number` | `-1`      | z-index of the canvas layer                                |
| `backgroundColor` | `string` | `"black"` or `#000` | Background color of the canvas                             |

---

### 📦 Compatibility

- React **17, 18, and 19**
- Supports **ESM** and **CommonJS**
- Lightweight — only React as a peer dependency

---

### 🛠 Development

```bash
npm run dev     # Start build watcher with tsup
npm run build   # Build for production
```

---

### 📄 License
MIT © [Évelyn Lacerda](https://github.com/evelynlacerda)