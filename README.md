# Alliance for OpenUSD (aousd)
The Alliance for OpenUSD (AOUSD) is a Linux Foundation project dedicated to promoting interoperability of 3D content through Universal Scene Description (OpenUSD). Founded by Pixar, Adobe, Apple, Autodesk, and NVIDIA, AOUSD standardizes 3D content ecosystems for film, gaming, architecture, industrial design, and the metaverse.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/aousd/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - 3D, Interoperability, Linux Foundation, Metaverse, OpenUSD, Specification, Standards, USD, Visual Effects

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### OpenUSD C++ API
The OpenUSD C++ API is the primary interface for working with Universal Scene Description data. Provides access to USD core, UsdImaging, Hydra rendering infrastructure, and schema APIs for geometry (UsdGeom), shading (UsdShade), lighting (UsdLux), physics (UsdPhysics), and volume (UsdVol). Available as open-source under the Apache 2.0 license.

**Human URL:** [https://openusd.org/release/api/index.html](https://openusd.org/release/api/index.html)

#### Tags:

 - 3D, C++, File Format, Library, OpenUSD, Rendering, Scene Description

#### Properties

- [Documentation](https://openusd.org/release/api/index.html)
- [APIReference](https://openusd.org/release/api/index.html)
- [GettingStarted](https://openusd.org/release/tut_usd_tutorials.html)
- [GitHubRepository](https://github.com/PixarAnimationStudios/OpenUSD)
- [Glossary](https://openusd.org/release/glossary.html)

### OpenUSD Python Bindings
OpenUSD provides comprehensive Python bindings for all major C++ modules, enabling scripting and pipeline integration in Python-based DCC workflows. Covers pxr.Usd, pxr.UsdGeom, pxr.UsdShade, pxr.UsdLux, pxr.UsdPhysics, pxr.Sdf, and Hydra.

**Human URL:** [https://openusd.org/release/api/index.html](https://openusd.org/release/api/index.html)

#### Tags:

 - 3D, OpenUSD, Python, Scene Description

#### Properties

- [Documentation](https://openusd.org/release/api/index.html)
- [SDK](https://pypi.org/project/usd-core/)
- [GitHubRepository](https://github.com/PixarAnimationStudios/OpenUSD)

## Common Properties

- [Portal](https://aousd.org)
- [Documentation](https://openusd.org/release/index.html)
- [GettingStarted](https://openusd.org/release/tut_usd_tutorials.html)
- [GitHubOrganization](https://github.com/PixarAnimationStudios)
- [GitHubRepository](https://github.com/PixarAnimationStudios/OpenUSD)
- [JSONSchema — USD Layer Schema](json-schema/aousd-usd-layer-schema.json)
- [Vocabulary](vocabulary/aousd-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Scene Composition | USD's composition arcs (references, payloads, variants, instancing, and specializes) enable non-destructive scene assembly from multiple asset layers. |
| Schema-Driven Extensibility | OpenUSD's schema system allows studios and tool vendors to extend the core specification with domain-specific schemas. |
| Hydra Rendering Architecture | The Hydra rendering delegate architecture enables pluggable render backends including Storm, Arnold, RenderMan, and others. |
| Multiple File Formats | OpenUSD supports ASCII (.usda), binary (.usdb), and packaged archive (.usdz) file formats. |
| Asset Resolution | The ArResolver system enables customizable asset path resolution for integrating USD with studio asset management systems. |

## Use Cases

| Name | Description |
|------|-------------|
| Film and Visual Effects Production | Exchange complex animated scenes between DCC tools and render farms using OpenUSD as the common format. |
| Game Development | Use OpenUSD as an interchange format between game engines like Unreal Engine and Unity and DCC content creation tools. |
| Architecture and Design Visualization | Share 3D building models, materials, and lighting between architectural design tools and visualization platforms. |
| Metaverse and XR | Enable interoperability of 3D assets across XR platforms, spatial computing devices, and virtual world applications. |
| Industrial Digital Twins | Represent complex mechanical assemblies for industrial digital twin applications using USD schemas. |

## Integrations

| Name | Description |
|------|-------------|
| Autodesk Maya / 3ds Max | Import and export USD files via Autodesk's official USD plugins for Maya and 3ds Max. |
| SideFX Houdini | Native USD integration in Houdini via LOPs (Layout Object Primitives) for creating and editing USD scenes. |
| Apple Reality Composer Pro | Apple's spatial computing tools use .usdz as the primary format for AR and visionOS content. |
| NVIDIA Omniverse | NVIDIA Omniverse is built on OpenUSD, using it as the foundation for collaborative 3D design and digital twin workflows. |
| Pixar RenderMan | RenderMan natively reads USD scenes, making it the primary production renderer for USD-based feature film pipelines. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [USD Layer Schema](json-schema/aousd-usd-layer-schema.json)
- [USD Prim Schema](json-schema/aousd-usd-prim-schema.json)

### JSON Structure

- [USD Layer Structure](json-structure/aousd-usd-layer-structure.json)
- [USD Prim Structure](json-structure/aousd-usd-prim-structure.json)

### JSON-LD

- [OpenUSD Context](json-ld/aousd-context.jsonld)

### Examples

- [USD Layer Example](examples/aousd-usd-layer-example.json)
- [USD Prim Example](examples/aousd-usd-prim-example.json)

## Vocabulary

- [Alliance for OpenUSD Vocabulary](vocabulary/aousd-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 10 actions, and OpenUSD schema domains

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
