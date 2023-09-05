# Follow these lines to ensure you write a good code.

1. Write comments to explain why the code is here, not what it is doing.
2. Prioritize readability over cleverness. It's generally better to write code that's easy to understand than code that's unnecessarily complex or "smart".
3. Leverage Vue's reactivity system by understanding its dependencies tracking mechanism. Avoid directly mutating a prop inside a child component.
4. Do not use "watch" unless absolutely necessary. Use computed properties or methods instead.
5. Use the "key" attribute with "v-for" whenever possible.
6. Use props and events (emits) for parent-child component communication.
7. Keep your templates clean and readable. Avoid putting complex logic in your templates - instead, move it to methods or computed properties.
8. Use environment variables for sensitive data like API keys and do not expose them in your Vue application's codebase.
9. Always clean up your side effects (like timers or event listeners) in the beforeUnmount lifecycle hook to avoid memory leaks.
10. Always handle errors and exceptions properly. Use try-catch blocks to catch errors (or catch() block for axios) and handle them gracefully.
11. In every repository, include a README which tells exactly how to run the project. Eg. copy .env.example to .env
