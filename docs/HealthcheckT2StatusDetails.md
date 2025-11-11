# HealthcheckT2StatusDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip_address** | **str** |  | [optional] 
**state** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.healthcheck_t2_status_details import HealthcheckT2StatusDetails

# TODO update the JSON string below
json = "{}"
# create an instance of HealthcheckT2StatusDetails from a JSON string
healthcheck_t2_status_details_instance = HealthcheckT2StatusDetails.from_json(json)
# print the JSON string representation of the object
print(HealthcheckT2StatusDetails.to_json())

# convert the object into a dict
healthcheck_t2_status_details_dict = healthcheck_t2_status_details_instance.to_dict()
# create an instance of HealthcheckT2StatusDetails from a dict
healthcheck_t2_status_details_from_dict = HealthcheckT2StatusDetails.from_dict(healthcheck_t2_status_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


