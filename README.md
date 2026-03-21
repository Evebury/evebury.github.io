# Evebury Open Source

**Production-ready .NET libraries for GS1 standards and typography.**

This repository hosts the [evebury.github.io](https://evebury.github.io) website — the open source hub for all Evebury libraries.

## Libraries

### Evebury.Gdsn.Gs1
A comprehensive .NET library for validating GDSN GS1 messages. Pre-validate your data before it reaches the GS1 network — catch errors early, save API costs, and reduce rejected messages.

- GDSN v3.1.33 support
- Validation messages in English, Dutch, French, and German
- Smart delta updates for efficient catalog syncing
- Zero dependencies

[![NuGet](https://img.shields.io/nuget/v/Evebury.Gdsn.Gs1?label=NuGet&color=FF4E45)](https://www.nuget.org/packages/Evebury.Gdsn.Gs1)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/Evebury/Evebury.Gdsn.Gs1)

```bash
dotnet add package Evebury.Gdsn.Gs1
```

### Evebury.Gs1.DigitalLink
A .NET library for generating strongly typed and validated GS1 Digital Link URIs with a fluent builder API.

- Type-safe builder with compile-time checks for all GS1 Application Identifiers
- Automatic check digit validation
- Custom branded domain support
- Zero dependencies

[![NuGet](https://img.shields.io/nuget/v/Evebury.Gs1.DigitalLink?label=NuGet&color=FF4E45)](https://www.nuget.org/packages/Evebury.Gs1.DigitalLink)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/Evebury/Evebury.Gs1.DigitalLink)

```bash
dotnet add package Evebury.Gs1.DigitalLink
```

### Evebury.Typography.OpenType
A comprehensive .NET library for reading and manipulating OpenType fonts — built for PDF embedding and image rendering.

- Precise font metrics and text layout
- Glyph rendering and full Unicode support (CMAP)
- Optimized for PDF document generation
- Zero dependencies

[![NuGet](https://img.shields.io/nuget/v/Evebury.Typography.OpenType?label=NuGet&color=FF4E45)](https://www.nuget.org/packages/Evebury.Typography.OpenType)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/Evebury/Evebury.Typography.OpenType)

```bash
dotnet add package Evebury.Typography.OpenType
```

## About Evebury

[Evebury](https://evebury.com) builds PIM (Product Information Management) software that helps manufacturers take control of their product data. These open-source libraries are the same building blocks we use in production — released for the community under the MIT license.

## License

All libraries are released under the [MIT License](https://opensource.org/licenses/MIT).
