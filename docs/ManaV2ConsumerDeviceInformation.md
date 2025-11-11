# ManaV2ConsumerDeviceInformation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**last_updated** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**site** | **int** |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_consumer_device_information import ManaV2ConsumerDeviceInformation

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ConsumerDeviceInformation from a JSON string
mana_v2_consumer_device_information_instance = ManaV2ConsumerDeviceInformation.from_json(json)
# print the JSON string representation of the object
print(ManaV2ConsumerDeviceInformation.to_json())

# convert the object into a dict
mana_v2_consumer_device_information_dict = mana_v2_consumer_device_information_instance.to_dict()
# create an instance of ManaV2ConsumerDeviceInformation from a dict
mana_v2_consumer_device_information_from_dict = ManaV2ConsumerDeviceInformation.from_dict(mana_v2_consumer_device_information_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


