---
sidebar_position: 5
---

# How to Create &  Manage  Knowledge Base

Upload, crawl, and manage content sources that power your AI assistant's knowledge and enable accurate, contextual responses to user inquiries.

## Overview

Knowledge Base allows you to create and manage various content sources that your AI assistants can reference when responding to users. This ensures your assistant provides accurate, up-to-date information specific to your business or use case.

## When to Use Knowledge Base

**Create knowledge sources when you need:**
- Business-specific information for assistant responses
- Updated documentation and policies
- Website content integration
- FAQ databases and support materials
- Custom training data for specialized topics

## Step-by-Step Process

### Step 1: Access Knowledge Base

Navigate to **Knowledge Base** in your dashboard sidebar to view and manage all your content sources.

**Before you start:**
- Identify what information your assistant needs
- Prepare your content sources (documents, URLs, text)
- Consider content organization and naming
- Plan for regular content updates

### Step 2: Choose Knowledge Source Type

Click **"Add Source"** to select the most appropriate method for adding your content.

**Available source types:**
- **Upload Document**: PDF, DOC, TXT, CSV, XLS, PPT files (max 21MB)
- **Add URL**: Single web page content extraction
- **Crawl Website**: Multiple pages from a website automatically
- **Create Text Corpus**: Manual text input for FAQs or policies

### Step 3: Configure Source Settings

Depending on your chosen source type, configure the specific settings for optimal content processing.

**Upload Document:**
- Drag and drop or click to upload files
- Enter descriptive source name
- Supported formats: PDF, DOC, TXT, CSV, XLS, PPT

**Add URL Source:**
- Enter complete website URL
- Content extracted and processed automatically
- Provide meaningful source name for identification

### Step 4: Set Processing Parameters

For advanced source types, configure processing parameters to optimize content extraction.

**Crawl Website settings:**
- Set maximum crawl depth (number of page levels)
- Choose comprehensive or focused crawling
- Monitor processing for large websites

**Text Corpus requirements:**
- Minimum 50 characters required
- Ideal for FAQs, policies, and structured content
- Format content clearly for best results

### Step 5: Monitor and Manage Sources

Track usage, update content, and maintain your knowledge sources for optimal assistant performance.

**Source management:**
- View processing status and completion
- Monitor usage statistics and access patterns
- Update or replace outdated content
- Delete unused or redundant sources

## Interactive Demo

<div style={{position: 'relative', boxSizing: 'content-box', maxHeight: '80vh', width: '100%', aspectRatio: '2.0041753653444676', padding: '40px 0 40px 0'}}>
<iframe 
  src="https://app.supademo.com/embed/cmdp1g9d022lq9f96g1icxuhj?embed_v=2&utm_source=embed" 
  loading="lazy" 
  title="How to navigate through Knowledge base" 
  allow="clipboard-write" 
  frameBorder="0" 
  webKitAllowFullScreen="true" 
  mozAllowFullScreen="true" 
  allowFullScreen 
  style={{position: 'absolute', top: 0, left: 0, width: '100%', height: '100%'}}
/>
</div>

## Advanced Configuration Options

### Content Processing
- **Format optimization**: Ensure content is properly structured
- **Size management**: Balance comprehensive content with processing efficiency  
- **Update frequency**: Establish regular content refresh schedules
- **Quality control**: Review extracted content for accuracy

### Source Organization
- **Naming conventions**: Use descriptive, consistent source names
- **Content categorization**: Group related sources logically
- **Version control**: Track content updates and changes
- **Usage monitoring**: Analyze which sources are most valuable

### Integration Planning
- **Assistant assignment**: Link sources to specific assistants
- **Content prioritization**: Ensure critical information is easily accessible
- **Cross-referencing**: Connect related content sources
- **Performance optimization**: Monitor response accuracy and speed

## Knowledge Source Types Guide

### Document Upload vs URL vs Website Crawl
| Method | Best For | Content Volume | Processing Time |
|--------|----------|----------------|-----------------|
| Upload Document | Existing files, policies, reports | Single documents | Fast |
| Add URL | Specific web pages, articles | Single page content | Fast |
| Crawl Website | Comprehensive site knowledge | Multiple pages | Moderate |
| Text Corpus | Custom FAQs, structured content | Manual input | Instant |

### Supported File Formats
**Documents:**
- **PDF**: Reports, manuals, presentations
- **DOC/DOCX**: Word documents, policies
- **TXT**: Plain text files, transcripts
- **CSV**: Data tables, contact lists
- **XLS/XLSX**: Spreadsheets, databases
- **PPT/PPTX**: Presentations, training materials

## Best Practices

### Content Preparation
1. **Organize information** before uploading to minimize processing time
2. **Use clear formatting** in documents for better extraction
3. **Remove sensitive data** that shouldn't be accessible to assistants
4. **Test content quality** with small samples first

### Source Management
1. **Regular updates** to keep information current and accurate
2. **Monitor usage patterns** to identify most valuable content
3. **Maintain naming consistency** for easy source identification
4. **Archive outdated content** rather than deleting permanently

### Performance Optimization
1. **Balance content volume** with response speed requirements
2. **Structure information** for easy assistant access and reference
3. **Test assistant responses** after adding new knowledge sources
4. **Optimize content organization** based on usage analytics

## Troubleshooting

### Common Upload Issues

**File not processing:**
- Verify file format is supported (PDF, DOC, TXT, CSV, XLS, PPT)
- Check file size is under 21MB limit
- Ensure file isn't corrupted or password-protected
- Try uploading smaller files first

**URL extraction problems:**
- Confirm URL is accessible and public
- Check website doesn't block automated access
- Verify content isn't behind login walls
- Test with simpler, static web pages first

**Website crawling issues:**
- Reduce crawl depth if processing takes too long
- Check website robots.txt file for restrictions
- Monitor processing status and adjust parameters
- Consider crawling sections rather than entire sites

## Next Steps

After setting up your knowledge base:

1. **[Assign to assistants](./assign-roles)** to make knowledge available
2. **[Test assistant responses](./guided-setup#review-and-test)** with knowledge integration
3. **[Monitor usage analytics](./analytics-setup)** to optimize content
4. **[Regular content updates](./content-management)** for accuracy

## Getting Help

Need assistance with knowledge base management?
- [View our knowledge documentation](/api/knowledge) for technical details
- [Contact support](mailto:support@travnex.com) for upload assistance  
- [Join our community](https://community.travnex.com) for content strategy tips

**💡 Pro Tip: Start with your most frequently asked questions and core business information, then expand your knowledge base based on assistant usage patterns.**