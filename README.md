# ThinkPad-X230-Hackintosh
An EFI to use OpenCore, to run on a Lenovo Thinkpad X230 (on any version of macOS)





									#DISABLED
*Fast Boot
*Secure Boot
*Serial/COM Port
*Parallel Port
*VT-d (can be enabled if you set DisableIoMapper to YES)
*CSM (or Legacy Support, or Hybrid Boot)
*Thunderbolt (For initial install, as Thunderbolt can cause issues if not setup correctly, if available)
*Intel SGX
*Intel Platform Trust
*CFG Lock (MSR 0xE2 write protection)(This must be off, if you can't find the option then enable AppleCpuPmCfgLock under Kernel -> Quirks. Your hack will not boot with CFG-Lock enabled)
									#ENDABLED	
*VT-x (Virtualization Support)
*Above 4G decoding
*Hyper-Threading
*Execute Disable Bit
*EHCI/XHCI Hand-off
*OS type: Windows 8.1/10 UEFI Mode
*DVMT Pre-Allocated(iGPU Memory): 32MB
*SATA Mode: AHCI
