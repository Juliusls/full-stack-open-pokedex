1. For linting Python we could use Flake8. Flake8 is a tool for style guide enforcement. This means flake8's principal purpose to ensure you style your codes properly. And also Pylint. Pylint is a bit different from flake8, it's the full dose really: it checks style guide, programmatic errors and follows best practices
For testing we could use pytest that makes building simple and scalable tests easy.
For Building we could use docker Docker to create a single self-contained, deployable unit of our app.

2. CI alternatives to Jenkins or GitHub Actions are: GitLab CI, Azure Pipelines, CircleCI, Buildkite, Atlassian Bamboo, TeamCity, Travis CI, BuildMaster, Bitrise, AWS CodePipeline, CruiseControl, Integrity, Shippable, CodeShip, GoCD, Semaphore CI, AppVeyor.

3. Decision would need to be made on the benefits and downsides of each environment. 

For self-hosted environment benefits are: It gives you absolute control of your build process, Ci server is provisioned the same way as your production machines are. Downside is hard configuration. Someone needs to configuring a CI server correctly and keeping it running 24/7.

For cloud-based environment benefits are: Easy to set up, no hardware or software infrastructure to maintain,It is much faster as the process can be distributed to multiple servers (of course that is done at some price). Downside is the security as the code will be handled by one of these providers.

As for our project our team is only 6 people so it would be better to use cloud-based environment as we would not need to use that much recourses for configuration and maintenance

