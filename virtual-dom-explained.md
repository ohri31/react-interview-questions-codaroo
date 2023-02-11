**Explain how VirtualDOM works.**
Virtual DOM is a lightweight, in-memory representation of the actual DOM. It is used to improve the performance of updates and changes to the actual DOM by reducing the number of expensive DOM manipulations. When a component's state or props change, React will create a new virtual DOM tree, compare it to the previous tree, and then apply only the minimal set of changes necessary to the actual DOM. This improves the performance of the application and reduces the number of unnecessary re-renders.