# Pushing a bundle

Optionally, once you have generated your custom rules bundle, you can distribute it automatically to one of our supported OCI registries by using the `push` command:

```
snyk-iac-rules push -r docker.io/example/test bundle.tar.gz
```

{% hint style="info" %}
Make sure to log into your container registry first. For example, using Docker run `docker login` before running the `snyk-iac-rules push` command
{% endhint %}

We use the OCI registries that support the [OCI artifact specification](https://github.com/opencontainers/artifacts) and leverage [ORAS](https://github.com/deislabs/oras) to achieve that. Amongst our currently supported registries we have [DockerHub](https://hub.docker.com), [Azure Container Registry](https://azure.microsoft.com/en-us/services/container-registry/), [Harbor](https://goharbor.io), and more to come.

Once you have run the command, your custom rules bundle will be pushed to your OCI registry using the `latest` tag.&#x20;

You can also provide your own tag if you want to version the bundle:

```
snyk-iac-rules push -r docker.io/example/test:v0.0.1 bundle.tar.gz
```

&#x20;You can now [run snyk iac test with your newly built custom bundle. ](../how-to-run-custom-rules-with-the-snyk-cli.md)
