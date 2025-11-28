# ICG-Project
video link: https://youtu.be/y_wI67ZTG8A
# 1. Lighting Models
<img width="1010" height="958" alt="image" src="https://github.com/user-attachments/assets/b4a3d2a3-4b4a-40ba-95a8-5a21ccf434ea" />
Toggle:
<img width="1201" height="613" alt="image" src="https://github.com/user-attachments/assets/50373a6d-3b49-4477-a29c-c48acfc45dca" />
Trigger1:
<img width="1176" height="960" alt="image" src="https://github.com/user-attachments/assets/dbc9ed6b-ac5c-46d8-afb5-ed3d83f446f2" />

# 2. Coller grading
<img width="1118" height="511" alt="image" src="https://github.com/user-attachments/assets/477eaee5-da6a-47d5-aecb-abfc976468ee" />
This is how it originally looks like:
<img width="1622" height="933" alt="下载" src="https://github.com/user-attachments/assets/470b73b9-d1b8-456e-8e8b-5079c0e99605" />
This is how it looks like under the effect:
<img width="1622" height="933" alt="LUT1" src="https://github.com/user-attachments/assets/4b9cae4e-0f3b-4c84-bb92-2e0eeb38de01" />
Toggle:
<img width="808" height="876" alt="image" src="https://github.com/user-attachments/assets/de7454eb-be76-4ce4-9ebd-6098bc67aea6" />
Trigger:
<img width="527" height="794" alt="image" src="https://github.com/user-attachments/assets/7e7e7861-3811-4e68-8f2e-e7d4f01f0c9a" />

# 3. Rim Lighting and Hologram Lighting
Rim Lighting:
<img width="940" height="328" alt="image" src="https://github.com/user-attachments/assets/a4ff1e95-df51-41c3-b928-178975e2f5b9" />
Hologram:
<img width="896" height="754" alt="image" src="https://github.com/user-attachments/assets/7e49157a-53d1-4bbf-98e4-91bfc015f8ce" />

# 4.Platform Controller
<img width="862" height="620" alt="image" src="https://github.com/user-attachments/assets/76c38968-bb25-480a-9e13-2f3a3673c181" />

# 5.Checkpoint
<img width="1254" height="458" alt="image" src="https://github.com/user-attachments/assets/e0abd409-48ce-4d62-8af4-9591d2c7fb3c" />
<img width="815" height="316" alt="image" src="https://github.com/user-attachments/assets/de38ccfe-ea33-4865-8470-090cc32862a0" />

----------------------------------------------------------------------------------------------------

# Textures:
<img width="1594" height="280" alt="image" src="https://github.com/user-attachments/assets/b8e276f5-d083-4447-86e9-82d7647fc9e7" />
The textures were made by Substance Painter and exported as URP assets, which includes albedo, metallic, emission and normal maps.
To implement this, I made a material and import them into the right blank.
<img width="622" height="401" alt="image" src="https://github.com/user-attachments/assets/11eaf638-d7d8-46d6-9b90-775f0734307e" />
As the image shows, I can change the color next to the base map to change the color of the textures.
<img width="2208" height="479" alt="image" src="https://github.com/user-attachments/assets/b6e874bd-78f6-4833-84e7-a298ea440583" />
# Texture Toggle
<img width="842" height="785" alt="image" src="https://github.com/user-attachments/assets/712fe74b-d9c0-4490-aeed-20e59f593133" />
<img width="830" height="784" alt="image" src="https://github.com/user-attachments/assets/d3fe8f2c-a1b9-4cef-82fc-c5748477bd86" />
# Visual Effects
## Portal
![ica-5](https://github.com/user-attachments/assets/ad9d120b-8da1-4da3-830d-f4f55c94acb1)
<img width="2252" height="812" alt="image" src="https://github.com/user-attachments/assets/1cb9f971-08b3-4469-8413-d39c1ffc2b0a" />
## Lava
![ica-6](https://github.com/user-attachments/assets/d7612979-464a-44d2-88b4-9b310985f14d)
<img width="1731" height="725" alt="image" src="https://github.com/user-attachments/assets/a7ce27aa-5e7a-430a-88de-3a21ce7e6151" />
## Outline Scan
![ica-7](https://github.com/user-attachments/assets/3699b18c-64d7-4c3d-8724-5c9652ee2da4)
Stencil Front
<img width="803" height="202" alt="image" src="https://github.com/user-attachments/assets/eac6f8d8-4464-4260-8a31-fd19b729aab8" />
Outline Shader
<img width="557" height="190" alt="image" src="https://github.com/user-attachments/assets/59c7b953-6df6-4bac-a6bc-90f00acd4a13" />
These above are the core of this function. Only if the ref matches, the shader would pass through the stencil shader.
