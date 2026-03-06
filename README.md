# Unofficial Rails 37 Signals Coding Style Skills

A curated collection of machine-readable skills derived from the *Unofficial 37signals Coding Style Guide* by Marc Kohlbrugge. These skills package the guide’s Rails patterns and development philosophy in the format described by the [OpenCode skill specification](https://opencode.ai/docs/skills/), making it easy to plug them into your own AI assistant.

## Why use these skills?

The 37signals way emphasizes simple, CRUD-oriented design, rich domain models, and a bias for vanilla Rails. Each skill encapsulates a specific topic - ranging from routing and controllers to caching, accessibility, and AI/LLM integration - and includes the full text of the corresponding section of the guide. By importing these skills into your agent, you allow it to answer questions and make decisions consistent with 37signals’ development principles.

## Getting started

After cloning this repository, you’ll find a directory named `rails-37-style-skills`. Inside are subdirectories, one per skill. Each subdirectory contains a `SKILL.md` file with YAML front matter (`name`, `description`, and `license`) followed by the full markdown content of the guide section.

To use a skill, copy its directory into your agent’s skills folder. For example, to add the routing patterns skill to your agent, run:

```bash
cp -r rails-37-style-skills/rails-37-style-core-rails-routing /path/to/your/agent/skills/
```

Refer to the [OpenCode skill documentation](https://opencode.ai/docs/skills/) for details on how your agent discovers and loads skills.

## Skill Index

The collection is organized by section. Each item below references a directory containing its `SKILL.md` file.

### Core Rails

- **Routing** - `rails-37-style-core-rails-routing`
- **Controllers** - `rails-37-style-core-rails-controllers`
- **Models** - `rails-37-style-core-rails-models`
- **Views** - `rails-37-style-core-rails-views`

### Frontend

- **Stimulus** - `rails-37-style-frontend-stimulus`
- **CSS** - `rails-37-style-frontend-css`
- **Hotwire** - `rails-37-style-frontend-hotwire`
- **Accessibility** - `rails-37-style-frontend-accessibility`
- **Mobile** - `rails-37-style-frontend-mobile`

### Backend

- **Authentication** - `rails-37-style-backend-authentication`
- **Multi-Tenancy** - `rails-37-style-backend-multi-tenancy`
- **Database** - `rails-37-style-backend-database`
- **Background Jobs** - `rails-37-style-backend-background-jobs`
- **Caching** - `rails-37-style-backend-caching`
- **Performance** - `rails-37-style-backend-performance`

### Real-time & Communication

- **ActionCable** - `rails-37-style-real-time-and-communication-actioncable`
- **Notifications** - `rails-37-style-real-time-and-communication-notifications`
- **Email** - `rails-37-style-real-time-and-communication-email`

### Features

- **Webhooks** - `rails-37-style-features-webhooks`
- **Workflows** - `rails-37-style-features-workflows`
- **Watching** - `rails-37-style-features-watching`
- **Filtering** - `rails-37-style-features-filtering`
- **AI/LLM Integration** - `rails-37-style-features-ai-llm-integration`

### Rails Components

- **Active Storage** - `rails-37-style-rails-components-active-storage`
- **Action Text** - `rails-37-style-rails-components-action-text`

### Infrastructure & Testing

- **Security Checklist** - `rails-37-style-infrastructure-and-testing-security-checklist`
- **Testing** - `rails-37-style-infrastructure-and-testing-testing`
- **Configuration** - `rails-37-style-infrastructure-and-testing-configuration`
- **Observability** - `rails-37-style-infrastructure-and-testing-observability`

### Philosophy

- **Development Philosophy** - `rails-37-style-philosophy-development-philosophy`
- **What They Avoid** - `rails-37-style-philosophy-what-they-avoid`

## Acknowledgements

## License

The analysis and commentary from the original guide are licensed under MIT.
Code snippets originate from the 37signals Fizzy codebase and are subject to the O'Saasy License.
