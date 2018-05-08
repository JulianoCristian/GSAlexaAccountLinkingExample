# Alexa GameSparks User Integration Example
## Setup Notes
1. Setup a new Alexa Skill in the [console](https://developer.amazon.com/alexa/console).
2. Create a credentials.js file, sample below.
3. Upload the project to a publicly accessable https resource location such as S3 with CloudFront.

### Sample credentials.js
```javascript
credentials = {
	apiKey: "<Your GameSparks API Key>",
	apiSecret: "<Your Gamesparks API Secret>",
	apiCredential: "device",
	alexaVendorId: "<Your Alexa Vendor Id>"
};
```

## GameSparks Information
* For more information about GameSparks visit: [http://www.gamesparks.com](http://www.gamesparks.com)
* Documentation and Tutorials can be found at: [https://docs.gamesparks.net](https://docs.gamesparks.net)
* For Support visit: [https://support.gamesparks.net/support/home](https://support.gamesparks.net/support/home)
* S3 Bucket Repository [https://s3-eu-west-1.amazonaws.com/gamesparks-ireland/GSRealTimeTestTool/GSRealTimeTestTool-master.zip](https://s3-eu-west-1.amazonaws.com/gamesparks-ireland/GSRealTimeTestTool/GSRealTimeTestTool-master.zip)