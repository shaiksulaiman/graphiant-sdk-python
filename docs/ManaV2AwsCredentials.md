# ManaV2AwsCredentials


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**access_key_id** | **str** |  | [optional] 
**secret_access_key** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_aws_credentials import ManaV2AwsCredentials

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2AwsCredentials from a JSON string
mana_v2_aws_credentials_instance = ManaV2AwsCredentials.from_json(json)
# print the JSON string representation of the object
print(ManaV2AwsCredentials.to_json())

# convert the object into a dict
mana_v2_aws_credentials_dict = mana_v2_aws_credentials_instance.to_dict()
# create an instance of ManaV2AwsCredentials from a dict
mana_v2_aws_credentials_from_dict = ManaV2AwsCredentials.from_dict(mana_v2_aws_credentials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


