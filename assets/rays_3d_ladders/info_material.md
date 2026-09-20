# Notes for LabPBR Material Standard
## Infos
[LabPBR Material Standard Specular Texture](https://shaderlabs.org/wiki/LabPBR_Material_Standard#Specular_Texture_(_s))  

Red Channel = 0 - 255 (smoothness) // 255 = 100% smoothness  
Green Channel = 0 - 255 (reflectance) // 230+ Metals // 229 = 100% reflectance  
Blue Channel = 0 - 64 (porosity) // 64 = 100% porosity // water absorption  
Blue Channel = 65 - 255 (subsurface scattering) // 255 = 100% scattering  
Alpha Channel = 0 - 254 (emissive) // 255 = 0 // 254 = 100% emissive

`Alpha channel in gimp -> Colors -> Components -> Decompose -> Color model = RGBA`

## Metals

- **Brass**  
Red   140 #8c8c8c  
Green 120 #787878  
Blue  0  
Alpha 255  

- **Copper**  
  Red = 170 #aaaaaa  
  Green = 234 #eaeaea  
  Blue = 0

- **Exposed Copper**  
  Red = 110  #6e6e6e  
  Green = 180 #b4b4b4  
  Blue = 0

- **Weathered Copper**  
  Red = 60 #3c3c3c  
  Green = 80 #505050  
  Blue = 0

- **Oxidized Copper**  
  Red = 20 #141414  
  Green = 0  
  Blue = 0

- **Iron**
Red   200 #c8c8c8  
Green 230 #e6e6e6  
Blue  0  
Alpha 255  

- **Industrial Iron**
Red   90 #5a5a5a2  
Green 140 #8c8c8c  
Blue  0  
Alpha 255  

- **Zinc**
Red   130 #828282  
Green 235 #ebebeb  
Blue  0  
Alpha 255  

## Materials

- **Wood**  
Red   40 #282828
Green 0  
Blue  12 #0c0c0c  
Alpha 255  

- **Burnt Wood**  
  Red   40 #282828
  Green 0  
  Blue  12 #0c0c0c  
  Alpha 255

- **Andesite**  
Red   80  #505050  
Green 0  
Blue  0  
Alpha 255  

- **Plant**
Red   25
Green 0
Blue  52
Alpha 255