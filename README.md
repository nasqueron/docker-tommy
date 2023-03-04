# docker-tommy

### Moved repository

The content of this repository has been merged with the `tommy`repository itself.

Please browse:

  - rTOMMY on DevCentral: https://devcentral.nasqueron.org/source/tommy/
  - nasqueron/tommy on GitHub: https://github.com/nasqueron/tommy

The commit history, excepted the archive one, has been fully integrated o the Tommy repository.
Hash merged: 036bb6690cf3

### Run the container

To run the container:

`docker run -dt -p 4567:4567 --name=tommy -e JENKINS_URL=http://ci.nasqueron.org nasqueron/tommy`

The JENKINS_URL variable environment should point
to your Jenkins or Hudson instance.

If a login is required to use the API,
use https://login:password@jenkins.domain.tld as syntax.
