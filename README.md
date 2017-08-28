# gravitational-vagrant

Quick Roadmap:

    1) Determine the workings of Vagrant and bring up some test machines.

    2) Explore the Kubernetes environment.

        a) Better determine if the image I chose in step 1) is adeqate for
           a Kubernetes rollout.

        b) If no determine what is, return to step 1) and perform a quick
           sanity check on the new image.

    3) Bring up an Kubernetes environment, single or multinode.

        a) Explore it.  Understand how its node-to-node communication functions.

        b) Explore the "hosted install" method and what it requires.


    4) Possibly revisit step 1) and build a new Vagrantfile for simple
       Kubernetes startup.

    5) Explore and understand the CNI plugin process.

    6) Write the CNI plugin to perform the task.  Revisit step 5) many times
       during this process.

    7) Finally, revisit step 1) and insert this plugin as part of the vagrant
       up process.

EOF
