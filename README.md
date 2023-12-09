# kubeplugin - pods and nodes CPU and memory usage information 

This script, `kubeplugin`, is designed to get CPU and memory usage information from Kubernetes cluster. 

## Prerequisites
- **Kubernetes Cluster:** Ensure you have a Kubernetes cluster configured and accessible.
- **kubectl:** Make sure `kubectl` is installed and configured to communicate with your Kubernetes cluster.

## Installation
1. Clone or download this repository to your local machine.
2. Ensure executable permissions for the `kubeplugin` script:
   ```chmod +x kubeplugin
   ```

## Usage
```
./kubeplugin pods demo
```
where: pods - resource (can be 'pods' on 'node')
       demo - namespace 
