<p align="center">
  <img src="https://github.com/user-attachments/assets/0402997a-2723-434d-9c25-71f947f33141" width="180" style="margin-right: 20px;"/>
  <img src="https://github.com/user-attachments/assets/e7c5bcbb-f329-460a-835c-507cb4f8dbb7" width="180" style="padding-bottom: 30px;"/>
</p>

# 🇨🇴 MapBiomas Colombia – Resources and Tools

MapBiomas Colombia is an initiative that monitors land use and land cover changes across the national territory through annual multitemporal mapping. It helps identify pressures on ecosystems and the expansion of human-modified areas. To generate annual maps, the project relies on a network of experts and tools such as Google Earth Engine. Collection 3 covers the entire Colombian territory and includes a set of cross-cutting themes that map specific ecosystems and land uses at a detailed level.

## 📂 Available Repositories

| Repository | Description |
|---|---|
| [**Coverage — Collection 3**](https://github.com/mapbiomas/colombia-collection-3) | Scripts for classifying land use and land cover across Colombia. Uses Google Earth Engine to apply the official MapBiomas mapping methodology across all biomes and regions. |

### 🎋 Cross-Cutting Themes (Collection 3)

Cross-cutting themes are specialized classification workflows that target specific land use classes beyond the general LULC map:

| Theme | Repository | Class |
|---|---|---|
| Mangrove | [colombia-mangrove](https://github.com/mapbiomas/colombia-mangrove) | Class 5 |
| Flooded | [colombia-wetlands](https://github.com/mapbiomas/colombia-wetlands) | Class 11 |
| Mining | [colombia-mining](https://github.com/mapbiomas/colombia-mining) | Class 30 |
| Urban Area | [colombia-urban-area](https://github.com/mapbiomas/colombia-urban-area) | Class 24 |
| Glacier | [colombia-glacier](https://github.com/mapbiomas/colombia-glacier) | Class 34 |

## 🌐 Other Products

Specialized repositories focused on key environmental monitoring products:

| Repository | Description |
|---|---|
| [**Secondary Vegetation and Vegetation Loss**](https://github.com/mapbiomas/colombia-sec-vegetation-veg-loss) | Annual mapping of secondary vegetation regrowth and native vegetation loss. |
| [**Fire**](https://github.com/mapbiomas/colombia-fire) | Annual fire scar mapping across the Colombian territory. |
| [**Water**](https://github.com/mapbiomas/colombia-water) | Surface water dynamics monitoring on a monthly and annual basis. |
| **Alert** | Near real-time alerts for land cover change detection. *(Coming soon)* |

## 📊 Analysis

| Repository | Description |
|---|---|
| **Accuracy** | Tools for assessing the accuracy of MapBiomas Colombia data products. *(Coming soon)* |

## 🚀 Getting Started

To run any of the scripts you will need:

- A [Google Earth Engine](https://earthengine.google.com/) account
- Access to the required assets (some are public, others must be copied to your account)
- Follow the instructions in each repository's `README.md` to set output paths and required modules

If you are not familiar with MapBiomas workflows, check the [official methodology documentation](https://colombia.mapbiomas.org/descripcion-general-de-la-metodologia/).

## 📬 Contact

For more information about MapBiomas Colombia, visit [colombia.mapbiomas.org](https://colombia.mapbiomas.org).

---

*Last update: March 2026*
