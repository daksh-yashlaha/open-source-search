Kubernetes
 


Kubernetes is an open source system for managing containerized applications
across multiple hosts. It provides basic mechanisms for deployment, maintenance,
and scaling of applications.
Kubernetes builds upon a decade and a half of experience at Google running
production workloads at scale using a system called Borg,
combined with best-of-breed ideas and practices from the community.
Kubernetes is hosted by the Cloud Native Computing Foundation (CNCF).
If your company wants to help shape the evolution of
technologies that are container-packaged, dynamically scheduled,
and microservices-oriented, consider joining the CNCF.
For details about who's involved and how Kubernetes plays a role,
read the CNCF announcement.

To start using Kubernetes
See our documentation on kubernetes.io.
Try our interactive tutorial.
Take a free course on Scalable Microservices with Kubernetes.
To start developing Kubernetes
The community repository hosts all information about
building Kubernetes from source, how to contribute code
and documentation, who to contact about what, etc.
If you want to build Kubernetes right away there are two options:
You have a working Go environment.
mkdir -p $GOPATH/src/k8s.io
cd $GOPATH/src/k8s.io
git clone https://github.com/kubernetes/kubernetes
cd kubernetes
make

You have a working Docker environment.
git clone https://github.com/kubernetes/kubernetes
cd kubernetes
make quick-release

For the full story, head over to the developer's documentation.
Support
If you need support, start with the troubleshooting guide,
and work your way through the process that we've outlined.
That said, if you have questions, reach out to us
one way or another.

