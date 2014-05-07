# Apache Experiments

Apache Experiments is the place to experiment with Apache directives and 
record what I've learned.

To boot up Apache:

    $ vagrant up

The Ansible playbook will install apache, enable the modrewrite module, 
and copy over the configuration file.

To access Apache:

    $ vagrant ssh

I purposely did not forward ports so avoid confusion, but that's certainly
an option.

As I learn, I will add to `000-default.conf`.
