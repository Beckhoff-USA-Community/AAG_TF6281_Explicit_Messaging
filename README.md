# About This Repository

This Repository includes a TF6281 example for Explicit Messaging with CIP. There is an included TwinCAT PLC project, as well as a Allen-Bradley CompactLogix ADC file for Studio 5000 and a ODF file for Kepware Server.

NOTE: When using Kepware Server, the TF6281 can only connect to the "Unsolicited" driver; A.K.A Allen-Bradley ControlLogix Ethernet Server. Kepware does not support a "Generic" EthernetIP driver at this momnent. This unsolicited driver method also does not support structured datatypes on the Kepware side, however arrays work well.


This sample is created by [Beckhoff Automation LLC.](https://www.beckhoff.com/en-us/), and is provided as-is under the Zero-Clause BSD license.

# How to get support

Should you have any questions regarding the provided sample code, please contact your local Beckhoff support team. Contact information can be found on the official Beckhoff website at https://www.beckhoff.com/en-us/support/.

# Further Information

Further Information on using TF6281 with Explicit Messaging and CIP can be found at the [Beckhoff Infosys](https://infosys.beckhoff.com) under the [Data Table Read and Write](https://infosys.beckhoff.com/content/1033/tf6281_tc3_ethernetipscanner/4350105867.html)

## Requirements

The following components must be installed to run sample code:

- [TE1000 TwinCAT 3 Engineering](https://www.beckhoff.com/en-en/products/automation/twincat/te1xxx-twincat-3-engineering/te1000.html) version 3.1.4024.0 or higher

## Disclaimer

All sample code provided by Beckhoff Automation LLC are for illustrative purposes only and are provided “as is” and without any warranties, express or implied. Actual implementations in applications will vary significantly. Beckhoff Automation LLC shall have no liability for, and does not waive any rights in relation to, any code samples that it provides or the use of such code samples for any purpose.
