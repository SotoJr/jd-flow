# JD Flow Architecture

## Components

### Frontend
Hostinger Horizon web application.

### Database
Supabase tables for dispatch orders, history, users and document records.

### Storage
Supabase storage buckets for dispatch packages and documents.

### SILA Connector
Tampermonkey script used to send selected SILA orders into JD Flow.

## High-Level Flow

SILA
→ Tampermonkey Connector
→ Supabase
→ JD Flow Dashboard
→ San Diego Dispatch Process
