apiVersion: fleet.cattle.io/v1alpha1
kind: GitRepo
metadata:
  name: dgiebert-fleet
  namespace: fleet-default
spec:
  branch: main
  repo: https://github.com/dgiebert/fleet.git