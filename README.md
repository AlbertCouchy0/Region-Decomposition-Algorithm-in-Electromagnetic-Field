# Region Decomposition Algorithm in Electromagnetic Field

### Project Description

**Project Background**:
Cylindrical electromagnetic scattering problems hold significant application value in fields such as radar, communication, and optical imaging. Traditional methods like Geometrical Optics and Physical Optics are computationally efficient but often result in large errors when dealing with complex scattering scenarios. In recent years, with the advancement of numerical simulation techniques, methods such as the Finite Element Method (FEM) and Method of Moments (MoM) have been widely applied. However, these methods face challenges of significantly increased computational time and memory demand when solving large-scale problems. The Domain Decomposition Method (DDM) has emerged as an optimized approach, reducing computational complexity and memory requirements by dividing the solution domain into multiple subdomains, thereby demonstrating clear advantages.

**Project Objectives**:
This project aims to investigate the application of conformal mesh and Mur absorbing boundary conditions in the domain decomposition algorithm to improve the computational accuracy and efficiency for two-dimensional cylindrical scattering problems. The specific objectives include:
1. Implementing conformal mesh division to match the object boundaries closely and enhance computational accuracy.
2. Applying Mur absorbing boundary conditions at the truncated boundaries to minimize reflective interference.
3. Validating the effectiveness and accuracy of the algorithm through numerical examples.
4. Analyzing the impact of mesh layers, mesh step size, and corner point division on computational accuracy.

**Research Content**:
1. **Conformal Mesh Division**: Increasing mesh points at critical geometric locations to accurately describe the cylindrical surface and reduce discretization errors.
2. **Mur Absorbing Boundary Conditions**: Implementing Mur conditions at truncated boundaries to simulate an infinite domain and reduce reflective interference.
3. **Implementation of Domain Decomposition Algorithm**: Dividing the computational domain into multiple subdomains, solving each subdomain separately, and then iteratively obtaining the overall solution.
4. **Numerical Example Analysis**: Using the surface current calculation of an infinitely long perfect conductor square cylinder as an example to validate the algorithm's effectiveness and analyze the impact of different parameters on computational accuracy.

**Research Outcomes**:
1. Proposing an efficient domain decomposition algorithm suitable for two-dimensional cylindrical scattering problems.
2. Validating the algorithm's accuracy and effectiveness through numerical examples.
3. Providing optimization recommendations for mesh layers, mesh step size, and corner point division.
4. Laying the theoretical foundation and technical support for future research on three-dimensional problems.

**Project Significance**:
The research outcomes of this project will provide an efficient and accurate method for the numerical solution of electromagnetic scattering problems, especially when dealing with complex geometries and large-scale problems. Additionally, this method can offer technical support for engineering applications in related fields, such as radar target identification and communication system optimization.
