## Rchain-CD/CD

The objective of this challenge is to build a CI/CD pipeline to support Rchain development, dockerize Rchain, and test the dockr image by deploying a 100 node testnet. 

## Objective
As a team you will work together on 1 github repo to build CI/CD pipeline for Rchain. Repo should contain a README with set up instructions and the code should be commented.  This is due 1 week from now.

1. Set up a Gitlab CI pipeline that checks for the following
   * Check Rusts syntax / compliation [[1]](https://medium.com/astraol/optimizing-ci-cd-pipeline-for-rust-projects-gitlab-docker-98df64ae3bc4)
   * Builds a new docker image [[1]](https://medium.com/@gustavo.guss/jenkins-building-docker-image-and-sending-to-registry-64b84ea45ee9)
2. Configure ArgoCD to deploy the docker image to an EKS cluster. [[1]](https://levelup.gitconnected.com/gitops-in-kubernetes-with-gitlab-ci-and-argocd-9e20b5d3b55b)
3. After ArgoCD deploys the container, scale up the EKS cluster to replicate a 100 node testnet. 
4. Screenshot the cluster running the testnet & terminal output of the testnet running [[1]](https://www.jeffgeerling.com/blog/2020/10000-kubernetes-pods-10000-subscribers)
5. Build a presentation that covers CI/CD pipeline for a large EKS cluster.
   * 1 slide - Introduction / Problem set up
   * 1 slide - Pros/Cons of Jenkins 
   * 1 slide - Pros/COns of ArgoCD 
   * 1 slide - Systems digram w/ proper AWS VPCs, avalability zones, etc.
   * 1 slide - Demo (screenshots, gif, video)
   * 1 slide - Challenges of setting up 100 node testnet
   * 1 slide - Contributions

