# V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**security_rules** | [**List[ManaV2SecurityPolicyRuleRow]**](ManaV2SecurityPolicyRuleRow.md) |  | [optional] 
**traffic_rules** | [**List[ManaV2TrafficPolicyRuleRow]**](ManaV2TrafficPolicyRuleRow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_monitoring_traffic_security_policy_post_response import V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse from a JSON string
v1_extranets_monitoring_traffic_security_policy_post_response_instance = V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse.to_json())

# convert the object into a dict
v1_extranets_monitoring_traffic_security_policy_post_response_dict = v1_extranets_monitoring_traffic_security_policy_post_response_instance.to_dict()
# create an instance of V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse from a dict
v1_extranets_monitoring_traffic_security_policy_post_response_from_dict = V1ExtranetsMonitoringTrafficSecurityPolicyPostResponse.from_dict(v1_extranets_monitoring_traffic_security_policy_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


