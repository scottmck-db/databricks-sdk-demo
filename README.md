This is a demo of the databricks SDK along with my notes for deployment. We use poetry to deploy this package in order to manage dependencies.

## Summary
1. Install poetry (https://python-poetry.org/docs/#installation)
2. Add packages using poetry add [package] (databricks-sdk, ipykernel)
3. Install the Databricks CLI (Azure: https://learn.microsoft.com/en-us/azure/databricks/dev-tools/cli/install)
4. Setup authentication (https://docs.databricks.com/en/dev-tools/auth/index.html#databricks-client-unified-authentication), I use the .databrickscfg file approach
5. Test authentication: databricks auth login

## Notes
The SDK is a good place to start with infrastructure management in Databricks because it directly maps to the API. The Databricks API is the 'source of truth' when it comes to managing Databricks infrastructure.

- Worth differentiating that DEFAULT and default in the config profiles might be different

## Resources
https://docs.databricks.com/en/dev-tools/sdk-python.html

