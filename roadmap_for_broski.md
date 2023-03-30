# Roadmap

## IT frontend-backend-fullstack scene in a nutshell

![Screen Shot 2023-03-31 at 2 13 07 am](https://user-images.githubusercontent.com/13658072/228882708-ef9c9e32-beaf-475e-9d04-573231482c11.png)

## Basic CS

### How internet work (https://cs.fyi/guide/how-does-internet-work)

- [what is HTTP](https://www.cloudflare.com/en-gb/learning/ddos/glossary/hypertext-transfer-protocol-http)

- [what is HTTPS](https://www.cloudflare.com/en-gb/learning/ssl/what-is-https)

- [why HTTPS over HTTP](https://www.cloudflare.com/en-gb/learning/ssl/why-is-http-not-secure)

- [DNS?](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns) (đọc cho vui để biết, không cần đọc quá sâu)

- [Same-origin policy](https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy) -> [Cross origin resource sharing](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)

### Data Structures & algorithms

> MUST KNOW

- [Big O, space complexity, time complexity](https://www.freecodecamp.org/news/big-o-notation-why-it-matters-and-why-it-doesnt-1674cfa8a23c/)

- [Cheatsheet](https://www.bigocheatsheet.com/)

- [Practice](https://adventofcode.com/)

- [Practice 4 Facebook / Amazon / Netflix / Google](https://leetcode.com/)

#### Data structures

- Array
- Stack
- Queue
- Hash table
- Linked List (vào làm thì không dùng mấy nhưng phỏng vấn rất dễ bị hỏi)

#### Algorithms

- Search (linear search & binary search)
- Sort (bubble sort, merge sort, quick sort)
- Recursion (quan trọng nhưng không bắt buộc phải biết để job-ready)

> Read for fun (không nên đọc quá sâu trừ khi muốn app Facebook / Amazon / Netflix / Google)

#### Data Structures

- Tree (Data structures của DOM)(Binary search tree, B-Tree, Trie,...)
- Graph
- Heap

#### Algorithms

- Sort (radix sort, bucket sort, shell sort)
- Tree traversal
- BFS, DFS
- Shortest Path (Dijkstra)

## Programming Language

> HTML, CSS

- [HTML reference](https://www.w3schools.com/html/default.asp)
- [CSS reference](https://www.w3schools.com/css/default.asp)

> JavaScript

- Core concept for job-ready

  - 3 main pillars of JavaScript

    - Types

      - Primitive Types
      - Abstract Operations
      - Coercion
      - Equality

    - Scope

      - Lexical Scope
      - Closure (MUST MUST MUST MUST KNOW)
      - Hoisting

    - Object (kém quan trọng nhất trong 3)

      - Object notation
      - `this` keyword -> .bind()/.apply()
      - Prototypal inheritance
      - Prototype chain
      - `new` keyword

  - Asynchronous Javascript

    - Why?
    - Web API / Browser features?
    - XHR (XMLHttpRequest) ?
    - Callback?
    - Promise? (hiểu concept trước khi đọc về method)
    - Async / await (modern Javascript)?
    - Callback queue? Event Loop?

  - Method (1 vài method dùng nhiều nhất)

    - Array

      - [.map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
      - [.filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
      - [.reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)
      - [.push](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push)
      - [.pop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop)

    - Object

      - [.assign](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)
      - [.keys](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys)
      - [.entries](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries)
      - [.prototype.hasOwnProperty](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty)

  - Modern Javascript

    - Arrow Function (vs function keyword)
    - let, const vs var
    - Default parameter
    - Spread operator
    - Destructuring assignment (on object & array)
    - Template literal
    - Nullish coalescing

- Reference

  - [Modern Javascript (ES6)](https://javascript.info/)
  - [Mozilla](https://developer.mozilla.org/en-US/)
  - [Spec](https://262.ecma-international.org/6.0/)

> TypeScript

- Why?
- [Doc / Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
- [Getting started free resource](https://www.totaltypescript.com/tutorials/beginners-typescript)
- Declaration file

> Node.js (đọc qua, sau này move sang backend / fullstack thì nghiên cứu sau)

> React

- Core concept

  - Components?
  - Data flow?
  - Virtual DOM?
  - JSX?
  - State? Props? State vs Props?
  - State Management?
  - Class-based components vs Functional Components? Class components are trash nowadays?!!!!!
  - Hooks
    > Must know
    - useState
    - useEffect
    - useReducer
    - useContext

    > Good to know
    - useMemo
    - useCallback
    - useRef
    - useLayoutEffect
    - v18+ hooks

- More advanced concepts

  - Client state? Server state?
  - Render prop vs hooks
  - Higher order components are trash !!!!!!
  - Context API?
  - Escape Hatches

- Usage with TypeScript

  - Typing State / Props
  - Typing CSS properties
  - Typing utility function

- State management solution nowadays

  > Client State
  - native useState / useReducer
  - Zustand (redux-principle-alike)
  - Jotai

  > Server state
  - react-query (highly-recommended)
  - swr

  > whole package (Redux)
  - Redux toolkit
  - Legacy Redux ecosystem (trash)

  **If choice = Redux -> 3 core principle of Redux ?**

- Setup a React project

  - [Vite](https://vitejs.dev/) (highly recommended)
  - [webpack](https://webpack.js.org/)
  - ESLint
  - Prettier

- Testing (viết app xong rồi học viết test sau, cái này sau đi làm học cũng được)

  - [Jest](https://jestjs.io/)
  - [Vitest if use Vite](https://vitest.dev/)
  - [react-testing-library](https://testing-library.com/docs/react-testing-library/intro/)

- Fullstack React framework (support Server-side rendering)

  - [Next.js](https://nextjs.org/)
  - [Remix](https://remix.run/)

- [React doc](https://react.dev/) (highly highly highly recommended)

- Practice

  - [fundamentals](https://github.com/kentcdodds/react-fundamentals)
  - [hooks](https://github.com/kentcdodds/react-hooks)
  - [advanced-hooks](https://github.com/kentcdodds/advanced-react-hooks)
  - [advanced-pattern (nên nghiên cứu sau khi đi làm)](https://github.com/kentcdodds/advanced-react-patterns)

## Todo / tip & trick

- build app as a portfolio (from scratch to deployment)
- practice interview
- thứ tự ưu tiên khi tra cứu: `official docs -> mdn -> stackoverflow -> tech blog`