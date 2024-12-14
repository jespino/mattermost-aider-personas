# Mattermost AI Development Personas

This repository contains a collection of "persona" documents designed to provide AI systems with comprehensive context about Mattermost development patterns, conventions, and best practices. These documents help AI tools make more accurate and contextually appropriate suggestions when working with Mattermost code.

## Purpose

When developing Mattermost features or reviewing code, AI systems can load these persona documents to understand:
- Coding standards and conventions
- Architectural patterns
- Testing requirements
- Performance considerations
- Security best practices

## Usage

These documents are designed to be consumed by AI tools like aider. For example:

```bash
aider --read ../mattermost-aider-personas/server_developer.txt
```

This loads the server development context into the AI, helping it provide more accurate and idiomatic suggestions for Mattermost server code.

## Available Personas

- [Server Developer](server_developer.txt) - Go backend development patterns
- [Web Application Developer](webapp_developer.txt) - React/Redux frontend practices
- [Plugin Developer](plugin_server_developer.txt) - Plugin system architecture
- [External Integrations](external_integrations_developer.txt) - Webhook and integration APIs

## Benefits

Using these personas helps AI systems:
1. Understand Mattermost's architecture and patterns
2. Follow established coding conventions
3. Implement proper testing approaches
4. Consider performance implications
5. Maintain security standards
6. Make more contextually appropriate suggestions

## Contributing

When adding or updating personas:
- Focus on patterns and principles
- Include concrete examples
- Cover key architectural decisions
- Document common pitfalls
- Reference official Mattermost guidelines

## License

This documentation is provided under the same terms as Mattermost - see [LICENSE](https://github.com/mattermost/mattermost-server/blob/master/LICENSE.txt) for details.
