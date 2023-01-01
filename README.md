# Docker Compose Teamcity

TeamCity is a general-purpose CI/CD software platform that allows for flexible workflows, collaboration and development practices.

## 📝 Installation
- Copy dir `agents/agent-sample` to `agents/agent-1`, `agents/agent-2`, `agents/agent-3`
- Change `serverUrl`, agent `name`, `authorizationToken` on each agent dir in `buildAgent.properties` file.
- run teamcity agent : `docker-compose -f docker-compose-agent.yml up -d`
- run teamcity : `docker-compose up -d`
- Authorize agent by going to `https://yourdomain.com/agent`

## 📚 Resources
- [Official Website](https://www.jetbrains.com/teamcity/)
  - [Docs](https://www.jetbrains.com/help/teamcity/teamcity-documentation.html)
  - [Learn](https://www.jetbrains.com/teamcity/learn/)
  - [Tutorial](https://www.jetbrains.com/teamcity/tutorials/)
