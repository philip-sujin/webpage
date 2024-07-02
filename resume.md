# SUJIN PHILIP

**LinkedIn:** [linkedin.com/in/sujinphilip](http://www.linkedin.com/in/sujinphilip)\
**Webpage:** [https://philip-sujin.github.io/webpage](https://philip-sujin.github.io/webpage)

## PROFILE
- MS. Computer Science with specialization in Graphics and Visualization
- Skilled in modern C++ programming
- 13+ years experience in the industry, mainly specialized in HPC
- Working on open source, scientific visualization software: VTK, ParaView, and VTK-m. VTK-m makes extensive use of modern C++ features (C++14)

## ACADEMIC QUALIFICATION
- MS. Computing – Graphics and Visualization, University of Utah, GPA 3.9, 2014
- BE. Computer, University of Pune, First Class, 2006

## TECHNICAL SKILLS
**Proficient:** C++, C, Python, Cuda, MPI, Multithreading, CMake\
**Competent:** OpenGL, TBB, Thrust, Shell Scripting

## WORK EXPERIENCE

### Kitware Inc.
**Staff R&D Engineer**\
*Nov 2014 – Present*

Member of the Scientific Computing Team. Working on some of the most popular and cutting-edge open source visualization software: VTK, VTK-m, and ParaView.

- Worked on [VTK-m](https://gitlab.kitware.com/vtk/vtk-m) as one of the primary developers under the DOE Exascale Computing Project:
  - Implemented VTK-m filters like Clip, ExternalFaces, etc
  - Implemented VTK file readers in VTK-m
  - Implemented a mechanism to simulate virtual functions on Cuda, which was used to implement abstract array types
  - Implemented functionality for serialization of VTK-m objects to support use of the DIY library (a parallelization library built on top of MPI)
  - Implemented the Kokkos-based device backend for VTK-m which is the backend used on the exascale machines Frontier and Aurora, with AMD and Intel GPUs
  - Improved and fixed bugs in core areas of other backends like Cuda (based on Thrust) and OpenMP.
  - Lead developer for VTK-m integration to VTK and ParaView
    - Implemented filters in VTK which internally utilized VTK-m filters for accelerated processing
    - Implemented factory overrides for filters, so that VTK-m based filters were transparently called when available
    - Implemented mechanisms to minimize data copy between device and CPU, such as wrappers for VTK-m arrays by subclassing VTK’s abstract arrays
    - Implemented other optimizations such as performing field range computation on device to avoid data transfer to CPU for this common operation
- Worked on the IARPA Haystac project
  - Implemented a parallel city traffic simulator in Python using SUMO and MPI
  - Implemented an Airflow DAG for the simulation workflow. The tasks were deployed using Kubernetes POD operators, on AWS EC2 instances, running Docker images. The intermediate and final results were stored on AWS S3.
- Other notable projects:
  - Implemented parallel filters and other functionalities for resampling multi-partition datasets of any type into a structured dataset. This was used to perform faster volume rendering of multi-piece unstructured datasets in ParaView.
  - Implemented a proof-of-concept application to demonstrate interoperability between VTK-m’s Cuda backend and OpenGL. Field data could be passed from VTK-m, directly to an OpenGL context, avoiding intermediate data transfers from GPU to CPU, and back to GPU.
- Made contributions to CMake and commercial projects

### Persistent Systems Limited
**Software Developer**\
*Sep 2006 – Jul 2009*

Member of the project group that handled PSL's client, Netezza Corporation.

- Development and maintenance of software for the Snippet Processing Unit (SPU)―the processing nodes of Netezza's massively parallel database appliance systems (NPS)
- Key projects:
  - Developed a tool to track heap memory allocations on the snippet processing units to help analysis of memory leaks
  - Investigated techniques to enable automatic leak detection on the SPUs. Implemented prototypes based on Mark and Sweep algorithm and methods based on tagging allocations with their intended scope and lifetime

## RESEARCH ASSISTANTSHIP AND INTERNSHIPS

### Scientific Computing and Imaging Institute
**Research Assistant**\
*Jan 2010 – Aug 2014*

Worked on heterogeneous parallel computing for scientific computing and visualization applications.

- Developed a scalable, parallel, out-of-core solver for gradient domain processing of large, gigapixel sized images using multithreading, GPGPU and MPI
- Developed a scalable, parallel, out-of-core technique for computing seams for gigapixel sized panoramas using multithreading and MPI

### Lawrence Livermore National Laboratory
**Graduate Intern**\
*Summer 2012*

Collaborated on the project to develop a scalable, parallel, out-of-core technique to compute seams for gigapixel sized panoramas

### Los Alamos National Laboratory
**Graduate Intern**\
*Summer 2011*

Developed a parallel ray casting based volume renderer using multithreading, GPUs and MPI.

### Lawrence Livermore National Laboratory
**Graduate Intern**\
*Summer 2010*

Collaborated on the project to develop a scalable, parallel, out-of-core solver for gradient domain processing of massive images

## PUBLICATIONS
- **Parallel Gradient Domain Processing of Massive Images.**
  S. Philip, B. Summa, P.-T. Bremer, and V. Pascucci, in Proceedings of the Eurographics Symposium on Parallel Graphics and Visualization 2011, pp. 11-19
- **Hybrid CPU-GPU Solver for Gradient Domain Processing of Massive Images.**
  S. Philip, B. Summa, P.-T Bremer and V. Pascucci, in Proceedings of the International Conference on Parallel and Distributed Systems 2011, pp. 244-251
- **Scalable Seams for Gigapixel Panoramas.**
  S. Philip, B. Summa, J. Tierny, P.-T. Bremer, and V. Pascucci, in Proceedings of Eurographics Symposium on Parallel Graphics and Visualization 2013, pp. 25-32 (Selected as Best Paper)
- **Distributed Seams for Gigapixel Panoramas.**
  S. Philip, B. Summa, J. Tierny, P.-T. Bremer, and V. Pascucci, in IEEE Transactions on Visualization and Computer Graphics, Volume 21, Issue 3, March 2015, pp 350-362
- **Visualization at Exascale: Making It All Work with VTK-m.**
  K. Moreland, et. al. in International Journal of High Performance Computing Applications, 2024 (publication pending)
- **The ViSUS Visualization Framework.**
  V. Pascucci, G. Scorzelli, B. Summa, P.-T. Bremer, A. Gyulassy, C. Christensen, S. Philip and S. Kumar. in High Performance Visualization: Enabling Extreme-Scale Scientific Insight, Chapman and Hall/CRC Computational Science, Ch. 19, Edited by E. Wes Bethel and Hank Childs (LBNL) and Charles Hansen (UofU), Chapman and Hall/CRC, 2012.
- **In Situ Analysis and Visualization of Fusion Simulations: Lessons Learned**
  M. Kim, J. Kress, J. Choi, N. Podhorszki, S. Klasky, M. Wolf, K. Mehta, K. Huck, B. Geveci, S. Phillip, R. Maynard, H. Guo, T. Peterka, K. Moreland, C. Chang, J. Dominski, M. Churchill, and D. Pugmire, in High Performance Computing. Springer International Publishing, 2018, pp. 230-242.
