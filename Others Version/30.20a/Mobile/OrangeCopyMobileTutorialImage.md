# !!!!! Read the steps carefully and do not necessarily trust everything that is on the image, whether the name of the pak or the offsets. !!!!
## Step 1)
Download [Files](https://play.google.com/store/apps/details?id=com.marc.files) 
- follow this [video](https://youtu.be/8N6MFhZ8XlY?si=ULY7uNq79dFiOSix)
- path pak : Android > data > com.epicgames.fortnite > files > InstalledBundles > FortniteBR > Content > Paks > pakchunk10_s3-Android_ASTCClient.ucas

## Step 2)
Download [Hex Editor](https://play.google.com/store/apps/details?id=tk.yunus.hexeditor&pcampaignid=web_share)
- go 'Open or Create File' > 'Open File' and select ```pakchunk10_s3-Android_ASTCClient.ucas```

![Screen](../../Assets/OrangeCopy/OrangeCopy1.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy2.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy3.jpg)

## Step 3) Orange Copy:
- go 'Select Range' > First Address: ```16D0BC0``` > Last Address: ```16D10E0``` and Select

![Screen](../../Assets/OrangeCopy/OrangeCopy4.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy5.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy6.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy7.jpg)

## Step 4)
- copy code hex: 

```
8C 06 00 05 1A 88 05 18 00 00 00 00 10 0A 00 00 50 0F 4C 03 47 82 81 D4 1D 00 00 00 22 00 80 37 0C 00 00 78 09 00 00 78 09 A0 E8 F8 0C 0A 0C 0A 1E 00 F3 07 64 C1 00 00 00 00 30 14 4A EA 88 59 6C 1E 53 F2 D4 7A D0 32 1D BA B0 E5 63 3B 03 45 12 AD B0 68 C1 E5 7B 0B 62 98 67 C7 CB 73 78 2B B9 2C 83 6C 9B 9C D3 AC 8F 09 E1 55 C2 03 DD 1E 77 97 38 3F 4E 71 01 51 D6 34 38 36 28 AB 36 8F E8 94 7E 64 CD 44 DB B0 82 9C F5 0B 58 AF 30 FE F7 9A 5D 05 79 4F 32 C6 04 7A 8F D2 E2 2C 47 96 64 46 BB A7 87 8D F3 2B 3B D9 86 48 CF F8 C0 7E A2 47 CD F9 91 AC F4 14 14 FF A5 EF FF B4 9D C3 62 3E C1 62 D4 5D B4 64 A1 3A 0D 7F FD E4 FF 4D D0 B6 8F 4F 45 0F C8 40 A6 4C 87 54 4E DD 1B 08 A7 82 8D 3B 5D EC 88 E3 79 80 89 94 8D 17 E5 08 1C 0D 9E F0 D2 87 A5 9A CE C2 08 1F 44 A3 25 7D 41 AC C1 B9 48 21 AD 6A 2E AC 60 80 63 80 97 E8 38 79 43 2E C7 07 76 17 07 8C F1 E3 E9 AF 69 AF 06 C4 CB A4 AC 41 BC BE 28 26 00 55 00 4F 00 2C 00 3E 00 4A 00 67 00 72 00 52 00 4C 00 59 00 5C 00 4E 00 52 00 52 00 47 00 57 00 52 00 50 00 48 00 33 00 14 00 34 00 30 00 21 00 29 00 26 00 36 00 06 00 21 00 7D 05 ED D1 7B 98 29 4A E2 71 0D ED D9 85 24 6B 22 58 22 09 7C DC D3 CE AC 51 E3 22 58 A5 6D 55 F8 70 6A 8A 1E 92 E4 EA E2 71 0A 02 1C 00 FF FF FF FF FF FF FF FF A0 B0 38 5B 65 3D F1 8C 0B 01 00 03 FB 1B 17 03 13 01 14 05 12 02 00 09 18 06 15 07 11 13 04 08 10 0A 0E 0B 0C 0C 0D 0D 07 0E 08 0F 0B 10 0F 11 0A 12 09 04 03 14 06 15 19 16 02 17 16 18 1A 19 01 1A 05 1B 00 00 00 00 03 00 00 00 00 00 00 00 00 A2 79 61 93 34 4A 4B 77 A5 D7 69 12 EA A4 56 BF 49 90 92 33 6E E1 E3 D0 4E 18 89 6A 03 DE 52 50 00 6A 00 71 2E B5 60 DE 67 6B 40 13 A0 40 0B DE D8 F4 34 CA A5 30 C7 8D 88 5B 78 D6 CB 4B 41 D1 82 02 07 8A 9B 52 49 19 71 E6 59 BD E8 7D 74 4B 93 9E 3D A4 4E F5 DB 83 E3 90 07 DF 23 73 FB 9B 47 52 84 DD AE 3F 3E 1E 18 D6 D0 BC E7 3D 59 5E 34 44 73 15 52 24 91 82 24 7B DE 6D E1 CA 28 8B 4E 2E 85 94 2A 24 3A D3 7F B7 F4 4A 1B 58 CD 8F 84 07 8D 07 BD 7D 11 87 D8 B1 5A 42 9A 6A F1 7F 89 68 36 A7 A2 06 41 13 9F F2 40 21 3E 50 6C F5 86 F8 8F 74 C4 AF 6B 8F CB 4D 31 E8 5E 5A DE E5 C4 92 C8 40 83 3A D5 E5 0E 1B C8 65 56 A2 0A C1 1B 5A E5 18 50 7B 9D 48 BD 9D 73 EF DE BA BC 70 58 13 59 4D 47 C1 D1 49 B5 25 54 7C 1B 3B F4 F4 84 ED 3A F7 64 33 02 18 3C 8A 85 4B FD 17 41 D2 DE 7C F4 37 38 B2 E7 C8 F9 26 3C 77 29 F2 75 EA 9D DB 08 38 D1 C4 C0 A6 A0 50 77 B0 70 AA 28 64 FD 2D 2C 72 49 7A 92 06 49 37 34 C0 C4 85 E2 98 32 7D 38 E4 FE 43 83 C4 68 A1 73 0F AA 5A B1 22 C2 F2 EB 79 82 BB D7 EA FA FF 28 1A 37 01 C7 4B 21 40 FD 12 CA 43 37 C7 6F 74 A7 82 CF 1C BD 14 D7 1C F7 AD 04 80 80 04 81 92 71 00 4E 0C 00 00 00 00 CE 05 02 03 05 05 05 02 02 02 CA D3 FD FB CC FD D4 DB 31 C8 83 51 DD 3F FC D8 02 C6 D0 C8 FC D0 DB FC E4 FB 34 CE C7 E8 CF DB D4 FC F8 D3 CF C8 D3 FD FC CB E0 31 FC DC CF DC DB 38 FC D7 AB 31 20 F4 EB D0 CC FC FC DC D3 DC D4 CB FC FC 03 78 78 38 C8 E4 FB FC C8 DB DB 38 FC DC DF D4 FC F9 FC F4 F8 C7 38 D4 D4 EF CB 38 CB D9 EF D8 CF FC EC C4 FF EF 38 C8 FC C8 D0 E7 D7 DC D8 EB DC D3 D4 E5 D0 C8 E5 D4 CA CD CB FC FC D9 E8 DB 52 12 DB D8 D8 C7 38 B5 39 C6 D8 DD 89 D4 0D 25 0D 25 0D 25 3A 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 80 80 79 15 16 10 12 1F 0E 1A 0B 15 0E 18 1F 11 22 19 10 1A 2A 2B 16 12 1B 09 10 20 0F 1F 11 1F 0A 1C 08 15 0F 1B 19 0C 22 2B 22 0B 10 1C 12 1C 2E 29 24 2A 2A 33 31 23 0B 30 0D 1B 29 22 0C 19 08 12 10 1B 38 10 38 38 0C 1B 38 0C 0E 1B 32 37 0E 1B 28 13 0A 2B 19 30 1B 17 16 2E 12 0A 34 14 15 0E 13 14 10 3C 1C 37 13 15 2E 0F 38 1E 33 1C 20 41 08 16 1A 0C 1B 20 1A 1E 0F 0D 00 00 43 0B FF 09 22 03 0B 05 09 02 05 05 09 0D 05 19 05 06 09 0A 01 04 04 11 09 05 06 09 12 04 03 06 01 03 06 0B 00 21 0B 05 18 01 03 00 02 01 08 02 01 12 0F 06 04 0C 04 19 03 04 04 0B 0B 2E 02 01 10 25 05 06 73 CC 44 82 59 69 38 33 5B 47 45 47 CE 66 41 BF A9 41 1B C8 F7 DB 63 09 8A 20 80 00 D5 E2 74 D3 C2 E0 DB 8F 60 A0 B3 97 FA 05 75 67 33 90 5F 92 4F
```

![Screen](../../Assets/OrangeCopy/OrangeCopy9.jpg)

## Step 5)
- go 'Edit' > 'Overwrite' > paste code hex and Apply

![Screen](../../Assets/OrangeCopy/OrangeCopy5e.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy8.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy10.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy11.jpg)

## Step 6) White Copy:
- go 'Select Range' > First Address: ```16CFBC3``` > Last Address: ```16CFD8B``` and Select

![Screen](../../Assets/OrangeCopy/OrangeCopy4.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy12.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy13.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy14.jpg)

## Step 7)
- go 'Edit' > 'Fill Overwrite' > Don't change anything and Apply

![Screen](../../Assets/OrangeCopy/OrangeCopy15.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy16.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy17.jpg)

## Step 8)
- go to the top left and press the last save icon

![Screen](../../Assets/OrangeCopy/OrangeCopy18.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy19.jpg)