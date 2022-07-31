# Lenovo Boot Logo Customization

Change firmware boot logo on some Lenovo (IdeaPad / Yoga / Xiaoxin / Legion) systems.

⏬ **[Download latest release](https://github.com/dantmnf/LenovoCustomLogo/releases/tag/ci-build)**


## Supported models

* Xiaoxin Pro 13 Ryzen

* Xiaoxin Air 14 2020 Intel

* Yoga Pro 14s 2022 AMD

* Other models that can query status with the tool. Feel free to test and add to this list.

## Usage

```console
> LenovoCustomLogo status
Custom logo status: 
  Enabled:      False
  Width:        3072
  Height:       1920
  Formats:      JPG, BMP
>
> LenovoCustomLogo set path/to/some/logo.bmp
Writing \\?\Volume{11451419-1981-0893-9313-643648894640}\EFI\Lenovo\Logo\mylogo_3072x1920.bmp
>
> LenovoCustomLogo status
Custom logo status: 
  Enabled:      True
  Width:        3072
  Height:       1920
  Formats:      JPG, BMP
  Current:      \\?\Volume{11451419-1981-0893-9313-643648894640}\EFI\Lenovo\Logo\mylogo_3072x1920.bmp
> 
> LenovoCustomLogo reset
>
> LenovoCustomLogo status
Custom logo status: 
  Enabled:      False
  Width:        3072
  Height:       1920
  Formats:      JPG, BMP
```

## See also

[Coxxs/LogoDiy](https://github.com/Coxxs/LogoDiy) in case you need a GUI.
