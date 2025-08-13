# Elevato-Elivion API

This project contains OpenAPI specifications for the integration between Elevato and Elivion recruitment systems.

## Overview

The project is structured around two main API specifications:

1. **elevato-elivion** - API endpoints for Elivion to interact with Elevato system
2. **elivion-elevato** - Webhook endpoints for Elevato to receive analysis results from Elivion

## OpenAPI Specifications

This project uses [OpenAPI 3.0](https://swagger.io/specification/) to define REST API specifications. The API definitions are organized using modular YAML files.

### Structure

```
├── elevato-elivion/
│   ├── elevato-elivion.yaml        # Main OpenAPI specification
│   └── paths/
│       └── recruitment.yaml        # Recruitment-related endpoints
├── elivion-elevato/
│   ├── elivion-elevato.yaml        # Main OpenAPI specification  
│   └── paths/
│       └── elivion.yaml            # Webhook endpoints for analysis results
└── README.md
```

## OpenAPI Generator

This project is designed to work with [OpenAPI Generator](https://openapi-generator.tech/) to automatically generate client libraries, server stubs, and documentation.

### Viewing API Documentation

You can view the API documentation using:
1. [Swagger UI](https://swagger.io/tools/swagger-ui/) - Load the YAML files directly
2. [Swagger Editor](https://editor.swagger.io/) - Online editor and viewer
3. Generate HTML documentation using OpenAPI Generator
