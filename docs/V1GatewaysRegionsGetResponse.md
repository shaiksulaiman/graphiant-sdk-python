# V1GatewaysRegionsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**regions** | [**List[ManaV2Region]**](ManaV2Region.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_gateways_regions_get_response import V1GatewaysRegionsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GatewaysRegionsGetResponse from a JSON string
v1_gateways_regions_get_response_instance = V1GatewaysRegionsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GatewaysRegionsGetResponse.to_json())

# convert the object into a dict
v1_gateways_regions_get_response_dict = v1_gateways_regions_get_response_instance.to_dict()
# create an instance of V1GatewaysRegionsGetResponse from a dict
v1_gateways_regions_get_response_from_dict = V1GatewaysRegionsGetResponse.from_dict(v1_gateways_regions_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


