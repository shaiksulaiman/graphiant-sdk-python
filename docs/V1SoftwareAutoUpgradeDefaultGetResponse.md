# V1SoftwareAutoUpgradeDefaultGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**profile** | [**UpgradeUpgradeCanaryProfile**](UpgradeUpgradeCanaryProfile.md) |  | [optional] 
**release** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_software_auto_upgrade_default_get_response import V1SoftwareAutoUpgradeDefaultGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1SoftwareAutoUpgradeDefaultGetResponse from a JSON string
v1_software_auto_upgrade_default_get_response_instance = V1SoftwareAutoUpgradeDefaultGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1SoftwareAutoUpgradeDefaultGetResponse.to_json())

# convert the object into a dict
v1_software_auto_upgrade_default_get_response_dict = v1_software_auto_upgrade_default_get_response_instance.to_dict()
# create an instance of V1SoftwareAutoUpgradeDefaultGetResponse from a dict
v1_software_auto_upgrade_default_get_response_from_dict = V1SoftwareAutoUpgradeDefaultGetResponse.from_dict(v1_software_auto_upgrade_default_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


