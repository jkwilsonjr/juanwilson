# Publishing Workflow

This document describes the workflow for publishing updates across our sites and subdomains.

## Preparation
- Gather all updated content, including markdown and HTML files, and ensure they are finalized.
- Verify file paths and naming conventions align with the repository structure.

## Version Control
- Commit changes to the repository with clear, descriptive messages.
- Ensure the main branch is up to date before adding new commits.

## Deployment
- For Carrd or other embed sites, copy the updated HTML files to the appropriate embed service.
- For Hostinger subdomains, upload the updated markdown files to the `web/hostinger/assets` directory and deploy through the hosting control panel.

## Review and Feedback
- After publishing, review the live content for accuracy and formatting.
- Collect feedback from stakeholders and make any necessary adjustments in a follow-up commit.

## Maintenance
- Regularly review all published pages for outdated content.
- Use the update protocol and versioning rules documents to ensure consistent updates over time.
