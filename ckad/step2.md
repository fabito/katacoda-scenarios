All operations in this question should be performed in the `ggckad-s2` namespace.

Create a ConfigMap called `app-config` that contains the following two entries:

* `connection_string` set to `localhost:4096`
* `external_url` set to `google.com`

Run a pod called `question-two-pod` with a single container running the `kubegoldenguide/alpine-spin:1.0.0` image, and expose these configuration settings as environment variables inside the container.
