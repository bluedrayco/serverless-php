# Description
The following example uses Silly for create a simple command line for send emails

# Example architecture
![Architecture](https://raw.githubusercontent.com/bluedrayco/serverless-php/master/02_console_command_with_ses/architecture.png)

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
```bash
./vendor/bin/bref cli example2-dev-hello --region us-east-2 -- send:emails
```