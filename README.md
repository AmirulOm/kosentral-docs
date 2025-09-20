# Kosentral Documentation Project

This repository contains the complete documentation for the Kosentral web application using MkDocs with Material theme.

## 📚 Documentation Structure

```
kosentral-docs-site/
├── mkdocs.yml                  # MkDocs configuration
├── docs/
│   ├── index.md               # Homepage
│   ├── getting-started/       # Introduction & setup guides
│   ├── account-setup/         # Registration, login, password reset
│   ├── members/               # Member management documentation
│   ├── invoices/              # Invoice creation and management
│   ├── transactions/          # Payment and transaction processing
│   ├── reports/               # Reporting and analytics
│   ├── settings/              # Organization and user settings
│   ├── features/              # System features (search, support)
│   ├── api/                   # API documentation
│   ├── dev/                   # Developer guides
│   └── includes/              # Shared content snippets
└── site/                      # Generated static site (auto-created)
```

## 🚀 Quick Start

### Prerequisites

- Python 3.8+
- Virtual environment (recommended)

### Setup

1. **Clone and navigate to the project:**
   ```bash
   cd kosentral-docs
   ```

2. **Activate virtual environment:**
   ```bash
   source .venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install mkdocs mkdocs-material
   ```

4. **Navigate to docs site:**
   ```bash
   cd kosentral-docs-site
   ```

### Local Development

**Serve the documentation locally:**
```bash
mkdocs serve
```

Visit `http://127.0.0.1:8000` to view the documentation.

**Build static site:**
```bash
mkdocs build
```

## 📖 Documentation Features

### Comprehensive Coverage

- **User Guides**: Step-by-step instructions for all features
- **API Documentation**: Complete REST API reference
- **Developer Guides**: Architecture and technical details
- **Quick Start**: 15-minute setup tutorial
- **Troubleshooting**: Common issues and solutions

### Modern Documentation Features

- **Material Design**: Clean, professional appearance
- **Responsive Layout**: Mobile-friendly design
- **Dark/Light Mode**: Automatic theme switching
- **Advanced Search**: Full-text search capabilities
- **Navigation**: Tabbed navigation with sections
- **Code Highlighting**: Syntax highlighting for multiple languages
- **Admonitions**: Info boxes, tips, warnings, and notes
- **Tabbed Content**: Organized content with tabs
- **Mermaid Diagrams**: Architecture and flow diagrams

### Content Organization

#### Getting Started Section
- Introduction to Kosentral concepts
- System requirements
- Quick start guide (15 minutes)

#### User Documentation
- Account setup and management
- Member lifecycle management
- Financial operations (invoices, transactions)
- Reporting and analytics
- Organization settings

#### Technical Documentation
- API reference with examples
- Architecture overview
- Database schema documentation
- Deployment guides

## 🎨 Theme Configuration

### Material Theme Features

- **Color Scheme**: Blue primary with automatic dark/light mode
- **Typography**: Optimized for readability
- **Icons**: Material Design and FontAwesome icons
- **Navigation**: Sticky header with tabs
- **Search**: Advanced search with suggestions
- **Social Links**: GitHub, Twitter, website links

### Custom Styling

The documentation uses MkDocs Material theme with custom configurations:

- **Palette**: Automatic dark/light mode switching
- **Navigation**: Tabs, sections, and instant loading
- **Search**: Enhanced search with highlighting
- **Content**: Code copy buttons, annotation support

## 📝 Content Guidelines

### Writing Style

- **Clear and Concise**: Use simple, direct language
- **User-Focused**: Write from the user's perspective
- **Action-Oriented**: Use action verbs and step-by-step instructions
- **Consistent Terminology**: Use the same terms throughout

### Markdown Best Practices

#### Headers
```markdown
# Page Title (H1 - one per page)
## Main Section (H2)
### Subsection (H3)
#### Detail Section (H4)
```

#### Admonitions
```markdown
!!! tip "Pro Tip"
    This is a helpful tip for users.

!!! warning "Important"
    This is important information to note.

!!! info "Information"
    This provides additional context.
```

#### Code Blocks
```markdown
```csharp
public class Example
{
    public string Property { get; set; }
}
```

#### Tabbed Content
```markdown
=== "Tab 1"
    Content for tab 1

=== "Tab 2"
    Content for tab 2
```

## 🔧 Maintenance

### Adding New Pages

1. **Create markdown file** in appropriate directory
2. **Update navigation** in `mkdocs.yml`
3. **Test locally** with `mkdocs serve`
4. **Update cross-references** in related pages

### Updating Existing Content

1. **Edit markdown files** directly
2. **Use live reload** during development
3. **Test all links** and references
4. **Verify responsive design** on mobile

### Managing Assets

- **Images**: Store in `docs/assets/images/`
- **Downloads**: Store in `docs/assets/downloads/`
- **Custom CSS**: Add to theme configuration

## 🚀 Deployment

### GitHub Pages (Recommended)

```bash
# Build and deploy to GitHub Pages
mkdocs gh-deploy
```

### Manual Deployment

```bash
# Build static site
mkdocs build

# Upload contents of site/ directory to web server
```

### Automated CI/CD

Example GitHub Actions workflow:

```yaml
name: Deploy Documentation
on:
  push:
    branches: [ main ]
jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v2
    - uses: actions/setup-python@v2
      with:
        python-version: 3.x
    - run: pip install mkdocs-material
    - run: mkdocs gh-deploy --force
```

## 📊 Analytics

### Google Analytics Integration

Add your Google Analytics key to `mkdocs.yml`:

```yaml
extra:
  analytics:
    provider: google
    property: YOUR_GA_TRACKING_ID
```

### Search Analytics

Monitor search queries to identify:
- Popular content
- Missing documentation
- User behavior patterns

## 🤝 Contributing

### Content Contributors

1. **Fork the repository**
2. **Create feature branch** for your changes
3. **Write/update documentation** following style guidelines
4. **Test locally** with `mkdocs serve`
5. **Submit pull request** with clear description

### Review Process

- **Technical accuracy** review by development team
- **Content clarity** review by documentation team
- **User experience** testing with target audience

## 📈 Future Enhancements

### Planned Features

- **Interactive API Explorer**: Live API testing interface
- **Video Tutorials**: Embedded video content
- **Multi-language Support**: Internationalization
- **Advanced Search**: Elasticsearch integration
- **User Feedback**: Rating and comment system

### Content Expansion

- **Use Case Examples**: Industry-specific scenarios
- **Integration Guides**: Third-party service integrations
- **Advanced Tutorials**: Complex workflow examples
- **Performance Guides**: Optimization recommendations

## 🆘 Support

### Documentation Issues

- **Content Errors**: Submit issue with page reference
- **Missing Information**: Request new content
- **Technical Problems**: Report bugs or formatting issues

### Contact Information

- **Documentation Team**: docs@kosentral.com
- **Technical Support**: support@kosentral.com
- **GitHub Issues**: Use repository issue tracker

---

**Built with ❤️ using MkDocs Material**

This documentation site represents a comprehensive resource for Kosentral users, developers, and administrators. It's designed to grow with the product and community needs.
