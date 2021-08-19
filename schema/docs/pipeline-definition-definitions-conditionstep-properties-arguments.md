# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Arguments
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## Arguments Type

`object` ([Details](pipeline-definition-definitions-conditionstep-properties-arguments.md))

# Arguments Properties

| Property                  | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                         |
| :------------------------ | :------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Conditions](#conditions) | `array` | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-conditionstep-properties-arguments-properties-conditions.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Arguments/properties/Conditions") |
| [IfSteps](#ifsteps)       | `array` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-conditionstep-properties-arguments-properties-ifsteps.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Arguments/properties/IfSteps")       |
| [ElseSteps](#elsesteps)   | `array` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-conditionstep-properties-arguments-properties-elsesteps.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Arguments/properties/ElseSteps")   |

## Conditions



`Conditions`

*   is required

*   Type: an array of merged types ([Details](pipeline-definition-definitions-conditionstep-properties-arguments-properties-conditions-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-conditionstep-properties-arguments-properties-conditions.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Arguments/properties/Conditions")

### Conditions Type

an array of merged types ([Details](pipeline-definition-definitions-conditionstep-properties-arguments-properties-conditions-items.md))

## IfSteps



`IfSteps`

*   is optional

*   Type: an array of merged types ([Details](pipeline-definition-definitions-conditionstep-properties-arguments-properties-ifsteps-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-conditionstep-properties-arguments-properties-ifsteps.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Arguments/properties/IfSteps")

### IfSteps Type

an array of merged types ([Details](pipeline-definition-definitions-conditionstep-properties-arguments-properties-ifsteps-items.md))

## ElseSteps



`ElseSteps`

*   is optional

*   Type: an array of merged types ([Details](pipeline-definition-definitions-conditionstep-properties-arguments-properties-elsesteps-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-conditionstep-properties-arguments-properties-elsesteps.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Arguments/properties/ElseSteps")

### ElseSteps Type

an array of merged types ([Details](pipeline-definition-definitions-conditionstep-properties-arguments-properties-elsesteps-items.md))