# ErenshorCRTFilter

Copy the files into your game folder:

CRTFilterPlugin.dll → Erenshor/BepInEx/plugins/

crt_overlay.png       → Erenshor/BepInEx/plugins/

Run Erenshor once to generate the config file (com.Recks.crtfilter.cfg).
[General]
# Enable or disable the CRT overlay
Enabled = true

# Path to your PNG overlay (relative to game folder)
TexturePath = ./BepInEx/plugins/crt_overlay.png

# Overlay opacity (0.0 to 1.0)
Opacity = 0.8
