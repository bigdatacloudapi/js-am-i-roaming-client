# BigDataCloud Free Am-I-Roaming API Client


A Javascript client for detecting whether a frontend user is currently roaming [BigDataCloud](https://www.bigdatacloud.com)
This client works without any Javascript dependencies and has no API key or account requirement... Simply load it up and you're ready check if your frontend users are roaming.

For more information about this API and how it works, [please click here.](https://www.bigdatacloud.com/docs/api/free-am-i-roaming-api) 


## Documentation

Documentation specific to this Free API Client is detailed below.
For more information on other available APIs, please visit our [API area](https://www.bigdatacloud.com/docs).



## Authentication / Identification

There is no authentication or identification required to use this API or client.
You may use this API and client for Free without an account.



## Usage Limits

This client-side API is completely FREE for both commercial and non-commercial use, including unlimited usage with no throttling or limitations.



## Manual Installation

1. Download the included javascript file and place it in a publically accessible location
2. Include the script tag `<script src="bigdatacloud_am_i_roaming.js" type="text/javascript"></script>` before your code execution
3. Initiate the Client Info API Client as per the below example



## CDN Installation

1. Include the CDN script tag `<script src="https://cdn.jsdelivr.net/gh/bigdatacloudapi/js-am-i-roaming-client@latest/bigdatacloud_am_i_roaming.min.js" type="text/javascript"></script>` before your code execution
2. Initiate the API Client and make the required calls as necessary



## Example usage

```javascript
<script src="https://cdn.jsdelivr.net/gh/bigdatacloudapi/js-am-i-roaming-client@latest/bigdatacloud_am_i_roaming.min.js" type="text/javascript"></script>
<script type="text/javascript">

    getBDCAmIRoaming(
        /* provide a callback function for the result */
        function(result) {
            console.log(result);
        }
    );

</script>
```


## Example output

```javascript
{
    "isRoaming": true
}
```
