### Welcome to my github page
I have recently finished my Master's thesis about human pose estimation of adult-child interaction.

## Interesting repositories/projects
I have a few public repositories with a more detailed explanation:
- [Sorting algorithms](https://github.com/martijndekker98/Sorting-algorithms): I have implemented a small program where a few sorting algorithms can be tested. Thanks to the general BasisSortAlgorithm, adding a new sorting algorithm is extremely easy. Meanwhile, the Random extension allows for generating all possible Int32 and Int64 numbers, without excluding the Int32.MaxValue. The wrappers for the numbers allow the program to be extended to sort non-numbers as well by simply adding a new class.
- [Simple neural networks](https://github.com/martijndekker98/SimpleNeuralNetworks): I created and tested a few simple neural networks to showcase what kind of network works best on classifying images (Mnist and Cifar10 datasets). As the images get larger and more complex (e.g., from monochrome to RGB) the use of a fully connected neural network becomes less plausible as the the required network becomes too large to train. Luckily convolutional neural networks can solve this problem by significantly reducing the number of parameters that need to be trained, and in turn they can achieve higher performances.
- [Multimedia retrieval system](https://github.com/martijndekker98/Multimedia-retrieval-system): Finding 3D meshes/models most similar to a query mesh/model can be quite difficult because determining how similar two meshes are is complex. In order to do so, the meshes should all be normalised to remove any 'noise' such as the size and orientation (these aspects are noise because a mesh can easily be rotated or scaled up/down without inherently changing the mesh). The retrieval system is able to find similar meshes based on a few features (such as surface area, the average distance between two random vertices etc) which are computed beforehand to speed up the process. Using K-nearest neighbors can speed up the querying but also tends to lower the quality of the results. Using a custom distance function is slower but has the highest performance. When a database of meshes is large, however, using a custom distance function will not be feasible because this would require too many computations.
<!--
**martijndekker98/martijndekker98** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
