# Basic Hardhat project using OpenZepplin Governor library

Comes with hardhat contract sizer plugin setup. 

```shell
npm install 
npx hardhat compile
```

Expected contract sizer output: 

```shell
 ·---------------------------------|-------------|---------------·
 |  Contract Name                  ·  Size (KB)  ·  Change (KB)  │
 ··································|·············|················
 |  AddressUpgradeable             ·      0.086  ·               │
 ··································|·············|················
 |  ECDSAUpgradeable               ·      0.086  ·               │
 ··································|·············|················
 |  Governor                       ·     15.301  ·               │
 ··································|·············|················
 |  SafeCastUpgradeable            ·      0.086  ·               │
 ··································|·············|················
 |  StorageSlotUpgradeable         ·      0.086  ·               │
 ··································|·············|················
 |  StringsUpgradeable             ·      0.086  ·               │
 ··································|·············|················
 |  TimelockControllerUpgradeable  ·      6.563  ·               │
 ··································|·············|················
 |  TimersUpgradeable              ·      0.086  ·               │
 ·---------------------------------|-------------|---------------·
```