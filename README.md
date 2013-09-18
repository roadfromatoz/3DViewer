3DViewer
========

apply homography to create planar 3D scene from a single photograph (or painting)

This MATLAB program creates a simple planar 3D scene from a single photograph. It assumes that the back plane in the photograph is in parallel with the image plane. By specifying the back plane and the vanishing point, it is able to divide the photograph into five planes (floor, ceiling, left, right, back) and compute homography matrix to restore each plane. From that, a 3D scene is easily built. You can also walk into the scene.



Virtual room from a photograph
http://www.youtube.com/watch?v=Q9sXZPS540U

Virtual scene from a painting
http://www.youtube.com/watch?v=HoBNbMwiU0A
