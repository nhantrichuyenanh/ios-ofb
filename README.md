# iOS Order of Business

## Control Center
### ♥
| Airplane Mode | Cellular Data |
| :--- | :--- |
| VPN | Open Access Point* |
| Bluetooth | Wi-Fi |
| Disable bluetooth* | Disable Wi-Fi* |
| AirDrop | Change Wi-Fi* |
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
| Open Claude | Type prompt |
| Open Le Chat | Open Grok |


## * Shortcut
### Library → All Shortcuts
- Open Access Point: Open **prefs:root=INTERNET_TETHERING**
- Disable Bluetooth: **Turn** Bluetooth **Off**
- Disable Wi-Fi: **Turn** Wi-Fi **Off**
- Change Wi-Fi:
  - **Toggle** Wi-Fi
  - **Toggle** Wi-Fi
- Change display colors: **Toggle** color filters

### Automation
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
- When battery level is 50%: **Turn** Low Power Mode **On**
- When battery level is 90%:
  - **Turn** Low Power Mode **Off**
  - Set brightness to **100%**
- When battery level rises above 80%:
  - **Turn** Low Power Mode **On**
  - Set brightness to **0%**
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
