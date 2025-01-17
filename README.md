# CloudNation Security Workbooks

**Author: Erik Snijder | Principal Consultant Cloud Security [CloudNation](https://www.cloudnation.nl/en/services/cloud-security)**

This project contains a collection of CloudNation Security workbooks for Azure. These workbooks will provide you key insights in your current Azure security posture.
The workbooks are inspired on several community workbooks with a CloudNation twist.

Current Workbooks:

- [Defender for Cloud Health Assessment workbook](https://github.com/CloudNationHQ/Security-Workbooks/blob/main/DfC%20Health%20Assessment%20workbook/ReadMe.md)
- [Disabled and Exempted MCSB policies workbook](https://github.com/CloudNationHQ/Security-Workbooks/blob/main/Disabled%20and%20Exempt%20workbook/ReadMe.md)

## Testing

For more information, please see our testing [guidelines](./TESTING.md)

## Notes

Using a dedicated module, we've developed a naming convention for resources that's based on specific regular expressions for each type, ensuring correct abbreviations and offering flexibility with multiple prefixes and suffixes.

Full examples detailing all usages, along with integrations with dependency modules, are located in the examples directory.

To update the module's documentation run `make doc`

## Authors

Module is maintained by [these awesome contributors](https://github.com/cloudnationhq/terraform-azure-sa/graphs/contributors).

## Contributing

We welcome contributions from the community! Whether it's reporting a bug, suggesting a new feature, or submitting a pull request, your input is highly valued.

For more information, please see our contribution [guidelines](./CONTRIBUTING.md).

## License

MIT Licensed. See [LICENSE](https://github.com/cloudnationhq/terraform-azure-sa/blob/main/LICENSE) for full details.
