# FaceMask-Detection

Techniques used to create images:
1. Taking normal images of faces
2. Creating a custom CV script to add face masks on them

Usually we infer the location of facial structures such as Eyes, Eyebrows, Nose, Mouth, Jawline, Moustache,etc.
Steps:
1. Started with an image of person without mask
2. Apply face detection to compute the bounding box location of face
3. Extracted face region of interest
4.Get image of a mask, and align it on top of the face properly
5. Repeating the steps for multiple images








