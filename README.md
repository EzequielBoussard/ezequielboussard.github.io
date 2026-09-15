# ezequielboussard.github.io

Este repositorio existe para que `https://ezequielboussard.github.io` no devuelva un 404. Sirve un único `index.html` que redirige a [ezequiel.is-a.dev](https://ezequiel.is-a.dev), que es el portafolio de verdad.

GitHub Pages no puede responder un 301, así que la redirección es del lado del cliente y va en tres capas: `meta refresh`, `location.replace` y un enlace visible por si el JavaScript está bloqueado. El `canonical` apunta al destino para que los buscadores no indexen esta página intermedia.

Nada más vive acá. Los proyectos están en sus propios repositorios.
