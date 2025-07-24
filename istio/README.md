Deploy the following resources in the istio-system namespace:

- istio.yaml

Deploy the following resources in the istio-cni namespace

- istio-cni.yaml

For none Ambient mode:
$ oc label ns {app-name} istio-discovery=enabled

$ oc label ns istio-system istio-discovery=enabled
$ oc label ns {gw-name} istio-discovery=enabled


