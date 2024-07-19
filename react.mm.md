---
title: React Mindmap
author: Alexandru Constantin
markmap:
  colorFreezeLevel: 1
---

## CLI Tools

- [Vite](https://vitejs.dev/guide/)
- [Create React App](https://react.dev/learn/start-a-new-react-project)

## Components

- Type
  - Class components
  - Functional components
- Basic
  - JSX
  - Props
    - passing
      - a variable
      - a single object {...props}
      - function as variable
    - receiving
      - grouping received props into a single object {...object}
    - default prop value {type="submit"}
    - updating object state immutably
      - in [JS](https://medium.com/@fortune.nwuneke/immutable-state-updates-in-javascript-b1ae93a1c8d6#:~:text=An%20immutable%20state%20ensures%20that,object%20with%20the%20updated%20values)
      - in React - setMyObject({ ...myObject, newStuff })
  - Composition
    - {children}
    - multiple slots
- State
  - useState
  - lift state up 
  - deriving state from prop (computed)

## Rendering
  - Lists and keys
  - [Conditional Rendering](https://www.robinwieruch.de/conditional-rendering-react/)
    - if
      - use to opt-out early from a rendering (guard pattern)
    - ternary
    - &&
    - multiple conditional rendering - enum
    - higher-order components (HOC)
    - can be avoided
      - if ...else
        - use it rarely, because it's verbose
        - instead, use ternary operator or logical && operator
      - switch
        - avoid using it, because it's too verbose
        - instead use enums
      - nested conditional rendering
        - avoid them for the sake of readability
        - use HOC
  - [Lifecycle](https://react.dev/learn/lifecycle-of-reactive-effects)
  - Refs and Portals
    - [useRef hook](https://www.robinwieruch.de/conditional-rendering-react/)
    - ref vs state: ref change doesn't reexecute
    - portal: [ createPortal](https://react.dev/reference/react-dom/createPortal) from react-dom
  - [Events](https://react.dev/learn/responding-to-events)

## Debugging
  - understand the error message in console
  - using break point (dev tool -> sources)
  - strict mode: StrictMode
  - React DevTools

## Advanced State Management
  - [ Context API ](https://react.dev/reference/react/useContext)
  - [ useReducer ](https://react.dev/learn/scaling-up-with-reducer-and-context)

## Basic Hooks
  - useState
  - useEffect
  - useCallback

## API calls
  - useEffect with Try - Catch with async - await

## Hooks
  - 
