[JSON Patch [RFC6902]](https://tools.ietf.org/html/rfc6902) is a format for expressing a sequence of operations to apply to a target JSON document. It requires to apply sequences in correct, sequential order. However, the JSON Patch spec does not suggest any way to achieve it in asynchronous world of JavaScipt

Versioned JSON Patch is proposed format (pair of formats) to specify the sequential nature of JSON Patches, and to make it more suitable for use with the asynchronous communication like HTTP PATCH, or Web Sockets. It also helps to achieve eventual consistency with Operational Transformations, and boost real-time collaboration on JSON documents. Versioned JSON Patch is in fact fully compatible JSON Patch, so it should not provide any compatibility issues, nor additional layers.

Note, that distributed collaboration on JSON document, may apply to many cases, like: client-serve, peer-peer, peer-to-many, etc.

Here goes spec for both formats
# [Versioned JSON Patch](Versioned-JSON-Patch.md)
 - [.md](Versioned-JSON-Patch.md)
 - [.nroff](Versioned-JSON-Patch.nroff)

# [Multiple  Versioned JSON Patch](Multiple-Versioned-JSON-Patch.md)
 - [.md](Multiple-Versioned-JSON-Patch.md)
 - [.nroff](Multiple-Versioned-JSON-Patch.nroff)

# Known implementations:
