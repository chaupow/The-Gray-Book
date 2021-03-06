# The VL.CoreLib

The default library of VL that provides nodes and types for the most basic patching needs. Here is an overview of the Categories it adds to a document that references it.

| Category | Content |
|---|---|
| 2D | 2d primitives like Vector2, Rectangle, Circle,... and 2d transformation and collision nodes. Further any 2d related math nodes.
| 3D | 3d primitives like Vector3, Box, Sphere,... and 3d transformation and collision nodes. Further any 3d related math nodes.
| Adaptive | Nodes that can operate on different datatypes, like a + [Adaptive] that can operate on numbers, strings, colors ... or a Length [Adaptive] that works for 2D and 3D vectors.
| Animation | Timebased nodes like time-generators (LFO, Stopwatch, ...) and filters (Damper, Oscillator, ...). Also has a subcategory *FrameBased* that contains similar nodes that operate framebased instead.
| [Collections](collections.md) | Contains most notably the Spread, but also other simple collections like the Sequence, Dictionary and HashSet.
| Color | Contains the RGBA color type and operations to convert to/from different color spaces.
| Control | Nodes to patch control flow, like FlipFlop, MonoFlop,...
| IO | Mouse, Keyobard and Touch nodes as well as nodes for file IO, Path (directory, filename) and Networking
| Math | General math, algorithms,...
| Primitive | Contains the primitive datatypes, like Bool, Byte, Integer32/64 Float32/64, Char, String
| [Reactive](reactive.md) | Nodes for reactive programming
| System | [XML](xml.md), [JSON](json.md), DateTime, [Serialization](serialization.md), ...
| Text | TypeWriter
