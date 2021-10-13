# Exercise 1
In this exercise, I selected Java as the language to discuss about.

## Tools for linting, testing, and building

### Linting
In Java, most of the modern IDEs such as IntelliJ and Eclipse have built-in tools to lint the code. Therefore, it is not always necessary to use any 3rd party tool for that. They still exist, and the most popular one is perhaps [Checkstyle](https://github.com/checkstyle/checkstyle).

### Testing
The most popular unit testing tool for Java is JUnit.

### Building
For building Java projects, there are two large and commonly used build tools you can use. Gradle and Maven. Since I don't really have experience with those, I can't give a comparison between them.

#

## More CI tools
In addition to Jenkins and GitHub Actions, there is a lot of other options for continuous integration. For example TravisCI, Azure DevOps, GitLab CI and Bamboo.

#

## Self-hosted or cloud-based environment?
When figuring out whether you should use a self-hosted or cloud-based environment, there are lot of factors you need to consider about. For example the size of the project, budget, skill level and so on.

Here is a small comparison between the two.

Pros for cloud-based environment:
- no need to maintain or update servers
- support system available 24/7
- easier to set up

Pros for self-hosted environment:
- you control the whole system and there is less middlemen between the product and consumers
- more cost-efficient specially if the application starts to grow

With these points in mind, going cloud might usually be better for small applications. It takes less time to set up, and while the app hasn't scaled to the moon, it is still relatively cheap to use cloud providers. But once the application scales, it comes more and more expensive to run it on cloud, so it might be better to think about going self-hosted. Even though it costs more time in hardware and software maintenance.