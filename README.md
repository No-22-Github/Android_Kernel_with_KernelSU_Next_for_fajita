## About This Fork

This fork is intended to implement **KernelSU Next** support on **Fajita (OnePlus 6T)** and includes some patches.

- The patch for **`su` privilege escalation** comes from:  
  [Bot-wxt1221's commit](https://github.com/Bot-wxt1221/android_kernel_oneplus_sdm845/commit/9793b0d0be0bc43e4a4bec6ab7674aa33863eb16)

- The patch for **successful module loading** comes from:  
  [qlAD's commit](https://github.com/qlAD/kernel_oneplus_sdm845/commit/d959a55778f6abf2cdebe0915e5a2564b63c6e90)

### Acknowledgments  
Special thanks to **Bot-wxt1221** and **qlAD** for their contributions!

## Hola amiguitos

This is my attempt to add a little crDroid customization flavor back into the sdm845 kernel tree for OnePlus 6 & 6T (enchilada & fajita).

- Rebased on bananafunction's lineage-20-test branch as of July 2024 (post-final update I guess ¯\_(ツ)_/¯ ).
- Merged official LineageOS lineage-21 branch as of January 2025 for U+ compatibility & retrofit dynamic partition support.
- Merged official LineageOS lineage-20 branch of common android_kernel_qcom_sdm845 kernel as of January 2025.
- Other goodies gathered from over the years including work from Anierin Bliss, mcdachpappe, EmanuelCN, snnbyyds, arter97, kerneltoast, etc (among others I'm sure).
