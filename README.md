# Silicon-Valley-Tech-Hubs
An interactive web map with custom zoom-in and zoom-out controls has been created in [index.html](file:///C:/Users/ishan/Documents/Projects/Silicon-Valley-Tech-Hubs/index.html). Open it in any browser to explore the hubs dynamically.

## Silicon Valley Tech Hubs (North to South)


### Controls:

- Zoom In: Double Click
- Zoom Out: Shift + Double Click

### 🗺️ [View Map with Colored Pins on geojson.io ↗](https://geojson.io/?data=gz:H4sIAAAAAAAACq2VXWvbMBRA_4qmvWxDDbFlO3bfsox03ZIutGMwRh-u5ZtWRNY1stI2K_nvI2qhYPwwg191hXSO7oeeuT80yM_5EsHvHS7IGFRek-WCb1_WWn7-57mzjwveOGrQeX2KP3ML9Sl8A5atwSNxwRXVDdgQ5zeWHrcGdijYNZWGnrjgNbgdujNFhhw_5-9jVGoWvQVa_fd0ZI2V3tf8KPgdUo3eHU73veJsSFsf7iJXaQs-0J5FcTyRcZoKOZukmbw9HsX_Giwd1vR65hv_T2wNsCUoT-4g2Apqdo0tglP3PSYyKfKqHMkkmhR5ngWTJE-HqFxj9UhUsYX2h47PDwfK4CfBPvemoijTosxGS0Uss-QkkORpPERgjdYQ24DbdfDX6IF9WILCkmj3sccgglIVajSDKI_yYJAW2RCDDRhic-O7_RDqSbCvmx70baSS6XY89EQG8iQqBr29No320HbAv6_mbEGuIQevU6KLj9kM43i04s-LIhR_IuNBfbymvfWgLful8bEjcUF0Z1CwS-v32vc5zBIlx6ueaS6Lk4PMs2iIw83e2sMDGOzwr7TdYXVpBfsN90Tv-gyKCDM5noHMQhXJLM8HGYD1wBYGHHQcrh50pSHkAI1g8_WXHotZVhbT6XiDNE3jYJEmw_IAln2jtpuGhW4VCTavqMQe-Om0VFUyXiPkeRTgZTIoBYt9WLPdETRvGtOHDRIAcMTKiV_efFj7rqhlF-CpO3-u0G-N7vuzylmkorF6NpoUWRz-rFimp-e-Pf4DqC-G5ysJAAA)



> **Note:** GitHub's built-in GeoJSON renderer does not support colored markers. Click the link above to see the map with properly colored pins, or open `index.html` locally for the full interactive experience.

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "name": "San Francisco",
        "companies": "Airbnb, Lyft, Shopify",
        "marker-color": "#a855f7",
        "marker-size": "medium"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-122.4194, 37.7749]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "name": "San Mateo",
        "companies": "Snowflake, Roblox",
        "marker-color": "#2ecc71",
        "marker-size": "medium"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-122.3255, 37.5630]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "name": "Fremont",
        "companies": "Tesla Factory, Lam Research",
        "marker-color": "#3498db",
        "marker-size": "medium"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-121.9886, 37.5485]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "name": "Redwood City",
        "companies": "Oracle*, Box",
        "marker-color": "#9b59b6",
        "marker-size": "medium"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-122.2364, 37.4852]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "name": "Menlo Park",
        "companies": "Meta (Facebook)",
        "marker-color": "#1abc9c",
        "marker-size": "medium"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-122.1818, 37.4596]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "name": "Palo Alto",
        "companies": "Tesla, HP",
        "marker-color": "#f1c40f",
        "marker-size": "medium"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-122.1430, 37.4419]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "name": "Milpitas",
        "companies": "KLA Corporation",
        "marker-color": "#e67e22",
        "marker-size": "medium"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-121.8996, 37.4323]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "name": "Mountain View",
        "companies": "Google, Microsoft, Intuit",
        "marker-color": "#e74c3c",
        "marker-size": "medium"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-122.0839, 37.3861]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "name": "Sunnyvale",
        "companies": "Amazon, LinkedIn, Yahoo!, Uber",
        "marker-color": "#e91e63",
        "marker-size": "medium"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-122.0363, 37.3688]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "name": "Santa Clara",
        "companies": "Nvidia, Intel, AMD, Qualcomm",
        "marker-color": "#76b900",
        "marker-size": "medium"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-121.9552, 37.3541]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "name": "San Jose",
        "companies": "Cisco, Adobe, Broadcom",
        "marker-color": "#00bcd4",
        "marker-size": "medium"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-121.8881, 37.3348]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "name": "Cupertino",
        "companies": "Apple",
        "marker-color": "#a3aaae",
        "marker-size": "medium"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-122.0322, 37.3230]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "name": "Los Gatos",
        "companies": "Netflix",
        "marker-color": "#b71c1c",
        "marker-size": "medium"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [-121.9624, 37.2358]
      }
    }
  ]
}
```

| City | Major Companies |
| :--- | :--- |
| 🟪 **San Francisco** | Airbnb, Lyft, Shopify |
| 🟩 **San Mateo** | Snowflake, Roblox |
| 🟦 **Fremont** | Tesla Factory, Lam Research |
| 🟪 **Redwood City** | Oracle*, Box |
| 🟩 **Menlo Park** | Meta (Facebook) |
| 🟨 **Palo Alto** | Tesla, HP |
| 🟧 **Milpitas** | KLA Corporation |
| 🟥 **Mountain View** | Google, Microsoft, Intuit |
| 🟥 **Sunnyvale** | Amazon, LinkedIn, Yahoo!, Uber |
| 🟩 **Santa Clara** | Nvidia, Intel, AMD, Qualcomm |
| 🟦 **San Jose** | Cisco, Adobe, Broadcom |
| ⬜ **Cupertino** | Apple |
| 🟫 **Los Gatos** | Netflix |

*\*Note: Oracle moved its official headquarters to Austin, Texas, but maintains a significant historic presence in Redwood City.*

