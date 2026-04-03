# Changelog

## v2.0.1

### Changes
- Fixed `TypeError: this.controller.instances is not iterable` when used on Clusterio alpha 23. Hornwitser/server_select#5
- Removed async logic on the controller side when updating the server list. Hornwitser/server_select#8
