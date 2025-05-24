## CI/CD Pipeline with GitHub Actions

This project uses GitHub Actions for CI/CD:

## Workflow Steps:
- Install Dependencies**: Installs Python dependencies using pip.
- Run Tests: Runs pytest on each commit.
- Build: Prepares the application for deployment.
- Deploy to Staging: Auto-deploys to staging when changes are pushed to staging branch.
- Deploy to Production: Auto-deploys to production when a new release is tagged.

## Secrets Configuration:
Add these secrets in GitHub:
- STAGING_API_KEY: Token/credential for staging deployment.
- PROD_API_KEY: Token/credential for production deployment.
