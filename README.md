# react-game-hub

# Init the project

```
npm create vite@4.1.0
```

Then choose:

1. project-name
2. React
3. TypeScript

Then run the following:

```
npm install
npm run dev
```

# UI library

chakra-ui.com

install chakra:

```
npm i @chakra-ui/react @emotion/react @emotion/styled framer-motion
```

then add the provider to main.tsx:

```
import * as React from 'react'
import { ChakraProvider } from '@chakra-ui/react'
import * as ReactDOM from 'react-dom/client'
import App from './App';

const rootElement = document.getElementById('root')
ReactDOM.createRoot(rootElement).render(
  <React.StrictMode>
    <ChakraProvider>
      <App />
    </ChakraProvider>
  </React.StrictMode>,
)
```
