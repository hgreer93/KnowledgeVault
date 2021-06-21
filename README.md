# PersonalResearch

https://acronymgenerator.com/

## Animation Programming
[Inverse Kinematics](https://zalo.github.io/blog/inverse-kinematics/)

[Animation Programming](https://animationprogramming.com/)

[Mocap Compression using Bezier Curve](https://www.mathworks.com/matlabcentral/fileexchange/61771-compression-of-motion-capture-data-using-quadratic-bezier-curve)

[Key Reduction](https://nfrechette.github.io/2016/12/07/anim_compression_key_reduction/)

## Graphics Programming

[Shader Playground](http://shader-playground.timjones.io/)

[Dynamic Draw Call Batching](https://www.gamedev.net/forums/topic/688462-is-dynamic-draw-call-batching-still-relevant/)

[Vertex/Index/Constant in Upload Heaps](https://www.gamedev.net/forums/topic/680559-buffers-vertex-index-constant-in-upload-default-heaps/)

[DXR Path Tracer](https://maknee.github.io/blog/2018/RTX-DXR-Path-Tracer-HLSL/)

[D3D12 Bindless](http://alextardif.com/Bindless.html)

[D3D12 Resource Alignment Secrets](https://asawicki.info/news_1726_secrets_of_direct3d_12_resource_alignment)

[Mesh Shaders](https://devblogs.microsoft.com/directx/coming-to-directx-12-mesh-shaders-and-amplification-shaders-reinventing-the-geometry-pipeline/)

[HLSL Closures](https://code4k.blogspot.com/2011/11/advanced-hlsl-using-closures-and.html)

[Triangle Visibility Buffer](https://diaryofagraphicsprogrammer.blogspot.com/2018/03/triangle-visibility-buffer.html)

[AMD Primitive Shader](https://www.resetera.com/threads/primitive-shader-amds-patent-deep-dive.186831/)

[HLSL Class Linking](https://www.gamedev.net/forums/topic/695003-class-linkage-system-with-dx12/)

[HLSL Dynamic Linking](https://www.gamedev.net/forums/topic/623020-hlsl-dynamic-linking/)

[GDC Advanced Graphics Techniques](https://www.gdcvault.com/play/1023511/Advanced-Graphics-Techniques-Tutorial-Day#:~:text=Object%20space%20lighting%20is%20a%20technique%20inspired%20by,rates%2C%20and%20many%20more%20effects%2C%20all%20in%20real-time)

[Terrain Rendering using VTF](https://galfar.vevb.net/wp/2013/android-terrain-rendering-vertex-texture-fetch-part-1/)

[D3D12 Limit Textures using LRU](https://github.com/xenia-project/xenia/commit/d0c872527015ef90b4efd6e7d7996479de590a47)

[Mesh Colors](http://www.cemyuksel.com/research/meshcolors/)

[D3D12 Copies to Same Buffer](https://asawicki.info/news_1722_secrets_of_direct3d_12_copies_to_the_same_buffer)

[Texture Object Space Lighting](https://kosmonautblog.wordpress.com/2016/12/19/texture-object-space-lighting/)

## Collision and Physics

[Digital Rune Collision Detection](https://digitalrune.github.io/DigitalRune-Documentation/html/629ec6f3-8533-4ef9-94d0-220ef375387c.htm#:~:text=The%20collision%20detection%20in%20DigitalRune%20Geometry%20can%20compute,stores%20additional%20information%20for%20the%20collision%20detection%20system)

[Sphere Triangle Intersection](https://realtimecollisiondetection.net/blog/?p=103)





https://gamedev.stackexchange.com/questions/7718/event-driven-communication-in-a-game-engine-yes-or-no
https://stackoverflow.com/questions/4574016/game-objects-talking-to-each-other/4580241#4580241


https://www.gamedev.net/articles/programming/general-and-gameplay-programming/game-engine-containers-handle_map-r4495/








## Virtual Geometry Textures
http://publications.lib.chalmers.se/records/fulltext/220583/220583.pdf

[OpenGI (Open Geometry Image)](http://opengi.sourceforge.net/about.html)


http://ogldev.atspace.co.uk/www/tutorial31/tutorial31.html
http://jan.ucc.nau.edu/lrm22/pixels2bytes/calculator.htm

## Math

[Dynamic AABB Tree](https://github.com/lohedges/aabbcc)



https://github.com/jpcy/xatlas



https://hbfs.wordpress.com/2013/02/12/float16/
https://stackoverflow.com/questions/36998123/how-to-quantize-floating-point-to-unsigned-byte-in-glsl
http://aras-p.info/texts/CompactNormalStorage.html

https://www.gamedev.net/forums/topic/674253-g-buffer-and-render-target-format-for-normals/
https://stackoverflow.com/questions/31181233/writing-a-hlsl-shader-for-rescaling-floating-point-textures
https://github.com/ihmeuw/glsl-rgba-to-float
https://docs.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl-asfloat

https://stackoverflow.com/questions/1659440/32-bit-to-16-bit-floating-point-conversion
 251x251 of 65x65 blocks.. positions are 64x64 where each position requires 1.5 pixels
 so 42x42 positions = 1764 points per block
 
 442,764 points per row
 111,133,764 total points per position page
 
 http://wiki.polycount.com/wiki/Polygon_Count
 
 this means each page is exactly 1024 MB in size
 
 https://stackoverflow.com/questions/59782637/directx-12-sharing-graphic-memory-between-two-processes
 https://developer.nvidia.com/blog/gpudirect-storage/
 https://scicomp.stackexchange.com/questions/2911/is-there-an-algorithm-to-find-an-almost-convex-hull-given-a-tolerance-angle
 
Pixels are stored as 64x64, but we keep 1 pixel of padding along the right and bottom of the image.
This helps to ensure the entire row is placed into GPU cache.
 

MIP CHAIN

64
32
16
8
4
2
1

https://scicomp.stackexchange.com/questions/2911/is-there-an-algorithm-to-find-an-almost-convex-hull-given-a-tolerance-angle
https://www.tutorialspoint.com/cplusplus-program-to-implement-graham-scan-algorithm-to-find-the-convex-hull
https://stackoverflow.com/questions/18416861/how-to-find-convex-hull-in-a-3-dimensional-space
http://www.science.smith.edu/~jorourke/books/compgeom.html
https://github.com/akuukka/quickhull
https://github.com/akuukka/unitvectorpack
https://www.ilikebigbits.com/2015_03_04_plane_from_points.html
https://github.com/karimnaaji/3d-quickhull/blob/master/quickhull.h


? 	Question, something to investigate
! 	Important
!! 	Very important
+	Feature
-	Removal
*	Bug fix
| 	Something external I did

///////////////////////////////////////////////////////////////////////////////
// 10/21/2020

? Constant buffer pools should use a single large buffer instead of multiple buffers.
  There really isn't a reason to add the additional buffer overhead.
  Perhaps all constant buffer pools should share the same dynamic uploader as well.
? GpuSyncPoints should track the frame they were created on (probably)..
? Does a BufferDescription really need a layout? What is the purpose?
! GenericGPUBuffer::WriteData does the buffer need to know alignment?
? Remove the GpuSurfaceHelper structure. It really isn't needed..
!!! Read more about state decay for render targets

When rendering there are technically two buffers used (for the most part..)
The first buffer contains the following:

struct MaterialTextureBinding
{
   uint StartIndex;
   uint Count;
};

The second buffer contains the following

Buffer<uint> TextureIndices;

This way when performing a texture lookup you would do the following

Texture2D GTexture2D : register(t10, 100)
Buffer<uint> TextureIndices;
Buffer<MaterialTextureBinding> TextureBindings;

MaterialTextureBinding Binding = TextureBindings[MaterialIndex];
Texture2D RealTextures<4>;

for (uint i = 0; i < Binding.Count; ++i)
{
 RealTextures[i] = GTexture2D[TextureIndices[Binding.StartIndex + i]];
}

// But if we have the shader code already written we can do something similar to the following..
// where TextureLookupStartIndex is a root parameter.
Texture2D MyTexture = GTexture2D[TextureIndices[TextureLookupStartIndex + ShaderTextureId]];

Which means we need to track the textures as they are posted into the shader code
where this means we keep a name->compile texture ID->Type tracker somewhere (I guess on the shader code).

Then materials can use the lookup table for editing.
Samplers/Surfaces/Buffers are stored as named parameters with a bind slot.

Materials also need to define their render state and the expected vertex layout for geometry..

! ShaderGraph needs to handle parameter connection rules
? Find a way to have both mesh shaders and normal shaders

? Color volumes: A color volume (or maybe a fog volume) is used to control color tinting at a given pixel on the screen
  The purpose is to help ensure certain section are not *too* dark.
  With lighting it would also be possible to have some sort of CPU raytrace occur and take advantage of the light going
  through the volumes. The volumes could help to describe the way the light would interact.
  
! There needs to be a pool of hardware sync points to handle threading issues.
  
///////////////////////////////////////////////////////////////////////////////
// 10/22/2020

* Fixed an issue where resources were not properly freed during rendering shutdown.
+ Properly handling static and dynamic constant buffer pools.
+ Acion service
- Acion now uses smart pointers over handles. This will make it easier.
+ Began work on Radiance, our scene designer. I need a break from graphics for right now.
| Emailed Rad about Oodle compression, not sure about license fee. Will report back later.

///////////////////////////////////////////////////////////////////////////////
// 10/26/2020

| Took a break, very tired.

///////////////////////////////////////////////////////////////////////////////
// 10/27/2020

| Still extremely tired.. Not sure why.
| Never got an email back. Probably didn't like my low ass budget. Fuckers.
| Because we are going completely bindless this means we need to rework the entire concept
  behind vertex buffers. There really should be something like
  
  RenderDevice::AllocateVertexStreamingSegment(uint32 VertexSize, uint32 VertexCount, EResourceUsage Usage)
  
  This should then suballocate within a single large buffer a chunk of vertex data for streaming.
  This buffer is actually just a ByteAddressBuffer which acts as the backing vertex buffer.
  The advantage is that we remove the entire concept of the Input Assembler from our PSO.
  Perhaps the main API can still return a 'GPUBuffer' but it's implementation is hidden depend on if
  the buffer is an index buffer or a verte buffer.. We already do the same with constant buffers..
  
  Perhaps what really needs to occur is have a generic buffer pooling system in place which covers
  all the types of buffers we would really need. This was discusssed for some time.

///////////////////////////////////////////////////////////////////////////////
// 10/28/2020

| Lazy day, rainy. Didn't really get to work until close to 4PM. This is terrible.
| Tons of research on geometry images. This seems like the future and honestly the way to go.
  They effectively map directly to using either mesh shaders or standard compute shaders.
  This is a big win, and makes backwards compatibility rather trivial.
  You have essentially 'free' LOD due to using a quadtree on the image. Utilizing vertex cache
  you don't need to worry about stitching, cracks, or seam generation.
  
  You also gain the ability to have the images losslessly compressed on the disk. And can use either
  a 32 bit float texture for high quality models (which wouldn't be compressed) or a standard RGB texture
  for things which need less fidelity.
  
  The overhead would come from updating LODs for objects however.
  
  Since each patch is the same size, you no longer need to worry about a vertex buffer.
  A single shared index buffer can be used. This means that streaming geometry data to the GPU
  is now really just streaming a texture.
  
  It would pair extremely well with something like a triangle visibility-buffer if you wanted. Though
  the downside of that approach is you lose the ability to have custom shaders for objects.
  Although, truthfully a majority of the objects in the scene would just share the same standard material
  anyway, so this really isn't a dealbreaker.
  
///////////////////////////////////////////////////////////////////////////////
// 10/29/2020

| Late start, tropical storm came through. Talk about some strong winds!
  I spent the majority of last night thinking more about a geometry texture system and
  I have come to the conclusion that is exactly how UE5 is doing it.
  Realtime Rendering has a section about PN Triangles and what not, which is more of a tessellation
  technique vs a non-tessellation technique. It also only works when going from low->high topology.
  
  I realized that there would be a problem with seams so the current line of thinking is to do the following:
  
  1) Deconstruct the mesh into a BVH. This is probably required so adjacent sections of geometry end up lying
     next to each other within the image atlas. Since a cube maps perfectly to the atlas, this is neat.
	 Each section can only have 4 potential neighbors (who themselves have 4 neighbors).
	 
	 Unwrapping this into an atlas will prove to be challenging, but it also helps to act as a quadtree for LOD.
	 
  2) Once we have done this, we take all the vertex data stored within each BVH node and unwrap it into an NxN square
     within the texture atlas. This is to say that, 1 pixel maps to 1 vertex on the highest LOD version.

  3) When the object is the lowest LOD, you only need a few (potentially 1) control point within the center of the
     region. Using barycentric coordinates it means that you can get a pretty good 'guesstimate', while still retaining
	 normal/texture UVs of the region. While distortion may occur, objects would be a sufficient distance such that 
	 the viewer wouldn't notice. But polygon count would remain sufficiently low that large numbers of these objects
	 wouldn't be a problem to render.
	 
     When switching to a higher LOD, you can sufficiently divide midpoints until you reach the highest LOD level.
	 this means that, for example, given a 64x64 grid of vertex information (4096 vertices) the interior has 8
	 subdivisions per LOD level.
	 
	 Because the total number of vertices isn't really the issue, you maintain a total of 256 base control points 
	 (64 points per side, 4 sides).
	 
///////////////////////////////////////////////////////////////////////////////
// 10/30/2020

Okay, I think I am super onto something here.

D3D12_RESOURCE_FLAG_ALLOW_SIMULTANEOUS_ACCESS


///////////////////////////////////////////////////////////////////////////////
// 11/1/2020

Cant stop thinking about Geotex. Looking into various algorithms to determine which things need to be paged in.
The paging process will work something like this.

Use 3D bounding boxes to get a rough 'guesstimate' about which major patch needs to be required. There will be overlap during this phase
but this is expected. Each box is transform as well with the local matrix. But this process should effectively eliminate a large number of
items, duplicates are expected (and recommended).

Once that phase is completed we know which things of geometry are potentially visible (though overdraw is a thing..). We figure out which
patches are required, sort by patch ID, then begin rasterizing the patch texture. Each patch during this phase has the following information:
	Each block section uses the following:
	 DXGI_FORMAT_R16G16B16A16_UINT
	 RGB - Vertex XYZ







Page in convex hull positions, essentially each 64 vertex strip should have a relatively small convex. It could potentially be
beneficial to have a 'clip plane' which represents the directional face of the convex strip. Each 64 strip would have 2 clip planes
(one per 32 vertices). This would reduce workload but being able to determine quickly if the sub-strip is even facing the camera.
It also guarantees that given an arbitrary set of points, that if at least 1 vertex is visible, the plane would also be visible.

Render these to a map and transform the convex as necessary, but this method will not support clip maps.
	For this it may be possible to go ahead and have a secondary clip map texture, deriving the alpha from the base image texture, and using that when
	computing the visible patches. This would give you granularity down to the pixel patch.
	
	The output image from this pass would be the following:
	R32_UINT
	
	This will give enough accuracy to determine the each patch ID to stream in. This number is high enough that you would never have a case where
	you exhausted all 4.2 million patch ids (4.2 million patches is roughly 17 trillion points).
	
	Now, for determine *which* patches to stream in you have the following information.
	
	The convex hull is stored with the following information (potentially coming from a single large buffer?)
	
	uint16 xyz - the coordinate of the hull vertex
	uint8 clip - the clip value (derived from the source alpha channel)
	uint8 unused - not sure what could go into here.. Maybe we could chain them together?
	
	This is just 64 bits per vertex, though it would be possible to eliminate the redundant 8 bits which are unused.
	This pass would run in a compute shader, and afterwards the CPU would use the resulting image to determine which patches
	need to be paged in.
	
	atlas id's are stored within a separate buffer, bound at runtime.
	
Paging

	Paging works in the following scenarios:
		If a patch is paged in, nothing needs to occur.
		If a patch is not paged in:
			Figure out all the available slots
			Perform an upload from CPU to GPU to fill out the patch texture. This texture is made using simultaneous access where
			writes to unused patches can occur at the same time patches are being renderer.
			This means you increase throughput but have to handle GPU fences.
			
			For each patch that is paged out, we will determine this on the CPU and keep track of it.
			
Rendering
	
	Patches know their shader ID which is required to render, so they are sorted with the global shader running first, followed by specialized shaders.
	After this process you end up with your full standard GBuffer.
	
Shadows and Post FX
	Because the clip map is stored with convex positions, we can utilize that technique for shadow processing as well. This guarantees a shadow buffer
	which is pixel accurate.

WAIT WAIT WAIT...
A convex hull won't give an accurate shape, unless the hull can be tuned.. :|

We need an 'alpha shape'. a concave hull generation
https://github.com/Liagson/ConcaveHullGenerator
https://stackoverflow.com/questions/38829464/cgal-concave-hull-3d-alpha-shapes-3
https://gis.stackexchange.com/questions/143821/how-to-find-the-concave-hull-for-a-cloud-of-points-in-3d-space
https://stackoverflow.com/questions/26303878/alpha-shapes-in-3d
https://github.com/mikolalysenko/alpha-shape
https://github.com/Ali2500/ConcaveHull
https://www.thecrazyprogrammer.com/2017/02/boundary-fill-algorithm-in-c.html
https://github.com/zeux/meshoptimizer
https://www.geeks3d.com/hacklab/20200518/demo-meshlets-and-mesh-shaders-vulkan/

https://github.com/sebbbi/perftest
We are looking at Linear loads on this.

https://stackoverflow.com/questions/7840429/calculate-the-xyz-point-of-a-sphere-given-a-uv-coordinate-of-its-texture
https://github.com/iRedSt4R/RedSt4R_Engine
https://www.reddit.com/r/hardware/comments/gkcd9b/pixels_triangles_whats_the_difference_how_i_think/
https://www.reddit.com/r/GraphicsProgramming/comments/jiu7qg/this_field_in_general_is_awfully_documented/
https://web.archive.org/web/20140226060757/http://devmaster.net/posts/6145/advanced-rasterization
https://stackoverflow.com/questions/11139724/i-need-a-pixel-perfect-triangle-fill-algorithm-to-avoid-aliasing-artifacts

New plan:

Vertex positions are stored using 

DXGI_FORMAT_R16G16B16A16_FLOAT

It uses the following scheme:
	RGB0 = XYZ0
	RGB1 = XYZ1
	RGB2 = XYZ2
	A0A1A2 = XYZ3

This means that a single triangle requires 3 loads
but a full face (two triangles) also only requires 3 loads. The 4th point is essentially 'free'.
It seems this concept isn't really as 'revolutionary' as I thought, it's been heavily researched and I am now convinced it is the way Epic is doing things.

https://twitter.com/JCGT_announce/status/1317878031751409664
https://stackoverflow.com/questions/187713/converting-floating-point-to-fixed-point
https://github.com/acgessler/half_float

///////////////////////////////////////////////////////////////////////////////
// 11/3/2020

Work above was from a previous day merged.

OptimizeIndicesForVertexCache - This function appears to be particularly slow when handling a large mesh. Unfortunately it doesn't seem like there is a good
way to compute this information in parallel. It was said that this should be run before performing meshlet generation, but I am unsure as to the actual performance
benefit this will provide. 

However, meshopt seems to have been able to cut the total number of vertices down significantly.
OpenFBX has a seriously wonky triangulator, and it's better to just use meshopt to generate the index buffer it seems..


1:16 - started (release mode, no debugging)

///////////////////////////////////////////////////////////////////////////////
// 11/9/2020

Didn't feel well.
Fixed the issues above, ofbx was being a piece of shit.

https://gamedev.stackexchange.com/questions/110448/how-to-convert-uv-position-to-texture-atlas-pos-and-reapply-to-uv-in-unity
https://simoncoenen.com/blog/programming/graphics/DxcCompiling.html
https://asawicki.info/news_1719_two_shader_compilers_of_direct3d_12
https://gamedev.stackexchange.com/questions/45941/what-compilers-are-used-in-game-development




https://www.artstation.com/artwork/ko2gz


///////////////////////////////////////////////////////////////////////////////
// 11/17/2020

+ Redoing the way objects work. We need to come up with a quick way to ensure rtti strings are stripped from the code..
+ Modules

https://stackoverflow.com/questions/39650122/how-to-ensure-constexpr-function-never-called-at-runtime
https://github.com/emilisb/OOP-4



///////////////////////////////////////////////////////////////////////////////
// 12/2/2020

Probably need the GraphicsSubsystem to have a factory associated with it. This might be worthwhile for multi-gpu but..
Are we really going to support this? We don't even have multi-gpu anyway so what's the point.

https://twitter.com/Reg__/status/1288123258970112000
https://auzaiffe.wordpress.com/2019/03/26/a-hybrid-rendering-pipeline-for-realtime-rendering-when-is-raytracing-worth-it/


https://www.gamedev.net/forums/topic/548213-terrain-editing-and-painting/
https://www.gamedev.net/forums/topic/651517-terrain-texturing-multi-texturing-brush-tool/
https://github.com/awkwardpolygons/cartographer
https://github.com/Aggroo/TerrainEditor
https://www.reddit.com/r/gamedev/comments/5c6czt/world_of_warcraft_level_design_panel_from/



https://chilliant.blogspot.com/2012/08/srgb-approximations-for-hlsl.html


///////////////////////////////////////////////////////////////////////////////
// 12/28/2020

Really need to get back into working, tired of living here. This place blows cock.

Current ideas - we are about to come into a weird dawn of heterogenous multigpu rendering, this is the future, and frankly, would be the best choice.
This would mean in the future you could have potentially a primary GPU and additional secondaries which are specialized to perform a certain task. This means
you can have something like a dedicated raytracer hardware..

I also see an increasing future for software rasterization which is sort of weird. There are some software rasterizers out there which can raster 1.2 million polys 
running at 10 fps (this was tested on a 4 core CPU however). This really is very interesting.

So the new concept is to remove the reliance on a dedicated IGraphicsRenderDevice within the rendering, and instead you select gpus based off classification.

enum class EGpuClassification
{
	Primary			= ( 1 << 0 ),
	Secondary0		= ( 1 << 1 ),
	Secondary1		= ( 1 << 2 ),
	Software		= ( 1 << 3 )
};

The primary GPU should be the GPU which is considered the strongest and is used to drive the primary rendering.

We support up to two secondaries (meaning, 3 gpus in total but that's sorta nutty). This could potentially be used to easily support SLI
where a secondary gpu is really just a specific node mask for SLI.

Finally we have the software rasterizer which can be used to perform things such as blurs, fullscreen post processing, or additional rasterization
to help compute information which would be too complicated to run on the GPU. The downside of this is that you are completely at the mercy of the physical CPU,
but the benefits are that this scales very well. Most new CPU's are now 8/12 cores anyway, so this honestly isn't a big issue.

This also means that, when asking for a command list, you ask the graphics interface for a command list based on the gpu classication

IGraphicsInterface::AllocateCommandList(GpuClassification, CommandListType)

This also means that, unfortunately, there need to be a series of 'Drivers' for the renderer shared by a common interface.

Examples include:
D3D12Driver
SoftwareDriver

https://github.com/Zielon/CPURasterizer







!!! Prepropogated audio occlusion volumes!
   - Call it PAVOC or something cool?
   The basic idea is to pre-generate audio occlusion information and store it into a series of invisible probes
   within a scene. At runtime, determine which probe(s) to lookup occlusion information from, and people will
   be like "Say that's pretty cool".
   
   



Interesting tile based rasterization
All new GPUs are using this technique. See https://www.realworldtech.com/tile-based-rasterization-nvidia-gpus/

The main idea would be to keep track of BVH data stored as a series of bitables (https://github.com/ConorStokes/bitable) 
The main idea is to first divide the entire screen into a series of tiles (something like, say, 8x8) because each tile can be performed in parallel this would 
be extremely fast. This also gives you an instant list without having to raster any geometry to know what tiles potentially contain what geometry.

At this stage, you just need to search for the geometry data that corresponds to the BVH nodes, this information could be stored within a memory mapped file 
which means that, if an upload needs to occur, a simple memcpy can be performed onto a mapped buffer.

With our cached geometry data loaded off an SSD, we can perform a fast 'zbuffer' pass where the zbuffer contains the depth of the scene, but also keeps track of 
model->bvh->vertex information. This means you end up with essentially a pixel perfect image of all the geometry you will be able to physically see. And since a BVH also contains
coarse culling information you can get away with having to bring in data that would be back-facing anyway..

https://vinayakgarg.wordpress.com/2011/10/25/time-comparison-of-quick-sort-insertion-sort-and-bubble-sort/


https://www.scratchapixel.com/lessons/advanced-rendering/introduction-acceleration-structure/bounding-volume-hierarchy-BVH-part1

!! IMPORTANT

https://www.artima.com/cppsource/safebool.html
https://github.com/jameswynn/simplefilewatcher
https://stackoverflow.com/questions/40504281/c-how-to-check-the-last-modified-time-of-a-file

https://medium.com/@vgasparyan1995/compile-time-merge-sort-c-bb0ace62cc23
https://stackoverflow.com/questions/13180842/how-to-calculate-offset-of-a-class-member-at-compile-time


https://stackoverflow.com/questions/8087836/is-the-order-of-file-level-static-variables-always-the-same-within-a-given-trans

IMPLEMENT_CLASS should always be done before any IMPLEMENT_PROPERTY calls


///////////////////////////////////////////////////////////////////////////////
// 1/11/2021

+ New property system.
* Fixed a problem where strings would not properly handle assignment.


https://docs.microsoft.com/en-us/windows/apps/winui/winui3/xaml-templated-controls-cppwinrt-winui-3



https://bottosson.github.io/posts/oklab/
https://www.gamedev.net/forums/topic/631399-linear-color-space/
https://blog.demofox.org/2018/03/10/dont-convert-srgb-u8-to-linear-u8/
https://bottosson.github.io/posts/colorwrong/#what-can-we-do%3F
https://stackoverflow.com/questions/35952564/convert-rgb-to-srgb
https://stackoverflow.com/questions/1659440/32-bit-to-16-bit-floating-point-conversion
https://exceptionshub.com/32-bit-to-16-bit-floating-point-conversion.html


https://answers.unrealengine.com/questions/25594/accessing-pixel-values-of-texture2d.html
https://github.com/iAmAsval/FModel/commit/09be7a9ea6cc6e2d4542ae6c7a4280aca1ee6e19
https://github.com/ColumbusUtrigas/TGA/blob/master/tga.h
https://github.com/nikoladimitroff/Game-Engine-Architecture

https://www.youtube.com/watch?v=2TTwMFpGR2Q



IFileHandle needs a Close method.
ContentDiskContainer::LoadContent

https://stackoverflow.com/questions/15068475/recursive-hard-disk-search-with-findfirstfile-findnextfile-c

https://github.com/usagi/cereal-UE4
https://bebylon.dev/ue4guide/engine-programming/uobject-serialization/uobject-ustruct-serialization/
https://forums.unrealengine.com/development-discussion/c-gameplay-programming/88477-spawning-actors-from-serialized-data?116235-Spawning-Actors-from-Serialized-Data=&viewfull=1

Very interesting voice synth
https://github.com/DanRuta/xVA-Synth/
https://15.ai/
https://research.nvidia.com/publication/infinite-resolution-textures
https://www.reddit.com/r/gameenginedevs/comments/ktj573/how_are_you_storing_your_rotationsorientations/


When using UCS storage, relative file paths should always be stored using / for folders/directories (not \\ on windows).

https://github.com/Vavassor/ad_mipmap
https://stackoverflow.com/questions/61645259/conversion-from-argb-to-rgba
https://stackoverflow.com/questions/11259391/fast-converting-rgba-to-argb
https://www.reddit.com/r/gamedev/comments/1izbyh/calculating_the_correct_mipmap_level_in_a_shader/
https://gamedev.stackexchange.com/questions/28401/detect-mip-mapping-level-in-the-shader
https://stackoverflow.com/questions/831893/does-it-make-sense-to-use-own-mipmap-creation-algorithm-for-opengl-textures
https://hacksoflife.blogspot.com/2016/05/simultaneous-mipmap-level-generation.html
https://graphics.stanford.edu/~seander/bithacks.html
http://web.cse.ohio-state.edu/~crawfis.3/cse781/Readings/MipMapLevels-Blog.html

https://www.gamedev.net/forums/topic/702951-effecient-texture-mipmap-offset/
https://www.gamedev.net/forums/topic/681709-texture-array-with-mipmaps/






https://www.scichart.com/wpf-chart-features/

https://www.codeproject.com/Articles/43776/Using-WPF-to-Visualize-a-Graph-with-Circular-Depen

https://gamedev.stackexchange.com/questions/3063/should-the-content-pipeline-tools-be-embedded-in-the-engine
https://www.mpc-rnd.com/

https://google.github.io/mediapipe/

FFlowgraphPortSchema
  * Stores the port type, visibility/name is handled within a node schema. 
  * Also stores a PortConnectionRule type, to know what sort of values can be inserted into this port.
    * This can be overridden when creating a flowgraph by providing PortConnectionRuleOverride values onto each port.
  
FFlowgraphNodeSchema
  * Stores information about ports (PortSchemas).
    * Ports can either be local to their owner graph, or global (EFlowgraphPortVisiblity::Local || EFlowgraphPortVisiblity::Global)
	* Ports can also be marked as optional (required by default).
  * Does not have an node instance however.
  * An execution type needs to be declared too (this is created by the compiler in order to actually execute something with the node).

FFlowgraphSchema
  * Stores node schemas, this is attached to a FlowgraphInstance
  * bAllowCyclical - allows for the graph to become a cyclical graph 
  * Also stores any 'default' nodes which are created.
  
FlowgraphNode
  * An instance of an FFlowgraphNodeSchema, has instances for all the ports.
  * These are owned by an FFlowgraph instance.
  
FFlowgraph
  * Stores a single schema, and creates the nodes which are represented via the schema.
  * Maintains connection information.
  * A flowgraph is just a general structure for maintaining a graph of nodes, a flowgraph has no way of knowing *what* the
    nodes actually will do.
  
FFlowgraphSubgraph
  * A subgraph is essentially a flowgraph but exposes only the global internal node parameters.
  * These can be used to create 'templates'.
  * If a subgraph is edited, a local copy is stored within the flowgraph. Otherwise, just a file reference is stored, with input/output slot matchups
  * Connectors 

FFlowgraphCompiler
  * Used to determine the order in which nodes are 'executed'. Supports both sequential and parallel processing of the nodes.
  * This can be overridden to handle special nodes if desired. At this point a final type-check is performed on the graph node.  

FFlowgraphExecutor
  * Executes the graph (depending on the order from the compiler), if nodes can't be executed execution will stop returnning EFlowgraphExecutionError::Node or something.
  
This sort of system suddenly makes new ideas possible where a flowgraph could be a graph which generates geometry at runtime based off a series of parameters
	* Vegetation 'zones', procedural placements of objects/buildings become possible.
	* It can also be used to provide the content pipeline with a graph based interface which can be quite helpful.
	
	
Basically what we need are just arbitrary 'streams' of data that can move through the pipeline. For example, if two materials share the same input files
we only want to process the texture a single time, store the stream somewhere, then access it when processing the remaining files.
	
  
  
https://github.com/githubuser0xFFFF/Qt-Advanced-Docking-System

https://stackoverflow.com/questions/7373205/returning-double-with-precision
https://stackoverflow.com/questions/16888621/why-does-returning-a-floating-point-value-change-its-value






https://www.youtube.com/watch?v=WlRaYZw1rKA - substance designer fern
https://shop.cg3dankfun.com/product/mud-soil-substance-designer_by-angel-fernandes/



https://www.codeproject.com/articles/43025/a-linq-tutorial-mapping-tables-to-objects
https://system.data.sqlite.org/index.html/tree?ci=trunk

https://stackoverflow.com/questions/5824803/linq-to-sql-association-mapping
https://www.codeproject.com/Articles/259317/TagCache-A-NET-cache-that-allows-you-to-tag-aka-la



https://github.com/mmp/pbrt-v3/commit/2f73f777943d8dce328079153464cc77f605e7ed
https://stackoverflow.com/questions/5695477/using-bitscanreverse64
https://stackoverflow.com/questions/3272424/compute-fast-log-base-2-ceiling

https://homepages.fhv.at/thjo/lecturenotes/sysarch/game-engine-architecture.html


TODO:

Move LERP into generics.h or something..
Rtti::TypeInfo_Private FRONT_SIZE needs to be able to distinguish between a class and a structure or something..

!!! CHANGE RANGE BASED FOR LOOPS

math book 
653
690-711
647-649
653-665

673

Smoothstep
https://www.codeproject.com/Articles/30838/Overhauser-Catmull-Rom-Splines-for-Camera-Animatio
https://pomax.github.io/bezierinfo/
https://answers.unrealengine.com/questions/395667/index.html
https://cubic.org/docs/hermite.htm
https://blog.demofox.org/2015/08/08/cubic-hermite-interpolation/

http://web.mit.edu/hyperbook/Patrikalakis-Maekawa-Cho/node12.html#:~:text=A%20B%C3%A9zier%20curve%20is%20a%20parametric%20curve%20that,basis%20function%20determine%20the%20shape%20of%20the%20curve.
https://pastebin.com/f7EzDB25
http://xahlee.info/SpecialPlaneCurves_dir/BezierCurve_dir/bezierCurve.html
https://www.icode.com/c-function-for-a-bezier-curve/

https://cs.wellesley.edu/~cs307/readings/10-bezier.shtml
https://github.com/oysteinmyrmo/bezier

https://www.sciencedirect.com/topics/computer-science/quaternion-multiplication
https://www.haroldserrano.com/blog/developing-a-math-engine-in-c-implementing-quaternions

https://www.cprogramming.com/tutorial/3d/quaternions.html#:~:text=Luckily,%20normalizing%20a%20quaternion%20isn't%20much%20harder%20than,For%20the%20unit%20quaternions,%20the%20magnitude%20is%20one.
http://www.mvps.org/directx/articles/catmull/
https://en.wikipedia.org/wiki/Smoothstep
https://www.gamedev.net/forums/topic/680832-horizonzero-dawn-cloud-system/?page=6
https://www.gamedev.net/forums/topic/603454-what-does-smoothstep-return/

https://www.reddit.com/r/gamedev/comments/fvdtml/smoothstep_the_most_useful_function/
https://www.cs.helsinki.fi/group/goa/mallinnus/curves/curves.html

https://www.gabrielgambetta.com/entity-interpolation.html

http://polymathprogrammer.com/tag/bezier/


https://www.cubic.org/docs/bezier.htm
https://towardsdatascience.com/b%C3%A9zier-interpolation-8033e9a262c2

https://gamedev.stackexchange.com/questions/179400/how-to-convert-unreal-engine-4-spline-to-a-bezier-curve

https://www.paulinternet.nl/?page=bicubic
https://gamedev.stackexchange.com/questions/179400/how-to-convert-unreal-engine-4-spline-to-a-bezier-curve


http://web.mit.edu/hyperbook/Patrikalakis-Maekawa-Cho/node22.html



rtr 593

https://codereview.stackexchange.com/questions/37592/computing-tangent-space-basis-vectors-for-an-arbitrary-mesh
https://stackoverflow.com/questions/4089443/find-the-tangent-of-a-point-on-a-cubic-bezier-curve
https://people.sc.fsu.edu/~jburkardt/c_src/spline/spline.html
https://stackoverflow.com/questions/785097/how-do-i-implement-a-b%C3%A9zier-curve-in-c

http://steve.hollasch.net/cgindex/curves/cbezarclen.html
http://mathbitsnotebook.com/Algebra1/FunctionGraphs/FNGTypeLinearQuad.html

https://www.gamasutra.com/blogs/MarcBeaujean/20200518/363095/Vector_Maths_for_Game_Dev_Beginners.php


https://stackoverflow.com/questions/4833380/how-to-convert-a-3x3-rotation-matrix-into-4x4-matrix


https://keithmaggio.wordpress.com/2011/02/15/math-magician-lerp-slerp-and-nlerp/
https://forum.unity.com/threads/solved-when-quaternion-slerp-finishes.44316/
https://forum.unity.com/threads/what-is-the-difference-of-quaternion-slerp-and-lerp.101179/

http://www.songho.ca/math/quaternion/quaternion.html

https://www.lemoda.net/maths/bezier-length/index.html
https://gamedev.stackexchange.com/questions/17967/how-would-one-determine-the-length-of-a-path


https://github.com/ocornut/imgui/issues/578
https://ninedegreesbelow.com/photography/linear-gamma-blur-normal-blend.html


https://bottosson.github.io/posts/oklab/
https://github.com/thomasp85/farver/tree/master/src


https://stackoverflow.com/questions/35952564/convert-rgb-to-srgb


https://www.ryanjuckett.com/rgb-color-space-conversion/


https://www.gamedev.net/forums/topic/672860-d3d12-placed-resources/
https://asawicki.info/news_1726_secrets_of_direct3d_12_resource_alignment


https://www.gamedev.net/forums/topic/700869-confirmation-on-gaffers-state-synchronization-method/
https://nbertoa.wordpress.com/2016/07/13/directx12-multithread-architecture-a-first-approach/
https://www.gamedev.net/forums/topic/673728-d3d12-command-queue-fence-synchronization/
https://github.com/MicrosoftDocs/win32/blob/docs/desktop-src/direct3d12/user-mode-heap-synchronization.md

https://iq.opengenus.org/author/alexa/


https://zhuanlan.zhihu.com/p/147207161
https://zhuanlan.zhihu.com/p/98572442
http://www.ademolathompson.com/blackosiris/2018/2/14/frame-graph

https://www.slideshare.net/naughty_dog/multiprocessor-game-loops-lessons-from-uncharted-2-among-thieves


/*
		When using multiple devices each resource will have an instance of FReplicatedResourceSet
		which is used to contain a series of FReplicatedResource instances.

		Replication can occur however the backing device wishes but, using a GPU->CPU replication for example,
		the following steps would occur

			A Texture exists on GPU memory, and wishes to be replicated to a CPU device.
			This will trigger a dynamic readback of the texture resource into CPU memory.

			CPUDevice->ReplicateResource(TextureResource);

			To check if the replication is ready

			FReplicatedResource* Replication;
			Replication->HasReplicated() -or- Replication->WaitForReplication();

			When command lists are submitted they are marked with a special flag which
			determines what hardware the command list will execute on. At this stage
			all resources referenced within the command list will check to ensure they have
			replication information on the executing device. If not, the resources are replicated
			and the command list will not be submitted until the replication is completed.

			This can be a potentially slow operation, so it is strongly recommended to create
			the replication information at the same time the resource is created.
	 */
	 
	 /*
	struct FD3D12SyncPointCallbackData
	{
		TDelegate<void(void*)> Callback;
		void* UserData;
	};

	void SyncPointCallback(void* Ptr)
	{
		FD3D12SyncPointCallbackData* CallbackData = (FD3D12SyncPointCallbackData*)Ptr;
		CallbackData->Callback(CallbackData->UserData);
	}

	void WaitForSyncPoint(FD3D12SyncPoint* SyncPoint)
	{
		SyncPoint->ThreadEvent->WaitForTrigger(Timespan::MaxValue());
		
		// Dispatch a job which notifies the caller of the sync point being completed..
		// This will return back to user code with the specified user data pointer..

		// At this point two things need to happen. First, the event needs to be reset..
		SyncPoint->ThreadEvent->Reset();

		// Free the hardware fence instance
		SyncPoint->HardwareFence = nullptr;

		// And finally, return the sync point to the pool..
		// FD3D12SyncPointPool::Return(SyncPoint);
	}
	*/

	/*
		A hardware fence has a single ID3D12Fence object, but when a sync is required, it can be performed in two ways.

		1)	The sync is performed synchronously using FHardwareFence::SyncToThis or FHardwareFence::SyncToValue
			This will cause the caller to perform a hard CPU stall waiting for the fence.
			This is the primary mode of synchronization. When this is performed no FD3D12SyncPoint will be queued.

		2)	The sync is performed asynchronously using FHardwareFence::PerformAsyncSync
			This will not perform a hard CPU stall, but will queue a single FD3D12SyncPoint and return a SyncPointHandle which can be waited upon.

			Due to the asynchronous nature it may take a period of time for the callback to be performed (thus indicating a sync).
			The reason for this is sync point checks are only performed once per frame, and callbacks are sent via the job system.
			
			Therefore these are best used for things such as streaming background data which will not be needed for a period of time.
			If the data is needed before rendering can continue one option is to use the FHardwareDevice::WaitForSyncHandle, which will perform
			a hard CPU stall, or if the sync point was submitted using the EmitSignal flag it is possible to perform a GPU sync.

			The advantage of using the signal will be it becomes possible to start using data for rendering before the callback has occurred,
			but if the callback performs manipulation on that data a CPU stall is the only way.

			Therefore:

			EAsyncSyncPointFlags
			{
				None					= ( 0 ),		// The callback performs no manipulation of the data which would affect the data as it exists on the GPU.
				PerformsCpuManipulation = ( 1 << 0 ),	// The callback performs manipulation of the data, as it would exist on the GPU (i.e. Map).
				PerformsGpuManipulation	= ( 1 << 1 ),	// The callback will perform manipulation of the data using GPU command lists.
				EmitSignal				= ( 1 << 2 )	// A GPU signal should be emitted on the FHardwareEngine the fence was using or something...
			}
	 */

https://docs.unrealengine.com/en-US/RenderingAndGraphics/RayTracing/MovieRenderQueue/index.html



D3D12_SHADER_CACHE_SUPPORT_FLAGS
https://docs.microsoft.com/en-us/windows/win32/direct3d12/memory-management-strategies

https://github.com/Microsoft/DirectX-Specs/blob/master/d3d/CPUEfficiency.md
https://www.reddit.com/r/buildapc/comments/imgwct/m2_nvme_speed/
https://www.paudal.com/2021/02/25/more-details-about-microsoft-directstorage-technology-paudal/
https://techreport.com/news/3473104/what-is-nvidia-rtx-io/#:~:text=RTX%20IO%20is,%20in%20short,%20the%20meeting%20of,number%20of%20IO%20requests%20made%20by%20modern%20games.
https://github.com/elasota/ConvectionKernels
https://github.com/dloss/binary-parsing
https://gamedev.stackexchange.com/questions/165435/why-are-committed-resources-better-than-placed-resources
https://docs.microsoft.com/en-us/windows/win32/direct3d12/upload-and-readback-of-texture-data


https://docs.microsoft.com/en-us/windows/win32/api/d3d12/ne-d3d12-d3d12_memory_pool
https://asawicki.info/news_1726_secrets_of_direct3d_12_resource_alignment


https://docs.microsoft.com/en-us/windows/win32/api/d3d12/ns-d3d12-d3d12_resource_desc

https://github.com/baldurk/renderdoc/commit/a59ebcbc3bfebf9ea7c61e76d724df472daacf11


https://zhangdoa.com/posts/walking-through-the-heap-properties-in-directx-12
https://techdifferences.com/difference-between-uma-and-numa.html
https://devblogs.microsoft.com/directx/dred/


https://pcpartpicker.com/b/h6DxFT (search for NUMA)

I'm looking forward to the RTX-3070 & air-cooling with thermosiphons. IceGiant's TS is a rather tall cooler, but its reliability should be good & simplicity counts.

RTX-3070: FP32 20 TFLOPS, Tensors are an eye-watering 80 TFLOPS.

AMD’s Threadripper designs are essentially VLSI’s of dual-socket Ryzens, w/ the NUMA overheads optimized using an infinity fabric** & 64-lane PCIe. An Intel equivalent would be a pretty beefy pair of Xeons on an expensive socket.

** akin to the 12-cube interconnects of the Thinking Machine CM's ca 1992

The RTX-3000's can direct fetch from NVMe (previously only available on the latest Titan cards (Turing, Volta & Pascal )), cutting IO considerably even for accel. DBMS (see pg-strom, Greenplum, etc.).

https://docs.microsoft.com/en-us/windows/win32/api/d3d12/ne-d3d12-d3d12_texture_layout
https://github.com/microsoft/DxCapsViewer/releases
https://polycount.com/discussion/107978/size-of-texture-on-video-memory

https://software.intel.com/content/www/us/en/develop/articles/parallel-processing-with-directx-3d-12.html
https://www.codeproject.com/articles/1094799/implementing-dynamic-resources-with-direct-d

https://docs.microsoft.com/en-us/windows/win32/direct3d12/residency
https://devblogs.microsoft.com/directx/coming-to-directx-12-more-control-over-memory-allocation/
https://www.slideshare.net/IntelSoftware/dynamic-resolution-techniques-for-intel-processor-graphics-siggraph-2018-tech-session
https://www.programmersought.com/article/283396314/
https://www.3dgep.com/learning-directx-12-2/

https://github.com/coolbutuseless/zstdlite


D3D12 pipeline library


Windows 10, version 1809 (10.0; Build 17763
https://docs.imgtec.com/Architecture_Guides/PowerVR_Architecture/topics/powervr_architecture_tile_based_deferred_rendering__tbdr.html 


		/** Signals this fence to a specific value. */
		virtual void Signal(uint64 Value) = 0;

		/** Returns the last value completed by the fence. */
		virtual uint64 GetLastCompletedValue() const = 0;
		
		/** Increments the fence value and returns the current fence value. */
		virtual uint64 IncrementFenceValue() = 0;

		/** Returns the current fence value. */
		virtual uint64 GetFenceValue() const = 0;

		/** Stalls the CPU while waiting for the fence to sync. */
		virtual void SyncToThis() = 0;

		/** Stalls the CPU while waiting for the fence to sync to a specific value. */
		virtual void SyncToValue(uint64 ValueToWaitFor) = 0;

		/**
		 * Performs an asynchronous sync point which allows for the caller to continue execution instead of blocking.
		 * 
		 * @param ValueToSyncTo			The fence value to sync to.
		 * @param SyncCallback			The callback to perform when the value has been reached (must not be invalid).
		 * @param CallbackUserData		Optional user data to add to the callback. This must exist until the callback has been executed.
		 * @param OptionalWaitCounter	An optional counter to allow for waiting on the sync point to occur.
		 */
		virtual void SyncToValueAsync(uint64 ValueToSyncTo, const HardwareFenceAsyncSyncDelegate& SyncCallback, void* CallbackUserData, Async::FiberCounter* OptionalWaitCounter) = 0;


D3D12_RESOURCE_HEAP_TIER1 (Indicates that heaps can only support resources from a single resource category.)

0: D3D12_HEAP_TYPE_DEFAULT + buffer
1: D3D12_HEAP_TYPE_DEFAULT + texture
2: D3D12_HEAP_TYPE_DEFAULT + texture RT or DS
3: D3D12_HEAP_TYPE_UPLOAD + buffer
4: D3D12_HEAP_TYPE_UPLOAD + texture
5: D3D12_HEAP_TYPE_UPLOAD + texture RT or DS
6: D3D12_HEAP_TYPE_READBACK + buffer
7: D3D12_HEAP_TYPE_READBACK + texture
8: D3D12_HEAP_TYPE_READBACK + texture RT or DS

otherwise
 0: D3D12_HEAP_TYPE_DEFAULT
1: D3D12_HEAP_TYPE_UPLOAD
2: D3D12_HEAP_TYPE_READBACK



Resource tiling (for mip-maps stored in their own heaps)

see Framework.cpp:1272 

By default, D3D12's TIER1 support for virtual addressing supports a 40-bit virtual address space, which is equal to 1 terabyte.
D3D12_TEXTURE_LAYOUT_64KB_UNDEFINED_SWIZZLE - Guaranteed with TIER_1










https://practical365.com/blog/how-to-use-azure-cdn-content-delivery-network/
https://github.com/sunnyszy/lrb
https://github.com/d07RiV/blizzget







	/*
		Notes for tomorrow:

		When using an upload buffer on a NUMA architecture, only MEMORY_POOL_L0 supports this,
		therefore it's easier to think that an upload buffer exists in RAM (not VRAM).

		An example of this is a GTX1070.

		AMD VEGA GPUs use UMA which means that the upload buffer could possible exist within VRAM (though, this isn't guaranteed).


		UMA
			There is only one physical memory pool shared by the GPU and CPU, example being an Xbox One, this means that
			only MEMORY_POOL_L0 is available.

		Most of the gaming desktop world though use NUMA architectures (except new AMD cards). In this case
		MEMORY_POOL_L0 is RAM and MEMORY_POOL_L1 is VRAM


		This means that using a heap type of CUSTOM allows for more flexible control over the heap configuration.
		The following guide only applies to NUMA architectures:

		D3D12_CPU_PAGE_PROPERTY_NOT_AVAILABLE
			L0 - Similar to HEAP_TYPE_DEFAULT, a GPU only RAM (nonsense for common usage cases).
			L1 - Similar to HEAP_TYPE_DEFAULT, GPU only VRAM

		D3D12_CPU_PAGE_PROPERTY_WRITE_COMBINE
			L0 - Similar to HEAP_TYPE_UPLOAD, uncached/inconsistent for CPU reading, but write operations are faster.
			L1 - Invalid, CPU can not access VRAM directly.

		D3D12_CPU_PAGE_PROPERTY_WRITE_BACK
			L0 - Similar to HEAP_TYPE_READBACK, GPU writes are cached, and CPU reading is consistent.
			L1 - Invalid, CPU can not access VRAM directly.

		Therefore, for NUMA architectures, a custom heap won't really provide any benefit. However, for better configuartion
		on all possible architectures, custom heaps are still a viable solution (especially considering AMD).

		Regardless, this opens the possibility where of using placed resources which are required to satisfy the
		requirements of our EResourceClassification system. This also means we will be maintaining the heap memory
		ourselves using a similar system as the core page allocator (essentially just blocks).

		However, not every heap type requires the same type of allocation strategies (Streaming heaps can use a ring buffer for example).

		So what we really need is something like a

		class D3D12HeapAllocator {

			// This returns the offset of the memory allocation within the heap.
			virtual uint64 GetAllocationOffset(uint32 TotalSizeInBytes) = 0;
		};
		
		class D3D12Heap {
			
			// Set the allocator which is used for this heap.
			D3D12Heap(D3D12HeapAllocator* Allocator);
		};

		Alternatively, we could just use a template for this (which saves us virtual calls).

		template <class UnderlyingAllocator>
		class D3D12Heap {
			uint64 GetAllocationOffset(uint64 SizeInBytes) {
				return UnderlyingAllocator::GetAllocationOffset(SizeInBytes);
			}
		}

		That system may be preferable since streaming memory will usually use a totally different heap..
	 */
	 
	 
https://launchpad.net/libmct
https://stackoverflow.com/questions/2504178/lru-cache-design/


enum class EHeapType
	{
		Default,
		Upload,
		Readback,
		Custom
	};

	enum class ECpuPageProperty
	{
		Unknown,
		NotAvailable,
		WriteCombine,
		WriteBack
	};

	enum class EMemoryPool
	{
		Unknown,
		L0,
		L1
	};

	enum class EHeapFlag
	{
		None,
		Shared,
		DenyBuffers,
		AllowDisplay,
		SharedCrossAdapter,
		DenyRenderTargetAndDepthStencilTextures,
		DenyNonRenderTargetOrDepthStencilTextures,
		HardwareProtected,
		WriteWatch,
		AllowAllBuffersAndTextures,
		AllowOnlyBuffers,
		AllowOnlyNonRenderTargetAndDepthStencilTextures,
		AllowOnlyRenderTargetOrDepthStencilTextures
	};

	struct HeapProperties
	{
		HeapProperties() :
			Type(EHeapType::Default),
			PageProperty(ECpuPageProperty::Unknown),
			MemoryPool(EMemoryPool::Unknown),
			SizeInBytes(0),
			Alignment(0),
			Flags(EHeapFlag::None)
		{ }

		/** The type of the heap. */
		EHeapType Type;

		/** CPU paging property for the heap. */
		ECpuPageProperty PageProperty;

		/**  memory location of the heap. */
		EMemoryPool MemoryPool;

		/** The size of the heap in bytes, only needed when calling CreateHeap */
		uint64 SizeInBytes;

		/** The alignment of the heap in bytes, only needed when calling CreateHeap */
		uint64 Alignment;

		/** Flags for the heap, only needed when calling CreateHeap */
		EHeapFlag Flags;
	};
	
	
HEAP defragmenter


https://www.gamedev.net/forums/topic/708960-directx12-many-pipelinestate-changes-vs-universal-shader-design/5435285/
https://microsoft.github.io/DirectX-Specs/d3d/BackgroundProcessing.html
https://github.com/xuechao-chen/DDGI
https://zhuanlan.zhihu.com/p/262332553
https://thetoolsmiths.org/codex/learning_paths/tools_engineer_learning_path/core_game_tools_development
https://forum.beyond3d.com/threads/game-development-presentations-a-useful-reference.46956/page-31
http://c0de517e.blogspot.com/2020/12/why-raytracing-wont-simplify-aaa-real.html
https://forum.beyond3d.com/threads/viability-of-aaa-game-development-spawn.61846/
http://alextardif.com/Antialiasing.html

https://stackoverflow.com/questions/936999/what-is-the-default-constructor-for-c-pointer

https://docs.microsoft.com/en-us/windows/win32/direct3ddxgi/variable-refresh-rate-displays
https://ptspts.blogspot.com/2013/08/non-recursive-fast-compact-stable-sort.html
https://www.geeksforgeeks.org/cpp-program-for-quicksort/
http://www.cplusplus.com/forum/beginner/119660/
https://docs.microsoft.com/en-us/windows/uwp/gaming/handling-device-lost-scenarios


https://codereview.stackexchange.com/questions/177616/avx-simd-in-matrix-multiplication

https://stackoverflow.com/questions/31181233/writing-a-hlsl-shader-for-rescaling-floating-point-textures

https://stackoverflow.com/questions/42042132/in-d3d12-can-the-render-target-view-be-any-buffer


https://github.com/baldurk/renderdoc/issues/1076







How d3d12 command list generation will work and notes about submission and memory organization

We use a double pass approach where initially the game state will flip to 'read-only', and we begin building
our command lists via a parallel system. This works best where, for example, when rendering something such as 
shadows, the shadow map will need to know about the geometry which is visible. And again this must also occur
when doing things such as the main gbuffer generation, ect, ect.

This means that as tasks are queued, they will be split such that for shadow command lists, for example, we try
to have a single version of geometry which has been uploaded at once, but the requirement for geometry is split 
across multiple buckets/command lists. This is done to help reduce the amount of uploading which needs to occur.

This is where the two part-command list graph comes into play.. each 'pass' of the scene which have a corresponding
series of command lists, which have their own version of data.

Resources are then identified using one of two special handles:

SharedHandle -  The resource is shared between multiple buckets/passes, used to mark a dependency between passes on a
				per-resource level. A majority of resources which are shared go here.
				
GlobalHandle - 	The resource is shared between multiple frames, always goes into the main heap.
				Resources using this handle should be kept to a minimum as they do not benefit
				from the memory-purge system. To release they a call to Driver::ReleaseCriticalResource
				must occur.
				
Now, some things such as shadow casters can be merged with other command lists, meaning, each bucket should
contain multiple tiny command lists, which are then merged at the end into single large streams.

This means it's possible that you can split the buckets up on the C++ side, then on the GPU side 
be using the geometry for essentially a shadow-pass followed by GBufferGen pass. Doing it this way guarantees
that the data which is required will always be in memory (since we are aiming for command list bundles of 3-5 each).

However, there becomes a slight problem where some things may require a full shadow map in order to draw properly..
For example, a directional light source is required to have all the data. So perhaps what needs to happen is have
a system which has resource groups (basically the shared handle), but there must also be a requirement or something.



		// Create the per-thread memory page allocators. This is important because we want to ensure that we divide evenly the total size
		// for an upload heap, as well as a regular GPU only heap. These sizes are tuned to the logic of more threads = less memory per thread.
		// However, we will need to ensure that eventually we are combining at least 3 command lists to each 'execute command list' call, ideally..
		// But to make this occur we need to know the expected workload of a command list (as in, how long it will take), and also to ensure that
		// each

CACHE SYSTEM - Detect multiply reuploads, only cache things which are > 2kb?


https://codereview.stackexchange.com/questions/242428/own-implementation-of-c-stdstring-view
https://github.com/martinmoene/string-view-lite
https://www.bing.com/search?q=std%3A%3Astring_view%20implementation%20github&qs=n&form=QBRE&sp=-1&pq=std%3A%3Astring_view%20implementation%20github&sc=0-38&sk=&cvid=E54F391CEE8C4B90B50E0BDD885CC547





NOTE FOR TOMORROW: Need to figure out how to do ToStringView for String and TFixedString.
String needs to be renamed to TString, not sure why this wasn't a thing before.

The string view needs to be clamped to the length of the string
the length needs to be clamped to the offset + count - length 

This also needs to be tested.

https://taylorconor.com/blog/enum-reflection/

https://www.unrealengine.com/en-US/blog/optimizing-tarray-usage-for-performance
https://www.foonathan.net/2020/09/move-forward/
http://bajamircea.github.io/coding/cpp/2016/04/07/move-forward.html
https://stackoverflow.com/questions/7054952/type-trait-for-moveable-types
https://stackoverflow.com/questions/257288/templated-check-for-the-existence-of-a-class-member-function
https://stackoverflow.com/questions/3413470/what-is-stdmove-and-when-should-it-be-used
https://stackoverflow.com/questions/6534041/how-to-check-whether-operator-exists
https://stackoverflow.com/questions/45747932/c-type-trait-to-say-trivially-movable-examples-of
https://docs.microsoft.com/en-us/cpp/cpp/explicitly-defaulted-and-deleted-functions?view=msvc-160
https://en.cppreference.com/w/cpp/language/copy_assignment
https://stackoverflow.com/questions/41936763/type-traits-to-check-if-class-has-member-function
https://stackoverflow.com/questions/2122319/c-type-traits-to-check-if-class-has-operator-member


Important implementation notes: We always perform a self-assignment operator in both standard assignment and move operators.
https://isocpp.org/wiki/faq/assignment-operators
https://www.gamedev.net/forums/topic/692697-copy-move-and-assignment-operators-with-a-derived-class/
http://www.vollmann.ch/en/blog/implementing-move-assignment-variations-in-c++.html

https://answers.unrealengine.com/questions/143888/how-do-i-remove-items-from-a-tarray-while-iteratin.html


/** An iterator which is used to help dereference items stored within a container. */
template <typename T, typename IteratorType>
class TDeferencedIterator
{

public:

	explicit TDeferencedIterator(IteratorType Iterator) :
		Iterator(Iterator)
	{ }

	FORCEINLINE T& operator*() const
	{
		return *(T*)*Iterator;
	}

	FORCEINLINE TDeferencedIterator& operator++() const
	{
		++Iterator;
		return (*this);
	}

	FORCEINLINE TDeferencedIterator& operator--() const
	{
		--Iterator;
		return (*this);
	}

private:

	/** The instance to deference. */
	IteratorType Iterator;
};
	
	
Delegate::RemoveBoundCallback needs to use the Find not do a manual search.

https://schani.wordpress.com/2010/04/30/linear-vs-binary-search/
https://developers.redhat.com/blog/2019/04/12/understanding-when-not-to-stdmove-in-c
https://jfdube.wordpress.com/2011/10/22/memory-management-part-3-memory-allocators-design/
https://algoland.wordpress.com/2013/12/29/a-tiny-parser-in-c/
https://github.com/tommybazar/TBRaymarchProject

https://www.youtube.com/watch?v=I75KU_ldfO8 - EBNF
https://www.codeproject.com/Articles/1214286/Formula-Compiler-using-Cplusplus-BNF-like-EDSL
https://github.com/katahiromz/EbnfParser


http://www.ignaciogarciadorado.com/p/2017_TOG/2017_TOG.html
http://ibreakdownshaders.blogspot.com/2015/03/noise-loudening.html
https://www.iquilezles.org/index.html
http://dwtkns.com/posts/flowing-ice.html

https://devblogs.microsoft.com/oldnewthing/20191011-00/?p=102989
https://www.learncpp.com/cpp-tutorial/class-template-specialization/
