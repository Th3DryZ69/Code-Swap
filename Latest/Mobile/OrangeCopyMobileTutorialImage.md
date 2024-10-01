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

## Step 3) Orange Copy:
- go 'Select Range' > First Address: ```19D6890``` > Last Address: ```19D6DCA``` and Select

![Screen](../../Assets/OrangeCopy/OrangeCopy4.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy5.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy6.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy7.jpg)

## Step 4)
- copy code hex: 

```
8C 06 00 05 34 88 05 32 00 00 00 00 48 0A 00 00 50 0F C4 03 5C 82 81 DE 1E 00 00 00 22 00 80 6F 0C 00 00 B0 09 00 00 B0 09 D8 20 0A 30 0A 44 44 1F 08 64 C1 00 00 00 00 30 14 4A EA 88 59 6C 1E 49 09 63 15 20 35 E0 09 53 F2 D4 7A D0 32 1D BA B0 E5 63 3B 03 45 12 AD B0 68 C1 E5 7B 0B 62 98 67 C7 CB 73 78 2B B9 2C 83 6C 9B 9C D3 AC 8F 09 E1 55 C2 03 DD 1E 77 97 38 3F 4E 71 01 51 D6 34 38 36 28 AB 36 8F E8 94 7E 64 CD 44 DB B0 82 9C F5 0B 58 AF 30 FE F7 9A 5D 05 79 4F 32 C6 04 7A 8F D2 E2 2C 47 96 64 46 BB A7 87 8D F3 2B 3B D9 86 48 CF F8 C0 7E A2 47 CD F9 91 AC F4 14 14 FF A5 EF FF B4 9D C3 62 3E C1 62 D4 5D B4 64 A1 3A 0D 7F FD E4 FF 4D D0 B6 8F 4F 45 0F C8 40 A6 4C 87 54 4E DD 1B 08 A7 82 8D 3B 5D EC 88 E3 79 80 89 94 8D 17 E5 08 1C 0D 9E F0 D2 87 A5 9A CE C2 08 1F 44 A3 25 7D 41 AC C1 B9 48 21 AD 6A 2E AC 60 80 63 80 97 E8 38 79 43 2E C7 07 76 17 07 8C F1 E3 E9 AF 69 AF 06 C4 CB A4 AC 41 BC BE 28 26 00 55 00 2F 00 4F 00 2C 00 3E 00 4A 00 67 00 72 00 52 00 4C 00 59 00 5C 00 4E 00 52 00 52 00 47 00 57 00 52 00 50 00 48 00 33 00 14 00 34 00 30 00 21 00 29 00 26 00 36 00 06 00 21 00 7D 04 ED D1 7B 98 29 4A E2 71 0D ED D9 85 24 6B 22 58 22 09 7C DC D3 CE AC 51 E3 22 58 A5 6D 55 F8 70 6A 8A 1E 92 E4 EA E2 71 18 02 1D 00 FF FF FF FF FF FF FF FF A0 B0 38 5B 65 3D F1 8C 0B 01 00 03 FB 1C 18 03 14 01 15 05 13 02 00 09 19 06 16 07 12 13 05 08 11 0A 0F 0B 0D 0C 0E 0D 08 0E 09 0F 0C 10 10 11 0B 12 0A 04 04 14 07 15 1A 16 03 17 17 18 1B 19 02 1A 06 1B 00 1C 00 00 00 00 03 01 00 00 00 00 00 00 00 A2 9D 6C 93 34 4A 4A BB D2 EE B5 25 CA A8 AD 7E 49 90 92 33 6E E1 E3 80 4E 1A 89 6A 03 DE 52 50 00 6F 00 71 AA AD 52 59 27 EB 93 E6 44 92 86 34 CD F1 01 56 CB 84 B1 55 FF 97 01 1E 70 44 F9 F5 B5 5D 6E 9A CC 07 97 17 16 89 CD 72 BB 9B 0B A2 81 8F 9E CA 27 C7 F1 93 93 29 9D 21 96 4C 4B 9F E5 08 69 67 3F 4F 0A B4 14 BC C7 22 BB 40 BA D5 11 EA C3 54 B6 EE 83 CB 0B 87 25 C3 5A DE 09 9D 1C AA 03 48 E9 ED B4 21 CF CF F4 B8 4C 5B 98 D3 9D 01 D4 CC 77 A0 4E 63 A7 D7 2F 70 88 9B 2A 86 E9 CD 08 45 A2 77 08 45 CC 61 E9 D9 CE 2F 95 44 2B 49 EA 10 1F 8A 9A 0B D1 C4 93 7A D5 DB C9 2D 8F 7A F0 90 37 AA DF 1E 9C 8E E5 E8 6B 64 1E 7E F3 09 32 64 D9 D5 01 3F 39 55 D5 D4 D9 7B D2 84 BE A6 91 A3 71 10 B6 1B DA 65 F4 B1 6C F8 94 E5 A3 1C EA EC DC E3 F9 BC E6 4E 67 FD 8B 8A 2A 86 07 08 98 AF CB 77 FC 07 19 4B 45 0A 97 47 59 92 63 73 36 AC B5 90 4A 91 04 A0 55 CD 10 D6 65 6C D6 5E FF 42 58 53 B8 F8 FC BB 56 94 A0 82 48 F4 B7 CD A3 A8 34 96 19 2C F6 55 E0 75 AE 82 95 5F 34 B6 5D 7E 03 64 7F C1 EF 16 C4 9D E2 11 1C BE F3 34 14 B5 56 87 A0 73 2B 52 86 9F 1B 7B C1 C3 60 3A 9C 36 F9 F6 84 1D DD 7A 39 2E 39 6F 83 04 80 80 04 81 92 71 00 56 10 00 0A 00 00 D8 05 02 03 05 02 02 05 05 C9 C9 D3 FD DF 35 D4 FB CC C9 34 D8 D7 D8 31 C8 13 DD 3F D4 34 D8 02 C6 D0 C8 D8 34 CC DF F0 34 E4 FB 34 CE C7 E8 CF DB D8 E4 34 F4 D3 CF C8 D3 FD FC CB E0 35 C8 34 E4 CF DC DF 34 FC D7 AB 1D 34 F4 EB D0 CC FC FC D8 D7 D8 D4 FB FC 03 78 7C C8 E4 FB FC C8 DB DF 34 FC DC DF D4 FC F9 E0 34 F4 F8 CB 34 D4 D4 EF CF 34 CB D9 EF D8 CF F0 34 EC C4 FF F3 34 C8 FC C8 D0 E7 D7 DC D8 EB DC D3 D4 E5 D0 C8 E5 D4 CF CB FC FC D9 E4 DB 52 12 DB D8 D8 CB 34 B5 29 C6 D8 DD 95 C8 0D 25 0D 25 0D 25 3A 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 80 80 7B 13 15 16 10 0C 15 12 22 0E 1A 20 0B 15 0E 18 1F 11 22 19 10 1A 2C 2C 16 12 1B 09 10 20 0F 1F 11 1F 0A 1C 08 15 0F 1B 19 0C 1A 34 22 0B 10 1C 12 1C 2E 29 24 2A 2A 33 31 23 0B 0D 1B 29 22 0C 19 08 12 10 1B 38 10 38 38 0C 1B 38 0C 0E 1B 32 37 0E 1B 28 13 0A 2B 19 30 1B 17 16 2E 12 0A 34 14 15 0E 13 14 10 3C 1C 37 13 15 2E 0F 1E 33 1C 20 41 08 16 1A 0C 1B 20 19 1E 0F 0D 00 00 3D 0B FF 09 13 1B 04 08 09 02 09 05 19 05 06 0A 01 04 04 11 09 06 09 12 04 03 06 01 04 06 10 21 0B 0F 05 18 01 03 00 02 01 02 01 12 0F 06 04 04 19 03 04 04 0B 0B 2E 04 02 01 10 25 05 06 D7 53 11 5C 96 5A 42 C6 6B 68 E9 7B 3A 06 08 FD BE 0C 2D 37 4D CE 04 45 60 18 50 ED F7 C8 1B 41 A9 BF 41 66 CE 47 F5 0B EA 8E 33 90 4E 92 C7 4F
```

![Screen](../../Assets/OrangeCopy/OrangeCopy9.jpg)

## Step 5)
- go 'Edit' > 'Overwrite' > paste code hex and Apply

![Screen](../../Assets/OrangeCopy/OrangeCopy5e.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy8.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy10.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy11.jpg)

## Step 6) White Copy
- go 'Select Range' > First Address: ```19D5893``` > Last Address: ```19D5A5B``` and Select

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
- go 'Select Range' > First Address: ```19D960A``` > Last Address: ```19D9719``` and Select

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
- go 'Select Range' > First Address: ```19D0025``` > Last Address: ```19D0195``` and Select

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