# ErenshorCRTFilter

Copy the files into your game folder:

Erenshor_CrtShader.dll → Erenshor/BepInEx/plugins/

crt_overlay.png       → Erenshor/BepInEx/plugins/

Run Erenshor once to generate the config file (com.Recks.crtfilter.cfg).
[General]
# Enable or disable the CRT overlay
Enabled = true

# Path to your PNG overlay (relative to game folder)
TexturePath = ./BepInEx/plugins/crt_overlay.png

# Overlay opacity (0.0 to 1.0)
Opacity = 0.8


Update: Updated the CRTFilter to be more reminiscent of the real thing. Filter now has slight animation and flicker effects with a slight glow
If you used the previous version please delete the config file and let the engine create a new one on load
