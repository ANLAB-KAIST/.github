
The Advanced Networking Laboratory engages in high-speed networking research.

Networking platforms have evolved from electronic telephone switches augmented with data communication features to packet switches and routers. Today’s network core routers demand 100Tbps of switching capacity, which no supercomputers of 21st century could achieve. Yet hyper-scale datacenters require not only core routers, but also 40G and 100G networking capacity out of a single server. Myriads of middleboxes are transitioning to virtualized NFs. Due to uneven increases in CPU speed, memory/storage capacity, networking bandwidths, accelerator speedups, and more, datacenter are in constant flux of architectural changes, pushing for hyper-scale and/or disaggregated datacenters.

In ANLab, we are pushing for two research topics at this point: reusable networking stack and networking system support for disaggregated datacenters.

Networking stacks are undergoing dramatic change in order to deliver 10Gbps and 40Gbps out of a single server. Yet, they are reinvented per new high-speed NIC and its SDK. We envision a new abstraction that will keep the core functions intact but let programmers focus on the shim layers for adaptation to new networking technologies. We are building a reusable networking stack in Rust and our goal is to demonstrate competitive performance to existing C/C++ implementations.

Datacenters are morphing from racks of commodity servers to pools of CPUs, GPUs, memory, and storage. We are investigating networking and distributed systems issues in datacenters.

In the past decade or so, we have conducted a wide range of online social media analysis. At the moment, we are conducting a text evaluation project. Qualitative evaluation of Korean writing has a broad spectrum of applications, but there is no well-established formal model. Based on K-12 textbooks, we are building a classifier system that assigns K-12 grades to sentences and paragraphs.

Our research is not limited to only the above. If you have fun and wild ideas, just drop by and let’s chat!
