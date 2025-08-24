# DNS Switcher

DNS Switcher is a simple Windows HTA (HTML Application) tool that lets you quickly switch between popular DNS providers or revert to automatic (DHCP).  
It provides a lightweight interface with automatic WiFi adapter detection.

## Features

- One-click switching between popular DNS providers:
  - Automatic (DHCP)
  - Google DNS (8.8.8.8, 8.8.4.4)
  - Cloudflare DNS (1.1.1.1, 1.0.0.1)
  - Quad9 DNS (9.9.9.9, 149.112.112.112)
- Displays current DNS configuration
- Requires administrator privileges to apply changes
- Lightweight, no installation required

## System Requirements

- Windows 7/8/10/11  
- Administrator privileges  
- Active WiFi connection  
- Built-in Windows HTA support (mshta.exe)

## Installation & Usage

1. Download or clone this repository.  
2. Run `dns-switcher.hta`.  
3. If prompted, allow it to restart with administrator privileges.  
4. Choose the DNS server you want from the buttons.  

## Supported DNS Providers

| Provider    | Primary DNS     | Secondary DNS    |
|-------------|-----------------|------------------|
| Cloudflare  | 1.1.1.1         | 1.0.0.1          |
| Google      | 8.8.8.8         | 8.8.4.4          |
| Quad9       | 9.9.9.9         | 149.112.112.112  |
| Automatic   | DHCP            | -                |

## Troubleshooting

**Administrator privileges required**  
- Right-click the `.hta` file and select **Run as administrator**.  

**No WiFi found**  
- Ensure you are connected to a WiFi network.  
- If your adapter uses a non-standard name, update the code accordingly.  

**DNS changes not applying**  
- Verify administrator rights.  
- Try flushing the DNS cache.  

## Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.  

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.  

---

**Made with ❤️ for faster, safer browsing on Windows**
