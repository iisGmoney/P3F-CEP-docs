# FAQ

### My question isn't listed here.
The fastest way to get support is on [**Discord**](https://discord.gg/aZkkqnw).

---

## Emulation/Gameplay

### What are the default keyboard controls?
If you've played P4G on PC with the default keyboard controls, they should be pretty familiar.

- Movement and camera:
  - Left stick > **WASD**
  - L1 > **Q**
  - R1 > **E**
- Face buttons:
  - Cross > **Space**
  - Circle > **C**
  - Square > **F**
  - Triangle > **R** (*Tab* is bound to PCSX2's Turbo function)
- Other:
  - Start > **Enter**
  
---

### What controllers does PCSX2 support?
If you are using an Xbox / XInput controller, P3F CEP will work with it without any additional setup.

All other controllers will need to be [configured manually](https://visihow.com/Configure_Controls_for_PCSX2_PlayStation_Emulator). 

You can ask for help on the Discord server if you're having trouble.

> Only XInput controllers support vibration.

---

### Can I play P3F at 60 FPS?

Unfortunately, no.

The game’s speed is tied to the framerate, so running the game at 60 FPS doubles the speed of everything (if you want to see for yourself, press the Tab key while playing). 
There are patch files out there for a broken “60 FPS,” but they have many movement and animation errors.

---

### Can I play P3F in widescreen?

Sort of, but we don't recommend it.

You can force PCSX2 to render the game in widescreen and use widescreen patches to fix some of the UI, but there will still be visual errors like characters running in place because the game thinks they’re offscreen.

For now, P3F CEP will not include instructions on widescreen support beyond adding support for Rebirth Cutscenes.

---

### Why don't you include/recommend the Direct Commands/Party Control patch?

- P3F was not balanced around direct control of your party members. The game becomes much easier with the patch and we don't think it makes for a good first-time experience.
- The patch is not 100% bug-free and weird stuff can happen with it enabled.
- Aemulus does not support PNACH files, so there is no way to automatically install/uninstall the patch.

There's nothing in P3F CEP that is strictly incompatible with the patch, so you can drop the PNACH in your `.PCSX2\cheats` folder if you like.

---

### How do I speed up the event scenes?
The fast-forward feature was not part of the Persona series until P4G, but there are still a few ways you can speed through events:

- **No hax option:** Hold the button mapped to **Triangle** to instantly advance dialogue without reading it.
  - The game will still run at normal speed.
- **Fast option:** Press **Tab** on your keyboard to enable PCSX2's Turbo mode, then hold **Triangle**.
  - The game will run at double speed until you press Tab again.
- **Extreme option:** Press **F4** to disable the frame rate cap, then hold **Triangle**. 
  - PCSX2 will run the game as fast as your CPU can handle it (4x speed or more on a good CPU) until you press F4 again.

---

## Hardware/Software

### Can I use P3F CEP with my PS2 console?

Sorry, not yet! Right now, our focus is on PC emulation because it's much easier to set up, test, and customize.

---

### Where can I get a PS2 and a copy of Persona 3 FES?

You’ll probably need to buy a PS2 from a used hardware site like eBay. Make sure to buy from a trustworthy seller. 

If you’re in the United States, you can buy P3F off of Amazon brand-new for about $20 USD. 

---

### What if I don't want to, uh, spend money?

P3F CEP Team do not endorse and cannot help you with the very cool crime of piracy.

We also can't provide support if you use an altered disc image and it doesn't work (this includes ISOs with "undub" patches applied).

---

### Will you guys ever make a P3P CEP?

We currently have no plans to make a P3P modpack as the number of mods available for P3P is very slim.

---

### Will you guys support a PC port of P3F if it ever releases?

If P3F is ever ported to PC and mods become available for it without a huge headache, P3F CEP development will move to PC and PS2 emulation support will be dropped.
