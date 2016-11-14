### Planned features and improvements

* CPU
 * [x] x86-32-only mode
 * [x] BIOS boot
 * [ ] x86-64-only mode (**dropping x86-32**)
 * [ ] Multicore HAL and scheduler
 * [ ] UEFI boot
 * [ ] USB fixes
* GPU
 * [x] Software OpenGL
 * [x] Virtualized OpenGL
 * [ ] Hardware OpenGL
 * [ ] Hardware Vulkan
 * [ ] D3D over Vulkan
* Kernel
 * [x] Basic stubs: memory manager, FAT filesystem, simple scheduler
 * [ ] Stable memory manager
 * [ ] GUI for OS installer instead of DOS terminal session
 * [ ] Moving from FAT to EXT4 filesystem (NTFS ok for external drives, but not for root, BTRFS is very linux specific)
 * [x] Initial NT 5.1 support (Windows XP)
 * [ ] Full NT 5.1 support (Windows XP)
 * [x] Initial NT 5.2 support (Windows Server 2003)
 * [ ] Full NT 5.2 support (Windows Server 2003)
 * [ ] Initial NT 6.1 support (jump directly to Windows 7, compatibility mode)
 * [ ] Full NT 6.1 support (Windows 7)
 * [ ] Linux subsystem (only software)
 * [ ] Android subsystem (based on linux's, only software)
* Visuals
 * [x] New default theming and visuals (Windows XP compatible)
 * [ ] Fix theming engine (Windows XP compatible)
 * [ ] GreenShell theme and toolkit for GreenStep
 * [ ] Overhaul of theming engine (shadows, blurs, effects)
* Shell and UI
 * [x] Initial implementations of shell, tray, explorer, start button and others
 * [ ] GreenStep widgets and gui elements
 * [ ] Stabilization of shell, tray, explorer, start button and others
 * [ ] Shell overhaul to add modern features and look
 * [ ] GreenLibs modules for GreenStep
