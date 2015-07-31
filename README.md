Cassandra Dockerfile for Usergrid
=================================

This Dockerfile is part of a collection of containers to run [Usergrid](https://usergrid.incubator.apache.org) on [Docker](https://www.docker.com).

For more information, see the base repository [usergrid-docker](https://github.com/yep/usergrid-docker).

This Cassandra Dockerfile is based on previous work from [here](https://github.com/munkyboy/docker_cassandra). Usergrid seems to require Cassandra 1.x, therefore using Docker's official Cassandra Dockerfile ([documentation](https://github.com/docker-library/docs/tree/master/cassandra), [repository](https://github.com/docker-library/cassandra)) is not possible as it only provides Cassandra 2.x.
