Object representing descriptive aspect for another objects that forms a conceptual whole. Value-objects are inherently [[Immutability|immutable]]. 

In most cases it is composed of primitive values or other value objects, but Value Object can even reference entities. For instance in online map drawn route from SF to LA may be represented as Route object linking entities.

It has no it's own identity compared to [[Entity]]. There's no point in distinguishing two value objects as well as maintaining this identification design complexity.

> In some application the same concept may be represented as [[Value Object]], while in others it would be full-fledged [[Entity]], - depending on the question if the identity of this concept matters.

