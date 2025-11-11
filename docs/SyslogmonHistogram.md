# SyslogmonHistogram


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**count** | **int** |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.syslogmon_histogram import SyslogmonHistogram

# TODO update the JSON string below
json = "{}"
# create an instance of SyslogmonHistogram from a JSON string
syslogmon_histogram_instance = SyslogmonHistogram.from_json(json)
# print the JSON string representation of the object
print(SyslogmonHistogram.to_json())

# convert the object into a dict
syslogmon_histogram_dict = syslogmon_histogram_instance.to_dict()
# create an instance of SyslogmonHistogram from a dict
syslogmon_histogram_from_dict = SyslogmonHistogram.from_dict(syslogmon_histogram_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


