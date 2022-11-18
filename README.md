# Sentiment Analysis

## Canvas Answers

- What are 3 advantages of deploying using Model Serving methods Vs. deploying on GitHub Pages or HuggingFace for free?
    - When you serve a model, you control it. If it's hosted on GitHub Pages or HuggingFace, it could be taken down for any reason by those sites.
    - Similarly, when you deploy on HuggingFace or GitHub Pages, you don't really know when or if those sites will be down or have issues, so you might not have access at business-critical times.
    - Serving on your own environment also gives you greater overall control over the application. Projects like GitHub Pages simplify things for maintenance, but come at a cost of giving you less granular control which could hurt scaling.
- What is ML model deployment?
    - ML model deployment is taking an ML model, and putting it into a production environment of some sort, so that it will run as part of an application in a live environment.
- What is Causal Inference and How Does It Work?
    - Causal Inference is about determining what a piece of a system actually does. This is done by seeing what one piece of a system causes to happen, and then tracing those cause and effect results through a system to see the final result, and understand the chain of events that led to that conclusion.
- What is serverless deployment and how its compared with deployment on server?
    - Serverless deployment is deploying to a cloud environment, where the actual server is totally maintained and controled by the cloud company, so you just have to write and deploy code.
    - Deployment on a traditional server (even in the cloud) would require you do maintain the server itself, including things like choosing how/when to scale.