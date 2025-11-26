# Art Directory

## Purpose
All art assets for the Medieval Dark Fantasy Dungeon Crawler.

## Owner
Alex Cabrera (Artist Lead)

## Naming Conventions
- Meshes: `Mesh_[AssetName]` or `SK_[SkeletalMesh]`
- Static Meshes: `SM_[AssetName]`
- Materials: `MAT_[AssetName]` or `M_[AssetName]`
- Textures: `T_[AssetName]_[Type]` (e.g., T_Wall_Diffuse)
- Animations: `Anim_[Character]_[Action]`

## Technical Standards (Ref #16)
- Units: Centimeters
- Scale: 1.0 = 1 meter
- File naming must follow established prefixes

## Import Settings (Ref #17)
- Check smoothing, normals, tangents
- Combine meshes where appropriate
- Set collision type

## Content Budget (Ref #12)
- Max texture sizes defined
- Poly count limits per asset class
- Material limits
- Audio format and bitrate
- Streaming rules

## Style Guide (Ref #15)
- See /_References/StyleGuide/ for:
  - Color palette
  - Material library
  - Brush rules
  - PBR vs hand-painted guidance

## LOD Policy (Ref #30)
- Player: [Define LOD distances]
- Enemies: [Define LOD distances]
- Props: [Define LOD distances]
- Traps: [Define LOD distances]
