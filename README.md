# Support Tickets Analysis Project

A comprehensive dataset and analysis project for customer support ticket management and insights.

## Dataset Overview

This project contains a customer support tickets dataset with detailed information about ticket resolution, customer satisfaction, and support operations.

### Data Structure

The `support_tickets.csv` file contains **1,100+ support tickets** with the following fields:

| Field | Description |
|-------|-------------|
| `ticket_id` | Unique ticket identifier (T1000-T1114+) |
| `customer_id` | Customer identifier |
| `category` | Ticket category (technical, billing, account, product, general) |
| `priority` | Priority level (low, medium, high, critical) |
| `status` | Current status (open, in_progress, resolved, closed) |
| `channel` | Support channel (email, web, chat, phone) |
| `product` | Product involved (Storage Plus, Analytics Suite, Data Pipeline, DataLake Pro, ML Platform) |
| `created_date` | Ticket creation date (2024) |
| `resolution_time_hours` | Time to resolution in hours |
| `satisfaction_score` | Customer satisfaction (1-5 scale) |
| `agent_id` | Support agent identifier |

## Project Files

- **`support_tickets.csv`** - Main dataset with support ticket records
- **`notebook1_struct_data.ipynb`** - Jupyter notebook for structured data analysis
- **`notebook2_unstruct_data.ipynb`** - Jupyter notebook for unstructured data analysis
- **`billing_faq.txt`** - Billing-related FAQ content
- **`product_guide.txt`** - Product guide documentation
- **`technical_faq.txt`** - Technical FAQ content

## Key Insights

- **Categories**: Technical, Billing, Account, Product, General inquiries
- **Products**: 5 main products (Storage Plus, Analytics Suite, Data Pipeline, DataLake Pro, ML Platform)
- **Channels**: Multi-channel support (Email, Web, Chat, Phone)
- **Time Period**: Full year 2024 data
- **Resolution Tracking**: Detailed timing and satisfaction metrics

## Usage

This dataset is ideal for:
- Customer support analytics
- Performance metrics analysis
- Satisfaction trend analysis
- Resource allocation optimization
- Machine learning model training for support automation

## Getting Started

1. Load the CSV file using pandas:
```python
import pandas as pd
df = pd.read_csv('support_tickets.csv')
```

2. Explore the Jupyter notebooks for analysis examples
3. Reference FAQ files for domain context

## Data Quality

- Complete records with no missing critical fields
- Consistent date formatting (YYYY-MM-DD)
- Standardized categorical values
- Realistic resolution times and satisfaction scores

## License

This dataset is provided for educational and analysis purposes.