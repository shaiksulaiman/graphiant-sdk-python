# V1LanSegmentsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**page_info** | [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**segments** | [**List[ManaV2Vrf]**](ManaV2Vrf.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_lan_segments_get_response import V1LanSegmentsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1LanSegmentsGetResponse from a JSON string
v1_lan_segments_get_response_instance = V1LanSegmentsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1LanSegmentsGetResponse.to_json())

# convert the object into a dict
v1_lan_segments_get_response_dict = v1_lan_segments_get_response_instance.to_dict()
# create an instance of V1LanSegmentsGetResponse from a dict
v1_lan_segments_get_response_from_dict = V1LanSegmentsGetResponse.from_dict(v1_lan_segments_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


