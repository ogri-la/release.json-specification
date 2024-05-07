# release.json specification

A [JSONSchema](https://json-schema.org/overview/what-is-jsonschema) specification of the `release.json` files used to
describe World of Warcraft addon metadata.

Versioning follows [SchemaVer](https://snowplow.io/blog/introducing-schemaver-for-semantic-versioning-of-schemas/#schemaver).

`release.json` files can be validated with the [release.json-validator](https://github.com/ogri-la/release.json-validator) tool.

## history

The idea of a metadata file to accompany GitHub add-on releases was pitched by layday, put forward to the add-on developer community by [AcidWeb](https://github.com/AcidWeb) and was implemented in [packager](https://github.com/BigWigsMods/packager) by [nebularg](https://github.com/nebularg).

This *specification* was created by [Torkus](https://github.com/torkus) on 2024-05 to formally describe the data structure, best practices and track
changes in its usage over time.

## 1-0-0

[Specification](1-0-0/schema.json).

[Examples](1-0-0/examples/).

[Extant example](https://github.com/AdiAddons/AdiBags/releases/tag/v1.10.26):

```json
{
  "releases": [
    {
      "name": "AdiBags",
      "version": "v1.10.26",
      "filename": "AdiBags-v1.10.26.zip",
      "nolib": false,
      "metadata": [
        {
          "flavor": "mainline",
          "interface": 100206
        },
        {
          "flavor": "wrath",
          "interface": 30401
        },
        {
          "flavor": "classic",
          "interface": 11500
        },
        {
          "flavor": "bcc",
          "interface": 20504
        }
      ]
    }
  ]
}
```

# Licence

`release.json-specification` by [Torkus](https://github.com/torkus).

To the extent possible under law, the person who associated CC0 with
`release.json-specification` has waived all copyright and related or neighboring rights
to `release.json-specification`.

You should have received a copy of the CC0 legalcode along with this
work. If not, see <https://creativecommons.org/publicdomain/zero/1.0/>.
