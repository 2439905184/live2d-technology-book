# live2d-technology-book
探究live2d与2d图像变现背后的原理和算法
自由变形技术（Free-Form Deformation）
自由变形技术Free-Form Deformation是编辑几何模型的重要手段，它于80年代由Sederberg等人提出，目前许多三维建模软件中都有这种变形算法。自由变形方法在变形过程中并不是直接操作几何模型，而是把几何模型嵌入到变形空间，然后通过操作变形空间来使得嵌入其中的几何模型发生变形，如图所示。
![image](https://user-images.githubusercontent.com/29478722/154044597-5fc81bc5-bed2-4232-b5b5-e6e3e2af1e70.png)
![image](https://user-images.githubusercontent.com/29478722/154045038-0dde6e26-1377-41f7-bfeb-9e30ada97450.png)


这就和编辑live2d模型的过程很像

技术书籍：
https://dafoam.github.io/docs/FFD/main.pdf

使用了这项技术的软件:
live2d（商业） spine（商业）  
### 开源
[inochi2d](https://github.com/Inochi2D/inochi2d/tree/main)

[dragonbones](https://github.com/DragonBones/DragonBonesCPP)

[AnimeEffects](https://github.com/hidefuku/AnimeEffects)

开源代码:
https://github.com/hboyadzhieva/deforming-techniques python 2d形变
