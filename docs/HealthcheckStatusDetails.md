# HealthcheckStatusDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp_core_state** | **List[bool]** |  | [optional] 
**bgp_odp_state** | **List[bool]** |  | [optional] 
**core_tunnel_state** | **List[bool]** |  | [optional] 
**device_id** | **int** |  | [optional] 
**enterprise_id** | **int** |  | [optional] 
**gnmi_state** | **bool** |  | [optional] 
**ipsec_core_status** | **str** |  | [optional] 
**ipsec_odp_status** | **str** |  | [optional] 
**odp_status** | [**HealthcheckOdpStatusDetails**](HealthcheckOdpStatusDetails.md) |  | [optional] 
**odp_tunnel_state** | **List[bool]** |  | [optional] 
**onboarding_status** | [**HealthcheckOnboardingStatusDetails**](HealthcheckOnboardingStatusDetails.md) |  | [optional] 
**t2_status** | [**HealthcheckT2StatusDetails**](HealthcheckT2StatusDetails.md) |  | [optional] 
**topo_gw_state** | **str** |  | [optional] 
**tt_tunnel_state** | **List[bool]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.healthcheck_status_details import HealthcheckStatusDetails

# TODO update the JSON string below
json = "{}"
# create an instance of HealthcheckStatusDetails from a JSON string
healthcheck_status_details_instance = HealthcheckStatusDetails.from_json(json)
# print the JSON string representation of the object
print(HealthcheckStatusDetails.to_json())

# convert the object into a dict
healthcheck_status_details_dict = healthcheck_status_details_instance.to_dict()
# create an instance of HealthcheckStatusDetails from a dict
healthcheck_status_details_from_dict = HealthcheckStatusDetails.from_dict(healthcheck_status_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


