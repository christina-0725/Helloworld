Issue Type: <b>Bug</b>

# <VScode> Jupyter extension - No module named 'tensorflow'
I used Anaconda to create a virtual environment with module tensorflow.
![Image of virtual environment](https://github.com/christina-0725/Helloworld/blob/main/3.PNG)

I can import tensorflow in Juypter notebook which was installed in Anaconda. 
![Image of Juypter notebook](https://github.com/christina-0725/Helloworld/blob/main/2.PNG)

I can also import tensorflow in VScode Python extension.
![Image of VScode Python extension](https://github.com/christina-0725/Helloworld/blob/main/4.PNG)

 But in VScode Juypter extension, when I input "import tensorflow as tf", the ModuleNotFoundError will occur.
![Image of Vscode Juypter extension](https://github.com/christina-0725/Helloworld/blob/main/1.PNG)


This problem also happened on my mac. I don't know why this happens. I hope someone can help me solve this question. Thanks!

Extension version: 2020.11.358541065
VS Code version: Code 1.51.1 (e5a624b788d92b8d34d1392e4c4d9789406efe8f, 2020-11-10T23:34:32.027Z)
OS version: Windows_NT x64 10.0.18363

<details>
<summary>System Info</summary>

|Item|Value|
|---|---|
|CPUs|Intel(R) Core(TM) i5-9400 CPU @ 2.90GHz (6 x 2904)|
|GPU Status|2d_canvas: enabled<br>flash_3d: enabled<br>flash_stage3d: enabled<br>flash_stage3d_baseline: enabled<br>gpu_compositing: enabled<br>multiple_raster_threads: enabled_on<br>oop_rasterization: disabled_off<br>opengl: enabled_on<br>protected_video_decode: enabled<br>rasterization: enabled<br>skia_renderer: disabled_off_ok<br>video_decode: enabled<br>vulkan: disabled_off<br>webgl: enabled<br>webgl2: enabled|
|Load (avg)|undefined|
|Memory (System)|7.84GB (2.97GB free)|
|Process Argv|C:\Users\kh\Desktop\VScode\服装图像训练.ipynb --crash-reporter-id 6a652439-042b-4523-8c8c-eea565986121|
|Screen Reader|no|
|VM|0%|
</details>
<!-- generated by issue reporter -->
