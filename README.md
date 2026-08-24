# AI FoundryCamp Website

Static website content for [ai-foundrycamp.com](https://ai-foundrycamp.com).

This repo is cloned by the EC2 instance provisioned by the `website-server.yaml`
CloudFormation template (see the `CloudFunding-Readiness` toolkit repo) via its
UserData script. It contains only the public-facing site content -- no internal
playbooks, checklists, or client data.

## Contents

- `ai-foundrycamp-website-v3.html` -- the site's single-page HTML file, served
  directly by Nginx as the site index.
