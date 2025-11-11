# V1SoftwareAutoUpgradeDefaultPutRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**profile** | [**UpgradeUpgradeCanaryProfile**](UpgradeUpgradeCanaryProfile.md) |  | [optional] 
**release** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_software_auto_upgrade_default_put_request import V1SoftwareAutoUpgradeDefaultPutRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1SoftwareAutoUpgradeDefaultPutRequest from a JSON string
v1_software_auto_upgrade_default_put_request_instance = V1SoftwareAutoUpgradeDefaultPutRequest.from_json(json)
# print the JSON string representation of the object
print(V1SoftwareAutoUpgradeDefaultPutRequest.to_json())

# convert the object into a dict
v1_software_auto_upgrade_default_put_request_dict = v1_software_auto_upgrade_default_put_request_instance.to_dict()
# create an instance of V1SoftwareAutoUpgradeDefaultPutRequest from a dict
v1_software_auto_upgrade_default_put_request_from_dict = V1SoftwareAutoUpgradeDefaultPutRequest.from_dict(v1_software_auto_upgrade_default_put_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


