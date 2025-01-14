# !!!!! Read the steps carefully and do not necessarily trust everything that is on the image, whether the name of the pak or the offsets. !!!!
## Step 1)
Download [Files](https://play.google.com/store/apps/details?id=com.marc.files) 
- follow this [video](https://youtu.be/8N6MFhZ8XlY?si=ULY7uNq79dFiOSix)
- path pak : Android > data > com.epicgames.fortnite > files > InstalledBundles > FortniteBR > Content > Paks > pakchunk40_s1-Android_ASTCClient.ucas

## Step 2)
Download [Hex Editor](https://play.google.com/store/apps/details?id=tk.yunus.hexeditor&pcampaignid=web_share)
- go 'Open or Create File' > 'Open File' and select ```pakchunk40_s1-Android_ASTCClient.ucas```

![Screen](../../Assets/OrangeCopy/OrangeCopy1.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy2.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy3.jpg)

## Step 3) Orange Copy:
- go 'Select Range' > First Address: ```368A00``` > Last Address: ```368F58``` and Select

![Screen](../../Assets/OrangeCopy/OrangeCopy4.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy5.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy6.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy7.jpg)

## Step 4)
- copy code hex: 

```
8C 06 00 05 52 88 05 50 00 00 00 00 78 0A 00 00 50 0F F4 03 6E 82 81 B7 1F 00 00 00 22 00 80 A0 0C 00 00 E0 09 00 00 E0 09 08 0A 50 0A 60 74 74 20 00 4A 08 64 C1 00 00 00 00 30 14 4A EA 88 59 6C 1E 49 09 63 15 20 35 E0 09 53 F2 D4 7A D0 32 1D BA B0 E5 63 3B 03 45 12 AD B0 68 C1 E5 7B 0B 62 98 67 C7 CB 73 78 2B B9 2C 83 6C 9B 9C D3 AC 8F 09 E1 55 C2 03 DD 1E 77 97 38 3F 4E 71 01 51 D6 34 38 36 28 AB 36 8F E8 94 7E 64 CD 44 DB B0 82 9C F5 0B 58 AF 30 FE F7 9A 5D 05 79 4F 32 C6 04 7A 8F D2 E2 2C 47 96 64 46 BB A7 87 8D F3 2B 3B D9 86 48 CF F8 C0 7E A2 47 CD F9 91 AC F4 14 14 FF A5 EF FF B4 9D C3 62 3E C1 62 D4 5D B4 64 A1 3A 0D 7F FD E4 FF 4D D0 B6 8F 4F 45 0F C8 40 A6 4C 87 54 4E DD 1B 08 A7 82 8D 3B 5D EC 88 E3 79 80 89 94 8D 17 E5 08 1C 0D 9E F0 D2 87 A5 9A CE C2 08 1F 44 A3 25 7D 41 AC 55 5C F8 3F 93 13 1C EF C1 B9 48 21 AD 6A 2E AC 60 80 63 80 97 E8 38 79 43 2E C7 07 76 17 07 8C F1 E3 E9 AF 69 AF 06 C4 CB A4 AC 41 BC BE 28 26 00 55 00 2F 00 4F 00 2C 00 3E 00 4A 00 02 ED D1 7B 98 29 4A E2 71 0D ED D9 85 24 6B 22 58 22 09 7C DC D3 CE AC 51 E3 22 58 A5 6D 55 F8 70 6A 8A 1E 92 E4 EA E2 71 2A 1E FF FF FF FF FF FF FF FF A0 B0 38 5B 65 3D F1 8C 0B 01 00 03 FB 1D 18 03 14 01 15 05 13 02 00 09 19 06 16 07 12 13 05 08 11 0A 0F 0B 0D 0C 0E 0D 08 0E 09 0F 0C 10 10 11 0B 12 0A 04 04 14 07 15 1B 16 03 17 17 18 1C 19 02 1A 06 1B 00 1C 01 1D 00 00 00 00 03 1A 00 00 00 00 00 00 00 A2 85 A5 94 04 44 B5 89 4A A9 77 AF 5D CA 93 D5 48 AD 7D 29 89 B3 37 53 91 9B 6F C3 1C 0C 0E 01 38 1A 89 6A 02 D5 1C CA 41 00 C0 80 00 67 F7 E4 9E DD C6 B5 EE BD BB 73 1F DC 5D 18 CA 5C 20 2F 83 D6 51 52 04 8E 4D 1C C6 70 45 12 4D 80 FD 5C EC 77 42 A4 06 5B CC 5F DE D6 D3 59 A2 5A 63 FC 40 CC 61 56 4B F3 45 8D 31 28 52 6B 31 BF 52 E8 5F 29 AA C0 1E 59 A3 4A AE 13 B7 C8 F3 DE F6 83 20 CE D1 5B 8D 13 6F 3C C8 5A 7A 14 6B 86 BC 36 6B 8C 1F C8 4F 09 75 4E BD ED 2E D4 25 3E E4 5D 19 F9 76 3B A5 4A 46 F9 89 05 0B 5F 08 EA 7E B9 CE 1D DC D6 7D 73 9F DC 77 F7 1F 66 B5 0D 42 25 A1 92 D3 1B 92 0F AB C2 8A C3 B3 02 66 0E 56 A1 CF AC 86 1A 6F F3 FE A1 00 4B 01 8E 15 86 AB 60 49 99 01 06 1A C4 8A 9C 3B D3 D4 CB CE 7C 5A 89 FC 33 6F D0 E6 D6 96 40 D4 FC A0 0E B9 49 BC 29 0D 7E A6 58 44 62 A5 2F 51 22 D6 25 F6 14 94 3C 93 9E 71 3E F6 D6 E7 15 0C 45 47 9A 09 78 14 41 C1 39 26 DC E1 5F D3 F4 88 57 00 3A 8D 61 C7 AF 16 E9 60 56 EE 7C 1A 45 0C E8 61 B8 46 2F 25 E4 01 73 20 0A 30 9A 83 E2 8F 34 92 F2 5F AF 93 F0 17 0F EF 1E 8B 88 17 A3 23 5E 39 E3 CE 18 BC 51 A8 4E 25 BC 2D 0D 29 65 E0 24 F1 86 B4 E3 D2 15 E2 79 52 35 64 EB 00 B8 7D 16 E6 DA 24 BD 1A 22 95 70 F2 21 4B 98 A6 FE D6 AD E4 57 10 AB A6 E7 4D B0 C7 66 CA C1 4A 61 4D 6C 6B 9D EE 8F BB DD D5 F7 3A E7 5C 7F 73 AE 04 80 80 04 81 92 71 00 2F 10 80 23 00 00 D7 05 02 03 02 02 05 05 05 02 CA D3 FD DF 35 D4 FB CC FD D8 D7 D8 31 C8 13 DD 3F D8 30 D8 02 C6 D0 C8 D8 34 CC DF FC E4 FB 34 CE EB CF DB D8 FC F4 D3 CF C8 D3 FD FC CB E0 35 FC E4 CF DC DF 34 FC D7 AB 1D 34 F4 EB D0 CC FC FC D8 D7 D8 D4 FB FC 03 78 7C C8 E4 FB FC C8 DB DF 34 FC DC DF D4 FC F9 FC F4 F8 CB 34 D8 D0 EF CF 34 CB D9 EF D8 CF FC EC C4 FF FF C8 FC C8 D0 EF 34 EF D7 DC D8 EB DC CC CA D3 D4 E5 D0 C8 E5 D4 CA CD CB FC FC D9 DC DB D5 15 DB D8 D8 FB 44 B5 29 C6 D8 DD 95 C8 0D 25 0D 25 0D 25 3A 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 80 80 7E 15 16 10 0C 15 12 22 0E 1A 20 0B 15 0E 18 1F 11 22 19 10 1A 2C 2C 16 12 1B 10 20 0F 1F 11 1F 0A 1C 08 15 0F 1B 19 0C 1A 34 22 0B 10 1C 12 1C 2E 29 24 2A 2A 33 31 23 0B 0D 1B 29 22 0C 19 08 12 10 1B 38 10 38 38 0C 1B 38 0C 0E 1B 32 37 0E 1B 28 13 0A 2B 19 30 1B 17 16 2E 12 0A 34 14 25 15 0E 13 14 10 1D 31 3C 1C 38 13 15 30 0F 38 1E 34 1C 20 41 08 16 19 1A 0C 1B 20 19 1E 0F 0D 00 00 44 0B FF 09 13 1B 02 04 08 09 02 09 0C 05 1C 05 06 09 0A 01 04 04 11 09 02 06 09 12 04 03 06 01 04 06 10 21 0B 0F 05 18 01 03 00 02 01 08 02 01 12 0F 06 04 0C 04 19 03 0C 04 04 07 0B 0B 23 02 01 10 25 05 06 7E 3C 92 74 8B 2D 21 63 35 B4 74 BD 9D 03 04 7E DF 06 1E E1 CA 3E DE 70 06 2D 80 24 A6 2A B0 D0 5A A5 11 94 FA 1B 64 E6 7C 54 BF A0 EE 38 03 AE 88 A9 4B
```

![Screen](../../Assets/OrangeCopy/OrangeCopy9.jpg)

## Step 5)
- go 'Edit' > 'Overwrite' > paste code hex and Apply

![Screen](../../Assets/OrangeCopy/OrangeCopy5e.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy8.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy10.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy11.jpg)

## Step 6) White Copy
- go 'Select Range' > First Address: ```367A2E``` > Last Address: ```367C10``` and Select

![Screen](../../Assets/OrangeCopy/OrangeCopy4.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy12.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy13.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy14.jpg)

## Step 7)
- go 'Edit' > 'Fill Overwrite' > Don't change anything and Apply

![Screen](../../Assets/OrangeCopy/OrangeCopy15.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy16.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy17.jpg)

## Step 8) Optionnal (Necessary for DeleteCopy)
- go 'Select Range' > First Address: ```36BF06``` > Last Address: ```36C027``` and Select

![Screen](../../Assets/OrangeCopy/OrangeCopy4.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy12.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy13.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy14.jpg)

## Step 9)
- go 'Edit' > 'Fill Overwrite' > Don't change anything and Apply

![Screen](../../Assets/OrangeCopy/OrangeCopy15.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy16.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy17.jpg)

## Step 10) Optionnal (Necessary for DeleteCopy)
- go 'Select Range' > First Address: ```362105``` > Last Address: ```362275``` and Select

![Screen](../../Assets/OrangeCopy/OrangeCopy4.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy12.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy13.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy14.jpg)

## Step 11)
- go 'Edit' > 'Fill Overwrite' > Don't change anything and Apply

![Screen](../../Assets/OrangeCopy/OrangeCopy15.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy16.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy17.jpg)

## Step 12)
- go to the top left and press the last save icon

![Screen](../../Assets/OrangeCopy/OrangeCopy18.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy19.jpg)