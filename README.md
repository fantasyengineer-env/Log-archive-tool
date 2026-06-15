# Log-archive-tool

# Day 2 -- RoadMap.sh -- Journey to Devops 

- Purpose: Learn bash scripting, git, various linux tools while applying them to real world applications seen in a engineering environment

## Future Plans for program:
  
  - Use Docker and Nextcloud to create a container based cloud storage server that will hold all archives
      
      - ##  What is my reasoning?
        
          - Nextcloud is opensource, providing freedom from vendor lock-in, security, and the ability to audit code
          
          - Nextcloud server is scablable. As the company increases the number of servers, naturally, an increase in demand for the storage of logs and backups will rise. Instead of investing further in costly hardware to store backups Nextcloud provides seamless plans to increase storage capacity based on these demands. 
          - Nextcloud provides redundancy, It can be upgraded to store system backups as a secondary location in case the primary backup location fails
             
          - Next cloud provides ease of use, Next cloud provides a simple GUI for team members both technical and nontechnical to navigate without the hassel of running any terminal commands
        
          -  Docker grants me the ability to containerize the cloud server infastructure, allowing me to ship it to other team members without worrying that they won't have the proper packages, dependencies, and apis configured on their device to utilize the program.
       

 ## Where is the tool right now?
 
 bash script that acts as a log archive tool. Compress files to be stored for later usage while keeping system clean.
