
<!---
ElcaNels/ElcaNels is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->ElcaNels/ElcaNels es un repositorio ✨ especial ✨ porque su archivo `README.md` (este archivo) aparece en tu perfil de GitHub.
## Política de pragma de Solidity

Este repositorio fomenta que los contratos derivados y proyectos downstream puedan compilar y extender los contratos sin choques de versión.

- Objetivo: Relajar pragmas estrictos fijados a `0.8.23` para permitir compiladores compatibles de la serie `0.8.x`.
- Recomendación concreta: usar `pragma solidity >=0.8.23 <0.9.0;` o `pragma solidity ^0.8.23;` en lugar de `pragma solidity 0.8.23;`.

Si ves contratos con la versión fijada exactamente a `0.8.23` y deseas que los actualicemos automáticamente a `^0.8.23`, abre un issue o PR, o contáctanos y aplicaremos los cambios y una matriz de CI para compilar con varias versiones 0.8.x.

Puedes hacer clic en el enlace Vista previa para ver los cambios.
--->
