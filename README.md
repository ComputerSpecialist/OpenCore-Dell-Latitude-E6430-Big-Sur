# OpenCore-Dell-Latitude-E6430-Big-Sur
OpenCore config for Dell Latitude E6430, tested with High Sierra, Mojave, Catalina and Big Sur

OpenCore 0.7.0

Issues: 

Trackpad not working in Big Sur
Laptop goes to sleep mode on boot with SSDT-PNFL.aml enabled, but it does enable display brightness controll

CAUTION:

Don't use OpenCore's Picker to boot Windows, but use F12 and choose Windows Boot Manager directly from UEFI BIOS. 
Else ACPI patches will be applied to windows too which can cause severe problems with the laptop.
