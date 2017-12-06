# Deploying to k8s 1000s of times a day
- CodeFresh
- GKE

## Importance of high velocity
- reduced risk 
- cost efficiency 
- security 
 
### Core principles

1. High velocity teams(HVT) center on images 
  - Connect the image to every step of SDLC ( tests, jiras, history )
  - Images transfer well and then the reproducibility is awesome 
  - Support Time Travel ( i want the image that was running at 915 last monday. How quickly can you answer that question. <30 seconds )
  - Make sure the image is closely tied to the git commit to find out what code is runnign in the image.

2. HVT shift left 
  - Get image of shift-left pipeline 
  - The idea is that you are reduce the time taken to code review because you have a higher quality code commit because you arent just running unit tests but everything including integration tests etc 
  
3. HVT maintain application portability 
  - Using helm charts 
  - Doing DRs 
  - Dont bake configuration into images 
  - Run same image in test and prod 
  - Configmaps and secrets are the way to define env configs 

4. HVT outsource Cluster Managment 
  - Focus dev team to build apps 
  - Rely on dedicated cluster ops team 
  - Plan for scaling/reliability 
  - Look for conformant offerings of K8s 
  
5. HVT connect all the dots 
  - Similar to codefresh UI to connect the k8s deployment to the image history ( jira, code, unit tests etc )
  - Make sure app is available, status is healthy etc
  - Have record of which helm chart lead to the deployment 

