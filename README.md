# Next.js 15 App Router - Unexpected Image Path Resolution

This repository demonstrates a potential issue with image path resolution in Next.js 15's App Router when using relative paths within components.  The issue manifests when the images are located in a subdirectory relative to the component. 

**Problem:** Images fail to load due to incorrect path resolution when the image is located in a subdirectory relative to the component file.

**Solution:** Use a `basePath` or adjust the image path to be absolute (starting from the `public` directory).  See the `bugSolution.js` file for a corrected approach.
