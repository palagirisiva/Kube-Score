# Kube-Score
kube-score is a tool that does "Static Code Analysis" of your Kubernetes object definitions.
The output is a "List of Recommendations" of what you can improve to make your application more secure and resilient.
This Kube-Score analyses Pod manifest files,Deployment manifest files or give any yaml file it will analyze whether the network policies are in place or resources are in place and affinity rules are configured, readiness and liveliness probes are properly configured & Container Security context is set as normal or root.
