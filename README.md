# SalahAPI Specification

## Overview

The **SalahAPI Specification** defines a standard, language-agnostic interface for exchanging Islamic prayer times (Salah) data across services and applications. This specification enables both humans and computers to discover and understand the structure of prayer times data without requiring access to source code, documentation, or network traffic inspection.

When properly defined through SalahAPI, applications can understand and interact with prayer times services with minimal implementation logic. 

## Current Version

The current version of the SalahAPI Specification is **1.0**.


## Versioning

The SalahAPI Specification uses [Semantic Versioning 2.0.0](https://semver.org/spec/v2.0.0.html) (semver).

## Contributing

The SalahAPI Specification is an open-source project. Contributions are welcome via:

- Opening issues for discussion
- Submitting pull requests for improvements
- Providing feedback on proposed changes

## License

The SalahAPI Specification is licensed under [MIT License](LICENSE).

- [Calculation Methods](https://praytimes.org/calculation)
- [ISO 8601 DateTime Format](https://en.wikipedia.org/wiki/ISO_8601)
- [IANA Time Zone Database](https://www.iana.org/time-zones)
- [Astronomical Calculations for Prayer Times](https://www.icoproject.org/accut.html)

---

**Note**: This specification is intended to facilitate the standardization and exchange of Islamic prayer times data. It does not prescribe which calculation method to use, as different communities follow different scholarly opinions. Implementers should consult with local Islamic authorities for guidance on appropriate calculation parameters.