# Description
The following example uses Silly for create a simple command line for send emails and it will be activated via cron (every 1 minute)

# Example architecture
![Architecture](https://raw.githubusercontent.com/bluedrayco/serverless-php/master/03_simple_cron_function/architecture.png)

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
The lambda will be execute every minute automatically
