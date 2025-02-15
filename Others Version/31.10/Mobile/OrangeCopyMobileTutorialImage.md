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
- go 'Select Range' > First Address: ```15372A0``` > Last Address: ```15377C0``` and Select

![Screen](../../Assets/OrangeCopy/OrangeCopy4.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy5.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy6.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy7.jpg)

## Step 4)
- copy code hex: 

```
8C 06 00 05 1A 88 05 18 00 00 00 00 10 0A 00 00 50 0F 60 03 4A 82 81 D4 1D 00 00 00 22 00 80 37 0C 00 00 78 09 00 00 78 09 A0 E8 F8 0C 0A 0C 0A 1E 00 F3 07 64 C1 00 00 00 00 30 14 4A EA 88 59 6C 1E 53 F2 D4 7A D0 32 1D BA B0 E5 63 3B 03 45 12 AD B0 68 C1 E5 7B 0B 62 98 67 C7 CB 73 78 2B B9 2C 83 6C 9B 9C D3 AC 8F 09 E1 55 C2 03 DD 1E 77 97 38 3F 4E 71 01 51 D6 34 38 36 28 AB 36 8F E8 94 7E 64 CD 44 DB B0 82 9C F5 0B 58 AF 30 FE F7 9A 5D 05 79 4F 32 C6 04 7A 8F D2 E2 2C 47 96 64 46 BB A7 87 8D F3 2B 3B D9 86 48 CF F8 C0 7E A2 47 CD F9 91 AC F4 14 14 FF A5 EF FF B4 9D C3 62 3E C1 62 D4 5D B4 64 A1 3A 0D 7F FD E4 FF 4D D0 B6 8F 4F 45 0F C8 40 A6 4C 87 54 4E DD 1B 08 A7 82 8D 3B 5D EC 88 E3 79 80 89 94 8D 17 E5 08 1C 0D 9E F0 D2 87 A5 9A CE C2 08 1F 44 A3 25 7D 41 AC C1 B9 48 21 AD 6A 2E AC 60 80 63 80 97 E8 38 79 43 2E C7 07 76 17 07 8C F1 E3 E9 AF 69 AF 06 C4 CB A4 AC 41 BC BE 28 26 00 55 00 4F 00 2C 00 3E 00 4A 00 67 00 72 00 52 00 4C 00 59 00 5C 00 4E 00 52 00 52 00 47 00 57 00 52 00 50 00 48 00 26 00 21 00 34 00 30 00 21 00 3B 00 14 00 36 00 06 00 21 00 7D 05 ED D1 7B 98 29 4A E2 71 0D ED D9 85 24 6B 22 58 22 09 7C DC D3 CE AC 51 E3 22 58 A5 6D 55 F8 70 6A 8A 1E 92 E4 EA E2 71 06 02 1C 00 FF FF FF FF FF FF FF FF A0 B0 38 5B 65 3D F1 8C 0B 01 00 03 FB 1B 17 03 13 01 14 05 12 02 00 09 18 06 15 07 11 13 04 08 10 0A 0E 0B 0C 0C 0D 0D 07 0E 08 0F 0B 10 0F 11 0A 12 09 04 03 14 06 15 19 16 02 17 16 18 1A 19 01 1A 05 1B 00 00 00 00 03 00 00 00 00 00 00 00 00 A2 81 64 93 34 4A 4B 77 55 DB 6A 49 CA A8 AD 7E 49 90 92 33 6E E1 E3 C0 4E 1B 89 6A 03 DE 52 50 00 6D 00 71 AE AD 52 D9 66 EB 92 E6 44 92 FA E4 9D 4D 0F 43 A9 95 39 DE 01 EE D3 A3 9D 9F 2A 89 56 92 B4 43 BC 2B 6A 2E 44 33 CF EA 55 AF A3 5B 9E F4 E8 21 0F AA DF 1E 9C 4E E5 E4 5B 64 EE 7F F3 08 A5 B4 D9 C7 8F F7 1B 85 35 74 6F 65 CB 56 16 0D D1 5C 05 4A 40 25 C8 56 36 5B F8 89 03 C9 A2 A3 3B 77 78 3C 2E 79 A7 8B FE 45 45 95 1B 03 D4 CC 0F A0 9D C6 9D 5E BE C0 21 0E AC 96 09 53 AB FE 2F 03 B3 39 AA 5A 0A 9A F9 B9 9C 10 E2 8D C4 56 EF C0 7F 64 00 BF AC 7B 5A 2E 4A 41 B7 DA F3 26 CF 2C 19 96 34 A8 A3 2D D7 74 4F 72 9E 15 68 29 78 87 55 0E 81 74 AF 13 D4 FB B9 EC DD 7B 97 41 D7 0C 6B F9 20 34 5E 01 D5 1E 32 B9 54 28 5A CA 38 E2 BF 5B 7E C1 1D 26 6C 3D E6 3F DD 23 F3 C8 1C 75 E9 49 8D 2E B1 CB DE 45 98 F0 32 A7 C9 8F B7 36 C2 0E 34 71 34 D5 D0 9A 4B 7B 3B 4D 55 53 93 F1 ED 43 96 73 B4 82 72 CB A5 A6 4B 10 CE 94 C9 C9 F4 E3 93 E5 4F 27 C0 D1 05 CC DD B9 66 C4 8B 13 CB BD E6 4D 57 AF DA FA FC A1 38 EE 81 C0 C8 A1 0E FA 24 50 8D 5F 1F B5 F3 9E 85 1C 3D 7A 39 AE 39 EF BD 04 80 80 04 81 92 71 00 4E 0C 80 02 00 00 CE 05 02 03 05 05 05 02 02 02 CA D3 FD FB CC FD D4 DB 31 C8 83 51 DD 3F FC D8 02 C6 D0 C8 FC D0 DB FC E4 FB 34 CE C7 E8 CF DB D4 FC F8 D3 CF C8 D3 FD FC CB E0 31 FC DC CF DC DB 38 FC D7 AB 31 20 F4 EB D0 CC FC FC DC D3 DC D4 CB FC FC 03 78 78 38 C8 E4 FB FC C8 DB DB 38 FC DC DF D4 FC F9 FC F4 F8 C7 38 D4 D4 EF CB 38 CB D9 EF 38 EF 38 EC C4 FF EF 38 C8 FC C8 D0 E7 DB CF D8 D7 DC D3 D4 E5 D0 C8 E5 D4 CA CD CB FC FC D9 E8 DB 52 12 DB D8 D8 C7 38 B5 29 C6 D8 DD 89 D4 0D 25 0D 25 0D 25 3A 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 0D 25 80 80 77 15 16 10 12 1F 0E 1A 0B 15 0E 18 1F 11 22 19 10 1A 2A 2B 16 12 1B 09 10 20 0F 1F 11 1F 0A 1C 08 15 0F 1B 19 0C 22 2B 22 0B 10 1C 12 1C 2E 29 24 2A 2A 33 31 23 0B 30 0D 1B 29 22 0C 19 08 12 10 1B 38 10 38 38 0C 1B 38 0C 0E 1B 32 37 0E 1B 28 13 12 30 1B 17 16 2E 12 0A 34 14 0D 1F 0E 1C 10 3C 1C 37 13 15 2E 0F 38 1E 33 1C 20 41 08 16 1A 0C 1B 20 19 1E 0F 0D 00 00 43 0B FF 09 22 03 0B 05 09 02 05 05 09 0D 05 19 05 06 09 0A 01 04 04 11 09 05 06 09 12 04 03 06 01 03 06 0B 00 21 0B 05 18 01 03 00 02 01 08 02 01 12 0F 06 01 04 19 03 04 04 07 04 10 2E 02 01 10 25 05 06 73 CC 44 82 59 69 38 33 5B 47 45 47 CE 66 41 BF A8 23 70 23 DF 6D 8C 22 28 80 18 50 2D 4E 37 09 83 D9 8F 60 A0 B3 97 FA 05 75 67 33 90 5F 92 4F
```

![Screen](../../Assets/OrangeCopy/OrangeCopy9.jpg)

## Step 5)
- go 'Edit' > 'Overwrite' > paste code hex and Apply

![Screen](../../Assets/OrangeCopy/OrangeCopy5e.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy8.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy10.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy11.jpg)

## Step 6) White Copy A:
- go 'Select Range' > First Address: ```1539FFA``` > Last Address: ```153A109``` and Select

![Screen](../../Assets/OrangeCopy/OrangeCopy4.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy12.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy13.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy14.jpg)

## Step 7)
- go 'Edit' > 'Fill Overwrite' > Don't change anything and Apply

![Screen](../../Assets/OrangeCopy/OrangeCopy15.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy16.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy17.jpg)

## Step 8) White Copy B:
- go 'Select Range' > First Address: ```1530A35``` > Last Address: ```1530BA5``` and Select

![Screen](../../Assets/OrangeCopy/OrangeCopy4.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy12.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy13.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy14.jpg)

## Step 9)
- go 'Edit' > 'Fill Overwrite' > Don't change anything and Apply

![Screen](../../Assets/OrangeCopy/OrangeCopy15.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy16.jpg)
![Screen](../../Assets/OrangeCopy/OrangeCopy17.jpg)

## Step 10) White Copy C:
- go 'Select Range' > First Address: ```15362A3``` > Last Address: ```153646B``` and Select

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