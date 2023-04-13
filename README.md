# Home Assistant Blueprint: Group Sync
This Home Assistant blueprint allows you to sync the state of multiple switches, turning one switch on when another is turned on, and vice versa. It's perfect for scenarios where you want to keep two or more switches in sync, such as controlling lights in different rooms, or managing devices in a smart home setup.

## Usage
1. Copy the blueprint code from the group_sync_blueprint.yaml file into your Home Assistant blueprints folder (mine is ../blueprints/automation/homeassistant).
2. Create a new automation in your Home Assistant configuration using the blueprint.
3. Configure the blueprint by specifying the switches you want to sync. You can select multiple switches using the entity selector, which will be used as the triggers for the automation.
4. Save and enable the automation.

From now on, whenever any of the specified switches are turned on or off, the other switches will be synced accordingly.

## Wait Template
Wait Template: Adds a delay of 0.5 seconds to ensure stable state changes.
If something isn't working try to reduce or increase both values.

## Credits
This blueprint is inspired by the Home Assistant community and is made possible by the contributions of the open-source community.
