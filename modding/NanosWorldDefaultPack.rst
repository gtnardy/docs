.. _NanosWorldDefaultPack:

*******************************
Nanos World Default Assets Pack
*******************************


nanos world provides a default Asset Pack already included in the base game, feel free to use the assets the way you want:

.. tip:: The following list is constantly updated and it's presentation will be improved soon™.


.. code-block:: toml

    # Assets Files
    [assets]
        # Maps
        [assets.maps]
        BlankMap = "Maps/BlankMap/BlankMap"
        TestingMap = "Maps/Testing/NanosTestingMap"

        # Static Meshes
        [assets.static_meshes]
        SM_Cone = "Props/BasicShapes/SM_Cone"
        SM_Cube = "Props/BasicShapes/SM_Cube"
        SM_Cylinder = "Props/BasicShapes/SM_Cylinder"
        SM_Plane = "Props/BasicShapes/SM_Plane"
        SM_Sphere = "Props/BasicShapes/SM_Sphere"

        SM_Ball_VR = "Props/VRShapes/SM_Ball"
        SM_Cube_VR_01 = "Props/VRShapes/SM_Cube_01"
        SM_Cube_VR_02 = "Props/VRShapes/SM_Cube_02"
        SM_Cube_VR_03 = "Props/VRShapes/SM_Cube_03"
        SM_Pyramid_VR = "Props/VRShapes/SM_Pyramid"

        SM_Error = "Props/Utils/SM_Error"
        SM_None = "Props/Utils/SM_None"

        SM_PlasticBarrel_01 = "Art/City/Construction_Props/Mesh/SM_PlasticBarrel_01"
        SM_RockingChair = "Art/City/House_Props/Meshes/SM_RockingChair"
        SM_RoundStand = "Art/City/House_Props/Meshes/SM_RoundStand"
        SM_Bottle_01 = "Art/Rural/InteriorDecoration/SM_Bottle_01"
        SM_Bottle_02 = "Art/Rural/InteriorDecoration/SM_Bottle_02"
        SM_Bottle = "Art/Rural/Extra/SM_Bottle"
        SM_Bunny = "Art/City/House_Props/Meshes/SM_Bunny"
        SM_CupC = "Art/City/House_Props/Meshes/KitchenWare/SM_CupC"
        SM_OilLamp = "Art/Rural/InteriorDecoration/SM_OilLamp"
        SM_PlierSet_01 = "Art/City/Construction_Props/Mesh/SM_PlierSet_01"
        SM_PliersSet_07 = "Art/City/Construction_Props/Mesh/SM_PliersSet_07"
        SM_Saw_01 = "Art/City/Construction_Props/Mesh/SM_Saw_01"
        SM_BarrelTub = "Art/Rural/Extra/SM_BarrelTub"
        SM_CoffeeTable = "Art/City/House_Props/Meshes/SM_CoffeeTable"
        SM_Crate_Base_01 = "Art/City/Construction_Props/Mesh/SM_Crate_Base_01"
        SM_Crate_Lid_01 = "Art/City/Construction_Props/Mesh/SM_Crate_Lid_01"
        SM_Toolbox_01 = "Art/City/Construction_Props/Mesh/SM_Toolbox_01"
        SM_Toolbox_06 = "Art/City/Construction_Props/Mesh/SM_Toolbox_06"
        SM_VaseA = "Art/City/House_Props/Meshes/Vases/SM_VaseA"
        SM_CupD = "Art/City/House_Props/Meshes/KitchenWare/SM_CupD"
        SM_Crate_01 = "Art/City/Construction_Props/Mesh/SM_Crate_01"

        SM_Eye = "Characters/Common/BodyParts/Eyes/SM_Eye"
        SM_Beard_Extra = "Characters/Common/BodyParts/Beard/SM_Beard_Extra"
        SM_Beard_Middle = "Characters/Common/BodyParts/Beard/SM_Beard_Middle"
        SM_Beard_Mustache_01 = "Characters/Common/BodyParts/Beard/SM_Beard_Mustache_01"
        SM_Beard_Mustache_02 = "Characters/Common/BodyParts/Beard/SM_Beard_Mustache_02"
        SM_Beard_Side = "Characters/Common/BodyParts/Beard/SM_Beard_Side"
        SM_Hair_Long = "Characters/Common/BodyParts/Hair/Male/SM_Hair_Long"
        SM_Hair_Short = "Characters/Common/BodyParts/Hair/Male/SM_Hair_Short"
        SM_Hair_Kwang = "Characters/Common/BodyParts/Hair/Kwang/SM_Hair_Kwang"

        SM_AK47_Mag_Empty = "Weapons/Rifles/AK47/SM_AK47_Mag_Empty"
        SM_AK74U_Mag_Empty = "Weapons/Rifles/AK74U/SM_AK74U_Mag_Empty"
        SM_GE36_Mag_Empty = "Weapons/Rifles/GE36/SM_GE36_Mag_Empty"
        SM_Glock_Mag_Empty = "Weapons/Pistols/Glock/SM_Glock_Mag_Empty"
        SM_DesertEagle_Mag_Empty = "Weapons/Pistols/DesertEagle/SM_DesertEagle_Mag_Empty"
        SM_AP5_Mag_Empty = "Weapons/Rifles/AP5/SM_AP5_Mag_Empty"
        SM_AR4_Mag_Empty = "Weapons/Rifles/AR4/SM_AR4_Mag_Empty"

        SM_T4_Sight = "Weapons/Common/Accessories/SM_T4_Sight"
        SM_Vertgrip = "Weapons/Common/Accessories/SM_Vertgrip"
        SM_Suppressor = "Weapons/Common/Accessories/SM_Suppressor5"
        SM_Scope_25x56_X = "Weapons/Common/Accessories/SM_Scope_25x56_X"

        SM_WoodenTable = "Art/Rural/InteriorDecoration/SM_WoodenTable"
        SM_WoodenChair = "Art/Rural/InteriorDecoration/SM_WoodenChair"
        SM_TireLarge = "Art/Rural/Extra/SM_TireLarge"
        SM_Stool = "Art/Rural/InteriorDecoration/SM_Stool"
        SM_TeaPot_Interior = "Art/Rural/InteriorDecoration/SM_TeaPot_Interior"
        SM_OilDrum = "Art/Rural/ExteriorDecoration/SM_OilDrum"
        SM_Bucket5Gallon = "Art/Rural/Extra/SM_Bucket5Gallon"
        SM_Crate_07 = "Art/Rural/Extra/SM_Crate_07"
        SM_Crate_03 = "Art/Rural/InteriorDecoration/SM_Crate_03"
        SM_Crate_04 = "Art/Rural/InteriorDecoration/SM_Crate_04"
        SM_Pot_01 = "Art/Rural/InteriorDecoration/SM_Pot_01"
        SM_Pot_02 = "Art/Rural/InteriorDecoration/SM_Pot_02"
        SM_Plate_Interior = "Art/Rural/InteriorDecoration/SM_Plate_Interior"
        SM_Barrel_02 = "Art/Rural/Extra/SM_Barrel_02"
        SM_Bamboo_Roof45_Right = "Art/Rural/HouseModular/SM_Bamboo_Roof45_Right"
        SM_MetalBucket_Interior_02 = "Art/Rural/InteriorDecoration/SM_MetalBucket_Interior_02"
        SM_Basket_01 = "Art/Rural/InteriorDecoration/SM_Basket_01"
        SM_Bamboo_Woodplank_01 = "Art/Rural/Extra/SM_Bamboo_Woodplank_01"

        SM_Grenade_G67 = "Weapons/Grenades/G67/SM_G67"
        SM_Torch = "Weapons/Torch/SM_Torch"

        SM_Tire_01 = "Vehicles/Common/Meshes/SM_Tire_01"

        # Skeletal Meshes
        [assets.skeletal_meshes]
        SK_Female = "Characters/Female/SK_Female"
        SK_Male = "Characters/Male/SK_Male"
        SK_Mannequin = "Characters/Mannequin/SK_Mannequin"
        SK_PostApocalyptic = "Characters/PostApocalyptic/SK_PostApocalyptic"
        SK_ClassicMale = "Characters/ClassicMale/SK_ClassicMale"

        SK_Shirt = "Characters/Common/BodyParts/Clothes/Shirt/SK_Shirt"
        SK_Underwear = "Characters/Common/BodyParts/Clothes/Underwear/SK_Underwear"
        SK_Pants = "Characters/Common/BodyParts/Clothes/Pants/SK_Pants"
        SK_Shoes_01 = "Characters/Common/BodyParts/Clothes/Shoes/SK_Shoes_01"
        SK_Shoes_02 = "Characters/Common/BodyParts/Clothes/Shoes/SK_Shoes_02"
        SK_Tie = "Characters/Common/BodyParts/Clothes/Tie/SK_Tie"
        SK_CasualSet = "Characters/Common/BodyParts/Clothes/CasualSet/SK_CasualSet"
        SK_Sneakers = "Characters/Common/BodyParts/Clothes/Shoes/SK_Sneakers"

        SK_Error = "Props/Utils/SK_Error"
        SK_None = "Props/Utils/SK_None"

        SK_AK47 = "Weapons/Rifles/AK47/SK_AK47"
        SK_AK74U = "Weapons/Rifles/AK74U/SK_AK74U"
        SK_GE36 = "Weapons/Rifles/GE36/SK_GE36"
        SK_Glock = "Weapons/Pistols/Glock/SK_Glock"
        SK_DesertEagle = "Weapons/Pistols/DesertEagle/SK_DesertEagle"
        SK_AR4 = "Weapons/Rifles/AR4/SK_AR4"
        SK_Moss500 = "Weapons/Shotguns/Moss500/SK_Moss500"
        SK_AP5 = "Weapons/Rifles/AP5/SK_AP5"
        SK_SMG11 = "Weapons/SMGs/SMG11/SK_SMG11"

        SK_Pickup = "Vehicles/Variety/Pickup/SK_Pickup"
        SK_SUV = "Vehicles/Variety/SUV/SK_SUV"
        SK_Truck_Box = "Vehicles/Variety/Truck/SK_Truck_Box"
        SK_Truck_Chassis = "Vehicles/Variety/Truck/SK_Truck_Chassis"
        SK_SportsCar = "Vehicles/Variety/SportsCar/SK_SportsCar"
        SK_Hatchback = "Vehicles/Variety/Hatchback/SK_Hatchback"

        # Sound Assets
        [assets.sounds]
        A_SMG_Dry = "Weapons/Common/Audios/A_SMG_Dry_Cue"
        A_Rifle_Dry = "Weapons/Common/Audios/A_Rifle_Dry_Cue"
        A_Pistol_Dry = "Weapons/Common/Audios/A_Pistol_Dry_Cue"
        A_Shotgun_Dry = "Weapons/Common/Audios/A_Shotgun_Dry_Cue"
        A_SMG_Load = "Weapons/Common/Audios/A_SMG_Load_Cue"
        A_Rifle_Load = "Weapons/Common/Audios/A_Rifle_Load_Cue"
        A_Pistol_Load = "Weapons/Common/Audios/A_Pistol_Load_Cue"
        A_Shotgun_Load_Bullet = "Weapons/Common/Audios/A_Shotgun_Load_Bullet_Cue"
        A_SMG_Unload = "Weapons/Common/Audios/A_SMG_Unload_Cue"
        A_Rifle_Unload = "Weapons/Common/Audios/A_Rifle_Unload_Cue"
        A_Pistol_Unload = "Weapons/Common/Audios/A_Pistol_Unload_Cue"
        A_AimZoom = "Weapons/Common/Audios/Rattle/A_AimZoom_Cue"
        A_Rattle = "Weapons/Common/Audios/Rattle/A_Rattle_Cue"
        A_M4A1_Shot = "Weapons/Common/Audios/A_M4A1_Shot_Cue"
        A_AK47_Shot = "Weapons/Common/Audios/A_AK47_Shot_Cue"
        A_Glock_Shot = "Weapons/Common/Audios/A_Glock_Shot_Cue"
        A_Rifle_Shot = "Weapons/Common/Audios/A_Rifle_Shot_Cue"
        A_DesertEagle_Shot = "Weapons/Common/Audios/A_DesertEagle_Shot_Cue"
        A_Shotgun_Shot = "Weapons/Common/Audios/A_Shotgun_Shot_Cue"
        A_LightMachine_Shot = "Weapons/Common/Audios/A_LightMachine_Shot_Cue"
        A_SMG_Shot = "Weapons/Common/Audios/A_SMG_Shot_Cue"
        A_Explosion_Large = "Weapons/Common/Audios/A_Explosion_Large_Cue"

        A_Male_Death = "Characters/Common/Audios/Death/A_Male_Death_Cue"
        A_Character_Damage_Taken = "Characters/Common/Audios/Pain/A_Character_Damage_Taken"

        A_VR_Click_01 = "Effects/VR/A_VR_Click_01"
        A_VR_Click_02 = "Effects/VR/A_VR_Click_02"
        A_VR_Click_03 = "Effects/VR/A_VR_Click_03"
        A_VR_Close = "Effects/VR/A_VR_Close"
        A_VR_Confirm = "Effects/VR/A_VR_Confirm"
        A_VR_Grab = "Effects/VR/A_VR_Grab"
        A_VR_Ungrab = "Effects/VR/A_VR_Ungrab"
        A_VR_Negative = "Effects/VR/A_VR_Negative"
        A_VR_Open = "Effects/VR/A_VR_Open"
        A_VR_Teleport = "Effects/VR/A_VR_Teleport"

        A_Vehicle_Brake = "Vehicles/Common/Sounds/A_Vehicle_Brake_Cue"
        A_Vehicle_Horn_Bike_01 = "Vehicles/Common/Sounds/Horns/A_Vehicle_Horn_Bike_01"
        A_Vehicle_Horn_Bike_02 = "Vehicles/Common/Sounds/Horns/A_Vehicle_Horn_Bike_02"
        A_Vehicle_Horn_Bike_03 = "Vehicles/Common/Sounds/Horns/A_Vehicle_Horn_Bike_03"
        A_Vehicle_Horn_Dixie = "Vehicles/Common/Sounds/Horns/A_Vehicle_Horn_Dixie"
        A_Vehicle_Horn_Toyota = "Vehicles/Common/Sounds/Horns/A_Vehicle_Horn_Toyota"
        A_Vehicle_Door = "Vehicles/Common/Sounds/A_Vehicle_Door_Cue"
        A_Car_Engine_Start = "Vehicles/Common/Sounds/A_Car_Engine_Start_Cue"
        A_Vehicle_Engine_01 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_01"
        A_Vehicle_Engine_02 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_02"
        A_Vehicle_Engine_03 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_03"
        A_Vehicle_Engine_04 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_04"
        A_Vehicle_Engine_05 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_05"
        A_Vehicle_Engine_06 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_06"
        A_Vehicle_Engine_07 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_07"
        A_Vehicle_Engine_08 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_08"
        A_Vehicle_Engine_09 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_09"
        A_Vehicle_Engine_10 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_10"
        A_Vehicle_Engine_11 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_11"
        A_Vehicle_Engine_12 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_12"
        A_Vehicle_Engine_13 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_13"
        A_Vehicle_Engine_14 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_14"
        A_Vehicle_Engine_15 = "Vehicles/Common/Sounds/Engine/A_Vehicle_Engine_15"

        # Animation Assets
        [assets.animations]
        AM_Mannequin_Reload_Pistol = "Characters/Common/Animations/Weapons/AM_Mannequin_Reload_Pistol"
        AM_Mannequin_Reload_Rifle = "Characters/Common/Animations/Weapons/AM_Mannequin_Reload_Rifle"
        AM_Mannequin_Reload_Shotgun = "Characters/Common/Animations/Weapons/AM_Mannequin_Reload_Shotgun"
        AM_Mannequin_Sight_Fire = "Characters/Common/Animations/Weapons/AM_Mannequin_Sight_Fire"
        AM_Mannequin_Sight_Fire_Heavy = "Characters/Common/Animations/Weapons/AM_Mannequin_Sight_Fire_Heavy"

        AM_Mannequin_Taunt_YouHere = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_YouHere"
        AM_Mannequin_Taunt_Bow = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Bow"
        AM_Mannequin_Taunt_ButtSlap_01 = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_ButtSlap_01"
        AM_Mannequin_Taunt_ButtSlap_02 = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_ButtSlap_02"
        AM_Mannequin_Taunt_CallMe = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_CallMe"
        AM_Mannequin_Taunt_Chop = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Chop"
        AM_Mannequin_Taunt_Clap = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Clap"
        AM_Mannequin_Taunt_ComeAtMe = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_ComeAtMe"
        AM_Mannequin_Taunt_CrossArms = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_CrossArms"
        AM_Mannequin_Taunt_Crutch = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Crutch"
        AM_Mannequin_Taunt_Dab = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Dab"
        AM_Mannequin_Taunt_DustOff = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_DustOff"
        AM_Mannequin_Taunt_EarCom = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_EarCom"
        AM_Mannequin_Taunt_EyesOnYou = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_EyesOnYou"
        AM_Mannequin_Taunt_FacePalm = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_FacePalm"
        AM_Mannequin_Taunt_FingerGun = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_FingerGun"
        AM_Mannequin_Taunt_FistCrush = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_FistCrush"
        AM_Mannequin_Taunt_FistPump_01 = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_FistPump_01"
        AM_Mannequin_Taunt_FistPump_02 = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_FistPump_02"
        AM_Mannequin_Taunt_Flex_01 = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Flex_01"
        AM_Mannequin_Taunt_Flex_02 = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Flex_02"
        AM_Mannequin_Taunt_Flex_03 = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Flex_03"
        AM_Mannequin_Taunt_Halt = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Halt"
        AM_Mannequin_Taunt_HandOnHips = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_HandOnHips"
        AM_Mannequin_Taunt_HandPunch = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_HandPunch"
        AM_Mannequin_Taunt_Heart = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Heart"
        AM_Mannequin_Taunt_Jog = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Jog"
        AM_Mannequin_Taunt_Jojo = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Jojo"
        AM_Mannequin_Taunt_Knees = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Knees"
        AM_Mannequin_Taunt_Kunfu = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Kunfu"
        AM_Mannequin_Taunt_NeckSlit = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_NeckSlit"
        AM_Mannequin_Taunt_OK = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_OK"
        AM_Mannequin_Taunt_Point = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Point"
        AM_Mannequin_Taunt_Ponder = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Ponder"
        AM_Mannequin_Taunt_Praise = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Praise"
        AM_Mannequin_Taunt_Salute_01 = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Salute_01"
        AM_Mannequin_Taunt_Salute_02 = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Salute_02"
        AM_Mannequin_Taunt_Savage = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Savage"
        AM_Mannequin_Taunt_Shoosh = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Shoosh"
        AM_Mannequin_Taunt_Shrug = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Shrug"
        AM_Mannequin_Taunt_Streach = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Streach"
        AM_Mannequin_Taunt_Sweat = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Sweat"
        AM_Mannequin_Taunt_TheHeavins = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_TheHeavins"
        AM_Mannequin_Taunt_ThumbsDown = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_ThumbsDown"
        AM_Mannequin_Taunt_ThumbsOnEars = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_ThumbsOnEars"
        AM_Mannequin_Taunt_ThumbsUp_01 = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_ThumbsUp_01"
        AM_Mannequin_Taunt_ThumbsUp_02 = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_ThumbsUp_02"
        AM_Mannequin_Taunt_Victory = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Victory"
        AM_Mannequin_Taunt_Watch = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Watch"
        AM_Mannequin_Taunt_Wave = "Characters/Common/Animations/Taunts/AM_Mannequin_Taunt_Wave"
        AM_Mannequin_Box = "Characters/Common/Animations/Poses/AM_Mannequin_Box"
        AM_Mannequin_Barrel_01 = "Characters/Common/Animations/Poses/AM_Mannequin_Barrel_01"
        AM_Mannequin_Barrel_02 = "Characters/Common/Animations/Poses/AM_Mannequin_Barrel_02"
        AM_Mannequin_Equip = "Characters/Common/Animations/Actions/AM_Mannequin_Equip"
        AM_Mannequin_Unequip = "Characters/Common/Animations/Actions/AM_Mannequin_Unequip"
        AM_Mannequin_DoorOpen_01 = "Characters/Common/Animations/Actions/AM_Mannequin_DoorOpen_01"
        AM_Mannequin_DoorOpen_02 = "Characters/Common/Animations/Actions/AM_Mannequin_DoorOpen_02"
        AM_Mannequin_DoorOpen_03 = "Characters/Common/Animations/Actions/AM_Mannequin_DoorOpen_03"
        AM_Mannequin_DoorOpen_04 = "Characters/Common/Animations/Actions/AM_Mannequin_DoorOpen_04"

        # Other Assets (for not yet categorized ones)
        [assets.others]
        # Particles
        P_Bullet_Trail = "Weapons/Common/Effects/ParticlesSystems/Weapons/P_Bullet_Trail_System"
        P_Weapon_BarrelSmoke = "Weapons/Common/Effects/ParticlesSystems/Weapons/P_Weapon_BarrelSmoke_System"
        P_Weapon_Shells_12Gauge = "Weapons/Common/Effects/ParticlesSystems/Weapons/P_Weapon_Shells_12Gauge_System"
        P_Weapon_Shells_762x39 = "Weapons/Common/Effects/ParticlesSystems/Weapons/P_Weapon_Shells_762x39_System"
        P_Weapon_Shells_9x18 = "Weapons/Common/Effects/ParticlesSystems/Weapons/P_Weapon_Shells_9x18_System"
        P_Weapon_Shells_556x45 = "Weapons/Common/Effects/ParticlesSystems/Weapons/P_Weapon_Shells_556x45_System"
        P_Weapon_Shells_545x39 = "Weapons/Common/Effects/ParticlesSystems/Weapons/P_Weapon_Shells_545x39_System"
        P_Weapon_Shells_45ap = "Weapons/Common/Effects/ParticlesSystems/Weapons/P_Weapon_Shells_45ap_System"
        P_Weapon_Shells_9mm = "Weapons/Common/Effects/ParticlesSystems/Weapons/P_Weapon_Shells_9mm_System"
        P_Explosion = "Effects/Particles/P_Explosion"
        P_Smoke = "Effects/Particles/P_Smoke"
        P_Sparks = "Effects/Particles/P_Sparks"
        P_Fire = "Effects/Particles/P_Fire"
        P_Explosion_Dirt = "Weapons/Common/Effects/ParticlesSystems/Explosions/PS_Explosion_Dirt"
        P_Explosion_Water = "Weapons/Common/Effects/ParticlesSystems/Explosions/PS_Explosion_Water"