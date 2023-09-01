# BoxGallary
BoxGallary collects rendered images from my real-time renderer(C++). It aims for supporting all features in [glTF](https://github.com/KhronosGroup/glTF) such as PBR.

Chess showcases of [KHR_materials_volume](https://github.com/KhronosGroup/glTF/blob/main/extensions/2.0/Khronos/KHR_materials_volume/README.md), [KHR_materials_transmission]https://github.com/KhronosGroup/glTF/tree/main/extensions/2.0/Khronos/KHR_materials_transmission)

![chess1](images/chess1.jpg)

![chess1](images/chess2.jpg)

The dragon features transmission and volume where different thickness leads to different attenuation (colour appears yellowish at foot).

![Dragon with attenuation](images/attenuation_dragon.jpg)

Iridescence is the effect of light interference due to thin film layers. Below features Suzanne with iridescence (rainbow colour), transmission and volume (refraction). The left Suzanne has a high metallic value, 400nm thin-film layer thickness value. 

![iridescene](images/iridescene_400.jpg)

The left Suzanne with 550nm thin-film layer thickness value while the right Suzanne has purple attenuation colour. 

![iridescene_550](images/iridescene_550.jpg)

Postprocessing effect of physical bloom. 

![bloom](images/bloom.jpg)
