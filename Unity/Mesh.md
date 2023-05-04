* Unity中可视化都需要使用一个mesh网格来处理
* 一个3D物体的渲染，一般需要两个组件，Mesh Filter和Mesh Renderer。Mesh Filter主要是对Mesh的引用，而Mesh Renderer则是用来配置Mesh如何被渲染的，使用哪种材质，是否需要阴影等等
* 一般给Mesh添加细节最快的方式就是提供一个Albedo map(反照率贴图)，它主要代表了Material的基本颜色。纹理的映射主要是通过向顶点添加2D texture coordinates来完成纹理的投影的。UV坐标系一般是从（0，0）到（1，1）的，超出这个范围的坐标则根据贴图的Warp Mode设置，Repeat或者Clamp