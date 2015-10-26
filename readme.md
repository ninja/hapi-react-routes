# ルート
## Rūto
### Hapi React Router plugin.

React Router handles all incoming requests. 302 redirects and 404 not founds are passed through to default Hapi routing.

Rendering a matched route can be either:
- **homomorphic**: Server and client render separately.
- **isomorphic**: Server renders. Client re-renders only upon user interaction.

See [examples](examples) and [tests](test.js) for details.
