
Properties -> Things from Unity Editor into Shader
Shader "\<Name\>"

Tags to categorize the Shader and for Render Queue

Vertex and Fragment Shader

Order: Vertex -> Fragment

Vertex Shader transforms points into camera space, Fragment shader runs in the rasterizer stage

float4 is an array with 4 slots

v2f = vertex to fragment, defines what comes *out* of the vertex shader and goes *into* the fragment shader

Normal maps define the direction of the normal vectors, this can make a plane look like a 3d object while the efficiency of a 2d object remains



## Texturing

- Bump maps are the predecessor of normal maps

> Normal maps are so blue, because z-Axis is between 0-1 while x+y between -1 and 1

- Parallax mapping = Simulate distance (move further away things slower than more nearby)

- Environment mapping -> What is being reflected? What does a Raycast hit



### A CUBE HAS **24** VERTICES


Anisotropic Filtering won't come to the test

Test: 
- A4 Schummelzettel
	- Lambpert diffusion lighting
	- Formeln only
- AM ZETTEL
- TASCHENRECHNER




Mögliche Testfrage:
Transparente Objekte müssen BACK TO FRONT berechnet Werden!!!



### Shader Project
- Normal Mapping
- Light Shader
- Hologram
- 2 Beleuchtete Objekte
- Wände = Quad mit Backface Culling
- Stencil Buffer



#### Stencil Buffer
- Mit 0 befüllt per default
- Objekte können Stencil Buffer zugewiesen werden
- Werte 1,2,3,...