# AlertserviceAllowAlertNotifcationListRecord


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**create_time** | **int** |  | [optional] 
**device_interface** | **str** |  | [optional] 
**device_name** | **str** |  | [optional] 
**enterprise_name** | **str** |  | [optional] 
**entity_id** | **str** |  | [optional] 
**is_wan_circuit** | **bool** |  | [optional] 
**note_text** | **str** |  | [optional] 
**peer_device_interface** | **str** |  | [optional] 
**peer_device_name** | **str** |  | [optional] 
**rule_id** | **str** |  | [optional] 
**rule_name** | **str** |  | [optional] 
**site_name** | **str** |  | [optional] 
**vrf_id** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.alertservice_allow_alert_notifcation_list_record import AlertserviceAllowAlertNotifcationListRecord

# TODO update the JSON string below
json = "{}"
# create an instance of AlertserviceAllowAlertNotifcationListRecord from a JSON string
alertservice_allow_alert_notifcation_list_record_instance = AlertserviceAllowAlertNotifcationListRecord.from_json(json)
# print the JSON string representation of the object
print(AlertserviceAllowAlertNotifcationListRecord.to_json())

# convert the object into a dict
alertservice_allow_alert_notifcation_list_record_dict = alertservice_allow_alert_notifcation_list_record_instance.to_dict()
# create an instance of AlertserviceAllowAlertNotifcationListRecord from a dict
alertservice_allow_alert_notifcation_list_record_from_dict = AlertserviceAllowAlertNotifcationListRecord.from_dict(alertservice_allow_alert_notifcation_list_record_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


