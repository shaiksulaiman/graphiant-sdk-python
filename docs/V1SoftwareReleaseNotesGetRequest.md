# V1SoftwareReleaseNotesGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**key** | [**UpgradeInventoryKey**](UpgradeInventoryKey.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_software_release_notes_get_request import V1SoftwareReleaseNotesGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1SoftwareReleaseNotesGetRequest from a JSON string
v1_software_release_notes_get_request_instance = V1SoftwareReleaseNotesGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1SoftwareReleaseNotesGetRequest.to_json())

# convert the object into a dict
v1_software_release_notes_get_request_dict = v1_software_release_notes_get_request_instance.to_dict()
# create an instance of V1SoftwareReleaseNotesGetRequest from a dict
v1_software_release_notes_get_request_from_dict = V1SoftwareReleaseNotesGetRequest.from_dict(v1_software_release_notes_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


