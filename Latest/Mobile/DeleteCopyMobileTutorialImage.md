# !!!!! Read the steps carefully and do not necessarily trust everything that is on the image, whether the name of the pak or the offsets. !!!!
## Step 1) 
Download [Files](https://play.google.com/store/apps/details?id=com.marc.files) 
- follow this [video](https://youtu.be/8N6MFhZ8XlY?si=ULY7uNq79dFiOSix)
- path pak : Android > data > com.epicgames.fortnite > files > InstalledBundles > FortniteBR > Content > Paks > pakchunk10_s2-Android_ASTCClient.ucas

## Step 2)
Download [Hex Editor](https://play.google.com/store/apps/details?id=tk.yunus.hexeditor&pcampaignid=web_share)
- go 'Open or Create File' > 'Open File' and select ```pakchunk10_s2-Android_ASTCClient.ucas```

![Screen](../../Assets/OrangeCopy/OrangeCopy1.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy2.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy3.jpg)

## Step 3)
- go 'Select Range' > First Address: ```1612B40``` > Last Address: ```1612EE0``` and Select

![Screen](../../Assets/OrangeCopy/OrangeCopy4.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy5.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy6.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy7.jpg)

## Step 4)
- copy code hex: 

```
00 00 00 00 08 03 00 00 0A 00 00 00 00 00 00 00 00 22 00 80 3D 05 00 00 70 02 00 00 70 02 00 00 98 02 00 00 E0 02 00 00 F0 02 00 00 04 03 00 00 04 03 00 00 0B 00 00 00 AC 01 00 00 00 00 64 C1 00 00 00 00 EF D6 41 99 7C 01 DF 4A 07 27 F3 53 6E 74 88 8D 9E F0 D2 87 A5 9A CE C2 F8 AD CD A3 89 88 53 D9 A2 00 89 72 E9 82 B7 E4 A8 57 72 66 BF 7B 40 61 FA A7 97 2C 60 81 09 0D 43 2E C7 07 76 17 07 8C 2B 6B 45 67 2F C3 74 D5 E2 59 11 65 8D 82 B8 E0 5C 15 84 44 94 09 18 65 00 22 00 2C 00 21 00 14 00 3B 00 2A 00 25 00 06 00 07 00 1D 00 75 2F 53 63 72 69 70 74 2F 46 6F 72 74 6E 69 74 65 47 61 6D 65 2E 42 75 69 6C 64 69 6E 67 41 63 74 6F 72 2F 53 63 72 69 70 74 2F 46 6F 72 74 6E 69 74 65 47 61 6D 65 2E 42 75 69 6C 64 69 6E 67 47 61 6D 65 70 6C 61 79 41 63 74 6F 72 43 34 2F 53 63 72 69 70 74 2F 46 6F 72 74 6E 69 74 65 47 61 6D 65 2E 42 75 69 6C 64 69 6E 67 50 72 6F 70 2F 53 63 72 69 70 74 2F 45 6E 67 69 6E 65 2E 41 63 74 6F 72 2E 46 6F 72 74 41 74 68 65 6E 61 56 65 68 69 63 6C 65 2F 53 63 72 69 70 74 2F 46 6F 72 74 6E 69 74 65 47 61 6D 65 2E 46 6F 72 74 43 68 61 72 61 63 74 65 72 56 65 68 69 63 6C 65 2F 53 63 72 69 70 74 2F 46 6F 72 74 6E 69 74 65 47 61 6D 65 2E 46 6F 72 74 50 68 79 73 69 63 73 50 61 77 6E 4F 62 6A 65 63 74 2F 53 63 72 69 70 74 2F 46 6F 72 74 6E 69 74 65 47 61 6D 65 2E 46 6F 72 74 50 69 63 6B 75 70 41 74 68 65 6E 61 4E 65 77 52 6F 77 50 69 63 6B 75 70 73 44 65 66 61 75 6C 74 5F 41 6C 6C 6F 77 65 64 5F 44 65 6C 65 74 65 4F 62 6A 65 63 74 73 2F 47 61 6D 65 2F 57 65 61 70 6F 6E 73 2F 50 72 6F 74 6F 74 79 70 65 2F 4F 62 6A 65 63 74 4D 6F 76 65 72 2F 42 6C 75 65 70 72 69 6E 74 73 2F 4F 62 6A 65 63 74 49 6E 74 65 72 61 63 74 69 6F 6E 42 65 68 61 76 69 6F 72 73 2F 44 65 6C 65 74 65 4F 62 6A 65 63 74 73 2F 44 65 66 61 75 6C 74 5F 41 6C 6C 6F 77 65 64 5F 44 65 6C 65 74 65 4F 62 6A 65 63 74 73 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ED D1 7B 98 29 4A E2 71 0D ED D9 85 24 6B 22 58 22 09 7C DC D3 CE AC 51 E3 22 58 A5 6D 55 F8 70 6A 8A 1E 92 E4 EA E2 71 00 00 00 00 00 00 00 00 8C 00 00 00 00 00 00 00 09 00 00 00 00 00 00 00 FF FF FF FF FF FF FF FF ED D1 7B 98 29 4A E2 71 FF FF FF FF FF FF FF FF 0D ED D9 85 24 6B 22 58 E0 2A 9F 40 38 AE 4D 3C 0B 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 01 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 03 FB FF FF FF 00 00 00 00 07 00 00 00 07 00 00 00 00 00 00 00 00 03 02 00 00 00 00 00 00 00 07 00 00 00 01 00 00 00 00 03 03 00 00 00 00 00 00 00 07 00 00 00 02 00 00 00 00 03 00 00 00 00 00 00 00 00 07 00 00 00 03 00 00 00 00 03 05 00 00 00 00 00 00 00 07 00 00 00 04 00 00 00 00 03 04 00 00 00 00 00 00 00 07 00 00 00 05 00 00 00 00 03 01 00 00 00 00 00 00 00 08 00 00 00 00 00 00 00 00 03 06 00 00 00 00 00 00 00 00 00 00 00 08 03 00 00 0A 00 00 00
```

![Screen](../../Assets/OrangeCopy/OrangeCopy9.jpg)

## Step 5)
- go 'Edit' > 'Overwrite' > paste code hex and Apply

![Screen](../../Assets/OrangeCopy/OrangeCopy5e.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy8.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy10.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy11.jpg)

## Step 6)
- go to the top left and press the last save icon

![Screen](../../Assets/OrangeCopy/OrangeCopy18.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy19.jpg)