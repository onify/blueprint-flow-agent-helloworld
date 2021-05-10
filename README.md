![Onify Blueprints](https://files.readme.io/8ba3f14-onify-blueprints-logo.png)

[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)

# Onify Blueprint: Flow and Agent HelloWorld

Here is an example how to execute a Onify Agent task (script) based on PowerShell. This also shows how we can use the result of the script to continue the process via a simple gateway in BPMN. Enjoy!

![alt text](flow.png "Flow")

## Requirements

* Onify Hub API 2.3.0 or later
* Onify Flow license
* Camunda Modeler 4.4 or later 
* Onify Agent with PowerShell

## Included

* 1 x Resources (agent)
* 1 x Flows

## Setup

### Resources

1. Copy `HelloWorld.ps1` to Onify Agent scripts folder

### Flows

#### Deploy

1. Open `flow-agent-helloworld.bpmn` in Camunda Modeler
2. Click `Deploy current diagram` and follow the steps

#### Run 

To test and run the flow, click `Start current diagram`

## Support

* Community/forum: https://support.onify.co/discuss
* Documentation: https://support.onify.co/docs
* Support and SLA: https://support.onify.co/docs/get-support

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
