# github-action

- workflows are defined at repository level
- a VM is scoped to a job: steps share the VM, but jobs dont't (by default, each job receives a clean VM instances)
- job runners might have pre installed softwares, packages you might need so check before install
- by using predefined actions in steps, it avoids repetive and extensive commands
