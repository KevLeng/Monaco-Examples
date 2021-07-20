# Monaco-Examples


## Deployment / Installation

To deploy (install) monaco, run:

`./deploy-monaco.ah`

## Dynatrace Environment Configuration
To push any monaco config in these examples first export the required environment variables DT_TENANT and DT_API_TOKEN:

```bash
export DT_TENANT=<Your Dynatrace Tenant URL>
export DT_API_TOKEN=<Your Dynatrace Token>

```


## Example: Application Deployment
Export environment variable APPNAME, the value of APPNAME will become the application name configured in Dynatrace

```bash
export APPNAME=<Your Application Name>

```
Then run monaco as follows:

```bash
./monaco_cli -e=monaco/environment.yaml -p=apponly monaco
```