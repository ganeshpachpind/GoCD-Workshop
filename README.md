Repository for <a href="">GO CD</a> hands on workshop.

# Installation :  
1. Download and extract GOCD Server and Agent zip.  
2. To start server run ./server.sh from server directory.   
3. copy agent directory multiple times rename as go-agent-1, go-agent-2 , go-agent-3 etc.  
4. Start each agent by running ./agent.sh from each agent directory.  

# Demo Sequence

1. Single_pipeline.xml  
    - Example of Material ,Job and task concepts  
2. Sequential_multi_pipeline.xml
    - Setting up multiple Pipeline  
    - Running python script  which produce a artifact
    - How to publish artifacts  
3. Sequential_Fetch_Artifact_multistage.xml
    - Fetch published artifacts from previous pipeline  
    - Use Environment variable  
    - MultiStage multitask example  
4. Fan_out.xml  
    - Example of Fan_out concept
5. Fan_in.xml  
    - Example of fan_in concept


# Todo :
- Add example for
  - How to add secure Environment variable
  - How to add custom tab to show test report
  - How to scheduled cron build



************************************************************************************************
