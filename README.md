# Bluegreen Deployment Example

This repository contains a basic Phoenix application that demonstrates how to deploy to Fly.io using the blue-green deployment strategy. This strategy allows you to release new versions of your app with zero downtime by running two environments (blue and green) side by side and switching traffic between them.

⸻

## Running Locally

To start the Phoenix server locally:
1.	Install and set up dependencies:

```bash
mix setup
```

2.	Start the Phoenix endpoint:

```bash
mix phx.server
```

Or start it inside IEx for an interactive shell:

```bash
iex -S mix phx.server
```

3.	Open your browser and visit: http://localhost:4000

⸻

## Deploying to Production

When you’re ready to deploy, check out the official Phoenix deployment guides.
For Fly.io-specific instructions and examples of blue-green deployment, see the Fly.io documentation.

⸻

## Additional Resources:
- Phoenix
- Website: phoenixframework.org
- Guides: hexdocs.pm/phoenix/overview.html
- API Docs: hexdocs.pm/phoenix
- Community Forum: Elixir Forum (Phoenix section)
- Source Code: GitHub – phoenixframework/phoenix
- Fly.io
- Website: fly.io
- Docs: fly.io/docs
