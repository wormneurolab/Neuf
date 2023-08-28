# Neuf
We design an image filter that particularly pick up those fiber-like- structures in image postprocessing. Fiber-like-structures stand out while other structures or background stand back after this postprocessing. 

**FiberImageEnhancer Manual**

1. Make sure your Matlab version is Matlab 2020b or newer, also make sure your Matlab has the Image Processing Toolbox installed (https://www.mathworks.com/products/image.html).

2. Double click the ‘FiberImageEnhancer.mlappinstall’ to install this app. The installed App can be found in Matlab-APPS-My APPS.
 
 ![image](https://github.com/wormneurolab/Neuf/assets/73413475/12c54695-4a3a-4f3f-a131-aa3d70285aed)

![image](https://github.com/wormneurolab/Neuf/assets/73413475/f22f4817-390b-4aba-a190-787ba39b11fc)

3. Click on this ‘FiberImageEnhancer’ to use it.
 ![image](https://github.com/wormneurolab/Neuf/assets/73413475/10c59371-2963-41ae-8459-3e5d55d43b1f)


4. This app deals with only 16-bit images in ‘tif’ format. You need to convert your images in ImageJ or other image processing software before importing them to this ‘FiberImageEnhancer’ App.

5. If your target image is a 2D image, click on the 'Import 2D image', if your target image is a 3D image stack, click on the 'Import 3D image'.
 
![image](https://github.com/wormneurolab/Neuf/assets/73413475/9d1ca9e7-0e90-406e-941d-bfe850044bb0)

6. After clicked ‘Import 2D/3D Image’, it will let you select the image you want to process.

7. Depending on the computer you are using and the size of your image, it may take a few seconds to a few mins for the App to import. The App cannot deal with larger than 4GB image yet.

8. After imported, the first slice of your image will show up.
 ![image](https://github.com/wormneurolab/Neuf/assets/73413475/b2d6ab35-3e4a-435c-a552-d0bbba273f8d)

9. You can use the ‘Slice Viewing’ to preview any slice in your image.
 ![image](https://github.com/wormneurolab/Neuf/assets/73413475/4e630daa-f523-471e-80f9-d10022293b1f)


10. You can play with the filter size to get the best image quality you prefer. Usually, use a larger filer size for thicker fiber in your image.
 ![image](https://github.com/wormneurolab/Neuf/assets/73413475/245ae5f6-a6e0-4dc3-8be1-2de606b481b1)


11. When you think the enhanced image with the current filter size is the best, click on the ‘Export Enhanced Image’ button. The App will let you select a folder to store the enhanced image. You don't need to give a name for the enhanced image, the App will give it automatically, with 'Enhanced' in the end of the enhanced image's name.
 ![image](https://github.com/wormneurolab/Neuf/assets/73413475/818c1e96-87c3-4ce6-8211-364289741590)
![image](https://github.com/wormneurolab/Neuf/assets/73413475/012d8a42-a03b-476f-8846-a0519c9f83fc)
![image](https://github.com/wormneurolab/Neuf/assets/73413475/c7314dbc-a2c1-4e2e-895a-f6aac13d21e9)

 Name example:
 ![image](https://github.com/wormneurolab/Neuf/assets/73413475/9941e40d-b7b3-415b-9092-e36c18ca6989)


12. You can then deal with the next image by clicking on the 'Import2D/3D Image' buttons.

13. Enjoy the fiber enhanced image. 



