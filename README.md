I'm trying to understand how to use SSE with Symfony and mercure.

# What is done at this moment:
* Publish

# Things I've found:
* I have to edit config\packages\framework.yaml to and the next:
```
framework:
    http_client:
        default_options:
            verify_peer: false
```
