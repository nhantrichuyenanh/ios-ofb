# iOS Order of Business

## Control Center
### ♥
| Airplane Mode | Cellular Data |
| :--- | :--- |
| VPN | Open Access Point* |
| Bluetooth | Wi-Fi |
| Disable bluetooth* | Disable Wi-Fi* |
| AirDrop | Maximum Capacity* |
| Change display colors* | Brightness |
| Reduce White Point | Volume |
| Reduce Motion | Reduce Transparency |

### ●
| Calculator | Translate |
| :--- | :--- |
| Timer | Screen Recording |
| Flashlight | Sound Recognition |
| Silent Mode | Low Power Mode |
| Orientation | Focus |
| Recognize Music | Voice Memo |
| Open Claude | NotebookLM |
| [Empty] | [Empty] |


## * Shortcut
### Library → All Shortcuts
>[!NOTE]
> You don't have to necessarily create these shortcuts. You could make your own or use [ThioJoe's](https://www.youtube.com/watch?v=3gq4J2zr07s "ThioJoe"), which I find some of them useful.
- Open Access Point: Open **prefs:root=MOBILE_DATA_SETTINGS_ID**
- Disable Bluetooth: **Turn** Bluetooth **Off**
- Disable Wi-Fi: **Turn** Wi-Fi **Off**
- Maximum Capacity: Open **prefs:root=BATTERY_USAGE**
- Change display colors: **Toggle** color filters

### Automation
- When any alarm goes off
  - Set **Media** volume to **100%**
  - **Turn** Silent Mode **Off**
  - Set **Ringtone** volume to **100%**
- When Waking Up:
  - **Turn** White Point **Off**
  - **Turn** Reduce Motion **Off**
  - **Turn** Reduce Transparency **Off**
  - **Turn** color filters **Off**
  - Set brightness to **85%**
- When Wind Down starts:
  - **Turn** White Point **On**
  - **Turn** Reduce Motion **On**
  - **Turn** Reduce Transparency **On**
  - **Turn** color filters **On**
  - Set brightness to **50%**
- When [NAME] is connected to power:
  - Set brightness to **0%**
  - **Turn** Airplane Mode **On**
  - **Turn** Cellular Data **Off**
  - **Turn** Wi-Fi **Off**
  - **Turn** Bluetooth **Off**
  - **Turn** Low Power Mode **On**
- When [NAME] is disconnected from power:
  - Set brightness to **85%**
  - **Turn** Airplane Mode **Off**
  - **Turn** Cellular Data **Off**
  - **Turn** Wi-Fi **On**
  - **Turn** Bluetooth **Off**
  - **Turn** Low Power Mode **On**
