# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/ModelClientConfig
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## ModelClientConfig Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-modelclientconfig.md))

# ModelClientConfig Properties

| Property                                                    | Type   | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                   |
| :---------------------------------------------------------- | :----- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [InvocationsMaxRetries](#invocationsmaxretries)             | Merged | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/ModelClientConfig/properties/InvocationsMaxRetries")       |
| [InvocationsTimeoutInSeconds](#invocationstimeoutinseconds) | Merged | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/ModelClientConfig/properties/InvocationsTimeoutInSeconds") |

## InvocationsMaxRetries



`InvocationsMaxRetries`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/ModelClientConfig/properties/InvocationsMaxRetries")

### InvocationsMaxRetries Type

merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

one (and only one) of

*   [Untitled integer in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## InvocationsTimeoutInSeconds



`InvocationsTimeoutInSeconds`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/ModelClientConfig/properties/InvocationsTimeoutInSeconds")

### InvocationsTimeoutInSeconds Type

merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

one (and only one) of

*   [Untitled integer in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")