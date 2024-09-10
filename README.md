# Project Deployment Information

## Overview

This document provides important details regarding the deployment of the backend and frontend services within our Kubernetes cluster. These services are accessible through their respective LoadBalancers, which route traffic to the appropriate pods in the cluster.

## External Access Details

### Backend Service

- **Type**: LoadBalancer
- **External IP**: a0ca54e002a6f4f68888c3fb0aca75d6-228317918.us-east-1.elb.amazonaws.com

The backend service is responsible for handling API requests, database interactions, and other core functionalities of the application. It is crucial to ensure that this service remains highly available and scalable to meet the demands of the application.

You can access the backend service externally using the following URL:

[Backend URL](http://a0ca54e002a6f4f68888c3fb0aca75d6-228317918.us-east-1.elb.amazonaws.com)

### Frontend Service

- **Type**: LoadBalancer
- **External IP**: a581543af9b0848b5ab5f83aca591cb9-2104745556.us-east-1.elb.amazonaws.com

The frontend service hosts the user interface of the application. It serves static files like HTML, CSS, and JavaScript, and interacts with the backend service to display dynamic content to the users.

You can access the frontend service externally using the following URL:

[Frontend URL](http://a581543af9b0848b5ab5f83aca591cb9-2104745556.us-east-1.elb.amazonaws.com)
