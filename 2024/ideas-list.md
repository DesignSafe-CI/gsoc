# Ideas Pages

This is the home page of projects ideas of NHERI for Google Summer of Code 2024.
Since NHERI is an umbrella organization you will only find links to the ideas
page of each organization under the NHERI umbrella at this page.

## Organizations Confirmed Under NHERI Umbrella

* [DesignSafe-CI](https://designsafe-ci.org)
* [Geoelements](https://geoelements.org)
* [NHERI SimCenter](https://simcenter.designsafe-ci.org/)
* [TACC TAPIS](https://tacc.utexas.edu/research/tacc-research/tapis/)

<table>
  <tr>
     <td>
       <img width="800px" src="https://github.com/geoelements/geoelements.github.io/blob/main/images/geoelements/logo.png?raw=true"/>
     </td>
     <td>
        <h1>Geoelements GNS</h1>
        <p>
          <a href="https://github.com/geoelements/gns">Graph Network-based Simulator (GNS)</a> is a generalizable, efficient, and accurate machine learning (ML)-based surrogate simulator for particulate and fluid systems using Graph Neural Networks (GNNs).
        </p>
        <p>
          <a href="https://www.geoelements.org/gns">Website</a> | <a href ="https://github.com/geoelements/gns/discussions/66">Ideas Page</a> | <a href="https://github.com/geoelements/gns/discussions"> Discussions</a> | <a href="https://github.com/geoelements/gns">Source Code</a>
        </p>
     </td>
   </tr>

  <tr>
     <td>
       <img width="800px" src="https://tapis-project.org/static/tapis-project-org/img/org_logos/tapis-logo-navbar.png"/>
     </td>
     <td>
        <h1>Tapis API</h1>
        <p>
          The Tapis Framework provides a hosted, unified web-based API for securely managing computational workloads across institutions so that experts can focus on their research instead of the technology needed to accomplish it..
        </p>
        <p>
          <a href="https://tapis-project.org/"> Website </a> | <a href ="https://github.com/tapis-project/admin/issues/6">Ideas Page</a>   |  <a href="https://github.com/tapis-project/"> Source Code </a>
        </p>
     </td>
   </tr>
</table>

---

## Ideas

## Geoelements GNS
## Evaluating physical properties from videos using NeRF and differentiable GNS

### Abstract
This project proposes an innovative approach to evaluate the physical properties of dynamic events, such as fluid dynamics and granular flow, from video data using Neural Radiance Fields (NeRF) using Nvidia Instant NGP and a Differentiable Graph Network Simulator (GNS). By converting video footage into high-fidelity 3D models with NeRF and simulating physical interactions with Differentiable GNS, this framework aims to predict and analyze the complex behaviors of natural phenomena with unprecedented accuracy. The project aligns with cutting-edge research in computational physics and machine learning, aiming to integrate with existing systems to offer a powerful tool for the simulation and understanding of granular and fluid flows and material properties.

| **Intensity** | **Priority** | **Involves** | **Mentors** |
| ------------- | ------------ | ------------- | ----------- |
| Moderate (350 hours - duration) | High | Integrating NeRF with Differentiable GNS for advanced simulations of physical phenomena. Developing and validating models for granular and fluid flows and material property evaluation with high fidelity. | [Krishna Kumar](https://github.com/kks32), [Pedro Arduino](https://github.com/parduino) and [Yongjin Choi](https://github.com/yjchoi1) |

### Project duration

The project duration is 350 hours. 

### Benefits of working on this Project
Participants will significantly broaden their expertise in:
- Advanced machine learning models and their application in physics simulations.
- Handling and processing video data for 3D model generation.
- Simulation of physical properties and behaviors using graph-based neural networks.
- Interdisciplinary skills bridging computational physics, computer vision, and machine learning.

### Motivation
Traditional methods for analyzing physical properties from video data often involve labor-intensive processes with limited accuracy and scalability. Integrating NeRF and Differentiable GNS presents a transformative solution, leveraging the power of neural radiance fields for detailed 3D reconstructions and graph network simulators for simulating physical interactions based on these reconstructions. This methodology opens new avenues for the real-time analysis of complex phenomena, enhancing the predictive capabilities and understanding of material behaviors in natural and engineered systems.

### Technical Details
- **Neural Radiance Fields (NeRF):** A deep learning technique for creating detailed 3D representations of scenes from a collection of 2D images, offering a powerful tool for accurate volume rendering and scene reconstruction.
- **Differentiable Graph Network Simulator (GNS):** A framework for simulating the dynamics of complex systems through differentiable physics, enabling the prediction of physical properties and behaviors in a computationally efficient manner.
- The project aims to seamlessly integrate NeRF-generated 3D models with Differentiable GNS to simulate and analyze physical phenomena directly from video data, bridging the gap between observation and simulation.

### Benefits to Project/Community
By advancing the capabilities for evaluating physical properties from videos, this project offers significant contributions to:
- The development of more accurate and dynamic models for understanding natural phenomena and material properties.
- The enhancement of digital twin technologies for real-world applications, from design to optimizing engineering processes.
- The research community provides a novel methodology for data-driven simulations and analysis.

### Helpful Experience
Ideal candidates should have:
- Proficiency in Python and familiarity with deep learning frameworks such as TensorFlow or PyTorch.
- Experience with computer vision techniques and 3D reconstruction.
- An interest or background in computational physics and simulations.

### First Steps
Interested participants are encouraged to:
- Explore the foundational concepts behind NeRF and its applications in 3D scene reconstruction. Read foundation [paper](https://arxiv.org/abs/2303.05512)
- Familiarize themselves with the Graph Network Simulator framework and its potential for simulating physical phenomena.
- Investigate existing datasets and tools for NeRF and GNS simulations to understand the workflow and integration process between 3D reconstruction and physical simulation.

---

## TACC TAPIS: Automated Reasoning Interfaces For Tapis Security Policies


### Mentors

* [Joe Stubbs](https://github.com/joestubbs/)
* [Smruti Padhy](https://github.com/smpadhy)


### Abstract

As the number of users of a cloud system grows, reasoning about the set of access control policies governing their resources becomes increasingly difficult. Tools from Formal Methods, such as Satisfiability Modulo Theories (SMT) [1], provide techniques for automatically reasoning about entire collections of policies, but using these tools requires expertise. This project will build upon the CloudSec library and the Tapis API framework to develop an HTTP RESTful API and graphical interface for analyzing entire sets of Tapis security policies by nonexperts.

| **Intensity** | **Priority** | **Involves** | **Mentors** |
| ------------- | ------------ | ------------- | ----------- |
| Easy to Moderate (175 hours - duration) | High | Developing new REST API and GUI interface to tools for analyzing Tapis security policies. | [Joe Stubbs](https://github.com/joestubbs/) and [Smruti Padhy](https://github.com/smpadhy) |

### Project Duration

This is a 175 hour project.

### Technical Details

The Tapis project provides web-based APIs enabling researchers to automate data management and computational tasks on cloud, high-throughput and HPC resources. Tapis uses a fine-grained permissions model that allows users to manage who can access their datasets and research codes. Often times, large projects (such as DesignSafe) will create a mixture of community resources (e.g., public datasets, public applications, etc.) as well as resources private to individual investigators or research labs. As users join and leave the community, Tapis permissions must evolve. Over time, large projects accumulate tens of thousands of permissions in Tapis. How can we be sure that the permissions are correct? In general, we would like to be able to check that these permissions conform to certain rules. For example, we might like to know that all users have modify access to their home directories on all HPC systems, and they have read-only access to published datasets, while only certain administrative users can add new files to the published data collection. With SMT, we can programmatically prove or disprove such statements, but using these libraries requires background and expertise in formal methods.

We have developed a Python library, CloudSec ([2, 3]), that provides an extensible, high-level Python interface for building policy specifications and formally reasoning about policy sets without any knowledge of SMT. CloudSec’s backend uses different SMT solvers, such as Z3 or CVC5, to prove statements about policies or find counterexamples. CloudSec also integrates third-party sources of policy information, such as Tapis security policies, through its Connectors abstraction.

This project will build upon the CloudSec library to develop a RESTful HTTP API for reasoning about Tapis policies. The HTTP API must be able to serialize and deserialize inputs to and results from the CloudSec core package, including the p_imp_q() function and the ImplResult class. It must also deal with other technical issues, such as options for running multiple solvers in parallel (already provided by the CloudSec library) and handling timeouts. The project will provide an OpenAPI specification for the HTTP API so that clients in various languages (e.g., Python, TypeScript) can be generated automatically. We will work with standard Python tools for API development, including FastAPI, jsonschema, and Uvicorn, Docker for containerization, and Python libraries for interacting with Tapis (e.g., the Tapipy library).

Finally, this project will develop a graphical interface to allow users to check Tapis policies against specifications they define in a web browser. The front-end will be embedded in the Tapis UI project [4] using the Tapis TypeScript library [5]. This part will involve updating the sidebar for the new panel, adding a service-level routers and layout, creating models for each endpoint to be exposed, and adding links to the service from the existing UI. Providing a graphical interface to the tool and API will allow it to be used by a wider audience.

### Helpful Experience

* Working knowledge of Python and TypeScript
* Familiarity with cloud and HTTP/RESTful APIs and technologies
* Familiarity with cloud security policies, including role-based access controls (RBAC)

### First steps

* Read about the Tapis project [6]
* Read our paper on CloudSec [3]
* Become familiar with API development in Python, for example, using FastAPI
* Become familiar with OpenAPI specifications [7]

### Benefits of working on this project

Students working on this project will develop skills in the following areas:

* Modern, state-of-the-art SMT solvers, including Z3 and CVC5.
* Web service development in Python and associated technologies, e.g., RESTful design, OpenAPI definitions, language SDK generation, etc.
* Front-end development in TypeScript, React and related technologies

#### References

[1] A. R. Bradley and Z. Manna. The Calculus of Computation: Decision Procedures with Applications to Verification. Springer, 2017.

[2] CloudSec GitHub Repository. https://github.com/applyfmsec/cloudsec

[3] CloudSec: An Extensible Automated Reasoning Framework for Cloud Security Policies. https://arxiv.org/pdf/2307.05745.pdf

[4] Tapis UI GitHub Repository. https://github.com/tapis-project/tapis-ui/

[5] Tapis TypeScript GitHub Repository. https://github.com/tapis-project/tapis-typescript

[6] Tapis Documentation. https://tapis.readthedocs.io/en/latest/

[7] OpenAPI Specification. https://swagger.io/specification/
