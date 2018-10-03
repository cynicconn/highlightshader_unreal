# highlightshader_unreal
Unreal 4 Project for testing and sharing Highlight Surface Shaders using Rendering Buffers
Engine Version: 4.14

## Material Descriptions
* __mMat_ExtrudeOutline__: for inflating mesh by Vertex Normals ( Mat applied on Mannequin OutlineMesh )
* __mMat_HighlightOutline__: Creating Outline around Mesh by sampling from Custom Stencil
* __mMat_HighlightToon__: Quick-and-Easy Toon Shader effect, meant to be paired with mMat_ExtrudeOutline on Manequin
### Inspired By Metroid Prime
* __mMat_HighlightGhost__: "ShakeyCam" Ghost Vision visual effect
* __mMat_HighlightThermal__: Thermal Vision visual effect using WorldNormal and SceneDepth Buffer
