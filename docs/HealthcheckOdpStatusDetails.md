# HealthcheckOdpStatusDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip_address** | **str** |  | [optional] 
**state** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.healthcheck_odp_status_details import HealthcheckOdpStatusDetails

# TODO update the JSON string below
json = "{}"
# create an instance of HealthcheckOdpStatusDetails from a JSON string
healthcheck_odp_status_details_instance = HealthcheckOdpStatusDetails.from_json(json)
# print the JSON string representation of the object
print(HealthcheckOdpStatusDetails.to_json())

# convert the object into a dict
healthcheck_odp_status_details_dict = healthcheck_odp_status_details_instance.to_dict()
# create an instance of HealthcheckOdpStatusDetails from a dict
healthcheck_odp_status_details_from_dict = HealthcheckOdpStatusDetails.from_dict(healthcheck_odp_status_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


