# Kubernetes the Deltatre way

This is the reference repository for the online community event series **Kubernetes the Deltatre way**, organized by *Deltatre Innovation Lab Academy* in *May and June 2020*.

Here you can find source codes, slides, and any other material the speakers showed and shared during each live event. It will be updated throughout the series.

You can stay in contact with us and be up to date with our initiatives and events by following us on your favourite social networks: [Youtube](https://www.youtube.com/channel/UCVuzquhKvLgLWHE1MGyXXtw?view_as=subscriber) | [Facebook](https://www.facebook.com/pg/Deltatre-Innovation-Lab-108960177483382/) |  [Twitch](https://www.twitch.tv/dila_social) | [Eventbrite](https://www.eventbrite.it/o/deltatre-innovation-lab-28573599825)

## List of episodes

1. *The basics - Introduction to Containers and Orchestrators* (May 18th, 2020)  
    by *Rauno De Pasquale* (Newesis), supported by *Cristiano Degiorgis* (Deltatre)

    Knowing the context and concepts behind container use is essential to be able to proceed on the path that will lead to master Kubernetes and Cloud Native applications. This initial session is about basic skills to answer questions such as: what is a container image? Why did anyone feel the need for an orchestrator? Are there any alternatives to Docker and Kubernetes? How does working with containers and Kubernetes connect to traditional virtualization? The session aims to provide the basic skills to be able to guide yourself in the next sessions where the ways of creating and execution of applications in Kubernetes environment will be tackled.

    Recorded session: [YouTube](https://www.youtube.com/watch?v=42QRgaOemqM) | [Facebook](https://www.facebook.com/108960177483382/videos/541441690093508/)

2. *Docker In Action* (May 25th, 2020)  
    by *Cristiano Degiorgis* (Deltatre), supported by *Matteo Savoré* (Deltatre)

    During this session we are going to walk you through the main containers concepts with a "docker workflow" hands-on. At the end of the session and with the samples shared on the dedicated GitHub repo, you'll be able to try to deploy in production your own application using the containers.

    Demos available in Cristiano's [GitHub repo](https://github.com/crixo/docker-TTG).

    Recorded session: [YouTube](https://www.youtube.com/watch?v=b9Qk2LMXs_Y) | [Facebook](https://www.facebook.com/108960177483382/videos/265351014815975/)

3. *Kubernetes basics* (June 3rd, 2020)  
    by *Enrico Sabbadin* (Deltatre), supported by *Diego D'Agostini* (Deltatre)

    The management of container-based applications requires tools that take care of running the necessary images, ensuring the necessary connectivity at the network network level and ensuring that the system status is always the desired one. This type of instruments are called "orchestrators" and Kubernetes (k8s) is currently the de facto standard. This session covers the basic concepts of k8s: clusters, deployments, services and ingresses. Some demos will show how to interact and manage a cluster via kubectl, helm and the visual Dashboard. Storage and security will be explored in dedicated sessions.

    Demos available in Enrico's [GitHub repo](https://github.com/sabbadino/deltatre-community-meetups-session-3).

    Recorded session: [YouTube](https://youtu.be/zjuy6wLXsFY) | [Facebook](https://www.facebook.com/108960177483382/videos/747008249375581/)

4. *Kubernetes advanced topics & Kind* (June 8th, 2020)  
    by *Carlo Alberto Scaglia* (Deltatre) and *Massimiliano Giovagnoli* (Kloudops)

    After fundamental concepts of orchestration on Kubernetes in previous sessions, in this talk we will analyze in detail how to configure the Pods to adapt them to the needs of our applications and how to configure a cluster to apply the right Security and protection rules. In the first part of the episode we will face the concepts of Authentication, Access Control, Confidentiality and Auditing, discussing for each the best approach to control communication and permissions both from outside and within the cluster. In the second part, instead, we will focus on how to properly segregate and assign resources and volumes to the Pods and what services are made available by the system to monitor and manage the life of applications. We will also see how, inside Kubernetes, it is possible to integrate static ("stateful") applications inside the Pods with a practical demonstration of creating an automated MongoDB replicaset using Kind.

    Advanced topics demos available in Carlo Alberto's [GitHub repo](https://github.com/CarloAlbertoS/KDW-AdvancedK8S).  
    Security topics demos available in Massimiliano Giovagnoli's [GitHub repo](https://github.com/maxgio92/k8s-aaca-security-topics-session).

    Recorded session: [YouTube](https://youtu.be/jhkYvEgNT4A) | [Facebook](https://www.facebook.com/108960177483382/videos/183960489615097/)

5. *Kubernetes CI/CD* (June 15th, 2020)  
    by *Rauno De Pasquale* (Newesis), supported by *Marcello Testi* (Sparkfabrik)

    The path we walked on took us closer to Docker and Kubernetes. In previous meetings we discovered how to create and publish an image containing our application and how this can be execute as a Container within a Pod, we have seen how to expose it through services and ingress controllers, how to manage its security and all the various settings that a Kubernetes cluster provides us to ensure their availability and access to resources such as storage and other services.

    A Kubernetes cluster does not exist per se but is a platform on which to run our software solutions. With this fifth appointment we will therefore try to talk about the possible approaches about the application release and update activities. We will compare the options offered by Kubectl, Kustomize, Helm and #erraform and we will see how to integrate all this in CI/CD tools using Azure DevOps Services in order to view some examples.

    Rauno's [GitHub repo](https://github.com/raunodepasquale/kubernetes-CI-CD-presentation) for slides and demo.  
    Marcello's GitHub [repo Terraform](https://github.com/sparkfabrik/demo-gitlab-ci-cd-terraform) and [repo App](https://github.com/sparkfabrik/demo-gitlab-ci-cd-app).

    Recorded session: [YouTube](https://youtu.be/5uV0UqOHBDE) | [Facebook](https://www.facebook.com/events/559485494954655/)

6. *Kubernetes CRD & Operators* (June 22nd, 2020)  
    by *Cristiano Degiorgis* (Deltatre), supported by *Gianluca Arbezzano* (Packet)

    During this session we'll discuss about the Kubernetes extensibility through the Custom Resource Definitions. We'll tackle this topic from two complementary sides: a challenge demo project born to investigate the CRD usage with a non-conventional scope and a standard CRD usage aimed to create an operator to deploy and monitor the project itself. If you survive to the russian-doll effect, at the end of the session you'll have a fair understanding about the CRD potentiality and the operator pattern.

    Cristiano's [GitHub repo](https://github.com/crixo/k8s-as-backend) for demo and presented content.

## Project Organization

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    |
    ├── ep1                <- Resources from Episode 1 (The basics)
    ├── ep2                <- Resources from Episode 2 (Docker in Action)
    |  └── src*
    ├── ep3                <- Resources from Episode 3 (Kubernetes basics)
    |  └── src*
    ├── ep4                <- Resources from Episode 4 (Kubernetes advanced topics)
    |  ├── src-advanced*
    |  └── src-security*
    ├── ep5                <- Resources from Episode 5 (Kubernetes CI/CD)
    |  ├── src-ci-cd-azure-devops*
    |  ├── src-gitlab-demo-app*
    |  └── src-gitlab-demo-terraform*
    └── ep6                <- Resources from Episode 6 (Kubernetes CRD & Operators)
       └── src*

*It is a submodule, pointing to the original repository managed by the speaker(s) directly.

## Setup a local copy

1. Clone this repository in a local folder
2. Clone and initialize all submodules (recursively)

## License

You may find specific license information for third party projects in each project sub-folder. If not otherwise specified, all the content in this repository is licensed under the [MIT License](./LICENSE).

Copyright (C) 2020 Deltatre and third-party contributors.
