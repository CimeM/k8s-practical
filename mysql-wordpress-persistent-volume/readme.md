
# Wordpress and mysql on kubernetes with persistent volume

These manifest files describe a wordpress service. Please make sure to change the passwords saved in the configuration files.

## Usage:

1. Start: `kubectl start -k ./`
2. Get url: `kubectl get services wordpress`
3. Cleanup: `kubectl delete -k ./` 


## Resources: 
- https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/
