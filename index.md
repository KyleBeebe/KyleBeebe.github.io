---
layout: default
---


<div align="left">
  <h3>Projects</h3>
  <a href="#740">Nori</a> 
  <br/>
  <a href="#425">Unity3D</a> 
  <br/>
  <a href="#OpenGL">OpenGL</a> 
  <br/>
  <a href="#417">Bittorrent</a> 
  <br/>
  <a href="#420">PMQuadtree</a> 
  <br/>
</div>
<div align="center">
  <body>
  
  <h3 id="740"> Nori Raytracer </h3>
  <p>
    <img src="images/740/cbox.png">
    <img src="images/740/med_med.png">
    <br/>
    <a href="https://github.com/KyleBeebe/Nori-Raytracer">Repository</a> 
    <br/>
    <a href="https://github.com/KyleBeebe/Nori-Raytracer/tree/master/Reports/PDF">Technical Reports</a> 
    <br/>
    The is an educational raytracer that I've been extending with extra features and functionality. An octree was created to partition the 3D scene and accerlation ray traversal, sample warping functions to help with sampling bsdf's, and various effects such as ambient occlusion. Additionally, full path tracing has been implemented with support for diffuse, specular, dielectric, and microfaceted materials. The most recent addition was the implementation of a volumentric rendering integrator. It allows the rendering of homogeneous mediums such as environmental fog with directed scattering via 
  the Henyey-Greenstein phase function model. 
  </p>
  
  <br/>
  <br/>
  
  <h3 id="425"> Unity3D SpaceGame </h3>
  <p> 
    <img src="images/425/4.jpg" alt="centrifuge">
    <a href="https://www.youtube.com/watch?v=S0BBw31RJLE&t=6s">Video Demo</a> 
    <br/>
    <a href="https://github.com/KyleBeebe/UnitySpaceGame">Repository</a> 
    <br/>
     <a href="https://github.com/KyleBeebe/KyleBeebe.github.io/tree/master/space_html/index.html">WebGL player</a> 
    <br/>
    This was created in Unity3D to show case some of the game programming techniques developed in CMSC 425 at UMD. 
    It was create as a team of three. All scripts were created using C#. The premise is a first person shooter on a space ship fighting 
    robots. The main gimmicks were the cubic Bezier curve based grappling hook, the centrifuge style level that allowed traversal along the inside walls, and the few destructible items within the environment. 
  </p>
  
  
  
  <br/>
  <br/>
  
  <h3 id="OpenGL"> OpenGL 4.6 engine </h3>
  <p>
    <img src="images/OpenGL/triangle.png">
    <a href="https://github.com/KyleBeebe/OpenGLEngine">Repository</a> 
    <br/>
    An in-progress OpenGL 4.6 engine in C++.  I have been generally following https://learnopengl.com/ but adhering to an OOP design 
  by separating components into logical classes. The objective to get a better farmiliarization with the modern OpenGL pipeline. A virtual camera has been implemented with yaw, pitch, and rolling. Basic 3D shapes with textures can be rendered. The default shaders can deal with diffuse and specular map textures. 
  </p>
  
  <h3 id="427"> OpenGL extensions </h3>
  <p>
    <img src="images/OpenGL/plane.png">
    <a href="https://github.com/KyleBeebe/OpenGLJava">Repository</a> 
    <br/>
    Showcases a few Java OpenGL extensions implemented as part of CMSC 427 (Computer Graphics). A barebones OpenGL framework was provided. Tasks include implementing animation trees, orbiting cameras, trackball cameras, lighting shaders, and procedural terrain  mesh generation. 
  </p>
  
  <br/>
  <br/>
  
  <h3 id="417"> Bittorrent Client </h3>
  <p>
    <a href="https://github.com/KyleBeebe/Bittorrent-Client">Repository</a> 
    <br/>
    A command line Bittorrent client created using C++ that handles single file torrents. The client is able to communicate with 
    public bittorrent trackers via TCP http get requests and exchanges file data with other clients via TCP connections. 
  </p>
  
  <br/>
  <br/>
  
  <h3 id="420"> PMQuadtree </h3>
  <p>
    <a href="https://github.com/KyleBeebe/PMQuadtree">Repository</a> 
    <br/>
    
Program in Java based around the PMQuadtree data structure by Hanan Samet. It is a trie based polygonal map that partitions the space based on keys. 
The project involved mapping cities as points and roads + airports as edges connecting cities. The application finds the shortest route between the cities using Dijkstra's algorithm. 
  </p>
  
  </body>
</div>

