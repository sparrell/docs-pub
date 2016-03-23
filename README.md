## Actions
All OpenC2 commands start with an ACTION which indicates the type of command to perform such as gather and convey information, control activities and devices, and control permissions and access.  The range of options and potential impact on the information system associated with a particular ACTION is a function of the ACTUATOR.  For cases that involve multiple options for an ACTION, modifiers are used.

[Action Details](actions.md)

## Target Vocabulary
The TARGET is the object of the ACTION (or conversely, the ACTION is performed on the TARGET).  OpenC2 will utilize pre-existing data models to provide the namespace for the TARGETs.  Initially, OpenC2 will reference the applicable CybOX objects in the OpenC2 TARGET namespace. However, OpenC2 can be supported by custom or other data models.  Refer to the following table for a summary of the OpenC2 TARGET Namespaces.

[Target Details](targets.md)

## Actuator Vocabulary
An ACTUATOR is the entity that puts command and control into motion or action. The ACTUATOR executes the ACTION on the TARGET. To the extent possible, OpenC2 will leverage existing standardized data models for ACTUATORs (e.g., IETF Security Automation and Continuous Monitoring, Information Security Continuous Monitoring (ISCM)).  Refer to the following table for a summary of the OpenC2 ACTUATOR Namespaces.

[Actuator Details](actuators.md)

## Modifier Vocabulary
Modifiers provide additional information about the action such as time, periodicity, duration, and location. Modifiers can denote the when, where, and how aspects of an action. The modifier can also be used to convey the need for additional status information about the execution of an action.  Modifiers can be used to indicate whether the actuator should explicitly acknowledge receipt of the command, respond upon completion of the execution of the command, or provide some other status information. The requested status/information will be carried in a RESPONSE. Refer to Section 4.6.

[Modifier Details](modifiers.md)

