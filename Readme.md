# Database Configuration & Migrations

## Overview

This project uses MySQL with Flyway for schema management.

## Features

* Version-controlled migrations
* Initial schema creation
* Seed data included

## Migration Files

* V1__init.sql → Creates employee table

## Configuration

* application.properties contains DB credentials
* Flyway auto-runs on startup
