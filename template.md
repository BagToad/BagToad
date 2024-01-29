### 👋 Hi there!

----
<div align="center">

## Photo of the day
  
  <a href="{{ unsplash-page-url }}"><img width="720" src="{{ unsplash-raw-url }}" alt="{{ unsplash-alt-description }}"></a>
  
  <em>{{ unsplash-alt-description }}</em>
  
  <em>{{ unsplash-description }}</em>

  Photo by {{ unsplash-name }} on [unsplash.com](https://unsplash.com/) • {{ socials }}
  
  Taken at {{ location }} • {{ google-maps }}
  
  ---
  
<details>
<summary>Photography Details</summary>
  
| Parameter     | Value |
| ------------- | ----- |
| Camera Model  | {{ model }} |
| Exposure Time | {{ exposure-time }} |
| Aperture      | {{ aperture }} |
| Focal Length  | {{ focal-length }} |
| ISO           | {{ iso }} |
| Location      | {{ location }} ({{ country }}) |
| Coordinates   | Latitude {{ latitude }}, Longitude {{ longitude }} |

### Map

{{ geojson }}

</details>

</div>

----

☝️ A random image is retrieved and posted to my profile daily via the [BagToad/random-unsplash-action](https://github.com/BagToad/random-unsplash-action) action!
