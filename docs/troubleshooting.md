# Troubleshooting

### My issue isn't listed here.
The fastest way to get support is on [**Discord**](https://discord.gg/aZkkqnw). Make sure to check the [**FAQ**](faq.md) as well.

---


## PCSX2 / Gameplay

### When I launch the game with Aemulus, PCSX2 opens and immediately closes.
PCSX2 has probably encountered an error, but you'll need to launch the game directly from PCSX2 to see it.

- Launch **PCSX2.exe**.
- Select **System > Run ELF...** in the toolbar. Find and open **SLUS_216.21.elf** in the `P3F Mods\PCSX2\elf` folder.
- An error message will probably appear; see below for a fix.

---

### Error: `The configured BIOS file does not exist. Please re-configure.`
This error occurs when PCSX2 cannot find **bios.bin** in the `P3F Mods\.PCSX2\bios` folder.

- Close PCSX2.
- Make sure **bios.bin** is in the `bios` folder and that it is named correctly.
- If the BIOS file is in the correct folder and is named correctly, and this error still appears, redump your BIOS.

---

### Error: `CDVD plugin failed to open.`
This error occurs when PCSX2 cannot find **P3F.iso** in the `P3F Mods\.PCSX2\iso` folder.

- Close PCSX2.
- Make sure **P3F.iso** is in the `iso` folder and that it is named correctly.
- If the game is in the correct folder and is named correctly, and this error still appears, redump your disc image.

---

### The game doesn't respond to my controller.
- If you are using a PS4 controller, make sure it is plugged in via USB.
- You might be able to use a program like [DS4Windows](https://github.com/Ryochan7/DS4Windows/releases) to play wirelessly with a PS4 controller. 

> You will need to manually set up PS3 controllers and some Nintendo controllers yourself, as I do not have these available for testing.

---

### I can play other games fine, but P3F is slow.

Emulation isn’t the same as playing a game made for the PC. Your computer isn’t running P3F like it would a normal Windows application, it’s imitating an entire PS2 console. This adds a massive CPU overhead compared to running a PC game.

In the future, we will include additional tips on how to optimize P3F emulation for low-end computers and laptops. You can ask on the Discord server if you want some tips right now.

---

## Aemulus

### The Aemulus executable disappeared.

Your antivirus probably deleted it. Redownload CEP if you have to and add an exception for your `Aemulus` folder.

---

### I messed up my Aemulus loadout and want to start over.

- Launch Aemulus.
- Open your `P3F Mods\Backups\Aemulus` folder.
- Drag and drop the **Persona3FESPackages.xml** file here into the Aemulus window to reset your package loadout.

> This will restore the original package load order. Any custom packages you have installed will be moved to the bottom of the grid and unchecked, and any packages you have deleted will still be gone.
