**What is the impact of indexes as keys?**

Using indexes as keys can have a negative impact on performance because they don't provide a stable identity for elements, and React has to rely on the order of elements in the array to determine which elements have changed. This can lead to unnecessary re-renders.