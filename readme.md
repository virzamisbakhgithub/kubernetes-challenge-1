Kodekloud Challenge 1
1. First of all we need to set the config
    $ kubectl config set-credentials martin --client-certificates='/root/martin.crt' --client-key='/root/martin.key'

2. $ kubectl config set-context developer --cluster=kubernetes --user=martin

3. Make a role.yml then apply

4. Make a role-binding.yml then apply

5. Setup the context with one we have made it before
    $ kubectl config use-context developer --user=martin --cluster=kubernetes

6. Make a svc.yml then apply

7. Make a pod.yml then apply

8. Make a pvc.yml then apply