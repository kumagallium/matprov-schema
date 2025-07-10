# MatPROV Context

This repository provides a JSON-LD context extension for PROV-JSONLD  
with inorganic materials science specific properties under the `matprov` namespace.

## Usage

Include the context in your JSON-LD document:

```json
{
  "@context": [
    "https://kumagallium.github.io/matprov-context/context.jsonld",
    "http://www.w3.org/ns/prov#"
  ],
  ...
}
```

## Versions

* Latest (v1.0): /context.jsonld
* v1.0: /releases/1.0/context.jsonld

Backward‑incompatible updates will be released under new releases/{version} folders and recorded in versions.json.


## License

Licensed under [CC BY 4.0](LICENSE) — see the [full license text](LICENSE) for details.
