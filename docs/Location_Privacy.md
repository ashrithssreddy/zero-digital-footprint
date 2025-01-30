# Location Privacy
## 1. Device-Level Protections

### Smartphones & Tablets

- **Limit GPS Use:** Go to settings → Location → Turn off GPS when not needed. On Android, enable "Device Only" mode to limit GPS to onboard sensors.
- [Advanced] **Use Location Adjustment Tools (If Needed):** Apps like [GPS Emulator (Android)](https://play.google.com/store/apps/details?id=com.rosteam.gpsemulator) or [iTools (iOS)](https://thinkskysoft.com/itools/) can modify location settings when necessary.
- **Remove Geotags from Photos:** Use apps like [ObscuraCam (Android)](https://guardianproject.info/apps/obscuracam/) or [Metapho (iOS)](https://apps.apple.com/us/app/metapho/id914457352) to strip metadata before sharing images.
- **Manage App Permissions:** On Android, go to Settings → Apps → Permissions → Location and restrict access. On iOS, go to Settings → Privacy → Location Services.
- [Advanced] **Consider a Privacy-Focused OS:** [GrapheneOS](https://grapheneos.org/) or [CalyxOS](https://calyxos.org/) for Android provide better control. On iOS, restrict background location tracking in settings.

### Laptops & Desktops

- **Disable Location Services:** Turn off system-wide tracking:
  - Windows: Settings → Privacy & Security → Location → Toggle off.
  - macOS: System Settings → Privacy & Security → Location Services → Disable.
  - Linux: Use `sudo systemctl stop geoclue` (depends on distribution).
- **Use a Privacy-Focused Browser:** Install [Brave](https://brave.com/) or [Firefox](https://www.mozilla.org/en-US/firefox/new/) with privacy extensions such as [NoScript](https://noscript.net/), [uBlock Origin](https://ublockorigin.com/), and [Privacy Badger](https://privacybadger.org/).
- [Advanced] **Mask Your IP Address:** Use VPN providers like [Mullvad](https://mullvad.net/), [ProtonVPN](https://protonvpn.com/), or [IVPN](https://www.ivpn.net/) and connect to different regions to vary your location footprint. Some VPNs allow multi-hop connections for added privacy. Additionally, using [Tor](https://www.torproject.org/) with bridges can help obscure your real location further.

## 2. Network-Level Protections

### Wi-Fi & ISP Tracking

- **Be Cautious with Public Wi-Fi:** If using it, connect via a VPN (Mullvad, ProtonVPN) or Tor.
- [Advanced] **Randomize MAC Address:** Prevent tracking across networks:
  - Android: Developer Options → Randomized MAC.
  - iOS: Settings → Wi-Fi → Private Address.
  - macOS: System Settings → Network → Wi-Fi → Click the network → Enable 'Limit IP Address Tracking'.
  - Windows: Use `netsh wlan set randomization=enabled` in Command Prompt.
  - Linux: Use [macchanger](https://github.com/alobbs/macchanger) or NetworkManager.
- [Advanced] **Use a VPN Router:** Travel routers like [GL.iNet](https://www.gl-inet.com/) with VPN support help encrypt connections.
- **Turn Off Bluetooth & NFC When Not Needed:** These can be used for tracking in public places.

### Cellular Networks

- [Advanced] **Use a Separate SIM for Privacy:** Consider a prepaid SIM that isn't tied to your identity.
- [Advanced] **Minimize Cellular Triangulation:** If privacy is a concern, disable mobile data when not in use.
- [Advanced] **Use Signal-Blocking Measures:** A Faraday bag can block signals when extra privacy is needed.

## 3. Online Service Strategies

### Browsing & Online Accounts

- **Use a VPN or Tor:** Helps prevent tracking through your IP address.
- **Disable Location-Based Services in Search Engines:** Google, Bing, and others allow you to turn off location-based search results.
- **Use Privacy-Focused Search Engines:** Try [Startpage](https://www.startpage.com/), [Searx](https://searx.github.io/), or [DuckDuckGo](https://duckduckgo.com/) instead of Google.

### Social Media & Apps

- **Avoid Sharing Location on Posts:** Many platforms let you remove location tags from photos and status updates.
- [Advanced] **Use Separate Accounts for Different Needs:** Reduce personal location data exposure by keeping work and private accounts separate.
- **Disable Location Tracking in Apps:** [Google Maps](https://www.google.com/maps), [Facebook](https://www.facebook.com/), and [Snapchat](https://www.snapchat.com/) often store your location history—review and turn these off.

## 4. Other Considerations

### Travel & Commuting

- **Use Offline Maps:** Apps like [OsmAnd](https://osmand.net/) or [Organic Maps](https://organicmaps.app/) work well without internet access.
- **Consider Alternatives to Ride-Sharing Apps:** Public transport or taxis paid in cash avoid linked location data.
- [Advanced] **Avoid Smart Transit Cards if Necessary:** Single-use tickets offer more anonymity.
- [Advanced] **Change Travel Patterns Occasionally:** Avoid predictable movement habits.

## 5. Additional Steps for Privacy-Conscious Users

- [Advanced] **Use a De-Googled Phone:** Devices running [GrapheneOS](https://grapheneos.org/) or [CalyxOS](https://calyxos.org/) provide better location control.
- [Advanced] **Run Your Own VPN or Proxy:** Setting up [Algo VPN](https://github.com/trailofbits/algo) or [WireGuard](https://www.wireguard.com/) on a personal server ensures more control.
- [Advanced] **Consider a Temporary Phone for Travel:** A secondary device can keep your primary phone's data separate.
