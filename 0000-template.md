- Feature Name: (fill me in with a unique ident, `my_awesome_feature`)
- Start Date: (fill me in with today's date, YYYY-MM-DD)
- RFC PR: [rust-lang/rfcs#0000](https://github.com/rust-lang/rfcs/pull/0000)
- Issue: [rust-lang/rust#0000](https://github.com/rust-lang/rust/issues/0000)

# Summary
[summary]: #summary

Una explicación de un párrafo sobre la característica.

# Motivation
[motivation]: #motivation

¿Por qué lo hacemos? ¿Qué casos de uso soporta? ¿Cuál es el resultado esperado?

# Guide-level explanation
[guide-level-explanation]: #guide-level-explanation

Explica la propuesta como si ya estuviera incluida en el lenguaje y la estuvieras enseñando a otro programador de Rust. Eso generalmente significa:

- Introducción de nuevos conceptos con nombre.
- Explicar la función en gran medida con ejemplos.
- Debe explicar el impacto de la manera más concreta posible.
- Si procede, proporcione ejemplos de mensajes de error, advertencias de desaprobación u orientaciones sobre la migración.
- Si procede, describa las diferencias entre enseñar esto a los programadores  existentes y a los nuevos programadores.

En el caso de las RFC orientadas a la implementación (por ejemplo, las internas del compilador), esta sección debería centrarse en cómo los colaboradores del compilador deberían pensar en el cambio, y dar ejemplos de su impacto concreto. En el caso de las RFC sobre políticas, esta sección debe ofrecer una introducción a la política basada en ejemplos y explicar su impacto en términos concretos.

# Reference-level explanation
[reference-level-explanation]: #reference-level-explanation

Esta es la parte técnica de la RFC. Explica el diseño con suficiente detalle que:

- Su interacción con otras características es clara.
- Está razonablemente claro cómo se implementaría la función.
- Los casos de esquina se diseccionan con un ejemplo.

The section should return to the examples given in the previous section, and explain more fully how the detailed proposal makes those examples work.

# Drawbacks
[drawbacks]: #drawbacks

¿Por qué *no* deberíamos hacerlo?

# Rationale and alternatives
[rationale-and-alternatives]: #rationale-and-alternatives

- Por qué este diseño es el mejor en el espacio de los diseños posibles?
- ¿Qué otros diseños se han considerado y cuál es la razón para no elegirlos?
- ¿Cuál es el impacto de no hacer esto?

# Prior art
[prior-art]: #prior-art

Discutir el estado del arte, tanto el bueno como el malo, en relación con esta propuesta.
Algunos ejemplos de lo que puede incluir son:

- ara propuestas de lenguajes, bibliotecas,  herramientas y compiladores: ¿Existe esta característica en otros lenguajes de programación y qué experiencia ha tenido su comunidad?
- Para las propuestas comunitarias: ¿Se ha hecho esto en alguna otra comunidad y cuáles fueron sus experiencias al respecto??
- Para otros equipos: ¿Qué lecciones podemos aprender de lo que otras comunidades han hecho aquí??
- Papers: ¿Existen artículos publicados o grandes entradas que discutan esto? Si tiene algunos documentos relevantes a los que referirse, esto puede servir como un fondo teórico más detallado.

This section is intended to encourage you as an author to think about the lessons from other languages, provide readers of your RFC with a fuller picture.
If there is no prior art, that is fine - your ideas are interesting to us whether they are brand new or if it is an adaptation from other languages.

Note that while precedent set by other languages is some motivation, it does not on its own motivate an RFC.
Please also take into consideration that rust sometimes intentionally diverges from common language features.

# Unresolved questions
[unresolved-questions]: #unresolved-questions

- What parts of the design do you expect to resolve through the RFC process before this gets merged?
- What parts of the design do you expect to resolve through the implementation of this feature before stabilization?
- What related issues do you consider out of scope for this RFC that could be addressed in the future independently of the solution that comes out of this RFC?

# Future possibilities
[future-possibilities]: #future-possibilities

Piense en cuál sería la extensión y evolución natural de su propuesta
y cómo afectaría a la lengua y al proyecto en su conjunto de forma holística.
de forma holística. Intente utilizar esta sección como una herramienta para considerar de forma más completa todas las posibles
interacciones con el proyecto y la lengua en su propuesta.
Considere también cómo encaja todo esto en la hoja de ruta del proyecto
y del sub-equipo correspondiente.

Este es también un buen lugar para "volcar ideas", si están fuera del alcance de la
RFC que está escribiendo pero que están relacionadas.

Si lo ha intentado y no se le ocurre ninguna posibilidad futura
puede decir simplemente que no se le ocurre nada.

Tenga en cuenta que tener algo escrito en la sección de posibilidades futuras
no es una razón para aceptar el RFC actual o uno futuro; tales notas deben estar
en la sección de motivación o justificación de esta RFC o de las siguientes.
La sección simplemente proporciona información adicional.
