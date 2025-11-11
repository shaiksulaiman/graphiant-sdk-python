# V1GlobalIpfixPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**exporters** | [**List[ManaV2IpfixExporter]**](ManaV2IpfixExporter.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_ipfix_post_response import V1GlobalIpfixPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalIpfixPostResponse from a JSON string
v1_global_ipfix_post_response_instance = V1GlobalIpfixPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalIpfixPostResponse.to_json())

# convert the object into a dict
v1_global_ipfix_post_response_dict = v1_global_ipfix_post_response_instance.to_dict()
# create an instance of V1GlobalIpfixPostResponse from a dict
v1_global_ipfix_post_response_from_dict = V1GlobalIpfixPostResponse.from_dict(v1_global_ipfix_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


