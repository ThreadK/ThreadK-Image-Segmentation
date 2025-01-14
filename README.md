# Application of Graph Segmentation Algorithm for Image Segmentation

This algorithm for graph-segmentation was originally developed by Pedro F. Felzenszwalb. The C++ implementation is available under the terms of the GNU General Public License.

Refer to the research work 'Efficient Graph-Based Image Segmentation' by Pedro F. Felzenszwalb and Daniel P. Huttenlocher, published in the International Journal of Computer Vision, Volume 59, Number 2, September 2004. Link: http://cs.brown.edu/~pff/segment/

Modified for this version by ThreadK.

This code is adapted to make the algorithm compatible with different image formats and flexible for use with popular libraries like OpenCV. It can now be easily integrated with the Robot Operating System (ROS).

To run this software, ensure the following dependencies are installed:

- OpenCV
- cmake

Compilation Instructions:

a. Navigate to the GraphSegmentation directory
b. Create a new directory named 'build'
c. Run the cmake command
d. Compile using the make command

The compiled binary will be in the build/apps directory. An example image has been provided in the img directory for quick testing.

Execution command:
a) ./graph_segmentation ../../img/339.jpg

   ./(name_of_binary) (path_to_image)