# infineon-tpm-update
TPM Firmware Update Tool for Infineon TPMs

# Common Commands

All of the following commands use `/dev/tpm0` as the default
device file for the TPM.
To override this, pass the following cli option:
```bash
-access-mode 3 <device-file>
```

- To Get Firmware Version:
```bash
TPMFactoryUpd -info
```
- To Update Firmware:
```bash
TPMFactoryUpd -update tpm20-emptyplatformauth -firmware <path-to-firmware-binary>
```
