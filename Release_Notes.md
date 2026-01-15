---
pagetitle: Release Notes for ST1VAFE3BX Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for ST1VAFE3BX Component Driver
Copyright &copy; 2024 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the ST1VAFE3BX component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}

<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 20-Sept-2024</label>
<div>

## Main changes

### First release

- First official release [ref. DS v1.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V2.0.0 / 08-Nov-2024</label>
<div>

## Main changes

- Align driver to DS Rev2

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V2.1.0 / 07-Apr-2025</label>
<div>

## Main changes

- fix drdy event clearing
- Make ctx a private structure

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V2.1.1 / 16-Apr-2025</label>
<div>

## Main changes

- Fix fifo_mode_set

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V2.2.0 / 07-Jul-2025</label>
<div>

## Main changes

- Fix driver formatting options
- Added pointer to private data in stmdev_ctx_t

##

</div>

<input type="checkbox" id="collapse-section6" aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V2.3.0 / 07-Oct-2025</label>
<div>

## Main changes

- Added checks before writes and membank setting
- Changed a wrong write into a read in wakeup_config_get
- Fix code style in mode_set and removed a write in emb_fsm_get
- Update the 'st1vafe3bx_mode_set()' function
- Fix High Performance mode selection
- Adding CODE_OF_CONDUCT.md and SECURITY.md

##

</div>

<input type="checkbox" id="collapse-section7" aria-hidden="true">
<label for="collapse-section7" aria-hidden="true">V2.3.1 / 05-Nov-2025</label>
<div>

## Main changes

- Fix ah_bio_active API

##

</div>

<input type="checkbox" id="collapse-section8" checked aria-hidden="true">
<label for="collapse-section8" aria-hidden="true">V2.4.0 / 15-Jan-2026</label>
<div>

## Main changes

- Remove hp_en from md_t struct
- Add embedded_state_set API and remove init_t struct
- Add reboot and sw_reset APIs, extracted from init_set

##

</div>
:::


:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on ST1VAFE3BX,
visit:
[ST1VAFE3BX](https://www.st.com/en/mems-and-sensors/st1vafe3bx.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 2.0">Info</abbr>
:::
:::
</footer>
