# JP-API-Collections
Postman Jamf Pro API collections up for grabs.

## About The Project
Do your own testing, I'm not responsible for any POST/DELETE you may run against your Jamf Pro Instance.
I provide the tool as is, and will be working on "issues" that are submitted via my Github project.

Security is written in Base64, I'm working on possibly getting a more secure option to do the API calls. For now it's using a bearer token that automatically gets fetched. If you do not think this is secure enough, do not use this.

<!-- GETTING STARTED -->
## Getting Started

here is a script included that automatically grabs the bearer token incase the last one is expired, the only details you need to fill in are the following:
* baseUrl: https://server.jamfcloud.com/api (or /JSSResource depending on the API you’re using)
* Username:
* Password:

For details on what permissions you need for the API calls you can use these pages: 
* https://developer.jamf.com/jamf-pro/docs/classic-api-minimum-required-privileges-and-endpoint-mapping
* https://developer.jamf.com/jamf-pro/docs/privileges-and-deprecations

For all details on using the API, please refer to this page: https://developer.jamf.com/jamf-pro/reference/classic-api

### Installation

1. download Postman https://www.postman.com/downloads/
2. Download files in the repo with the right version and click on import, you can see where it is below:
  ![image-20220725-075846](https://user-images.githubusercontent.com/90345470/181239836-bf6cb81d-74d2-4508-9a8a-6cdf8d9ac3a4.jpeg)
  
3. upload the file and click on import
4. Right click on the newly created collection and click on edit.

Here you see a couple of things, you can ignore 75% of it and click on Variables. There you need to fill in your details to create the bearer token to do your API calls. Make sure to fill in the **CURRENT VALUE** because the initial value can be synced to the postman cloud if you have this turned on. The **CURRENT VALUE** is always kept locally on the device.
Keep in mind that you need to update the **CURRENT VALUE** everytime you make changes to the account details like username/password.

Figured with saying **CURRENT VALUE** 3 times above and now a 4th time you’ll remember to put your server credentials in the **CURRENT VALUE**.
That’s all, run your queries, fill in the right details and enjoy I guess

<p align="right">(<a href="#top">back to top</a>)</p>

