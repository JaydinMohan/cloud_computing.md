# cloud_computing.md
What is Cloud Computing? 
What is cloud computing?

In 2013, Cloud computing is a jargon term without a commonly accepted non-ambiguous scientific or technical definition. (Anything that is not on your computer, e.g.: gmail)
In 2016, Proponents claim that cloud computing allows companies to avoid upfront infrastructure costs, and focus on projects that differentiate their businesses instead of on infrastructure. Proponents also claim that cloud computing allows enterprises to get their applications up and running faster, with improved manageability and less maintenance, and enables IT to more rapidly adjust resources to meet fluctuating and unpredictable business demand. Cloud providers typically use a "pay as you go" model. This can lead to unexpectedly high charges if administrators do not adapt to the cloud pricing model. (Everyone has different flavor)
Cloud Characteristics (Lecture notes and then my paraphrasing)

On-demand self-service
A consumer can provision computing capabilities as needed without requiring human interaction with each service provider.
Scale computing resources up and down by needs without requiring human interaction with each service provider.
For anyone in any time - infinite availability (key)
Networked access
Capabilities are available over the network and access through standard mechanisms that promote use by heterogeneous client platforms.
Resources can be access through network and adapted to heterogeneous client platforms.
Resource pooling
The provider's computing resources are pooled to serve multiple consumers using a multi-tenant model potentially with different physical and virtual resources that can be dynamically assigned and reassigned according to consumer demand.
Provider’s resources are pooled and can be dynamically assigned and reassigned by need.
Enough resource to scale up & down
Rapid Elasticity
Capabilities can be elastically provisioned and released, in some cases automatically, to scale rapidly upon demand.
Capabilities can scale easily and rapidly upon demand.
Measured Service
Cloud systems automatically control and optimize resource use by leveraging a metering capability at some level of abstraction appropriate to the type of service.
Resourcing optimization by measuring usage
monitor for load balance (e.g.: nigix)
Flavour

Compute clouds
Amazon Elastic compute cloud
Azure
Data Clouds
Amazon Simple Storage Service
Google docs
iCloud
Dropbox
Application Clouds
App store
Virtual image factories
Public(credit card and pay for using) /Private(Unimelb research cloud)/Hybrid(MRC run out of resource nad buy from Amazon)/Mobile/Health Clouds
complexity arise in: decision about what can we move out/what cost ot stay in/who is allowed this to happen
History - tends in computing

Computing and Communication Technologies (r)evolution
from centralised to decentralised
distributed system history
Once upon a time we had standards
Then we had more standards
mid-90s: focused on computer-computer interaction
internet: peer-to-peer
challenge: sharing data between different organizations
soln: grid computing
Grid: only need access to it no matter it is data or super computer the process to move things
problem: people have different ways to do it
Distributed System
Transparency and heterogeneity in computer-computer interactions
Finding resources -> Binding resources -> run time type checking -> invoking resources
Dealing with heterogeneous of system
Challenges
Complexity of implementations
Vendor specific solutions
Scalability problem
Sharing data between different organizations
Grid Computing
From computer-computer focus to organisation-organisation focus
Can be thought of as a distributed system with non-interactive workloads.
It is in contrast to the traditional notion of a supercomputer, which has many processors connected by a local high-speed computer bus instead of Ethernet.
Grid computing is distinguished from conventional high-performance computing systems such as cluster computing in that grid computers have each node set to perform a different task/application. Grid computers also tend to be more heterogeneous and geographically dispersed (thus not physically coupled) than cluster computers.
Although a single grid can be dedicated to a particular application, commonly a grid is used for a variety of purposes. Grids are often constructed with general-purpose grid middleware software libraries. Grid sizes can be quite large.
Challenge
What resources are available
To determine the status of resources
Job scheduling
Virtual organization support
Security
Public key infrastructure
