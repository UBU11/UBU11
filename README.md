```yaml
version: "1.0"

profile:
  name: ubu
  role: engineering-student
  focus:
    - backend-systems
    - devops
    - system-design

services:
  backend:
    stack:
      - nodejs
      - typescript
    responsibilities:
      - api-design
      - authentication
      - background-jobs
      - real-time-communication

  database:
    primary:
      - postgresql
      - mongodb
    supporting:
      - redis
    concerns:
      - indexing
      - caching
      - consistency
      - performance

  infrastructure:
    tools:
      - linux
      - docker
      - ci-cd
      - K8S
    principles:
      - automation
      - observability
      - reliability

  frontend:
    usage: pragmatic
    tools:
      - react
      - nextjs
      - tailwindcss
    note: used_when_product/project_requires_it

status:
  learning: active
  building: continuous
  direction: backend_and_platform_engineering
