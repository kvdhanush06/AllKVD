# Security Policy

AllKVD is a static personal landing site and acts as the canonical hub for Venkata Dhanush Kakarlamudi's public professional and project links.

## Reporting a Vulnerability

Please report security vulnerabilities privately to the repository owner through GitHub or the contact information published on https://allkvd.dev/. Do not publish exploitable details in a public issue.

Include the affected component, reproduction steps, impact, and relevant evidence.

## Security Practices

- The site is static and has no application database or authentication service.
- Public links are intentionally limited to documented profiles and deployed projects.
- Structured data should contain public professional information only.
- Secrets and private deployment credentials must never be committed.
- `robots.txt`, `sitemap.xml`, and `llms.txt` are public discovery resources and must not contain private information.

## Secret Handling

Never commit API keys, access tokens, private credentials, or deployment configuration containing secrets.
