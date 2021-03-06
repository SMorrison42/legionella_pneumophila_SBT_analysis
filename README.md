# Legionella pneumophila SBT Analysis

Version: 0.8.0

This tool, version 0.8.0, was intended for the in silico assessment of Sequence Based Typing alleles for Legionella pneumophila whole genome sequenced isolates using the Illumina MiSeq sequencing platform. The input requirement is paired end data with 250 bp length. The [InSilicoAllele_DataSetAssessment_2019.xlsx](./data/InSilicoAllele_DataSetAssessment_2019.xlsx) document should be used as a guide for allele accuracy.

The allele sequences and schema profiles represented sequences and profile from 2020-06-24. Any new allele sequence and ST profile after this data will not be included in this version of the tool, until the updated version is released. In the event that an allele or ST has 'NF' determination the user should go to the EWGLI database to verify that the allele or ST profile is potentially a new ST or allele identified.

THIS IS NOT A CLIA APPROVED TEST.

## Requirements

In order to execute this workflow please ensure that your computing environment meents the following requirements:

    1. Linux Operating System

    2. SquashFS, required for executing Singularity containers - Most standard Linux distributions have SquashFS installed and enabled by default. However, in the event that SquashFS is not enabled, we recommend that you check with your system administrator to install it. Alternatively, you can enable it by following these instructions (warning: these docs are for advanced users): https://www.tldp.org/HOWTO/html_single/SquashFS-HOWTO/

    3. Docker

## Running the Pipeline Script

## Building the Docker Container

### CDC Users


### External Users


## Docker UID and GID


## Developed by

[Shatavia Morrison](https://github.com/SMorrison42)

[John Phan](https://github.com/jhphan)

[Jason Caravas](mailto:JCaravas@cdc.gov)

## License

The repository utilizes code licensed under the terms of the Apache Software License and therefore is licensed under ASL v2 or later.

This source code in this repository is free: you can redistribute it and/or modify it under the terms of the Apache Software License version 2, or (at your option) any later version.

This source code in this repository is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the Apache Software License for more details.

You should have received a copy of the Apache Software License along with this program. If not, see http://www.apache.org/licenses/LICENSE-2.0.html

The source code forked from other open source projects will inherit its license.

## Privacy

This repository contains only non-sensitive, publicly available data and information. All material and community participation is covered by the Surveillance Platform Disclaimer and Code of Conduct. For more information about CDC's privacy policy, please visit http://www.cdc.gov/privacy.html.

## Contributing

Anyone is encouraged to contribute to the repository by forking and submitting a pull request. (If you are new to GitHub, you might start with a basic tutorial.) By contributing to this project, you grant a world-wide, royalty-free, perpetual, irrevocable, non-exclusive, transferable license to all users under the terms of the Apache Software License v2 or later.

All comments, messages, pull requests, and other submissions received through CDC including this GitHub page are subject to the Presidential Records Act and may be archived. Learn more at http://www.cdc.gov/other/privacy.html.

## Records

This repository is not a source of government records, but is a copy to increase collaboration and collaborative potential. All government records will be published through the CDC web site.

## Notices

Please refer to CDC's Template Repository for more information about contributing to this repository, public domain notices and disclaimers, and code of conduct.
