# V1ExtranetsB2bPeeringConsumerMatchIdPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**consumer_activity_id** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**lan_segment** | **int** |  | [optional] 
**nat** | [**List[ManaV2B2bNat]**](ManaV2B2bNat.md) |  | [optional] 
**site_information** | [**List[ManaV2B2bSiteInformation]**](ManaV2B2bSiteInformation.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_consumer_match_id_post_response import V1ExtranetsB2bPeeringConsumerMatchIdPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringConsumerMatchIdPostResponse from a JSON string
v1_extranets_b2b_peering_consumer_match_id_post_response_instance = V1ExtranetsB2bPeeringConsumerMatchIdPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringConsumerMatchIdPostResponse.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_consumer_match_id_post_response_dict = v1_extranets_b2b_peering_consumer_match_id_post_response_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringConsumerMatchIdPostResponse from a dict
v1_extranets_b2b_peering_consumer_match_id_post_response_from_dict = V1ExtranetsB2bPeeringConsumerMatchIdPostResponse.from_dict(v1_extranets_b2b_peering_consumer_match_id_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


