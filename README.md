# soulkiller-plymouth

![Alt text](soulkiller_logo.png)

Custom plymouth theme for SoulkillerOS

### Usage
Copy all the assets to the `/usr/share/plymouth/themes` directory, rename the `soulkiller-plymouth` directory to `soulkiller`, and update the plymouth theme with `plymouth-set-default-theme -R soulkiller`.

If that doesn't work then you can use:
```
sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/soulkiller/soulkiller.plymouth 200
sudo update-alternatives --config default.plymouth
sudo update-initramfs -u
```
