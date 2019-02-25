
Before we begin lets create some aliases:

`alias k=kubectl `{{execute}}
`alias kg=k get `{{execute}}
`alias krm=k delete `{{execute}}
`alias kd=k decribe `{{execute}}
`alias ka=k apply -f `{{execute}}
`alias ke=k edit `{{execute}}

Change the default editor

By default vim is the default editor. If you rather use nano you should run:

`export KUBE_EDITOR=nano`{{execute}}
