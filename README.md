# Office Feedback Web App

This is a simple Webex Device Kiosk Web App which collects office feedback ratings from users passing by.

![Office Feedback Web App](https://github.com/wxsd-sales/office-feedback-web-app/assets/21026209/a55b9343-019f-4210-8464-8c67627d8104)

## Overview

This is a simple Webex Device Kiosk collects user building/office feedback and sends the collected rating to a remote server via HTTP Post.

If the user gives a low rating, the Web App will then display a QR code prompt which can link to additional support or user data collection.

## Setup

### Prerequisites & Dependencies: 

- RoomOS/CE 11.0 or above Webex Board of Desk series device
- Control Hub Admin or Device Web admin access to the device to set the Kiosk URL
- Network connectivity so your Webex Device open access Web App hosted on the GitHub pages domain (*.github.io)

### Setup Steps:

1. Set the Kiosk URL to:
```
https://wxsd-sales.github.io/office-feedback-web-app/officeFeedbackWebApp.html
```
![image](https://github.com/wxsd-sales/office-feedback-web-app/assets/21026209/f592eef7-cc99-4ce8-bc05-fef14696cff4)

3. Enable Kiosk Mode:

![image](https://github.com/wxsd-sales/office-feedback-web-app/assets/21026209/0927df71-f130-4a73-8a02-8565e4cdcea5)


## Validation

Validated Hardware:

* Board Pro
* Desk Pro
  
This macro should work on other Webex Devices but has not been validated at this time.


    
## Demo

*For more demos & PoCs like this, check out our [Webex Labs site](https://collabtoolbox.cisco.com/webex-labs).

## License
<!-- MAKE SURE an MIT license is included in your Repository. If another license is needed, verify with management. This is for legal reasons.--> 

<!-- Keep the following statement -->
All contents are licensed under the MIT license. Please see [license](LICENSE) for details.


## Disclaimer
<!-- Keep the following here -->  
Everything included is for demo and Proof of Concept purposes only. Use of the site is solely at your own risk. This site may contain links to third party content, which we do not warrant, endorse, or assume liability for. These demos are for Cisco Webex usecases, but are not Official Cisco Webex Branded demos.


## Questions
Please contact the WXSD team at [wxsd@external.cisco.com](mailto:wxsd@external.cisco.com?subject=RepoName) for questions. Or, if you're a Cisco internal employee, reach out to us on the Webex App via our bot (globalexpert@webex.bot). In the "Engagement Type" field, choose the "API/SDK Proof of Concept Integration Development" option to make sure you reach our team. 
