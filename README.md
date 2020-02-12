# Neural Network Collaboration
## About
An open source neural network versioning system designed to separate model management functions and computationally expensive training operations.

## Features

- Fetch, update, and publish models from anywhere
- Track metrics
- Manage model history on the web
- Add team members, make contributions

### Example commands
```
>>> localModel = nnc.download(modelName)
```
```
>>> nnc.showHistory(project)
```
```
>>> nnc.update(modelname, localModel)
```
## Comparison with other platforms
![Traditional Cloud Worlflow](/TraditionalCloudWorkflow.png?raw=true)
![Local Training Workflow](/LocalTrainingWorkflow.png?raw=true)
