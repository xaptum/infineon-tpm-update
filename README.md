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
## License
Copyright (c) 2020 Xaptum, Inc.

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301, USA.
