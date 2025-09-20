# Global Search

Kosentral's powerful global search feature helps you quickly find members, invoices, and other important information across your organization.

## Overview

The global search functionality provides:

- **Real-time search** across multiple data types
- **Intelligent suggestions** as you type
- **Quick navigation** to relevant pages
- **Multi-category results** in a unified interface

## Accessing Global Search

### From the Dashboard

1. Navigate to your **Home Dashboard**
2. Locate the search bar at the top of the page
3. Begin typing your search query
4. Results appear automatically after 2+ characters

### Search Categories

Global search covers these main categories:

=== "Members"

    **Search Fields**:
    - Member name
    - Membership ID
    - IC number
    - Email address
    - Phone number
    
    **Result Format**:
    - Member name as title
    - Membership ID as subtitle
    - IC number in metadata
    - Direct link to member details

=== "Invoices"

    **Search Fields**:
    - Invoice number
    - Member name
    - Invoice description
    - Amount ranges
    
    **Result Format**:
    - Invoice number as title
    - Member name as subtitle
    - Amount and status in metadata
    - Direct link to invoice details

=== "Receipts"

    **Search Fields**:
    - Receipt number
    - Transaction description
    - Member name
    - Payment amounts
    
    **Result Format**:
    - Receipt number as title
    - Member name as subtitle
    - Amount and date in metadata
    - Direct link to transaction details

## Search Features

### Instant Results

- **Minimum Characters**: 2 characters required
- **Real-time Updates**: Results update as you type
- **Maximum Results**: 10 per category by default
- **Quick Preview**: Essential information shown immediately

### Search Operators

Use these operators for more precise searches:

| Operator | Usage | Example |
|----------|-------|---------|
| **Quotes** | Exact phrase matching | `"John Doe"` |
| **Wildcard** | Partial matching | `john*` |
| **Range** | Numeric ranges | `amount:50-100` |
| **Date** | Date-specific searches | `date:2024-01-01` |

### Advanced Filters

#### Member Search Filters
```
name:john status:active
ic:123456* email:@gmail.com
joined:2024 gender:male
```

#### Invoice Search Filters
```
number:INV-2024* status:unpaid
amount:>100 member:john
date:2024-01-01..2024-01-31
```

#### Transaction Search Filters
```
receipt:RCP-2024* type:membership
amount:<50 date:today
member:jane
```

## Using Search Results

### Navigation

1. **Click any result** to navigate directly to the details page
2. **Use keyboard arrows** to navigate between results
3. **Press Enter** to select highlighted result
4. **ESC key** to close search results

### Result Information

Each search result displays:

- **Primary identifier** (name, number, etc.)
- **Secondary information** (ID, member name, etc.)
- **Metadata** (status, amount, date, etc.)
- **Direct navigation link**

## Performance Optimization

### Database Indexing

Search performance is optimized through:

- **Full-text indexes** on searchable fields
- **Composite indexes** for multi-field queries
- **Partial indexes** for status-based filtering
- **Trigram indexes** for fuzzy matching

### Caching Strategy

- **Query result caching** for frequent searches
- **Suggestion caching** for autocomplete
- **User-specific cache** for personalized results
- **Cache invalidation** on data updates

## Best Practices

### Effective Search Strategies

1. **Start with key identifiers**: Use membership IDs, invoice numbers, or IC numbers for precise results
2. **Use partial names**: Search works well with partial member names
3. **Combine filters**: Use multiple criteria to narrow results
4. **Check spelling**: Verify spelling for accurate results

### Common Search Patterns

#### Finding Members
```
# By name
john doe

# By membership ID
M2024001

# By IC number
123456-78-9012

# By email domain
@company.com
```

#### Finding Invoices
```
# By invoice number
INV-2024-001

# By member and status
john unpaid

# By amount range
amount:50-100

# By date
january 2024
```

#### Finding Transactions
```
# By receipt number
RCP-2024-001

# By transaction type
membership fee

# By member name
jane payment

# By amount
amount:>100
```

## Troubleshooting Search

### No Results Found

If your search returns no results:

1. **Check spelling** and try alternative spellings
2. **Reduce search terms** to broader queries
3. **Try partial matches** instead of exact phrases
4. **Verify data exists** in the system
5. **Check permissions** for accessing the data

### Slow Search Performance

If search is running slowly:

1. **Reduce search scope** with more specific terms
2. **Use exact identifiers** when possible
3. **Avoid wildcard-heavy queries**
4. **Contact support** if performance issues persist

### Unexpected Results

If search returns unexpected results:

1. **Review search operators** used in the query
2. **Check for typos** in search terms
3. **Verify filter syntax** is correct
4. **Try simpler queries** to isolate issues

## Mobile Search

### Mobile Optimizations

- **Touch-friendly interface** with larger result areas
- **Swipe gestures** for result navigation
- **Voice search support** on compatible devices
- **Offline search cache** for recent queries

### Mobile-Specific Features

- **Quick filters** for common search types
- **Recent searches** for easy re-access
- **Search shortcuts** for frequent queries
- **Barcode scanning** for membership ID lookup

---

!!! tip "Search Pro Tips"
    
    - **Bookmark frequent searches**: Save time by bookmarking common search results
    - **Use keyboard shortcuts**: Arrow keys for navigation, Enter to select
    - **Try different keywords**: If one term doesn't work, try synonyms
    - **Combine search with filters**: Use the advanced filtering for more precise results

!!! info "Search Limitations"
    
    Current search limitations:
    
    - Results limited to current organization only
    - Maximum 50 results per category
    - No full-text search in document contents
    - Deleted items not included in results
