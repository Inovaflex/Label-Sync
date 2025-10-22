# Label-Sync

Keeps entity labels in sync with their device labels when the device has a specific label (default: "sync"). 
Adds missing labels and removes labels that no longer exist on the device.

# Install
/config/blueprints/automation/<your favorite directory>/label_sync.yaml
Create a label to use with syncing an place it on each device (not entity) that you want to make sync from.

# Create
Create a automation based on the blueprint. Choosee a labelname for the sync (default: 'sync'). 
