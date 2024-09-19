| [Home](/README.md) | 
|--------------------------------------------|

# Contents

The **SOC Simulator** solution pack contains following resources.

## Connector

| Connector               | Description                                                                                                            |
|:------------------------|:-----------------------------------------------------------------------------------------------------------------------|
| FortiSOAR SOC Simulator | Simulates a SOC environment and creates various scenarios-based artifacts such as alerts, incidents, etc. in FortiSOAR |

>[!Warning]
>After deployment, this solution pack installs/upgrades the *FortiSOAR SOC Simulator* connector.

## Module Schema

| Module Schema | Description                                                                           |
|:--------------|:--------------------------------------------------------------------------------------|
| Scenario      | A schema for listing scenarios included with other solution packs that are installed. |

## Playbook Collection

|02 - Use Case - SOC Simulator|
|:--                          |

| Playbook Name                | Description                                                                             |
|:-----------------------------|:----------------------------------------------------------------------------------------|
| Reset Scenario               | Deletes created alerts and related records                                              |
| Reset Scenario - Get Correlated Records<sup>New</sup> | Fetches all the correlated records of the demo record created for the simulation |
| Run Scenario                 | Executes a scenario and create its related records triggered from the 'Scenario' record |
| Run Scenario - Create Alerts | Creates records related to a scenario                                                   |
| Run Selected Scenario        | Executes a scenario and create related records triggered from the 'Alerts' page         |

>[!Warning]
>Modifying these playbooks may break scenario simulation functionality. Hence, we recommend that you exercise caution.
