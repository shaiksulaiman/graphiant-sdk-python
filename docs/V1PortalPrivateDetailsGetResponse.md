# V1PortalPrivateDetailsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**details** | [**List[OnboardingPrivateGcsDetails]**](OnboardingPrivateGcsDetails.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_portal_private_details_get_response import V1PortalPrivateDetailsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1PortalPrivateDetailsGetResponse from a JSON string
v1_portal_private_details_get_response_instance = V1PortalPrivateDetailsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1PortalPrivateDetailsGetResponse.to_json())

# convert the object into a dict
v1_portal_private_details_get_response_dict = v1_portal_private_details_get_response_instance.to_dict()
# create an instance of V1PortalPrivateDetailsGetResponse from a dict
v1_portal_private_details_get_response_from_dict = V1PortalPrivateDetailsGetResponse.from_dict(v1_portal_private_details_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


