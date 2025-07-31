# Credit

This patch is based entirely on the work of [this AskUbuntu answer](https://askubuntu.com/a/1550592). I’ve simply wrapped it up as an easy-to-apply local patch.

---

## Installation

### On CachyOS

1. Download the patch file ([`0001-bluetooth-disable-read-local-ext-features.patch`](https://github.com/nwrafael/CM748-ugreen-bluetooth-adapter-patch-linux/releases/download/V1.0/0001-bluetooth-disable-read-local-ext-features.patch).  
2. Open **CachyOS Kernel Manager**.  
3. Select your currently active kernel (it’s usually checked by default).  
4. Click **Configure**, then switch to the **Patches** tab.  
5. Click **Add Local Patch** and choose the downloaded patch file.  
6. Return to the **Options** tab and click **Build Kernel**.  

   > ⚠️ This can take some time depending on your hardware—just sit back and wait!  
7. When the build finishes, reboot your machine to load your new patched kernel.  
8. Enjoy

### On Other Distributions

If your distro doesn’t provide a kernel-manager GUI, you’ll need to apply and build the kernel manually.
