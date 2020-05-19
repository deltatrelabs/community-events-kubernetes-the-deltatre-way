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

    During this session we are going to walk you through the main containers concepts with a "docker workflow" hands-on. At the end of the session and with the samples shared on the dedicated [GitHub repo](https://github.com/crixo/docker-TTG), you'll be able to try to deploy in production your own application using the containers.

## Project Organization

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    |
    |── ep1                <- Resources from Episode 1 (The basics)
    └── ep2                <- Resources from Episode 2 (Docker in Action)
       └── src*

*It is a submodule, pointing to the original repository managed by the speaker(s) directly.

## Setup a local copy

If not already configured, you need to install/enable [Git LFS support](https://git-lfs.github.com/) on your machine.

1. Clone this repository in a local folder
2. Clone and initialize all submodules (recursively)

## License

You may find specific license information for third party projects in each project sub-folder. If not otherwise specified, all the content in this repository is licensed under the [MIT License](./LICENSE).

Copyright (C) 2020 Deltatre and third-party contributors.
