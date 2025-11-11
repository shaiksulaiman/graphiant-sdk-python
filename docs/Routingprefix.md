# Routingprefix


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**afi_safi_name** | **str** |  | [optional] 
**prefix_rcvd** | **int** |  | [optional] 
**prefix_sent** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.routingprefix import Routingprefix

# TODO update the JSON string below
json = "{}"
# create an instance of Routingprefix from a JSON string
routingprefix_instance = Routingprefix.from_json(json)
# print the JSON string representation of the object
print(Routingprefix.to_json())

# convert the object into a dict
routingprefix_dict = routingprefix_instance.to_dict()
# create an instance of Routingprefix from a dict
routingprefix_from_dict = Routingprefix.from_dict(routingprefix_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


