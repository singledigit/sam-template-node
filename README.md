# SAM-Template-Node

This is a simple starting point for SAM serverless applications for NodeJS 8.10

```bash
.
├── README.MD                   <-- This instructions file
├── service .                   <-- Source code for a lambda function
│   └── app.js                  <-- Lambda function code
│   └── package.json            <-- NodeJS dependencies and scripts
│   └── tests                   <-- Unit tests
│       └── unit
│           └── test-handler.js
├── template.yaml               <-- SAM template
```

## Included Layers
- AWS-SDK
- AWS-XRAY-SDK