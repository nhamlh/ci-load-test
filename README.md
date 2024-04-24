# CI workflow for http service load testing

## Getting started
Clone this repository.

Enable Github Actions (if not enabled yet).

Allow Github Actions to comment on PR: go to Settings -> Actions -> General -> Workflow permissions and tick the 'Read and write permissions' then Save.

Open a sample PR to see it in action.

## Development
This section describes my process or thought model to develop this application.

First, try to deliver a feature complete setup. It just need to deliver what we promise to our users: when a PR is openned, trigger a CI job to perform a load testing of http services (foo and bar as place holder services) then comment the load testing report to the PR. At this stage, code maintainability/D.R.Y/performance/etc can be compromised.

Internal enhancement: when the feature is delivered, we can continue to improve on the codebase in the background.

# Worklog
## Research
start: 21:45
end: 22:20

- github actions with a dummy comment on PR
- explore kind action

## Working on local instance of kind cluster for faster development
start: 22:20
end: 23:30

- provision cluster
- provision resources
- vegeta attack and report
- comment

## Feature complete workflow
start: 18:15
end: 19:30
