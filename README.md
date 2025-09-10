# Da-Dash After Story – FMOD Audio Project

> **Note**: This README was enhanced by AI and reviewed by the project maintainer.

This repository contains the **FMOD Studio project** for the Da-Dash After Story game, designed specifically for audio professionals and sound designers.

**Perfect for:**
- Music composers and sound designers
- Audio implementers working on game audio
- Team members who need to work with audio without Unity setup

---

## 🎯 Quick Start

### Prerequisites
- **[FMOD Studio](https://www.fmod.com/download)** (free download required)
- **[GitHub Desktop](https://desktop.github.com/)** (recommended) or Git CLI

### Getting the Project
1. **Install GitHub Desktop** if you haven't already
2. **Clone this repository:**
   - Click the green **"Code"** button above
   - Select **"Open with GitHub Desktop"**
   - Choose your desired local folder (e.g., `Documents/Projects/DDAS-FMOD`)
3. **You're ready to go!** The FMOD project is now on your machine

---

## 🎼 Audio Development Workflow

### Opening the Project
1. Launch **FMOD Studio**
2. Open the main project file: `Da-Dash-After-Story_Fmod.fspro`
3. You'll see the complete audio architecture for the game

### Making Changes
- **Add new audio assets** (music tracks, sound effects, voice lines)
- **Create and modify events** for dynamic audio implementation
- **Adjust parameters** for adaptive music and interactive sound design
- **Set up audio routing** and effects processing

### Building for Integration
1. After making changes, **build the banks:**
   - Go to **File → Build** in the top menu
   - This generates the `.bank` files that Unity will use
2. **Always build before committing** to ensure integration files are up to date

---

## 🔄 Version Control Best Practices

### Submitting Your Changes
1. **Open GitHub Desktop**
2. **Review your changes** in the left panel
3. **Write a descriptive commit message** (examples):
   - `Add new dash sound effect with random pitch variation`
   - `Update boss battle music with dynamic layers`
   - `Fix reverb settings for cave environments`
4. **Click "Commit to main"** then **"Push origin"**

### Staying Up to Date
1. **Before starting work:** Open GitHub Desktop and click **"Fetch origin"** → **"Pull origin"**
2. **This ensures you have the latest changes** from other team members
3. **Resolve any conflicts** if they arise (rare with FMOD projects)

---

## ⚠️ Important Guidelines

### Files You Should NOT Modify
- **`Build/` folder** - Contains generated bank files
- **`.cache/` folder** - FMOD's temporary files
- **`.fspro` filename** - Don't rename the main project file
- **Metadata files** - Let FMOD manage these automatically

### Recommended Workflow
1. **Always pull first** - Get the latest version before starting
2. **Work in focused sessions** - Complete related changes together
3. **Test your audio** - Play through events before building
4. **Build banks** - Generate fresh `.bank` files
5. **Commit with clear messages** - Help team members understand changes
6. **Push immediately** - Share your work with the team

---

## 🆘 Troubleshooting

### Common Issues
- **Missing audio files?** Check if they're committed to the repository
- **Banks not updating in Unity?** Make sure you built after your changes
- **Project won't open?** Try pulling the latest changes first
- **Merge conflicts?** Contact the lead programmer for assistance

### Need Help?
- **Technical issues:** Contact the lead programmer
- **Audio questions:** Consult the team's audio lead
- **Git problems:** Check GitHub Desktop's help documentation

---

## 📁 Project Structure
```
Da-Dash-After-Story_Fmod/
├── Da-Dash-After-Story_Fmod.fspro    # Main FMOD project file
├── Assets/                            # Audio source files
├── Build/                            # Generated bank files (auto-generated)
├── Metadata/                         # FMOD metadata (auto-managed)
└── .cache/                           # Temporary files (auto-managed)
```

---

## 🎵 Contributing Audio Assets

When adding new audio content:
- **Use appropriate file formats** (WAV recommended for music, various formats for SFX)
- **Maintain consistent naming conventions**
- **Document any special implementation notes** in commit messages
- **Test events thoroughly** before building banks

---

*This project uses FMOD Studio for professional game audio implementation. For more information about FMOD, visit [fmod.com](https://www.fmod.com/).*
