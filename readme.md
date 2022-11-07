# Gunslinger Clan DIM Weapon Wish List

## Usage:

### Setting up DIM to use this list

Use this list in DIM by going to DIM>Settings>Wish List>"Optionally, supply the URL(s) for a wish list (pipe | separated)" and add the following URL:
```
https://raw.githubusercontent.com/Gunslinger-Tank/Weapon-Wish-List/main/D2_GS_Wishlist
```

![DIM menu > settings](https://github.com/Gunslinger-Tank/Weapon-Wish-List/blob/main/screenshots/dim_settings.png)
![DIM settings add wishlist](https://github.com/Gunslinger-Tank/Weapon-Wish-List/blob/main/screenshots/dim_settings_add_wishlist.png)

### Searching note text in DIM

You can use the following code to search for wish list notes in DIM in the search bar (in this examples, looking for notes with the term "PvE":
```
wishlistnotes:PvE
```

You can also combine this with the logical operators in DIM to look for more than one tag/note text at the same time (in this examples, looking for notes with the term "PvE" and "PC":
```
wishlistnotes:PvE and wishlistnotes:PC
```


## Rules for adding new rolls:

- Always add notes to your entries
  - Name of the item and role if possible (i.e. Boss damage / add clear, etc.)
  - Tag of the type of actvity: PvE or PvP
  - Tag if this roll is for Console or PC
  - Add your in-game name and date of addition to the notes
  
Example: 
```
// Taipan-4fr - Taipan-4fr | Boss Damage (god-pve)
//notes: tags:PvE, Boss, PC/Console
//Submitted by: Eschyr 11/7/2022
dimwishlist:item=1911060537&perks=3250034553,2680121939,573122728,395388285
```


## Tools:

- Littlelight's Wishlist creator (https://wishlists.littlelight.club) - Can create multiple rolls automatically for you (different barrel/magazine perks for each perk combination)
- D2 Gunsmith (https://d2gunsmith.com) - Build your roll and then press the "Copy Wishlist Item" button to generate your item code
- Link to Voltron's wishlist for reference (https://raw.githubusercontent.com/48klocs/dim-wish-list-sources/master/voltron.txt)
