# ToDo:

> 27-01-22:
  - Have To Try New Clip Models. (Try it out first time on 28/01)
  - Also tell Ajay, to decide for a no of prompts, so we can make our quality banchmarking more effective.
> 15-02-22:

  - Waiting for EC2 g4dn limit approval.
  - try out the different approaches in COLAB, using same repo structure, so can be coordinated.
  - Also have ot study different Deployment Approaches, as **AIM IS TO COME UP WITH OPTIMAL SOLUTION.** 
  - Also go through the AutoScaling, Route53, API Gateway integration etc.
  - Resulting Images should be saved, and best would be if github can be maintained with them.
  - 
> 23-03022:

  - Try to make LOCAL mode work in BYOC, as will expedite the process.
  - Also ASYNC API working, and also CONCURRENT-REQUESTS-PER-INSTANCE working, but not responding to queued invocation..... ***
  - 



# AWS Updates:

> Finally endpoint deployed using BYOC extending cuda image, as failed with pytorch container. Tried sklearn container, but that cannot be used with cuda.
> 
> Till now fould that with g4dn.xlarge we get almost same latency as p3.2xlarge, but cost is relatively very low. With p2.xlarge, latency is almost 3 times more.
> 
> With real time endpoint, we have this limitation that max wait time is 60 secs, the process continues in background, but the cell errors out. So we have to use async API.
> 
> till now, not able to use "LOCAL" mode with custom container, but try to make it work, as will expedite the process by considerable margin.
> 
> **Discuss the no of cores functionality with AJAY, as for now restricte to use 1 core, as otherwise result in time cost. MAybe we can use them to handle concurrent requests.**
> 
> Tell AJAY, GCP account approved, so have to try it or not. As MAHYAR, showed they provide more flexibilty over machine settings, i.e no of cores, RAM etc.
> 





