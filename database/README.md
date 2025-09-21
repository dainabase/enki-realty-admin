# Database Structure

This directory contains all database-related files for ENKI Reality.

## Supabase Configuration

Project Details:
- **Project ID**: ccsakftsslurjgnjwdci
- **URL**: https://ccsakftsslurjgnjwdci.supabase.co
- **Region**: eu-central-2

## Directory Structure

```
database/
├── migrations/      # SQL migration files
│   ├── 001_initial_schema.sql
│   ├── 002_add_golden_visa.sql
│   └── ...         # Other migrations
├── seeds/          # Sample data
│   ├── developers.sql
│   ├── projects.sql
│   └── properties.sql
├── functions/      # Database functions
│   ├── calculate_commissions.sql
│   └── update_golden_visa.sql
└── policies/       # RLS policies
    └── security_policies.sql
```

## Main Tables

1. **developers** - Real estate development companies
2. **projects** - Development projects
3. **buildings** - Buildings within projects
4. **properties** - Individual units
5. **leads** - Customer prospects
6. **commissions** - Commission tracking
7. **amenities_reference** - Amenity types

## Key Features

- Row Level Security (RLS) on all tables
- Automatic Golden Visa detection (≥€300,000)
- Commission calculation triggers
- Multi-currency support
- VAT calculations (5% residential, 19% commercial)
