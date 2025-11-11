# AlertserviceAlertRecord


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**acknowledged_list** | **List[str]** |  | [optional] 
**acknowledgement_reason** | **str** | Reason put by users when acknowledged | [optional] 
**alert_body** | **str** | Latest event(s) behind the alert (required) | [optional] 
**alert_id** | **str** | Unique id of the alert (required) | [optional] 
**allow_listed** | **bool** | whether entity in alert is put in allowlist/excludelist, disabling alert (required) | [optional] 
**children_alert_list** | [**AlertserviceChildrenAlertListResponse**](AlertserviceChildrenAlertListResponse.md) |  | [optional] 
**descendant_present** | **bool** | Whether or not descendants are present (required) | [optional] 
**device_id** | **str** | Internal device id to navigate to troubleshooting | [optional] 
**end_time** | **int** | When this alert was last seen as a continuation (required) | [optional] 
**enterprise_id** | **str** | Internal enterprise id to navigate to troubleshooting (required) | [optional] 
**entity** | **str** | Entity that triggered the alert. Edge, core, etc. (required) | [optional] 
**interface_name** | **str** | Device Interface Name | [optional] 
**mute_listed** | **bool** | whether entity in alert is put in notification mutelist (required) | [optional] 
**notification_created** | **bool** | whether notification exists for this rule (required) | [optional] 
**occurrences** | **int** | Number of times alert was raised as a continuation (required) | [optional] 
**peer_device_id** | **str** | peer device id | [optional] 
**peer_interface_name** | **str** | Peer Interface Name | [optional] 
**peer_name** | **str** | Peer Name | [optional] 
**plane** | **str** | Plane of the rule generating the alert (required) | [optional] 
**reason** | **str** | Reason why alert was generated (required) | [optional] 
**recommendation** | **str** | Recommendation to recover from alert (required) | [optional] 
**rule_id** | **str** | Unique id of the rule generating the alert (required) | [optional] 
**severity** | **str** | Severity of the rule behind the alert (required) | [optional] 
**site_id** | **str** | Internal site id to navigate to troubleshooting | [optional] 
**start_time** | **int** | When this alert was first triggered (required) | [optional] 
**status** | **str** | Status of the alert whether active or inactive (required) | [optional] 
**troubleshooting_disabled_reason** | **str** | Reason to not navigate to troubleshooting | [optional] 
**troubleshooting_enabled** | **bool** | Navigate or not navigate to troubleshooting dashboard (required) | [optional] 
**tunnel_interface_name** | **str** | Tunnel Interface Name | [optional] 
**type** | **str** | Type of alert (required) | [optional] 

## Example

```python
from graphiant_sdk.models.alertservice_alert_record import AlertserviceAlertRecord

# TODO update the JSON string below
json = "{}"
# create an instance of AlertserviceAlertRecord from a JSON string
alertservice_alert_record_instance = AlertserviceAlertRecord.from_json(json)
# print the JSON string representation of the object
print(AlertserviceAlertRecord.to_json())

# convert the object into a dict
alertservice_alert_record_dict = alertservice_alert_record_instance.to_dict()
# create an instance of AlertserviceAlertRecord from a dict
alertservice_alert_record_from_dict = AlertserviceAlertRecord.from_dict(alertservice_alert_record_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


