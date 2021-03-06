## 2.2.4
* TOC bump for 7.2.0.

## 2.2.3
* TOC bump for 7.1.0.

## 2.2.2
* Like really really fixed artifact item level display (hiding offhand item level when no offhand).

## 2.2.1
* Really fixed artifact item level display.

## 2.2.0
* Added a way to whisper currently previewed items to other people.
* Added slash command to open the dressing room. Type /dressup or /dressingroom.
* Fixed weirdness with weapon previews.

## 2.1.7
* Fixed a bug in previous update.

## 2.1.6
* Fixed offhand item level number when using artifact weapons.

## 2.1.5
* Fixed error with item level updating.

## 2.1.4
* Added option to keep item levels permanently visible.
* Colorizing item levels by range. Lowest item levels are colored orange while higher end blue. Colorizing can be disabled in the options.
* Fixed error with side panel background.

## 2.1.3
* Revert the background change (again) and reinclude the Blizzard assets.

## 2.1.2
* Switched background images to use Blizzard Transmogrify textures so that the addon doesn't have to distribute Blizzard assets.
* Added option to always hide shirt.
* Other minor tweaks.

## 2.1.1
* Added help info about proper updating of addon.
* Added hint to emphasize the new resize feature.
* Aligned interface elements around slightly.

## 2.1.0
* Fixed bug introduced by the previous fix causing weapon slots not to be updated properly.
* Dressing room window is now resizable.
	* But for a price (from the development standpoint). DressUp now has to overwrite Blizzard dressing room frames with its own which may cause conflicts with other addons that may tweak the default Blizzard frames.
	* Following frames are overwritten: DressUpFrame, DressUpFrameOutfitDropDown, DressUpFrameResetButton, DressUpModel, DressUpFrameCancelButton. Old frames are still accessible by prefixing frame name with "Blizz" e.g. BlizzDressUpFrame.

## 2.0.1
* Fixed nil error when previewing saved outfits.

## 2.0.0
* Updated for Legion:
  * Added support for the outfits and new outfit dropdown.
  * With a proper way to retrieve previewed items, the weapon preview ordering is finally fixed.
  * Removed helm and cloak toggles since they're now changeable by transmog only (:angry fist: at Blizzard).

## 1.2.0
* Added options to automatically hide currently worn tabard and weapons when previewing items.

## 1.1.0
* Added an option to hide the display of item levels on character panel.
* Added an option to hide the display of helm and cloak toggle checkboxes on character panel.
* Added options menu button to character panel.
