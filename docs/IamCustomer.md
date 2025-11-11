# IamCustomer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_email** | **str** |  | [optional] 
**company_name** | **str** |  | [optional] 
**counts** | [**IamCounts**](IamCounts.md) |  | [optional] 
**enterprise_id** | **int** |  | [optional] 
**impersonation_enabled** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.iam_customer import IamCustomer

# TODO update the JSON string below
json = "{}"
# create an instance of IamCustomer from a JSON string
iam_customer_instance = IamCustomer.from_json(json)
# print the JSON string representation of the object
print(IamCustomer.to_json())

# convert the object into a dict
iam_customer_dict = iam_customer_instance.to_dict()
# create an instance of IamCustomer from a dict
iam_customer_from_dict = IamCustomer.from_dict(iam_customer_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


