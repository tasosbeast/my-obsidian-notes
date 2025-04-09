**Props** (short for _properties_) are read-only inputs passed from a [[parent component]] to a [[child component]] in [[React]]. They allow [[components]] to be dynamic and [[reusability|reusable]] by providing them with custom [[data]], configuration, or behavior.

Props support **unidirectional [[data]] flow**, meaning [[data]] moves from parent to child, not the other way around. This makes the [[application]] more [[predictable]] and easier to [[debugging|debug]].

Unlike [[state]], props cannot be modified by the component that receives them. They are essential for [[component composition]] and for building [[reusability|reusable]] UI elements.