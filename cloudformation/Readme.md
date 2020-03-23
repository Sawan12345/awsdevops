# CloudFormation

This is readme for cloudformation 

Here are other python based tools to generate template:
- https://github.com/cloudtools/troposphere
- https://github.com/cloudtools/stacker


Cloud Formation Intrinsic Functions

	- Fn:Base64  (stringValue)
	- Fn:FindInMap (nameofMap,ref,param)
	- Ref  (value of parameter or resource)
	- Fn:Cidr ipblock,count,cidrBits
	- Fn:GetAttr
	- Fn:GetAZs
	- Fn:ImportValue  (used to cross reference stacks)
	- Fn:Join (join values)
	- Fn:Select select an object from list
	- Fn:Split (split values)
	- Fn:Sub (substitute)
	- Fn:Transform (macro for custom processing)

Conditional Functions

	- Fn:And
	- Fn:Equals
	- Fn:If
	- Fn:Not
	- Fn:Or

Wait Conditions (EC2 and Autoscaling service support only)

	- DependsOn
	- CreationPolicy
	- Wait Condition Handlers
	- WaitHandle
	- WaitCondition
	- Handle

Resource Type Ref:
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-template-resource-type-ref.html
