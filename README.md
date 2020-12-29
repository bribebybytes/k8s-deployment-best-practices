# k8s-deployment-best-practices
This repository contains Kubernetes spec that covers all the important elements one would normally come across while deploying apps in production. It contains a test app deployment with some best practices k8s concepts implementation that one should be aware of while deploying workloads in production.

The spec covers some best practices while doing production deployments addressing key areas such as high availability, security, resiliency. 

1. Externalize app configurations & crednetials using Configmaps, secrets (Env variables, app config files mounted to container filesystem)
2. Replicas (High Availability)
3. Pod Security Context (Security)
4. Pod Anti-Affinity (High Availability)
5. Container ImagePullPolicy (Security)
6. Graceful container shutdown (Resiliency)
7. Container Resource Requests & Limits (Infrastructure usage efficiency)
8. Liveness and Readiness Probes (High Availability & Resiliency)
9. Timezone Env variable (Ease of use)
10. Optional Proxy Settings 
11. Pod Disruption Budget (High Availability)

Feel free to contribute, comment if you feel anything is a miss.

## Usage

```shell
kubectl apply -f k8s-prod-ready-deployment.yml
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

TODO: Write history

## Credits

TODO: Write credits

## License

TODO: Write license
