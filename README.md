﻿# WATS Converter - KlippelLog

A WATS Client converter plugin for importing test data from Klippel test software to WATS.

## Getting Started

* [About WATS](https://wats.com/manufacturing-intelligence/)
* [About submitting data to WATS](https://virinco.zendesk.com/hc/en-us/articles/207424613)
* [About creating custom converters](https://virinco.zendesk.com/hc/en-us/articles/207424593)

## Download

You can download the latest released version of the converter [here](releases/latest). See the Custom Converter section in the [WATS Client Installation Guide](https://wats.com/download) for your version of the WATS Client for how to install a converter.

### Parameters

This converter uses the following parameters:

| Parameter         | Default value | Description                                                    |
|-------------------|:-------------:|----------------------------------------------------------------|
| partNumber        | ABC123        | If log is missing a part number, use this one.                 |
| partRevision      | 1.0           | If log is missing a revision, use this one.                    |
| sequenceName      | MainSequence  | If log is missing sequence name, use this one.                 |
| sequenceVersion   | 1.0.0         | If log is missing sequence version, use this one.              |
| operationTypeCode | 10            | If log is missing operation code (process code), use this one. |

## Contributing

We're open to suggestions! Feel free open an issue or create a pull request.

Please read [Contributing](CONTRIBUTING.md) for details on contributions.

# Contact

* Issues with the converter or suggestions for improvements can be submitted as an issue here on GitHub.
* Ask questions about WATS in the [WATS Community Help](https://virinco.zendesk.com/hc/en-us/community/topics/200229613)
* Suggestions for the WATS Client itself or WATS in general can be submitted to the [WATS Idea Exchange](https://virinco.zendesk.com/hc/en-us/community/topics/200229623)
* Sensitive installation issues or other sensitive questions can be sent to [support@virinco.com](mailto://support@virinco.com)

## License

This project is licensed under the [LICENSE.md](LICENSE.md).
