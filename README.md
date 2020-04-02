# Thinkpad T440p Mods & Windows Configuration
The T440p is a highly modifyable laptop. It is an excellent laptop one can get for cheap and then mod it so it can compare with a high-end laptop while still saving money.

**There are other reasons to get a Thinkpad T440p:**
- Excellent MIL-SPEC build quality.
   - Many modern laptops with a high price tag have a such poor build quality.
- Many USB ports.
- Display port.
- DVD drive (If you actually still want one.)
- Unsoldered RAM
- Superb key travel. (Thinkpads have the best keyboards of any laptop.)
- Thinkpads are just cool.

**Reasons not to get a Thinkpad T440p:**
- Depending on the price you find one, it may actually be better to get a newer laptop.
- No Thunderbolt (Sucks especially if you want to use a portable monitor)
- Heavy and thick.
   - No getting around the weight and thickness. Eventually you'll get tired of having to lug around something like this if you walk with it everywhere. Newer laptops have gotten much thinner.
- Large bezels.
   - I've certainly seen larger bezels on laptops, but high end laptops these days have such thin bezels and look so nice, you might be a little jealous of them.
 - Different charger connector.
   - Older Thinkpads have a different round charger connector while the T440p has a rectangle charger. So if you were hoping to use your older charger, you need to buy a new one. Why they did this, I do not know.

The mods in **bold** are the most important to me. You'll be surprised as to what you can do and how easily you can do them, even the panel replacement which is the most surprising.

### Mods
- **CPU Replacement (Replace with the i7-4810mq)**
- **Upgradable RAM up to 16GB (Thank goodness for unsoldered RAM)**
- **Replacable SATA drive (SSD)**
- **Hackintoshable (Easy to do. I personally done this and have a [repo about a T440P Hackintosh](https://github.com/NawalJAhmed/T440p-Hackintosh).)**
- **Keyboard replacement with backlit keyboard (Only if yours did not come with one)**
- **Trackpad replacement with better 3 button trackpad from T450**
- **Replace screen with 1920x1080p IPS display (Use LG Panel)**
- Ultrabay/Optical drive replacement (Replace DVD drive with SATA SSD)
- MSATA SSD (I don't actually use this because of the price but you can if you want)
- Internal wifi card replacement for Hackintoshing. (Need to whitelist from BIOS)
- Coreboot support (I didn't do this but there is official support)

## Guides
Hands down the best guide on how to perform all of these upgrades is [OctoPerf's T440p Ultimate Buyer's Guide](https://octoperf.com/blog/2018/11/07/thinkpad-t440p-buyers-guide/).

For Corebooting, visit the [official documentation](https://doc.coreboot.org/mainboard/lenovo/t440p.html).

The 2 guides above are really all you need. If you need a more visual walkthrough, there are several videos on YouTube about the topic.

## Recommendations
I just want to emphasize some common recommendations from the 2 guides.

1. If you are going to replace the Optical drive with an SSD, please use a high quality adapter as the generic ones will eventually have trouble connecting the drive after a few reboots. I have personally experienced this.
2. If you are going to replace the trackpad, then use a genuine Synaptics trackpad and not an ALPs or fake Synaptic trackpad as those are probably ALPs in disguise. Using a Synaptics trackpad will help save you headaches especially if you want to Hackintosh your laptop.
3. Try to get a faster charger if you get the panel replacement as the higher resolution and nits will warrent more energy usage. Downside will be an even heavier charger.
3. When you are done upgrading, try to sell the spare parts you have.

## Trackpad Fixing on Windows
When you replace the default trackpad with the 3 button trackpad from the T450, you need to modify some files so that the buttons will work.
