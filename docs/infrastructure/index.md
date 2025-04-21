# Infrastructure

This section of the documentation details the infrastructure that we have within Wye Make and how to access it.

Where appropriate, it also details how to interact with these systems and the tasks they perform.

## Physical Servers

Wye Make own the following physical servers:

| Name | Location |
|------|----------|
| [mmsvr01](./servers/mmsvr01.md) | Inside the space |

## Deploying Applications

!!! danger "IMPORTANT!"

    Your application will *only* be accessible within the space and only to people who are connected to the Wye Make WiFi.

    All applications run on [mmsvr01](./servers/mmsvr01.md) by default.

    If you want to launch applications that are available from the outside world, please raise a support ticket via [the member portal](https://members.makemonmouth.co.uk/) and someone will discuss what you're trying to do and whether we can accomodate it.

### What do I need to know?

If you want to deploy an application, you'll need to understand the following things:

   * How to use [Github](https://github.com/) including how to raise a Pull Request
   * The Wye Make Developer Guidelines
   * [Docker Compose](https://docs.docker.com/compose/)

!!! bug "How do I learn this?"

    Courses on all the above will be uploaded to [the learning portal](https://learn.makemonmouth.co.uk/) as soon as we are able, however in the mean-time you can ping `@proffalken` on Discord and he'll setup some time to talk you through it.

### How do I do it?

Once you have the above setup, then provisioning a new application is really straight-forward:

   1. Clone the [Service Infrastructure](https://github.com/MakeMonmouth/service-infrastructure) git repository
   2. Create a new branch (`git checkout -b service/<application_name>` if using the command line)
   3. Add your docker compose file in the [compose directory](https://github.com/MakeMonmouth/service-infrastructure/tree/main/compose)
   4. Commit your code and raise a pull request
   5. Your PR will be reviewed, and once it is merged your application should automatically spring into life within the space

