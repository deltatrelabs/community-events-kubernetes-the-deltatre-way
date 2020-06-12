# Kubernetes the Deltatre way

This is the reference repository for the online community event series **Kubernetes the Deltatre way**, organized by *Deltatre Innovation Lab Academy* in *May and June 2020*.

Here you can find source codes, slides, and any other material the speakers showed and shared during each live event. It will be updated throughout the series.

You can stay in contact with us and be up to date with our initiatives and events by following us on your favourite social networks:  
[Youtube](https://www.youtube.com/channel/UCVuzquhKvLgLWHE1MGyXXtw?view_as=subscriber) | [Facebook](https://www.facebook.com/pg/Deltatre-Innovation-Lab-108960177483382/) |  [Twitch](https://www.twitch.tv/dila_social) | [Eventbrite](https://www.eventbrite.it/o/deltatre-innovation-lab-28573599825)

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

## Project Organization

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    |
    |── ep1                <- Resources from Episode 1 (The basics)
    |── ep2                <- Resources from Episode 2 (Docker in Action)
    |  └── src*
    |── ep3                <- Resources from Episode 3 (Kubernetes basics)
    |  └── src*
    └── ep4                <- Resources from Episode 4 (Kubernetes advanced topics)
       |── src-advanced*
       └── src-security*

*It is a submodule, pointing to the original repository managed by the speaker(s) directly.

## Setup a local copy

1. Clone this repository in a local folder
2. Clone and initialize all submodules (recursively)

## License

You may find specific license information for third party projects in each project sub-folder. If not otherwise specified, all the content in this repository is licensed under the [MIT License](./LICENSE).

Copyright (C) 2020 Deltatre and third-party contributors.
