# ![LOGO](logo.png) AWS IoT 1-Click Devices Service **flow**ground Connector

## Description

A generated **flow**ground connector for the AWS IoT 1-Click Devices Service API (version 2018-05-14).

Generated from: https://api.apis.guru/v2/specs/amazonaws.com/iot1click-devices/2018-05-14/swagger.json<br/>
Generated at: 2019-07-08T14:35:39+03:00

## API Description

Stub description<br/>

## Authorization

Supported authorization schemes:
- API Key
## Actions

### ClaimDevicesByClaimCode
> Adds device(s) to your account (i.e., claim one or more devices) if and only if<br/>
>  you received a claim code with the device(s).<br/>

#### Input Parameters
* `claimCode` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### ListDevices
> Lists the 1-Click compatible devices associated with your AWS account.<br/>

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### DescribeDevice
> Given a device ID, returns a DescribeDeviceResponse object describing<br/>
>  the details of the device.<br/>

#### Input Parameters
* `deviceId` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### ListDeviceEvents
> Using a device ID, returns a DeviceEventsResponse object containing<br/>
>  an array of events for the device.<br/>

#### Input Parameters
* `deviceId` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### FinalizeDeviceClaim
<blockquote><p>Given a device ID, finalizes the claim request for the associated device.</p><note>
 <p>Claiming a device consists of initiating a claim, then publishing a device
 event, and finalizing the claim. For a device of type button, a
 device event can be published by simply clicking the device.</p>
 </note></blockquote>

#### Input Parameters
* `deviceId` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### InitiateDeviceClaim
<blockquote><p>Given a device ID, initiates a claim request for the associated device.</p><note>
 <p>Claiming a device consists of initiating a claim, then publishing a device
 event, and finalizing the claim. For a device of type button, a
 device event can be published by simply clicking the device.</p>
 </note></blockquote>

#### Input Parameters
* `deviceId` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### GetDeviceMethods
> Given a device ID, returns the invokable methods associated with the<br/>
>  device.<br/>

#### Input Parameters
* `deviceId` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### InvokeDeviceMethod
> Given a device ID, issues a request to invoke a named device method (with possible<br/>
>  parameters). See the "Example POST" code snippet below.<br/>

#### Input Parameters
* `deviceId` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### UpdateDeviceState
> Using a Boolean value (true or false), this operation<br/>
>  enables or disables the device given a device ID.<br/>

#### Input Parameters
* `deviceId` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### UnclaimDevice
> Disassociates a device from your AWS account using its device ID.<br/>

#### Input Parameters
* `deviceId` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

## License

**flow**ground :- Telekom iPaaS / amazonaws-com-iot-1-click-devices-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
