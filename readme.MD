# selectors

taint the node

kubectl taint nodes ip-192-168-16-53.ec2.internal hardware=gpu:NoSchedule

untaint the node 

kubectl taint nodes ip-192-168-16-53.ec2.internal hardware=gpu:NoSchedule-

label node

kubectl label nodes ip-192-168-26-169.ec2.internal hardware=gpu

Ref: https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes
 