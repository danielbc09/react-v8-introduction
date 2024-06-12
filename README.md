# Complete Intro to React V8
Complete Intro to React V8, Frontend Masters

## Lesson 1 : Pure React & createElement

    - Introduction.
    - Links

## Lesson 2: Pure React Q&A

    - Build React basic project.
    - Import the react library.
    - On Dev tools console you can type in order to check the library.
            - React
            -ReactDom
    - Show the basic way to create components in react.

## Lesson 3: Pure React Q&A

    QA:
        - Why createRoot.
        - Why use react?
            - Library to render DOM.
            - Handle state of the web app.

## Lesson 4: Pure React Components

    - Create Pet component.
    - React have a data flow from parent to childs. 
        this makes the flow of data more easy to read and follow.
    - Pass props to child component.


## Lesson 5: JSX

    - Using JSX to render components.
    - install npm.
        npm init -y
    - Using and configure Prettier.
        npm i -D prettier@2.7.1

## Lesson 6: Set up Eslint and Gitignore
    - Set up Eslint and Gitignore
    - npm i -d eslint@8.24.0 eslint-config-prettier@8.5.0

## Lesson 6: Set up Vite and react

    - Install vite
        npm i -D vite@3.1.4 @vitejs/plugin-react@2.1.0 --legacy-peer-deps.
    - Install react 18.2.0    
        npm install react@18.2.0 react-dom@18.2.0
## Lesson 7: React Core Concepts.

    - ESLint + React 

         npm install -D eslint-plugin-import@2.26.0 eslint-plugin-jsx-a11y@6.6.1 eslint-plugin-react@7.31.8

## Lesson 10
   
    - Hooks in react
        https://react-v8.holt.courses/lessons/core-react-concepts/hooks
    - How react render.
    - They have to be called in the same order, not inside ifs or conditionals.
    - Let's add the ESLint rule. 
        npm i -D eslint-plugin-react-hooks@4.6.0

## Lesson 14: Effects and customs Hooks

    - useEffect 
        useEffect allows you to say do a render of this component first so the user can see something then as soon as the render is done, then do something.
     - use custom Hooks.   
        useBreedList

## Lesson 16: Handling user Input and COMPONENT COMPOSITION

    -  Handling user input.
    -  Make subcomponts.
        - Recommendation: Don't decompose too much.

## Lesson 16: Dev Tools

    - NODE_ENV=development.
    - Strict Mode
    - Dev Tools
        React has wonderful dev tools that the core team maintains.

## Lesson 17: React Router

    - React Router is by far the most popular client side router in the React community. It is mature, being used by big companies, and battle tested at large scales.
    - npm i react-router-dom@6.4.1

    - https://react-v8.holt.courses/lessons/react-capabilities/react-router

## Lesson 22: React Query

    - Right now react query is a must !
    - The idea behind React is that you want to cache most of what you fetch from a database. 
    - npm install @tanstack/react-query@4.10.1
    - how to fetch with react query.

## Lesson 24 : Refactor 

    - Refactor useBreedList to see react query simplicity.
    - If it is possible, avoid useEffect.


## Lesson 25 : Uncontrolled Forms
    
    - We do have a controlled input on animal to properly have it determine the useBreedList animal. But we're not using the controlled input to submit the form, we're just using the form event anyway

## Lesson 26 : Class Components
    
    - Class components have lifecycle methods. These for the most part are what useEffect does for function components. They're for doing things like making API calls, starting and ending

## Lesson 28 : Error Boundaries

    - Frequently there's errors with APIs with malformatted or otherwise weird data.
    - This is something you can't do with hooks so if you needed this sort of functionality you'd have to use a class component.

## Lesson 29 : PORTALS AND REFS

    - Another nice feature React is something called a Portal. You can think of the portal as a separate mount point (the actual DOM node which your app is put into) for your React app. 

###### Resources

-- Course notes https://react-v8.holt.courses/lessons/welcome/intro
-- Course repo https://github.com/btholt/complete-intro-to-react-v8
-- Course Github https://github.com/btholt/citr-v8-project/tree/main/01-no-frills-react

