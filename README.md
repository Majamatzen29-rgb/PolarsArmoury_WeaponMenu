# PolarsArmoury_WeaponMenu

A Qbox weapon menu for FiveM servers.

## 📦 Installation Tutorial

### Step 1 — Download

Download the **PolarsArmoury_WeaponMenu ZIP** from GitHub.

### Step 2 — Open the ZIP

Open the downloaded ZIP file.

Inside the ZIP, you will see:

`PolarsArmoury_WeaponMenu-main`

### Step 3 — Open the folder

Open:

`PolarsArmoury_WeaponMenu-main`

Inside, you will see:

`PolarsArmoury_WeaponMenu`

### Step 4 — Copy the resource

Take the **PolarsArmoury_WeaponMenu** folder.

Put it into your FiveM server's:

`resources`

folder.

### Step 5 — Add it to server.cfg

Open your server's `server.cfg`.

Add:

```text
ensure PolarsArmoury_WeaponMenu
```

### Step 6 — Add permissions

You **need to add your own permission lines** to `server.cfg` so the people you choose can use the weapon menu.

Example:

```text
add_ace group.admin polarsmenu.admin allow
add_ace group.admin polarsmenu.open allow
add_ace group.admin polarsmenu.giveweapon allow
add_ace group.admin polarsmenu.giveall allow
add_ace group.admin polarsmenu.giveothers allow
add_principal identifier.license:YOUR_LICENSE_HERE group.admin
```

Replace `YOUR_LICENSE_HERE` with your own FiveM license identifier.

### Step 7 — Restart

Save `server.cfg` and restart your FiveM server.

## ⚙️ Configuration

The resource includes:

`config.lua`

Use this file for the available configuration settings.

## 📁 Resource Structure

* `server`
* `html`
* `client`
* `README.md`
* `fxmanifest.lua`
* `config.lua`
* `.fxap`

## Requirements

* FiveM
* Qbox


https://www.youtube.com/@CaptainJacksparrowVR
