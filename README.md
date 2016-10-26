# Installation :  
1. Download and extract GOCD Server and Agent zip.  
2. To start server run ./server.sh from server directory.   
3. copy agent directory multiple time rename as go-agent-1, go-agent-2 , go-agent-3.  
4. Start each agent by running ./agent.sh from each agent directory.  

# Demo Sequence

1. Single_pipeline.xml  
    -- Material , Job and task concepts  
2. Sequential_multi_pipeline.xml
    -- Setting up multiple Pipeline  
    -- running python script  
    -- How to publish artifacts  
3. Sequential_Fetch_Artifact_multistage.xml
    -- Fetch published artifacts from previous pipeline  
    -- Use Environment variable  
    -- MultiStage multitask example  
4. Fan_out.xml  
5. Fan_in.xml  




************************************************************************************************
