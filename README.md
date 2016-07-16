Manifest for Android KitKat / CyanogenMod 11.0
====================================
Project Kanas|GalaxyCore2

---

Manual Way:

To initialize CyanogenMod 11.0 Repo:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-11.0 -g all,-notdefault,-darwin

---

To initialize Manifest for Galaxy Core 2 devices:

    curl --create-dirs -L -o .repo/local_manifests/kanas_manifest.xml -O -L https://raw.github.com/TeamVee-Kanas/android_.repo_local_manifests/cm-11.0/kanas_manifest.xml


---

Sync the repo:

    repo sync

---

Initialize the environment:

    source build/envsetup.sh

---

You need to apply some patchs, im working to convert then to correct way to massive apply

---

To build for Galaxy Core 2:

    brunch kanas
