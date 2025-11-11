# V2IntegrationPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**integration** | [**AlertserviceIntegration**](AlertserviceIntegration.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_integration_post_response import V2IntegrationPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2IntegrationPostResponse from a JSON string
v2_integration_post_response_instance = V2IntegrationPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2IntegrationPostResponse.to_json())

# convert the object into a dict
v2_integration_post_response_dict = v2_integration_post_response_instance.to_dict()
# create an instance of V2IntegrationPostResponse from a dict
v2_integration_post_response_from_dict = V2IntegrationPostResponse.from_dict(v2_integration_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


