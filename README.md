# Kubernetes (K8s)

What is kuberenetes?

Kubernetes, or k8s (k, 8 characters, s...get it?), or “kube” if you’re into brevity, is an open source platform that automates Linux container operations. It eliminates many of the manual processes involved in deploying and scaling containerized applications. In other words, you can cluster together groups of hosts running Linux containers, and Kubernetes helps you easily and efficiently manage those clusters. These clusters can span hosts across public, private, or hybrid clouds. For this reason, Kubernetes is an ideal platform for hosting cloud-native applications that require rapid scaling, like real-time data streaming through Apache Kafka.

Kubernetes was originally developed and designed by engineers at Google. Google was one of the early contributors to Linux container technology and has talked publicly about how everything at Google runs in containers. (This is the technology behind Google’s cloud services.) Google generates more than 2 billion container deployments a week—all powered by an internal platform: Borg. Borg was the predecessor to Kubernetes and the lessons learned from developing Borg over the years became the primary influence behind much of the Kubernetes technolog

Red Hat was one of the first companies to work with Google on Kubernetes, even prior to launch, and has become the 2nd leading contributor to Kubernetes upstream project. Google donated the Kubernetes project to the newly formed Cloud Native Computing Foundation in 2015.

# What can you do with Kubernetes?

The primary advantage of using Kubernetes in your environment, especially if you are optimizing app dev for the cloud, is that it gives you the platform to schedule and run containers on clusters of physical or virtual machines. More broadly, it helps you fully implement and rely on a container-based infrastructure in production environments. And because Kubernetes is all about automation of operational tasks, you can do many of the same things that other application platforms or management systems let you do, but for your containers.

With Kubernetes you can:
*    Orchestrate containers across multiple hosts.
*   Make better use of hardware to maximize resources needed to run your enterprise apps.
*    Control and automate application deployments and updates.
*    Mount and add storage to run stateful apps.
*    Scale containerized applications and their resources on the fly.
*    Declaratively manage services, which guarantees the deployed applications are always running how you deployed them.
*    Health-check and self-heal your apps with autoplacement, autorestart, autoreplication, and autoscaling.

Kubernetes, however, relies on other projects to fully provide these orchestrated services. With the addition of other open source projects, you can fully realize the power of Kubernetes. These necessary pieces include (among others):

*    Registry, through projects like Atomic Registry or Docker Registry.
*    Networking, through projects like OpenvSwitch and intelligent edge routing.
*    Telemetry, through projects such as heapster, kibana, hawkular, and elastic.
*    Security, through projects like LDAP, SELinux, RBAC, and OAUTH with multi-tenancy layers.
*    Automation, with the addition of Ansible playbooks for installation and cluster life-cycle management.
*    Services, through a rich catalog of precreated content of popular app patterns.


https://blog.risingstack.com/the-history-of-kubernetes/
https://www.redhat.com/en/topics/containers/what-is-kubernetes
