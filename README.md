# MMD2UDP

**[Download](https://github.com/KurisuMakise004/MMD2UDP/raw/main/MMD2UDP_x64.7z)**

A tool for converting MikuMikuDance models (.pmx) with motions(.vmd) to UltraDensePose sequences. 

This is an unofficial implementation based on @transpchan 's [UltraDensePose](https://github.com/transpchan/transpchan.github.io/blob/57efe17cdce35cf2c49c8d11ebd9bac108d1ac59/live3d/CoNR.pdf). 


## Usage

Using this tool for commercial purposes is allowed. However, you will still need to ask for permission if you are using the MMD models created by someone else.

1. Create a ZIP file named `model.zip` with all your MMD files (your_model.pmx, and textures). Note that tar, 7z, rar, or other formats are not supported.
2. Rename your motion file to `motion.vmd`, and optionally your camera file to `camera.vmd`.
3. Put `motion.vmd`, `camera.vmd` and `model.zip` into the same folder as `UltraDensePose.exe`.
4. Run UltraDensePose.exe and wait for the results in the `output` folder. The process might take very long for models with complicated physics setups, as the conversion process need to go through your `motion.vmd` and compute for each frame to obtain an UltraDensePose sequence.
