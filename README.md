# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

### Setup Node Environment

You'll need to create a new node server. Open a new terminal within the project directory and run:

1. Initialize a new project: `npm i`
2. run the development server with `npm run dev`

### Create a new endpoint in the server.ts file

```typescript
import {filterImageFromURL, deleteLocalFiles} from './util/util';
```

### Deploying your system
To Deploy the application, use eb cli commands to push and publish the application on the cloud.
In windows, install Python and PIP and ensure python is added to the environment variables.
Use ```eb init``` to initialize the application
It will give you the procedures to follow along.
to crest the application environment, ```eb create```
and use ```eb deploy``` to deploy the  application

## Application endpoints
To filter the public image, use this url to filter the images
<a>http://udagram-dev2.us-east-1.elasticbeanstalk.com/filteredimage?image_url={imageurl}</a>

## Environment snapshots
To see the deployment environment, check che snapshots folder to assess the application dashboard

## Clone/Fork
To clone or fork the repo, it can be done through this link with apprpriate git bash commands
