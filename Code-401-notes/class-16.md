# Class 16 - Serverless Functions

## Reading

### What is Serverless Computing?

[What is Serverless Computing?](https://www.ibm.com/topics/serverless)
- Serverless is a cloud computing application development and execution model that enables developers to build and run application code without provisioning or managing servers or backend infrastructure.
- allows devs to write their application code and deploy it to containers managed by a cloud service provider
- developers never pay for idle capacity
- serverless platforms from leading cloud service providers include Amazon Web Services (AWS Lambda), Microsoft Azure (Azure Functions), Google Cloud (Google Cloud Functions) and IBM Cloud (IBM Cloud Code Engine)
- Function-as-a-service, or FaaS, is a cloud computing service that enables developers to run code or containers in response to specific events or requests
- FaaS is the compute model central to serverless, and the two terms are often used interchangeably
- Scaling: Auto-scaling—including auto-scaling to zero—is instant and inherent for serverless. The other models offer automatic but slow scaling that requires careful tuning of auto-scaling rules, and no scaling to zero.
- Serverless applications are often deployed in containers
- Kubernetes is an open-source container orchestration platform that automates the deployment, management and scaling of containers

## Additional Resources

[venv - Creation of Virtual Environments](https://docs.python.org/3/library/venv.html)

[Vercel - Get Started](https://vercel.com/docs/concepts/get-started/deploy)

[http.server](https://pymotw.com/3/http.server/index.html)

[Requests](https://requests.readthedocs.io/en/latest/)

[Python & APIs](https://realpython.com/python-api/)

## Videos - What is Serverless?
[Source Credit](https://www.youtube.com/watch?v=vxJobGtqKVM)
- containers is packaging code and all dependencies into a container (like Docker)
- Advantages of Serverless
    - Pay for Execution
    - Auto Scalable
    - Faster Time to Market
    - Polyglot Environment (not limited to specific supported languages)
    - Highly Available (clould provider take care of fault tolerance and such things)

## Bookmark and review

[Serverless Functions](https://vercel.com/docs/concepts/functions/serverless-functions)

[Effective Python Environment](https://realpython.com/effective-python-environment/)

## Things I want to know more about

- Are there things we would want or need control of that would be automatically managed by a serverless environment?
- Can we deploy containers to serverless or do we deploy the code directly? 