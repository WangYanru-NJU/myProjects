#### myProjects
some demos of my projects

If you are interested in any part of the following demos,you can contact me by 1161068239@qq.com or wyr@smail.nju.edu.cn

# demo1 **Texture mapping and rendering based on OpenGL**
护手霜|手办1|大佛|手办2
---|:--:|:---:|:---:
![](https://github.com/2013211543/myProjects/blob/master/demos/hushoushuang.gif)|![](https://github.com/2013211543/myProjects/blob/master/demos/kona2.gif)|![](https://github.com/2013211543/myProjects/blob/master/demos/dafo.gif)|![](https://github.com/2013211543/myProjects/blob/master/demos/duncan2.gif)


**1. introduction**
- From this picture we can know why we need texture mapping,as you can see,vertex-coloring model seems blurry,even if you take 16 times refinement,the texture-mapping model still seems much more clear.So texture mapping can reserve finer details.


<p align="center">
    <img src="https://github.com/2013211543/myProjects/blob/master/demos/whytexturemapping.png" alt="Sample"  width="450" height="340">
    <p align="center">
        <em>🥇 vertex-coloring  🥈 16times refine vertex-coloring  🥉 texture-mapping</em>
    </p>
</p>

- I designed a ''optimized-view texture mapping based on constrained normal''algorithm.Its main idea is chosing the optimized view for each face of the model,I also add Occlusion detection module to make it more robust.
---
# demo2  **Interactive Bullet Time**
result|interact demo
---|:--:
![](https://github.com/2013211543/myProjects/blob/master/demos/0115-2.gif)|![](https://github.com/2013211543/myProjects/blob/master/demos/0115.gif)

**1. introduction**
- Build multi-camera system,then capture photos Synchronously,rectify photos,and render them in interactive panel finally
<p align="center">
    <img src="https://github.com/2013211543/myProjects/blob/master/demos/12.jpg" alt="Sample"  width="450" height="340">
    <p align="center">
        <em>multi-camera system</em>
    </p>
</p>

- This system was built in Beijing for GUARDIAN ART CENTER[嘉德艺术中心](http://www.cguardianart.com/shows.php?id=25)
<p align="center">
    <img src="https://github.com/2013211543/myProjects/blob/master/demos/大雅宝.png" alt="Sample"  width="550" height="240">
    <p align="center">
        <em>嘉德艺术中心展会</em>
    </p>
</p>

---
# demo3  **Free viewpoint of video**

## indoor mini scene

Original|Render in new scene
---|:--:
![](https://github.com/2013211543/myProjects/blob/master/demos/0114-2.gif)|![](https://github.com/2013211543/myProjects/blob/master/demos/0114.gif)

**1. introduction**
- Different from the Bullet Time mentioned above,this is a dynamic time video which you can select any viewpoint they like in a view range,just slide the silder on the left side
- The silder on the left side represents the viewpoint(space),the silder on the bottom represents time

## indoor larger scene
<p align="center">
    <img src="https://github.com/2013211543/myProjects/blob/master/demos/0115-4.gif" alt="" width="600" height="340">
    <p align="center">
        <em>basketball team training scene</em>
    </p>
</p>


---
# demo4  **Face reconstruction based on Deep Learning**

## reconstruction from single photo
- you can just take one front photo as input,without 1s you can get your 3d face

input|output
---|:--:
![](https://github.com/2013211543/myProjects/blob/master/demos/yidi.jpg)|![](https://github.com/2013211543/myProjects/blob/master/demos/demo1.gif)


---
# demo5  **Face swap**

### just for fun

original|reference1|reference2
---|:--:|:--:
 null|![](https://github.com/2013211543/myProjects/blob/master/demos/lyf.png)|![](https://github.com/2013211543/myProjects/blob/master/demos/tlp.jpg)
 ![](https://github.com/2013211543/myProjects/blob/master/demos/demo3small.gif)|![](https://github.com/2013211543/myProjects/blob/master/demos/demo3-1small.gif)|![](https://github.com/2013211543/myProjects/blob/master/demos/demo3-2small.gif)

