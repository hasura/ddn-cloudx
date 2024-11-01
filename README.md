# ddn-cloudx

- Session Link - https://apiworld2024.sched.com/event/1i0N5

## Pre Requisites

- [Install Hasura CLI & Login](https://hasura.io/docs/3.0/cli/installation)
- [Install Docker](https://docs.docker.com/engine/install/), you'll need docker compose v2.27.1 or later.
- Keep your Anthropic API Key ready

## Session (Demo) Outline

  - Introduction to Hasura DDN and Market Trends
    - Metadata-Centric Data Access: Discover how DDN’s declarative metadata model creates a unified, flexible data access layer that seamlessly integrates traditional databases and external services. This metadata-driven approach reduces the need for custom code, allowing teams to focus on high-impact areas, especially as AI technologies shift the development paradigm.   
  - Chapter 1 - Greenfield Application
    - Google Docs/Figma Style Real time commenting 
    - Github Repo: https://github.com/hasura/ddn-comments 
  - Chapter 2 - Sample Cloud Heavy Read Only Application
    - Multi Region Ecommerce domain - Airbnb
    - Github Repo: https://github.com/hasura/ddn-sample-app
  - Chapter 3 - PromptQL Demo
    - Creating an AI Assistant for your Github Repo
    - https://promptql.hasura.io/docs/example-github
  - Advanced Topics
    - Chapter 4 - Multi Repo/ Multi Team Workflows
      - Indpendent Team CI/CD without breaking changes
      - Github Repos:
        - Team 1 - https://github.com/hasura/ddn-sample-app/tree/multirepo/team1admin 
        - Team 2 - https://github.com/hasura/ddn-federation-sample-team2
    - Open Techincal RFCs for the DDN Platform
      - Protobuf based API (Github Repo: https://github.com/hasura/grpc-api-experiments)
      - [Distributed Entitlements based AuthZ System](https://github.com/hasura/graphql-engine/blob/abhinav/v3-authorization-rules-rfc/rfcs/v3/authorization-rules.md)

