null
====

A minimal standalone HPE Helion Stackato app for exploration and testing.

This app does nothing but provide a container for inspection and testing.

## Deploying to HPE Helion Stackato

    $ stackato push -n

## SSH to Container

Once the app has been deployed, use the `stackato` client to open an SSH session to the container.

    $ stackato ssh -a null
    null:~$
