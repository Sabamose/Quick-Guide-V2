---
sidebar_position: 6
---

# How to Integrate Assistant to Your Website

Create a website channel to embed your AI assistant directly into your website with a simple script tag, enabling visitors to interact through text chat, voice chat, or both.

## Overview

Website integration allows you to deploy your configured assistant on any website through a generated script tag. This creates a seamless communication channel where visitors can interact with your AI assistant using their preferred method.

## Prerequisites

**⚠️ Important: Before integrating to your website, you must:**
- ✅ **[Create your assistant](./create-assistant)** with proper configuration
- ✅ **[Create assistant roles](./create-roles)** defining behavior and capabilities
- ✅ **[Test your assistant](./guided-setup#review-and-test)** to ensure proper responses

*Website integration will not work without a properly configured assistant and assigned roles.*

## When to Integrate Assistant to Website

**Choose website integration when you need:**
- Direct customer interaction on your website
- 24/7 automated support capabilities
- Reduced support workload
- Enhanced user engagement
- Voice or text-based communication options

## Step-by-Step Integration Process

### Step 1: Access Website Channel Creation

Navigate to your assistant dashboard and click **"Create Website Channel"** to begin the integration setup process.

**Before you start:**
- Ensure your assistant is fully configured
- Have your website URL ready
- Decide on communication preferences
- Confirm assistant roles are assigned

### Step 2: Configure Website Details

Enter your website information to identify and configure this integration channel.

**Website Name:**
- Provide a descriptive name to identify this website integration
- Example: "Company Support Site" or "Product Landing Page"

**Website URL:**
- Enter the complete URL where the assistant will be deployed
- Must include https:// or http://
- Example: `https://example.com`

### Step 3: Choose Communication Type

Select how visitors will interact with your assistant on your website.

**Available communication options:**
- **Text Chat**: Traditional text-based chat interface
- **Voice Chat**: Voice-only interactions for hands-free communication  
- **Unified**: Both text and voice options available to visitors

**Communication type considerations:**
- **Text Chat**: Best for detailed inquiries and information sharing
- **Voice Chat**: Ideal for quick questions and accessibility needs
- **Unified**: Maximum flexibility, letting users choose their preference

### Step 4: Select Your Assistant

Choose which assistant will handle interactions on this website from your available configured assistants.

**Assistant selection:**
- Select from your created assistants dropdown
- This assistant will handle all website interactions
- Ensure the chosen assistant matches your website's purpose

### Step 5: Assign Assistant Role

Select the specific role that defines how your assistant should behave when responding to website visitors.

**Role assignment:**
- Choose from your configured roles dropdown
- Role determines assistant personality and capabilities
- Select role appropriate for website visitor interactions

### Step 6: Generate Integration Code

Click **"Create Website Channel"** to generate your unique script tag for website integration.

**After creation:**
- Receive unique script tag immediately
- Script enables assistant with voice chat capabilities
- Code is ready for immediate website implementation

## Interactive Demo

<div style={{position: 'relative', boxSizing: 'content-box', maxHeight: '80vh', width: '100%', aspectRatio: '2.0041753653444676', padding: '40px 0 40px 0'}}>
<iframe 
  src="https://app.supademo.com/embed/cmdozjsx720rs9f965i2uvci8?embed_v=2&utm_source=embed" 
  loading="lazy" 
  title="Integrate your website with our platform easily" 
  allow="clipboard-write" 
  frameBorder="0" 
  webKitAllowFullScreen="true" 
  mozAllowFullScreen="true" 
  allowFullScreen 
  style={{position: 'absolute', top: 0, left: 0, width: '100%', height: '100%'}}
/>
</div>

## Code Implementation

### Universal Website Integration

The generated script tag works with any website platform:

**Website Builders:**
- **WordPress**: Add to theme footer or widget area
- **Wix**: Insert in HTML embed component
- **Squarespace**: Add to code injection footer
- **Webflow**: Insert in custom code section

**No-Code Development Platforms:**
- **Lovable**: Add to custom code section or embed component
- **Replit**: Insert in HTML head or body section  
- **Base44**: Add to generated app's custom HTML section
- **Bubble**: Insert in page header or HTML element
- **Glide**: Add to app's custom code or web embed feature
- **FlutterFlow**: Include in custom widget or web view component
- **Webflow**: Insert in site's custom code section
- **Zapier**: Add to automation webhook or custom code step

**E-commerce Platforms:**
- **Shopify**: Add to theme liquid files
- **BigCommerce**: Insert in footer scripts
- **WooCommerce**: Add via WordPress methods

### Example Implementation

```html
<!-- Your generated script tag will look similar to this -->
<script>
  // Generated code from your website channel
  // Copy and paste exactly as provided
</script>
```

## Advanced Configuration Options

### Communication Settings
- **Response timing**: Instant or delayed responses
- **Availability hours**: Set business hours for interactions
- **Fallback options**: Human handoff when needed
- **Language preferences**: Multi-language support

### User Experience
- **Welcome messages**: Custom greetings for new visitors
- **Conversation starters**: Suggested questions or topics
- **Visual customization**: Match your website branding
- **Mobile optimization**: Responsive design considerations

### Analytics and Monitoring
- **Conversation tracking**: Monitor user interactions
- **Performance metrics**: Response times and accuracy
- **User feedback**: Satisfaction ratings and comments
- **Usage analytics**: Peak times and popular queries

## Troubleshooting

### Common Setup Issues

**Script not working:**
- Verify assistant and roles are properly configured
- Check that website URL is correct
- Ensure script tag is placed correctly
- Test in different browsers

**Assistant not responding:**
- Confirm assistant roles are assigned
- Check assistant configuration status
- Verify communication type settings
- Review role permissions and capabilities

**Voice features not working:**
- Ensure microphone permissions are enabled
- Check browser voice API support
- Verify secure HTTPS connection
- Test audio device functionality

## Best Practices

### Pre-Integration Checklist
1. **Test assistant thoroughly** in dashboard before website deployment
2. **Configure multiple roles** for different interaction scenarios  
3. **Set clear expectations** in assistant welcome messages
4. **Plan escalation paths** for complex inquiries

### Implementation Guidelines
1. **Test on staging environment** before production deployment
2. **Monitor initial conversations** for optimization opportunities
3. **Gather user feedback** to improve assistant responses
4. **Document integration settings** for team reference

### Optimization Strategies
1. **Analyze conversation patterns** to improve role configurations
2. **Update assistant knowledge** based on common questions
3. **Refine communication flows** for better user experience
4. **Scale to additional websites** with proven configurations

## Next Steps

After successful website integration:

1. **[Monitor assistant performance](./analytics-setup)** and user engagement
2. **[Refine assistant roles](./create-roles)** based on real conversations  
3. **[Create additional channels](./assign-roles)** for other communication methods
4. **[Advanced customization](./custom-assistant)** for enhanced capabilities

## Getting Help

Need assistance with website integration?
- [View our integration documentation](/api/integration) for technical details
- [Contact support](mailto:support@travnex.com) for setup assistance
- [Join our community](https://community.travnex.com) for implementation tips

**⚠️ Remember: Website integration requires pre-configured assistants and roles. Complete assistant setup before attempting website integration.**