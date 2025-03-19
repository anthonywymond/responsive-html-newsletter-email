# Responsive Newsletter Email Template

This email template (see preview image below) is based on the Webflow Partner Newsletter design. It uses a table-based HTML structure to ensure compatibility across various email clients.

## Features

- Fully responsive design that works across desktop and mobile email clients
- Table-based layout for maximum email compatibility
- Properly structured CTA buttons that render well in most email clients
- Consistent content width (480px) with proper margins
- Placeholder images that can be easily replaced with your own assets

## Usage Instructions

### Social Icons

The template includes placeholder social media icons. To use your own icons:

1. Source icon images from a reliable provider:
   - [Simple Icons](https://simpleicons.org/)
   - [Font Awesome](https://fontawesome.com/)
   - [Mailchimp's Social Icon Gallery](https://templates.mailchimp.com/resources/social-icon-builder/)
   - [Campaign Monitor's Free Icon Builder](https://www.campaignmonitor.com/resources/tools/icon-builder/)

2. Replace the placeholder URLs in the social icon section with direct links to your hosted images:
   ```html
   <img src="your-icon-url.png" width="32" height="32" alt="LinkedIn" style="display: block;">
   ```

### Inlining CSS

While the template already includes inline styles, if you make changes to the CSS, it's essential to run the template through a CSS inliner before sending. This ensures all styles are properly applied in email clients that strip `<style>` tags.

Recommended CSS inliners:
- [Mailchimp's CSS Inliner](https://templates.mailchimp.com/resources/inline-css/)
- [HTML Email's Inline CSS Tool](https://htmlemail.io/inline/)
- [Campaign Monitor's CSS Inliner](https://www.campaignmonitor.com/resources/tools/css-inliner/)

### Email-Friendly Code Features

The template incorporates several email-friendly coding practices:

1. **Nested Tables**: Used for layout structure instead of divs or other HTML5 elements
2. **Width Attributes**: Both HTML `width` attributes and CSS `width` properties are used for better rendering
3. **MSO Conditionals**: Includes comments for Outlook-specific fixes
4. **Image Display Block**: All images use `display: block` to prevent unwanted spacing
5. **Border-collapse**: Tables use `border-collapse: collapse` to prevent unwanted gaps
6. **Responsive Design**: Uses media queries for mobile optimization
7. **Alt Text**: All images include alt text for accessibility
8. **Mobile Stack Classes**: Custom classes to control how content stacks on mobile devices

## Testing

Before sending, test your email in multiple email clients. Services like [Litmus](https://www.litmus.com/) or [Email on Acid](https://www.emailonacid.com/) can help you preview how your email will render across different platforms.

## Customization

- Replace all instances of "XYZ Company" with your company name
- Update colors to match your brand (search for color codes like `#146EF5`)
- Replace placeholder images with your own hosted images
- Update all link URLs to point to your desired destinations

## License

This template is provided as-is under the MIT License. Feel free to use and modify it for your own purposes.

## Additional Notes

- When working with email templates, always test thoroughly across multiple email clients
- Consider using AI tools to help with customization and content generation
- For complex designs, build incrementally and test each component separately

![preview](https://github.com/user-attachments/assets/662a0aed-1246-4ffd-b11f-2fea6abfbeda)
