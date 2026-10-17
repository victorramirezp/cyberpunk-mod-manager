# CYBERMOD 2077 // Modular Catalog & Virtual Atelier Hub

> Aplicación web avanzada para la catalogación modular, gestión y orden de carga de mods de **Cyberpunk 2077**. Diseñada con estética Night City (paleta oscura `#08090d`, amarillo Kiroshi `#fcee0a`, cian `#00f0ff`, rojo Arasaka `#ff003c` y morado Neón `#b537f2`), 100% autocontenida en `index.html` y desplegada en **GitHub Pages**.

---

## ⚡ Estado Actual del Juego (65 Módulos Activos tras Depuración)

Tras el escaneo exhaustivo de `archive/pc/mod` (426 archivos `.archive`, 253 `.xl`), `r6/scripts`, `r6/tweaks`, `bin/x64/plugins` y `red4ext/plugins`, la base de datos predeterminada refleja **el estado exacto de mods activos instalados**:

| ID | Mod | Categoría Principal | Subcategoría | Origen | Atelier Ref | Crítico / Prescindible |
|---|---|---|---|---|---|:---:|
| **MOD_001** | Cyber Engine Tweaks (CET) | Core | Framework Motor | bin/x64/plugins/cyber_engine_tweaks | — | ❌ Crítico |
| **MOD_002** | RED4ext & Input Loader | Core | Framework Motor | red4ext/plugins & input_loader | — | ❌ Crítico |
| **MOD_003** | ArchiveXL | Core | Framework Motor | archive/pc/mod/ArchiveXL.archive & red4e | — | ❌ Crítico |
| **MOD_004** | TweakXL | Core | Framework Motor | red4ext/plugins/TweakXL & r6/tweaks | — | ❌ Crítico |
| **MOD_005** | Redscript | Core | Framework Motor | r6/scripts | — | ❌ Crítico |
| **MOD_006** | Codeware | Core | Framework Motor | red4ext/plugins/Codeware | — | ❌ Crítico |
| **MOD_007** | Equipment-EX | Core | Framework Customización | archive/pc/mod/EquipmentEx.archive & r6/ | — | ❌ Crítico |
| **MOD_008** | Virtual Atelier Framework | Core | Framework Tiendas | archive/pc/mod/VirtualAtelier.archive &  | — | ❌ Crítico |
| **MOD_009** | Appearance Change Unlocker (ACU) | Core | Framework Customización | red4ext/plugins/ACU & r6/scripts/appeara | — | ❌ Crítico |
| **MOD_010** | Appearance Menu Mod (AMM) | Core | Framework Customización | bin/x64/plugins/cyber_engine_tweaks/mods | — | ❌ Crítico |
| **MOD_011** | Native Settings UI & Mod Settings | Core | UI / Configuración | bin/.../nativeSettings & red4ext/plugins | — | ❌ Crítico |
| **MOD_012** | Virtual Car Dealer | Core | Framework Vehículos | archive/pc/mod/VirtualCarDealer.archive  | — | ❌ Crítico |
| **MOD_013** | Native Interactions Framework | Core | Framework Inmersión | archive/pc/mod/nativeInteractions.archiv | — | ❌ Crítico |
| **MOD_014** | Deceptious Quest Core | Core | Framework Quests | archive/pc/mod/zDeceptiousQuestCore.arch | — | ❌ Crítico |
| **MOD_015** | AudioXL & Material Override System | Core | Framework Motor | red4ext/plugins/AudioXL & ###_nim_materi | — | ❌ Crítico |
| **MOD_016** | Hyst Angel Body Mod (Fem V) | Fem_v | Cuerpo & Piel | archive/pc/mod/!!!!!!!05_Hyst_Angel_Body | — | ❌ Crítico |
| **MOD_017** | VTK Sienna Skin 4K & Microdetails | Fem_v | Cuerpo & Piel | archive/pc/mod/02_VTK_Hyst_SIENNA_Skin_T | — | ✔️ Prescindible |
| **MOD_018** | xBaebsae VanillaHD Head & Textures | Fem_v | Cuerpo & Piel | archive/pc/mod/xBaebsae_VanillaHD_Head.a | — | ✔️ Prescindible |
| **MOD_019** | Wingdeer & Vessnelle Hair Megapack | Fem_v | Pelo & Belleza | archive/pc/mod/WINGDEER_FemV_HAIR_* & ve | — | ✔️ Prescindible |
| **MOD_020** | Piercings Megapack (PRC Framework 128) | Fem_v | Piercings & Tatuajes | archive/pc/mod/PRC_f_* (28 archivos de j | — | ✔️ Prescindible |
| **MOD_021** | Storytattoo Black Ink Tattoo Suite | Fem_v | Piercings & Tatuajes | archive/pc/mod/Storytattoo_Body_Black_F. | — | ✔️ Prescindible |
| **MOD_022** | Arkhe Makeup & Eyebrow Enhancers | Fem_v | Pelo & Belleza | archive/pc/mod/!_Arkhe_MAKEUP_Enhancer.a | — | ✔️ Prescindible |
| **MOD_023** | Gymfiend [VTK] Body & Refits (Mas V) | Mas_v | Cuerpo & Piel | archive/pc/mod/02_Gymfiend_[VTK]_v.1.4.2 | — | ❌ Crítico |
| **MOD_024** | 02_MV_Head [VTK] & Gauged Ears MASC | Mas_v | Cuerpo & Piel | archive/pc/mod/02_MV_Head_[VTK].archive  | — | ✔️ Prescindible |
| **MOD_025** | PinkyDude Male V Facial Expressions | Mas_v | Expresiones & Animación | archive/pc/mod/PinkyDude_ANIM_FacialExpr | — | ✔️ Prescindible |
| **MOD_026** | Veegee Casual & Streetwear Outfits | Fem_v | Ropa: Veegee | archive/pc/mod/Casual Style Outfit Pt36/ | Veegee Atelier | ✔️ Prescindible |
| **MOD_027** | Veegee Chic & Elegant Collection | Fem_v | Ropa: Veegee | archive/pc/mod/Chic And Elegant Style Ou | Veegee Atelier | ✔️ Prescindible |
| **MOD_028** | Veegee Cyber Samurai Armor & Netrunner Suits | Fem_v | Ropa: Veegee | archive/pc/mod/Cyber Samurai Armor & 001 | Veegee Atelier | ✔️ Prescindible |
| **MOD_029** | PeachuXL Fashion, Gothic Sets & Tech Bodysuits | Fem_v | Ropa: Peachu & Nemie | archive/pc/mod/Peachu - Chains Top, Goth | PeachuXL Atelier | ✔️ Prescindible |
| **MOD_030** | Nemiepies Varsity & Butterfly Heels | Fem_v | Ropa: Peachu & Nemie | archive/pc/mod/Nemiepies Varsity Set.arc | PeachuXL Atelier | ✔️ Prescindible |
| **MOD_031** | Nola Dreamer Boutique & Lingerie | Fem_v | Ropa: Nola Dreamer | archive/pc/mod/ND_female_virtual_boutiqu | Nola Dreamer Boutique | ✔️ Prescindible |
| **MOD_032** | Nola and Aquelyras Atelier & Goth Footwear | Fem_v | Ropa: Nola Dreamer | archive/pc/mod/ND_Aquelyras_goth_shoes_F | Nola Dreamer Boutique | ✔️ Prescindible |
| **MOD_033** | Atomiic Shop CeleXstar, Valby & Sharen Outfits | Fem_v | Ropa: Atomiic | archive/pc/mod/Atomiic Shop.archive & r6 | Atomiic Store | ✔️ Prescindible |
| **MOD_034** | Axellysse Virtual Atelier 1 & 2 Boutiques | Fem_v | Ropa: Axellysse & Meluminary | archive/pc/mod/axellysse_virtual_atelier | Axellysse / Meluminary | ✔️ Prescindible |
| **MOD_035** | Meluminary Fashion & High-Knee Socks | Fem_v | Ropa: Axellysse & Meluminary | archive/pc/mod/MELUMINARY - Over The Kne | Axellysse / Meluminary | ✔️ Prescindible |
| **MOD_036** | Dusty Virtual Atelier Suit Collection | Fem_v | Ropa: Dusty | archive/pc/mod/Dusty_FreynaUltimateSuit  | Dusty Atelier | ✔️ Prescindible |
| **MOD_037** | Raem Atelier Pearls, Valentino Gear & Holsters | Fem_v | Ropa: Raem | archive/pc/mod/rm_!atelier_accessories_* | Raem Atelier | ✔️ Prescindible |
| **MOD_038** | Hyst Atelier Store Dresses & Refits | Fem_v | Ropa: Hyst & HeRa | archive/pc/mod/Hyst_Atelier_Store.archiv | Hyst Atelier Store | ✔️ Prescindible |
| **MOD_039** | HeRa Atelier & Melgardens Lingerie | Fem_v | Ropa: Hyst & HeRa | archive/pc/mod/HeRa Atelier.archive & me | HeRa Atelier | ✔️ Prescindible |
| **MOD_040** | Sanchez Boutique, Sumi & Masuryan Stores | Fem_v | Ropa: Sanchez, Sumi & Otros | archive/pc/mod/sanchezvirtualboutique &  | Sanchez Boutique | ✔️ Prescindible |
| **MOD_041** | V49 Footwear Megapack & Nike Sneaker Collection | Fem_v | Calzado & Sneakers | archive/pc/mod/vault_49_virtual_atelier. | V49 Footwear Atelier | ✔️ Prescindible |
| **MOD_042** | Bugatti Tourbillon V16 | Vehiculos | Superdeportivos (Virtual Car Dealer) | archive/pc/mod/MAXSA5 --- Bugatti_Tourbi | — | ✔️ Prescindible |
| **MOD_043** | Ferrari Daytona SP3 | Vehiculos | Superdeportivos (Virtual Car Dealer) | archive/pc/mod/ferrari_daytona & r6/twea | — | ✔️ Prescindible |
| **MOD_044** | Shelby Cobra 427 S/C | Vehiculos | Superdeportivos (Virtual Car Dealer) | archive/pc/mod/Okrasha_Shelby_Cobra_427. | — | ✔️ Prescindible |
| **MOD_045** | Kawasaki Ninja ZX-10R | Vehiculos | Motos Deportivas | r6/tweaks/kawasaki_ninja/kawasaki_ninja. | — | ✔️ Prescindible |
| **MOD_046** | Enhanced Vehicle Camera | Vehiculos | Cámara de Vehículos | bin/x64/plugins/cyber_engine_tweaks/mods | — | ✔️ Prescindible |
| **MOD_047** | Romance Hangouts Enhanced (Judy, Panam & Meredith) | Historia | Romances Extendidos | archive/pc/mod/#RomanceHangoutsEnhanced  | — | ✔️ Prescindible |
| **MOD_048** | Non-Canon Romances Enhanced | Historia | Romances Extendidos | archive/pc/mod/#NonCanonRomancesEnhanced | — | ✔️ Prescindible |
| **MOD_049** | Quest Add-on: Mai Hasegawa | Historia | Misiones Adicionales | archive/pc/mod/zGetTenSOMaiHasegawa.arch | — | ✔️ Prescindible |
| **MOD_050** | Luxe Corpo Plaza & Palapas Tower Apartments | Historia | Apartamentos de Lujo | archive/pc/mod/luxe_corpoplaza_apartment | — | ✔️ Prescindible |
| **MOD_051** | The Glen Project Luxury Garage & Mansion DLC | Historia | Apartamentos de Lujo | archive/pc/mod/TheGlenProject_GarageAddo | — | ✔️ Prescindible |
| **MOD_052** | HoloMemories BD Companion | Historia | Misiones Adicionales | archive/pc/mod/HoloMemories.archive & r6 | — | ✔️ Prescindible |
| **MOD_053** | Cyberware-EX & Enhanced Capacity | Gameplay | Ciberware & Brazos Modulares | r6/scripts/CyberwareEx & Enhanced Cyberw | — | ✔️ Prescindible |
| **MOD_054** | KiasuBurger Faction Cyberarms (Arasaka, Tyger & Valentino) | Gameplay | Ciberware & Brazos Modulares | r6/scripts/kiasu-burger-* & bin/.../Cybe | KiasuBurger Cyberware | ✔️ Prescindible |
| **MOD_055** | Immersive Third Person (ITP Complete Suite) | Gameplay | Cámara en Tercera Persona (ITP) | archive/pc/mod/immersive_third_person &  | — | ✔️ Prescindible |
| **MOD_056** | Actual Blackwall Quickhacks & Low Cost | Gameplay | Combate & Armas | archive/pc/mod/Actual_Blackwall_Quickhac | — | ✔️ Prescindible |
| **MOD_057** | Stealth Finishers & ZKV Takedowns 2 | Gameplay | Combate & Armas | r6/scripts/ZKVTakedowns2 & bin/.../ZKVTa | — | ✔️ Prescindible |
| **MOD_058** | Silent Silencers & Retrievable Weapon Mods | Gameplay | Combate & Armas | archive/pc/mod/SilentSilencers.archive & | — | ✔️ Prescindible |
| **MOD_059** | Katana Iaido & JChimera Laser Perks | Gameplay | Combate & Armas | archive/pc/mod/KatanaIaido_SlashWarp & r | — | ✔️ Prescindible |
| **MOD_060** | Night City World Immersion & Vendors | Gameplay | Inmersión en Night City & Vendedores | archive/pc/mod/ImmersiveBartenders, Imme | — | ✔️ Prescindible |
| **MOD_061** | Quality of Life Suite (First Equip, Elevators & Stash) | Gameplay | Calidad de Vida | archive/pc/mod/AlwaysFirstEquip.archive, | — | ✔️ Prescindible |
| **MOD_062** | Nova LUT 4.0 & LUT Switcher Suite | Graficos | LUTs & Iluminación | archive/pc/mod/###-NovaLUT4.archive & bi | — | ✔️ Prescindible |
| **MOD_063** | Edge LUT 3 & Nova City 2 | Graficos | LUTs & Iluminación | archive/pc/mod/#####-EdgeLUT3.archive &  | — | ✔️ Prescindible |
| **MOD_064** | Preem Map 3D Scanner & Minimap Tweaks | Graficos | Mapas & Overrides | archive/pc/mod/###-PreemMap.archive & ba | — | ✔️ Prescindible |
| **MOD_065** | More Occluders & More Gore V3.0 | Graficos | Mapas & Overrides | archive/pc/mod/MoreOccluders.archive & M | — | ✔️ Prescindible |

---

## 🛍️ Directorio Virtual Atelier In-Game (52 Endpoints Activos)

El catálogo web sincroniza las tiendas registradas mediante scripts Redscript (`r6/scripts`) en el navegador de Valerie y Vincent:

1. **Veegee Atelier Suite** (5 tiendas: Casual, Chic & Elegant, Netrunner Pt6/Pt7, Samurai Armor, Yujin Heels & Joyería - 600+ items).
2. **PeachuXL & Nemiepies Atelier** (Gothic Sets, Afterlife, Long Dress, Chains Top, Varsity bomber y Butterfly Heels).
3. **Nola Dreamer & Aquelyras** (4 tiendas: Female Boutique, Male Boutique, Accessories Store, Nola and Aquelyras - 1,200+ items).
4. **Atomiic Shop** (Sets completos Valby A-Girls, Sharen CeleXstar, Gley, Bunny Corsets, Maid outfits, Urban Sprinter - 850+ items).
5. **Axellysse & Meluminary Boutiques** (7 tiendas: Tops de cadenas, monos romper, medias altas, bodysuits deportivos - 1,500+ items).
6. **Dusty Virtual Atelier** (Trajes cibernéticos Freyna Ultimate, Viper Suits, Bunny Suits y chaqueta de Leon Kennedy).
7. **Raem Atelier** (6 tiendas: Cartucheras de pistola Valentino, collares de perlas, colgantes bala V, relojes Claire/Reyes - 1,500+ items).
8. **Hyst Atelier Store** (Vestidos Seduce, vestidos elegantes de noche, medias de rejilla y trajes navideños adaptados a Angel Body).
9. **HeRa Atelier & Melgardens** (Botas altas Pucii, bodysuits Desire, slip dresses Nivola y lencería Marselle).
10. **Sanchez Boutique, Sumi & Masuryan** (Minivestidos plisados tubo, tacones slingback, chaquetas Pozer Corpo y vestidos Sunrise).
11. **V49 Footwear Atelier & Nike Collection** (Megapack de tacones altos con lazos y gemas + Nike Air Jordan 4 y Air Max Plus).
12. **KiasuBurger Cyberware Suite** (6 tiendas temáticas con brazos de Johnny Silverhand, Songbird, Arasaka, Valentino y Tyger Claws).
13. **All Vanilla Clothes Stores** (2 tiendas con más de 1,500 prendas de ropa del juego base y Phantom Liberty).
14. **TonyDiz, Tottes, Deadlink, Alvarix, KMKC2 & The Bean Trunk** (Tiendas especializadas de ropa casual, cyberwear y accesorios).

---

## 🏎️ Concesionario Virtual & Superdeportivos

Soporte completo para superdeportivos y motos deportivas adquiribles a través del **Virtual Car Dealer**:
- **Bugatti Tourbillon V16** (1800 CV, sonido custom e interior detallado).
- **Ferrari Daytona SP3** (V12 atmosférico con alerón activo).
- **Shelby Cobra 427 S/C** (Clásico descapotable de competición).
- **Kawasaki Ninja ZX-10R** (Superbike de alta velocidad).
- **Enhanced Vehicle Camera** (Control de cámara libre y FOV en tercera persona).

---

## ⚔️ Gameplay, Combate & Ciberware

- **Immersive Third Person (ITP Complete Suite)**: Cámara en tercera persona con combate fluido, movimiento 360°, sincronización labial y compatibilidad con armaduras.
- **Actual Blackwall Quickhacks & Low Cost**: Hacks del Muro Negro con propagación en cadena devastadora.
- **Stealth Finishers & ZKV Takedowns 2**: Animaciones ampliadas de derribo sigiloso con katanas, cuchillos y manos desnudas.
- **Cyberware-EX**: Ampliación de slots cibernéticos para equipar múltiples sistemas operativos.
- **Night City World Immersion**: Interacción visual completa en bares, puestos de comida, matasanos y apartamento de Viktor Vector.

---

## 🚀 Despliegue en GitHub Pages

- **URL de Producción:** [https://victorramirezp.github.io/cyberpunk-mod-manager/](https://victorramirezp.github.io/cyberpunk-mod-manager/)
- **Repositorio:** [https://github.com/victorramirezp/cyberpunk-mod-manager](https://github.com/victorramirezp/cyberpunk-mod-manager)

---

*Desarrollado para la comunidad de modding de Cyberpunk 2077.*
