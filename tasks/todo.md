# MTX Gov LPI Landing Page

## Plan

* [x] Review source PDFs, existing site, repository state, and reference sites.
* [x] Replace the obsolete page with a responsive MTX Gov LPI product page.
* [x] Replace the deployment workflow with one root\-artifact GitHub Pages workflow.
* [x] Validate HTML semantics, accessibility basics, links, responsive behavior, and workflow syntax.
* [x] Commit and push the replacement directly to `main`.
* [x] Verify the Pages workflow and live URL.

## Review

HTML validation passes. Workflow YAML validation passes. Lighthouse reports an accessibility score of 100 with no failed binary audits. Manual desktop, keyboard, and 400px mobile checks pass, including the responsive navigation. Repository checks confirm one Pages workflow, no uploaded source documents, and no obsolete product terminology. The GitHub Pages deployment completed successfully, and the live page returned HTTP 200 with content matching the local release.

## Platform\-Agnostic Update

* [x] Remove Microsoft\-only positioning from metadata, hero copy, and architecture copy.
* [x] Update the architecture visual to show Microsoft, Salesforce, and AWS technology options.
* [ ] Validate, publish, and verify the live update.
