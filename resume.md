# SUJIN PHILIP

**LinkedIn:** [linkedin.com/in/sujinphilip](http://www.linkedin.com/in/sujinphilip)\
**Webpage:** [https://philip-sujin.github.io/webpage](https://philip-sujin.github.io/webpage)

## PROFILE
- MS. Computer Science with specialization in Graphics and Visualization
- Skilled in modern C++ programming
- 13+ years experience in the industry, mainly specialized in HPC, computer graphics and visualization

## ACADEMIC QUALIFICATION
- MS. Computing – Graphics and Visualization, University of Utah, GPA 3.9, 2014
- BE. Computer, University of Pune, First Class, 2006

## TECHNICAL SKILLS
**Proficient:** C++, C, Python, Cuda, MPI, Multithreading, CMake\
**Competent:** OpenGL, TBB, Thrust, Shell Scripting

## WORK EXPERIENCE

### Amazon
**Software Development Engineer**\
*Sep 2024 - Present*

- Research and development of DFM (Design For Manufacturing) checks for Amazon’s internal manufacturing operations. Primarily focused on SLS 3D printing
- Lead developer of software packages that implement algorithms for performing DFM checks and other processing on 3D parts models
  - The algorithms are implemented in C++ (standard version 2017) for high performance
  - Cloud development kit (CDK) is used to package the algorithms inside docker containers and deploy them as Lambda functions, and for CI/CD

### Kitware Inc.
**Staff R&D Engineer**\
*Nov 2014 – Aug 2024*

Member of the Scientific Computing Team. Contributed to leading open-source visualization software: VTK, VTK-m, and ParaView.
- VTK-m (DOE Exascale Computing Project)
  - Developed VTK-m filters such as Clip and ExternalFaces.
  - Implemented VTK file readers in VTK-m.
  - Implemented virtual function simulation in CUDA for abstract array types.
  - Enabled VTK-m object serialization to support the DIY parallelization library (MPI-based).
  - Developed the Kokkos-based device backend for VTK-m, deployed on Frontier (AMD GPUs) and Aurora (Intel GPUs).
  - Improved CUDA (Thrust-based) and OpenMP backends by optimizing performance and fixing core issues.
- VTK-m Integration with VTK and ParaView
  - Led the integration of VTK-m with VTK and ParaView for accelerated data processing.
  - Implemented VTK-m powered filters within VTK and optimized data transfers between CPU and GPU.
  - Developed factory overrides for seamless switching to VTK-m filters when available.
  - Optimized field range computation directly on the GPU, minimizing CPU-GPU data transfers.
- IARPA Haystac Project
  - Developed a parallel city traffic simulator using SUMO, MPI, and Python.
  - Created an Airflow DAG-based workflow for simulation deployment on AWS (EC2, Kubernetes, S3, Docker).
- Other Notable Contributions
  - Developed parallel filters for resampling multi-partition datasets into structured datasets for faster volume rendering in ParaView.
  - Built a proof-of-concept for CUDA-OpenGL interoperability, enabling direct GPU-GPU data transfers.
  - Contributed to CMake and commercial projects.

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
  K. Moreland, et. al. in International Journal of High Performance Computing Applications, Volume 38, Issue 5, September 2024, pp 508-526
- **Gradient-based Trajectory Optimization with Parallelized Differentiable Traffic Simulation.**
  S. Son, L. Zheng, B. Clipp, C. Greenwell, S. Philip, M C Lin. 2025
- **The ViSUS Visualization Framework.**
  V. Pascucci, G. Scorzelli, B. Summa, P.-T. Bremer, A. Gyulassy, C. Christensen, S. Philip and S. Kumar. in High Performance Visualization: Enabling Extreme-Scale Scientific Insight, Chapman and Hall/CRC Computational Science, Ch. 19, Edited by E. Wes Bethel and Hank Childs (LBNL) and Charles Hansen (UofU), Chapman and Hall/CRC, 2012.
- **In Situ Analysis and Visualization of Fusion Simulations: Lessons Learned**
  M. Kim, J. Kress, J. Choi, N. Podhorszki, S. Klasky, M. Wolf, K. Mehta, K. Huck, B. Geveci, S. Phillip, R. Maynard, H. Guo, T. Peterka, K. Moreland, C. Chang, J. Dominski, M. Churchill, and D. Pugmire, in High Performance Computing. Springer International Publishing, 2018, pp. 230-242.
