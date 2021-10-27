# Description
The following example uses SlimPHP for create a simple Rest Service over AWS Lambda and API Gateway

# Example architecture
![Architecture](https://raw.githubusercontent.com/bluedrayco/serverless-php/master/01_rest_api_over_gateway/architecture.png)

# Installation
Download dependencies
```bash
composer install -o --prefer-dist
```

# Deploy lambda
```bash
serverless deploy
```

# Remove lambda
```bash
serverless remove
```

# Execute
Open to browser tab in the following URL:

{URL_GIVEN_FROM_SERVERLESS}/hello/{text}

Example:

**https://33kmvugsb6.execute-api.us-east-2.amazonaws.com/hello/pipo**