# Optimized for OpenCore 0.9.7 and macOS Sanoma


# WARNING

> [!WARNING]  
> Use your own Serialnumber and SystemUUID. I have removed these values from the `config.plist`
# BIOS Setup

- I recommend you to upgrade to the latest BIOS (2023) from the same BIOS HP Network utility, easy and automated.
- TPM Embedded Security - Set to hidden
- Intel Software Guard Extension (SGX) - Disabled
- In boot options - USB Storage boot is enabled but PXE, Fast and CD-ROM boot are disabled. It's down to you and your drives for the boot order.
- Secure boot configuration - Set to Legacy Support Disable and Secure Boot Disable
- System Options - Turbo-boost, Multi-processor, VT (VTx), M.2 SSD and Allow PCIe/PCI SERR# Interrupt are left enabled.
- Virtualization options are secure and stable to use
- Built in device options - Embedded LAN controller, audio device and internal speakers are enabled. Increase video memory size to 512mb.
- Port options - enable them all
- Optional ROM policy - All legacy
- Power management options - enable all apart from unqiue sleep state blink rates
- Remote management options - disable all options here

# Thanks to:

- https://github.com/Wamphyre/HP-ELITEDESK-800-G2-DM-MINI-HACKINTOSH-35W

# What works?

- No Wireless
- No Audio
- 100% Super performant hardware and astonishing compatbility

## Don't forget to buy me a beer!
https://ko-fi.com/wamphyre94078