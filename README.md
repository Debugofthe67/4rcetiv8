# 4rcetiv8

4rcetiv8  is an open-source fork of hacktiv8(formerly A5_Bypass_OSS). It will have a wide spread of iOS devices `A4` , `A5`, and `A6`
## Disclaimer

This project is intended strictly for research and educational purposes.  
It is not designed for, and must not be used in, production environments or for unlawful activities.  
The authors and contributors take no responsibility for any misuse or damage caused to devices, data, or systems.

## Requirements

The both host and target devices must be connected to Wi-Fi at all times during operation.  
Network connectivity is mandatory for the application workflow to function correctly.

## Compatibility

The tool targets iOS 9 and 10 devices (and Wi-Fi-only devices on iOS 8).

## Backend Configuration

The backend URL is stored in the `BACKEND_URL` global constant of [`main.py`](https://github.com/overcast302/hacktiv8/blob/main/main.py#L18)

Due to legacy iOS devices lacking trust for modern certificate authorities, the backend must either use HTTP, or serve an SSL certificate that chains to a root CA trusted by legacy iOS. Modern certificate authorities such as Let's Encrypt are not trusted on legacy iOS versions and will cause HTTPS connections to fail on target devices.

## Credits
- [pkkf5673](https://github.com/bablaerrr)
- [bl_sbx](https://github.com/hanakim3945/bl_sbx)
- [pymobiledevice3](https://github.com/doronz88/pymobiledevice3)
- [overcast302](https://github.com/overcast302/)

## License

Refer to the repository license file for licensing details.
