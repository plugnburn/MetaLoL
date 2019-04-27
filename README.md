# Metaprog

MetaLOL - Created by the community for the lulz and Ъ fun

## About

MetaLOL (or AMP, _AntiMetaProg_) is a community effort to create a multi-paradigm visual programming environment which would be a viable Metaprog alternative created using modern technologies and techniques.

Core MetaLOL/AMP principles shall be:

- **Simplicity** - the code must be readable even for complicated software;
- **Stability** - generated code must be prone to low-level errors despite its complexity;
- **Extensibility** - one should be able to extend the language and environment with no limits once the core functionality is in place. Including any system library bindings.

## Concept ideas (subject to change)

1. [Red](https://www.red-lang.org/) as the backend language. _Rationale_: cross-platform, homoiconicity, simplified code generation, powerful GUI APIs, compact compiler, lots of "batteries" included.
2. [Graphviz](https://www.graphviz.org/) as the code diagram plotting engine. _Rationale_: cross-platform, declarative, versatile, consistent representation of nodes and their links.
3. Low number of different graph node types - as of now, just 8 of them are planned: module declaration, block declaration, function declaration, literal node, call node, event node, object node. _Rationale_: everything else can be extended on top of these basic node types.
4. Each node, except module declaration nodes, can have some number of input and output slots. Unlike simple points of the graph, which define the flow of code, slots define the flow of data. If no slots are explicitly defined, it's assumed that the node has 1 input slot and 1 output slot.
