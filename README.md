# Orb Labs website

The public-facing website for Orb Labs, the experimental studio within Orb Corporation.

Orb Labs explores unusual questions across software, hardware, computation, simulation and creative technology. The website deliberately distinguishes illustrative experiment briefs from actual published project records.

## Local preview

This is a dependency-free static website. Open `index.html` directly, or run:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Create a static-site service using this repository as the source. Leave the build command empty and set the publish directory to the repository root (`.`). No Node.js installation or package manager is required.

## Structure

- `index.html` — studio overview, fields of work, example briefs and experiment index
- `site.css` — responsive dark visual system
- `site.js` — accessible mobile navigation and dynamic footer year
- `favicon.svg` — site icon

## Experiment records

Example briefs on the website are explicitly labelled as concepts. They are not claims that an experiment has been started or completed. Published records should include the question, hypothesis, constraints, method, observations, limitations and next steps.

Statuses used by the public index:

- `ONGOING`
- `COMPLETED`
- `FAILED`
- `ABANDONED`
- `ARCHIVED`

A result does not need to become a product to be worth documenting.

## Organisation

Orb Labs is the experimental studio of Orb Corporation. Work that demonstrates practical user value may be considered for further product development by Orb Technologies, but productisation is never a requirement.
