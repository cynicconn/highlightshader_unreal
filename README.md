# highlightshader_unreal
Unreal 4 Project for testing and sharing Highlight Surface Shaders using Rendering Buffers
Engine Version: 4.14

--MATERIAL DESCRIPTIONS--
mMat_ExtrudeOutline: for inflating mesh by Vertex Normals ( Mat applied on Mannequin OutlineMesh )
mMat_HighlightOutline: Creating Outline around Mesh by sampling from Custom Stencil
mMat_HighlightToon: Quick-and-Easy Toon Shader effect, meant to be paired with mMat_ExtrudeOutline on Manequin
mMat_HighlightGhost: "ShakeyCam" Ghost Vision visual effect ( Inspired by Metroid Prime )
mMat_HighlightThermal: Thermal Vision visual effect using WorldNormal and SceneDepth Buffer ( Inspired by Metroid Prime )
