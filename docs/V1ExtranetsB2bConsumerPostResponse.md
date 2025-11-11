# V1ExtranetsB2bConsumerPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device** | [**List[ManaV2ConsumerDeviceInformation]**](ManaV2ConsumerDeviceInformation.md) |  | [optional] 
**id** | **int** |  | [optional] 
**policy** | [**List[ManaV2ExtranetConsumerLanSegmentPolicyResponse]**](ManaV2ExtranetConsumerLanSegmentPolicyResponse.md) |  | [optional] 
**site_information** | [**List[ManaV2B2bSiteInformation]**](ManaV2B2bSiteInformation.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_consumer_post_response import V1ExtranetsB2bConsumerPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bConsumerPostResponse from a JSON string
v1_extranets_b2b_consumer_post_response_instance = V1ExtranetsB2bConsumerPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bConsumerPostResponse.to_json())

# convert the object into a dict
v1_extranets_b2b_consumer_post_response_dict = v1_extranets_b2b_consumer_post_response_instance.to_dict()
# create an instance of V1ExtranetsB2bConsumerPostResponse from a dict
v1_extranets_b2b_consumer_post_response_from_dict = V1ExtranetsB2bConsumerPostResponse.from_dict(v1_extranets_b2b_consumer_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


