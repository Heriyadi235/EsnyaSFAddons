# Esnya SF Addons

Addons and utilities for [SaccFlightAndVehicles](https://github.com/Sacchan-VRC/SaccFlightAndVehicles).

## Features
### Custom Inspectors / Gizmos
#### SaccEntityEditor
![image](https://user-images.githubusercontent.com/2088693/148947722-70cbda93-6721-4722-b0c7-527bd5a32c38.png)

Custom inspector for SaccEntity with validation and autofill buttons.

![image](https://user-images.githubusercontent.com/2088693/148947839-bf8f137f-38dd-4faf-8d96-b9fffd6b6c99.png)

Auto find and fill reference for DFUNCs and Extentons. Also finds specified named GameObject below:
- InVehicleOnly
- HoldingOnly
- CenterOfMass
- SwitchFunctionSound
- DisabledAfter10Seconds

![image](https://user-images.githubusercontent.com/2088693/148948264-03c1996c-7864-45a8-bc33-305bf76e154e.png)

Auto align StickDisplay MFD items.
- Parent GameObject must be named "StickDisplayL" or "StickDisplayR". Recommended to use prefabs in Template folder.
- Name of each items must be started with "MFD_".

#### SAV_KeyboardControlsEditor
![image](https://user-images.githubusercontent.com/2088693/142752033-5c491832-0b28-4bf2-9317-dae26314fe8e.png)

Custom inspector for SAV_KeyobardCantrols with autofill button.

#### SVGizmoDrawer
![image](https://user-images.githubusercontent.com/2088693/142752067-16101550-75a2-4800-bca4-51fd82704d39.png)

Add gizmos for TargetEyeHeight in SaccVehicleSeat and FloatPoints in FloatScript.

### Udon
#### SFRuntimeSetup
![image](https://user-images.githubusercontent.com/2088693/142752139-16044ef1-ca37-40ce-b437-f3d3f4cec1c8.png)

Applies the parameters specified in the world to all vehicles when world loaded without prefab overrides.

#### SAV_UdonChips (Optional)
![image](https://user-images.githubusercontent.com/2088693/142752173-58ba708d-1f6f-4f80-9457-b394f02baa47.png)

Integrate UdonChips with SaccFlight.

## Requirements (Use latest version!!)
- [UdonSharp](https://github.com/MerlinVR/UdonSharp)
- [SaccFlightAndVehicles](https://github.com/Sacchan-VRC/SaccFlightAndVehicles): 1.51 or later
- [InariUdon](https://github.com/esnya/InariUdon): Using UdonLogger

### Requirements of SFUdonChips
- UdonChips

## Install
1. Import all requirements.
2. Download the unitpackage from [Lates Release](https://github.com/esnya/EsnyaSFAddons/releases/latest).
3. Import them all by drag & drop into Unity project window.
4. Click "EsnyaSFAddons/Features/Install" on the MenuBar *if you want it.*
