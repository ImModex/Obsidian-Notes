
Properties -> Things from Unity Editor into Shader
Shader "\<Name\>"

Tags to categorize the Shader and for Render Queue

Vertex and Fragment Shader

Order: Vertex -> Fragment

Vertex Shader transforms points into camera space, Fragment shader runs in the rasterizer stage

float4 is an array with 4 slots

v2f = vertex to fragment, defines what comes *out* of the vertex shader and goes *into* the fragment shader

Normal maps define the direction of the normal vectors, this can make a plane look like a 3d object while the efficiency of a 2d object remains

