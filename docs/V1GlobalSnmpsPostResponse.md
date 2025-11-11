# V1GlobalSnmpsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**snmps** | [**List[ManaV2Snmp]**](ManaV2Snmp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_snmps_post_response import V1GlobalSnmpsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalSnmpsPostResponse from a JSON string
v1_global_snmps_post_response_instance = V1GlobalSnmpsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalSnmpsPostResponse.to_json())

# convert the object into a dict
v1_global_snmps_post_response_dict = v1_global_snmps_post_response_instance.to_dict()
# create an instance of V1GlobalSnmpsPostResponse from a dict
v1_global_snmps_post_response_from_dict = V1GlobalSnmpsPostResponse.from_dict(v1_global_snmps_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


