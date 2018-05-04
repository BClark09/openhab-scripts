### Addons

The following add-ons are newly introduced with the 2.3 release:

 - AzureIOT
 - innogy
 - Seneye
 - velbus
 - Misc

The following changes were done on existing addons:


### 2.x Addons

| Binding | Type | Issue# | Change |
|-|-|-|-|
| | | | |
| **Zigbee** | *Enhancements* | [#120](https://github.com/openhab/org.openhab.binding.zigbee/pull/120) | Add AIS CIE System converter into converter factory |
| | | [#156](https://github.com/openhab/org.openhab.binding.zigbee/pull/156) | Add battery voltage channel |
| | | [#132](https://github.com/openhab/org.openhab.binding.zigbee/pull/132) | Add configuration and support for Ember concentrator |
| | | [#98](https://github.com/openhab/org.openhab.binding.zigbee/pull/98) | Add handleRemoval handler to send leave command to device |
| | | [#99](https://github.com/openhab/org.openhab.binding.zigbee/pull/99) | Add power converter to display power readings |
| | | [#66](https://github.com/openhab/org.openhab.binding.zigbee/pull/66) | Additions: Configuration, Polling, Channel Consolidation |
| | | [#121](https://github.com/openhab/org.openhab.binding.zigbee/pull/121) | Color converter enhancements to support CT and Attribute discovery |
| | | [#96](https://github.com/openhab/org.openhab.binding.zigbee/pull/96) | Improve network performance during discovery |
| | | [#95](https://github.com/openhab/org.openhab.binding.zigbee/pull/95) | Improve property discovery performance |
| | | [#177](https://github.com/openhab/org.openhab.binding.zigbee/pull/177) | Remove ColorHelper and use HSBType methods for color conversion |
| | *Bug Fixes* | [#89](https://github.com/openhab/org.openhab.binding.zigbee/pull/89) | Update libraries to fix Telegesis / Ember concurrent queue issue |
| | | [#91](https://github.com/openhab/org.openhab.binding.zigbee/pull/91) | Update ZigBee Property Discovery to update inbox with manufacturer and model |
| | | | |
| **ZWave** | *Enhancements* | [#871](https://github.com/openhab/org.openhab.binding.zwave/pull/871) |  Add support for including controllers |
| | | [#846](https://github.com/openhab/org.openhab.binding.zwave/pull/846) | Don't initialise sleeping devices that are already initialised |
| | *Bug Fixes* | [#782](https://github.com/openhab/org.openhab.binding.zwave/pull/782) | Fix error in binary switch converter when NOGET is true |
| | | [#854](https://github.com/openhab/org.openhab.binding.zwave/pull/854) | Fix error with inclusion transaction timeout |
| | *Enhancements* | [#787](https://github.com/openhab/org.openhab.binding.zwave/pull/787) | Refactor inclusion code into separate class for readability and testing |

### 1.x Addons

| Binding | Type | Issue# | Change |
|-|-|-|-|
| | | | |
| **Swegonventilation** | *Enhancements* | [#5561](https://github.com/openhab/openhab1-addons/pull/5561) |  Added value cache to minimize item updates |
| | | | |
| **Bticino** | *Enhancements* | [#5486](https://github.com/openhab/openhab1-addons/pull/5486) |  Several enhancements for Heating Control / Door Lock / Shutter / Dimmer |
| | | | |
| **CalDav** | *Bug Fixes* | [#5391](https://github.com/openhab/openhab1-addons/pull/5391) |  Fix NPE during updateItemsForEvent |
| | | | |
| **CUL transport** | *Enhancements* | [#5329](https://github.com/openhab/openhab1-addons/pull/5329) |  Throttle commands, which are sent to the CUL |
| | | | |
| **CUL** | *Bug Fixes* | [#5434](https://github.com/openhab/openhab1-addons/pull/5434) |  Bugfix issue 5433 |
| | | | |
| **Documentation** | *Enhancements* | [#5556](https://github.com/openhab/openhab1-addons/pull/5556) |  Fix all incorrect usages of 'can not' |
| | | | |
| **Epsonprojector** | *Enhancements* | [#5446](https://github.com/openhab/openhab1-addons/pull/5446) |  Fixed timeouts to meet specification |
| | | [#5505](https://github.com/openhab/openhab1-addons/pull/5505) |  Improved connection stability |
| | | | |
| **Fritzboxtr064** | *Enhancements* | [#5443](https://github.com/openhab/openhab1-addons/pull/5443) |  Close connection and re-init in case of failure (#5331) |
| | *Bug Fixes* | [#5536](https://github.com/openhab/openhab1-addons/pull/5536) |  Fix the ArrayIndexOutOfBoundsException |
| | | | |
| **IHC** | *Enhancements* | [#5444](https://github.com/openhab/openhab1-addons/pull/5444) |  NPE fix |
| | | | |
| **Intertechno** | *Enhancements* | [#5316](https://github.com/openhab/openhab1-addons/pull/5316) |  Added support for Intertechno V3 protocol |
| | | | |
| **JDBC persistence** | *Bug Fixes* | [#5394](https://github.com/openhab/openhab1-addons/pull/5394) |  Fix storage of time values for DATETIMEITEM. |
| | | | |
| **KNX** | *Enhancements* | [#5513](https://github.com/openhab/openhab1-addons/pull/5513) |  Added file description and specific mappings |
| | | [#5277](https://github.com/openhab/openhab1-addons/pull/5277) |  Update generic KNXCoreTypeMapper |
| | | | |
| **LgTv** | *Bug Fixes* | [#5393](https://github.com/openhab/openhab1-addons/pull/5393) |  Trap IllegalArgumentException during deactivate() |
| | | | |
| **MQTT** | *Enhancements* | [#5519](https://github.com/openhab/openhab1-addons/pull/5519) |  Allow broker URL and clientID to be modified while running |
| | *Bug Fixes* | [#5554](https://github.com/openhab/openhab1-addons/pull/5554) |  Improve error handling for config processing |
| | | | |
| **MystromEcoPower** | *Enhancements* | [#5482](https://github.com/openhab/openhab1-addons/pull/5482) |  Add feature and config files to support OH2 compatibility |
| | | | |
| **Neohub** | *Enhancements* | [#5439](https://github.com/openhab/openhab1-addons/pull/5439) |  Add Holiday and HolidayDays fields |
| | | | |
| **Nest** | *Enhancements* | [#5563](https://github.com/openhab/openhab1-addons/pull/5563) |  January 2018 API update |
| | | | |
| **Novelanheatpump** | *Enhancements* | [#5503](https://github.com/openhab/openhab1-addons/pull/5503) |  Add new simple state without time |
| | | | |
| **OEM binding** | *Enhancements* | [#5340](https://github.com/openhab/openhab1-addons/pull/5340) |  - direct serial port support |
| | | | |
| **Panstamp** | *Enhancements* | [#5489](https://github.com/openhab/openhab1-addons/pull/5489) |  binding fixes |
| | | | |
| **Pilight** | *Bug Fixes* | [#5464](https://github.com/openhab/openhab1-addons/pull/5464) |  Fix NullPointerExceptions in the checkItemState() method |
| | | | |
| **Pushbullet** | *Enhancements* | [#5516](https://github.com/openhab/openhab1-addons/pull/5516) |  Added ability to push notes to a channel |
| | | | |
| **Pushover** | *Enhancements* | [#5483](https://github.com/openhab/openhab1-addons/pull/5483) |  Added Receipts and Callback API for handling of emergency-priority notifications |
| | | [#5527](https://github.com/openhab/openhab1-addons/pull/5527) |  added support for attachment/image push |
| | | | |
| **Serial** | *Bug Fixes* | [#5543](https://github.com/openhab/openhab1-addons/pull/5543) |  Fix configuration parsing error in the serial binding |
| | | | |
| **Telegram Action** | *Bug Fixes* | [#5418](https://github.com/openhab/openhab1-addons/pull/5418) |  Fix sending of photos with authentication |
| | *Enhancements* | [#5504](https://github.com/openhab/openhab1-addons/pull/5504) |  Send base64 image with Telegram message |
| | | | |
| **UCPRelayboard** | *Enhancements* | [#5465](https://github.com/openhab/openhab1-addons/pull/5465) |  Add configurations for OH2 compatibility |
| | | | |
| **Misc** | *Bug Fixes* | [#5421](https://github.com/openhab/openhab1-addons/pull/5421) | Fatek PLC Switch item with two registers |
